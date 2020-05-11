<template>
  <div>
    Message :<h1 @click="sayHello">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    msg: String
  },
  methods:{
    sayHello(){
      console.log(Date.now(),this.msg)
    }
  }
}
</script>

<style scoped>
h1{
color: red;
}
</style>
