<template>

   <v-btn class="button_test" @click="increase()">{{inc}}</v-btn>

   <div class="testing">{{a}}</div>


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

<style lang="scss">

.button_test{
  
  display: flex;
  align-items: center;

}

.testing{
  text-align: center;
}

</style>
