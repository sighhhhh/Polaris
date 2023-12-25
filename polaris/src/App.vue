<template>
  <div class="container">
    <header>
      <div class="project-name"> {{ title }} </div>
      <ul>
        <li><a href="">Support</a></li>
        <li><a href="">About</a></li>
        <li><a href="">Contact us</a></li>
      </ul>
    </header>
    <div class="divider"></div>

    <footer>{{ welecome }}</footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Polaris",
      welecome: "Welecome to Polaris !",
    }
  }
}
</script>