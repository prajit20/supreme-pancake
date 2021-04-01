/* eslint-disable vue/no-parsing-error */
<template>

   <v-btn @click="increas()">{{hello}}</v-btn>

</template>

<script>


export default {
  name: 'HelloWorld',

   data() {
      return {
        a:1,
      }
    },
    methods:{
      increase(){
        this.a = this.a++
        console.log(this.a)
      }
    },
    mounted() {

      this.hello = 'World'
    },
  }
</script>
