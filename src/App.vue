<template>
  <div id="app">
    <div id="nav">
      <dash-header />
      <dash-body />
    </div>
  </div>
</template>

<script>
import DashHeader from "./components/DashHeader.vue"
import DashBody from "./components/DashBody.vue"

export default{
  components: {
    DashHeader,
    DashBody,
  }
}
</script>


<style>
@import url(./assets/preCSS/main.scss);
</style>
