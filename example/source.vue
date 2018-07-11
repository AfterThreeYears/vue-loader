<template lang="pug">
div(ok)
  h1(:class="$style.red") hello
  h2 world
</template>

<script>
export default {
  data () {
    return {
      msg: 'fesfff'
    }
  }
}
</script>

<style module>
.red {
  color: red;
}
</style>

<style>
h2 {
  color: blue;
}
</style>


<foo>
export default comp => {
  console.log(comp.options.data())
}
</foo>
