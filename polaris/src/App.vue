<template>
  <div class="container">
    <header> {{ title }} </header>
    <div class="main">
      <div class="main-content">
        <router-view></router-view>
      </div>
      <aside class="sidebar sidebar-left">Left Sidebar</aside>
      <aside class="sidebar sidebar-Right">Right Sidebar</aside>
    </div>
    <footer>Footer</footer>
  </div>
</template>

<script>

export default {
  name:'App',
  data() {
    return {
      title: "Polaris",
      welecome: "Hello! Welecome to Polaris !",
      dynamicID: "AppID",
      dynamicClass: "AppClass",
      isBtnDisabled: false
    }
  }
}
</script>

<style>
.AppClass {
  color: rgb(59, 47, 122);
  font-size: 50px;
}
</style>