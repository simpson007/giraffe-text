<template>
  <div class="nav">
    <div class="content">
      Labels.vue
    </div>
    <Nav/>
  </div>
</template>

<script lang="ts">
export default {
  name: "Labels"
}
</script>

<style lang="scss" scoped>
.nav{
  border: 1px solid red;
  display: flex;
  flex-direction: column;
  height: 100vh;
}
.content{
  border: 2px solid green;
  overflow: auto;
  flex-grow: 1;
}
</style>