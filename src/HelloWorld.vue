<template>
  <div>
    Message :<h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1{
color: red;
}
</style>
