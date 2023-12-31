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


  <main>
    <menu-mask class="box-shadow-25">
      <div class="project-name">Menu</div>
    </menu-mask>
    <div class="sidebar box-shadow-25">
      <menu-ul>
        <menu-li><a href="">HOME</a></menu-li>
        <menu-li><a href="">Combine</a></menu-li>
        <menu-li><a href="">Carrot</a></menu-li>
        <menu-li><a href="">Polish Characters</a></menu-li>
      </menu-ul>
    </div>

    <div class="main-area">
      <div class="project-name">Here is the Main area</div>
    </div>
  </main>


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