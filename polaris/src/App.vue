<template>
  <header>
    <title-ul>
      <title-li><a href="">Support</a></title-li>
      <title-li><a href="">About</a></title-li>
      <title-li><a href="">Contact</a></title-li>
    </title-ul>
    <div class="project-name" style="background-color: white;"> {{ title }} </div>
    <div class="divider"></div>
  </header>

  <div class="sidebar side-nav box-shadow-25">
    <div class="project-name">Menu</div>
    <ul style="padding-left: 0;">
      <menu-li><a href="">HOME</a></menu-li>
      <menu-li><a href="">Combine</a></menu-li>
      <menu-li><a href="">Carrot</a></menu-li>
      <menu-li><a href="">Polish Characters</a></menu-li>
    </ul>
  </div>

  <main-area>
    <p>123456789</p>
  </main-area>


  <footer>{{ welecome }}</footer>
</template>

<script>
export default {
  data() {
    return {
      title: "Polaris",
      welecome: "Welecome to Polaris ! sighhh0704@gmial.com",
    }
  }
}

</script>