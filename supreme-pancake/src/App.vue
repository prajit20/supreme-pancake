/* eslint-disable vue/no-parsing-error */
<template>

   <v-btn @click="increase()">{{inc}}</v-btn>

</template>

<script>


export default {
  name: 'HelloWorld',

   data() {
      return {
        a:0,
        inc: 'Press to increase the value'
      }
    },
    methods:{
      increase(){
        this.a = this.a + 1
        console.log(this.a)
      }
    },
  }
</script>

<style scoped>

</style>
