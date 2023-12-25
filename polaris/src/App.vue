<template>
  <div class="container">
    <header class="nav"> {{ title }} </header>
    <div class="main">
      <div class="left">Left</div>
      <div class="right">Right</div>
      <div class="center">Center</div>
    </div>
    <footer>{{ welecome }}</footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Polaris",
      welecome: "Hello! Welecome to Polaris !",
    }
  }
}
</script>