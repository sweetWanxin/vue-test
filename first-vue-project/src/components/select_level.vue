<template>
  <div>
    <input type="text" v-model="content">
  </div>
</template>
<script>
  export default{
    data(){
      return {
      }
    },
    computed:{
      content(){
        return this.$store.state.cart.name
      }
    }
  }
</script>
<style>

</style>
