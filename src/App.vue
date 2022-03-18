<template>
  <div id="app">
    <div id="nav">
      <dash-body />
    </div>
  </div>
</template>

<script>
import DashBody from "./components/DashBody.vue"

export default{
  components: {
    DashBody,
  }
}
</script>


<style>
@import url(./assets/preCSS/main.scss);
</style>
