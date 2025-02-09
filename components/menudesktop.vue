<template>
    <nav class="navbar is-flex is-justify-content-space-between p-3">
      <div class="navbar-item">
        <img src="/logo.png" alt="Logo" class="logo">
      </div>
      
 
      <div class="navbar-burger" :class="{ 'is-active': isMenuOpen }" @click="toggleMenu">
        <span></span>
        <span></span>
        <span></span>
      </div>
      
      <div class="navbar-menu" :class="{ 'is-active': isMenuOpen }">
        <div class="navbar-start is-flex is-justify-content-center w-100">
          <a class="navbar-item" href="#">صفحه اصلی</a>
          <a class="navbar-item" href="#">درباره ما</a>
          <a class="navbar-item" href="#">محصولات</a>
          <a class="navbar-item" href="#">تماس با ما</a>
        </div>
      </div>
      <div class="navbar-item">
        <img src="/right-image.png" alt="Right Image" class="logo">
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: "ResponsiveNavbar",
    data() {
      return {
        isMenuOpen: false
      };
    },
    methods: {
      toggleMenu() {
        this.isMenuOpen = !this.isMenuOpen;
      }
    }
  };
  </script>
  
  <style scoped>
  .navbar {
    background-color: white;
  }
  .logo {
    max-height: 50px;
  }
  .navbar-menu {
    flex-grow: 1;
    display: flex;
    justify-content: center;
  }
  .w-100 {
    width: 100%;
  }
  
  /* Mobile Menu */
  .navbar-burger {
    display: none;
    cursor: pointer;
  }
  .navbar-burger span {
    display: block;
    width: 25px;
    height: 3px;
    margin: 5px auto;
    background-color: black;
  }
  
  @media screen and (max-width: 768px) {
    .navbar-burger {
      display: block;
    }
    .navbar-menu {
      display: none;
      width: 100%;
    }
    .navbar-menu.is-active {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 10px;
    }
  }
  </style>
  