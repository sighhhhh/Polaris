<template>
  <header>
    <ul>
      <li><a href="">Support</a></li>
      <li><a href="">About</a></li>
      <li><a href="">Contact</a></li>
    </ul>
    <div class="project-name"> {{ title }} </div>
  </header>
  <div class="divider"></div>
  <div class="sidebar">
    <div class="project-name">Menu</div>
    <ul>
      <li><a href="">HOME</a></li>
      <li><a href="">Combine</a></li>
      <li><a href="">Carrot</a></li>
      <li><a href="">Polish Characters</a></li>
    </ul>
  </div>
  <footer>{{ welecome }}</footer>
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