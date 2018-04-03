<template>
  <p>lorem</p>
</template>
<script>
export default {
  watch: {
    data1 (val) {
      this.data2 = 1
    },
    data2 (val) {}
  }
}
</script>
