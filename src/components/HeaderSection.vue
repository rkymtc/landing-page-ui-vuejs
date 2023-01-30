<template>
  <header class="header">
    <div class="container">
      <div class="header-content">
        <img src="../assets/img/logo.svg" alt="logo" class="header-logo" />

        <div class="header-mobile-menu" @click="showMenu()">
          <img src="../assets/img/menu.svg" alt="menu" />
        </div>

        <nav class="header-nav" :class="this.showMobileMenu ? 'is-active' : ''">
         
            <ul class="header-nav-list">
            <li>
              <a
                href="javascript:;"
                class="header-nav-item is-active"
                >Free designs</a
              >
            </li>
            <li>
              <a
                href="javascript:;"
                class="header-nav-item"
                >License</a
              >
            </li>
            <li>
              <a
                href="javascript:;"
                class="header-nav-item"
                >Articles</a
              >
            </li>
            <li>
              <a
                href="javascript:;"
                class="header-nav-item"
                >Contributors</a
              >
            </li>
            <li>
              <a
                href="javascript:;"
                class="header-nav-item"
                >About</a
              >
            </li>
          </ul>
         
        </nav>

        <div class="header-account">
          <a href="javascript:;" class="header-account-login">Log in</a>
          <a href="javascript:;" class="header-account-signup">Sign Up</a>
        </div>
      </div>
    </div>
  </header>
</template>
<script>


export default {
  

  data() {
    return {
      showMobileMenu: false,
    };
  },
  methods: {
    showMenu() {
      this.showMobileMenu = !this.showMobileMenu;
    },
  },
};
</script>
<style lang="scss">
@import "../assets/scss/_header.scss";
</style>
