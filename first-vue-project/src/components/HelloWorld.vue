<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <selectLevel/>
  </div>
</template>

<script>
  import selectLevel from './select_level.vue'
export default {
  name: 'HelloWorld',
  components:{
    selectLevel
  },
  data () {
    return {
      msg: 'First Component'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
