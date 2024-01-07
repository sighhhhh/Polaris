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
    <transition v-show="isVisible" @mouseover="hidemenu" id="menu-mask">
      <p class="project-name" style="width: 380px;">
        Menu
      </p>
    </transition>
    <div class="sidebar box-shadow-25" @mouseleave="showmenu">
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
      isVisible : true
    };
  },
  methods: {
    hidemenu(){
      this.isVisible = false;
    },
    showmenu(){
      this.isVisible = true;
    }
  }
}
</script>