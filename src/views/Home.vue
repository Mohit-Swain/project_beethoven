<template>
  <div class="Home">
    {{ count }}
    <button>Click me</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      count: 0
    }
  }
}
</script>

<style scoped>
.Home {
  @apply bg-green-300;
}
</style>
