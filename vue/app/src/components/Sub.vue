<template>
    <div :style="textStyle">
        Sub
        {{ color }}
    </div>
</template>
<style scoped>
div {
  font-weight: bold;
  margin: 20px;
}
</style>

<script>
export default {
  props: ['color'],
  computed: {
    textStyle () {
      return 'color: ' + this.color
    }
  }
}
</script>
