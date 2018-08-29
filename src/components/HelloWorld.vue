<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Vue with sass</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ' Home Vue'
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit SCSS to this component only -->
<style lang="scss" scoped>
  @import "~@/style/index.scss";
</style>
