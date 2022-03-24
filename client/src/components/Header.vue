<template>
  <header class="header">
    <div class="container">
      <div class="row jcs alc">
        <div class="logo">
          <a href="#!"
            ><img src="../assets/img/1.png" alt="logo" style="height: 44px"
          /></a>
          <p class="text-logo">eatTagil</p>
        </div>
        <button
          :class="{ active: burgerToogle }"
          class="nav-toggler"
          @click="navToggler()"
          type="button"
        >
          <span></span>
        </button>
        <nav :class="{ open: burgerToogle }" class="nav">
          <ul>
            <li @click="closeMenu()" class="nav-item">
              <a href="#home">Главная</a>
            </li>
            <li @click="closeMenu()" class="nav-item">
              <a href="#about">О нас</a>
            </li>
            <li @click="closeMenu()" class="nav-item">
              <a href="#our-menu">Наше меню</a>
            </li>
            <li @click="closeMenu()" class="nav-item">
              <a href="#testimonial">Отзывы</a>
            </li>
            <li @click="closeMenu()" class="nav-item">
              <a href="#team">Наша команда</a>
            </li>
            <li @click="closeMenu()" class="nav-item">
              <a href="#contact">Контакты</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "Header.vue",
  data() {
    return {
      burgerToogle: false,
      windowTop: 0,
    };
  },
  methods: {
    navToggler() {
      this.burgerToogle = !this.burgerToogle;
    },
    closeMenu() {
      this.burgerToogle = false;
    },
    onScroll(e) {
      this.windowTop = e.target.documentElement.scrollTop;
      if (this.windowTop > 60) {
        let nav = document.querySelector(".header");
        nav.classList.add("sticky");
      } else {
        let nav = document.querySelector(".header");
        nav.classList.remove("sticky");
      }
    },
  },
  mounted() {
    window.addEventListener("scroll", this.onScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.onScroll);
  },
};
</script>
