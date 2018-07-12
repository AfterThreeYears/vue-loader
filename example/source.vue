<template lang="pug">
div(ok)
  h1(:class="$style.red") hello
  h2 world
  h3 666
  <ui-test />
</template>

<script>
import UiTest from './UITest.vue';
export default {
  data () {
    return {
      msg: 'fesfff'
    }
  },
  components: {
    UiTest,
  },
}
</script>

<style module>
.red {
  color: red;
}
</style>

<style scoped>
h2 {
  color: blue;
}
h3 {
  color: yellow;
}
</style>


<foo>
export default comp => {
  console.log(comp.options.data())
}
</foo>
