<template>
  <div id="app">
    <router-view :key="$route.path"></router-view>
  </div>
</template>

<script>
</script>

<style lang="scss">
#app {
  font-family: $mainfont, Helvetica, Arial, sans-serif;
}
</style>
