<template>
  <nav class="navbar is-flex is-justify-content-space-between py-1 px-3">
    <div class="container">
      <div class="navbar-content is-flex is-align-items-center">
        <div class="navbar-burger" :class="{ 'is-active': isMenuOpen }" @click="toggleMenu">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="navbar-item left-logo">
          <img src="/logo right.png" alt="Logo" class="logo">
        </div>
        <div class="navbar-menu" :class="{ 'is-active': isMenuOpen }">
          <div class="navbar-start is-justify-content-center w-100">
            <NuxtLink to="/" class=" mx-5 mt-10px color-blue-dark" href="#">
              صفحه اصلی
            </NuxtLink>
            <NuxtLink to="/" class=" mx-5 mt-10px has-text-black is-flex is-align-items-center" href="#">
              <p>
                نصب اپلیکیشن
              </p>
              <img src="Chevron down.png" alt="">
            </NuxtLink>
            <NuxtLink to="/" class=" mx-5 mt-10px has-text-black is-flex is-align-items-center" href="#">
              ثبت نام تعمیرکاران
            </NuxtLink>
            <NuxtLink to="/" class=" mx-5 mt-10px has-text-black is-flex is-align-items-center" href="#">
              درباره آراسرویس
            </NuxtLink>
          </div>
        </div>
        <div class="navbar-item right-logo">
          <img src="/logo left.png" alt="Right Image" class="logo">
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
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
  position: fixed;
  top: 10px;
  left: 50%;
  transform: translateX(-50%);
  background-color: white;
  max-width: 1208px;
  width: 100%;
  border-radius: 15px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
  z-index: 1000;
}

.logo {
  max-height: 50px;
}

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

.navbar-menu {
  flex-grow: 1;
  display: flex;
  justify-content: center;
}

@media screen and (max-width: 768px) {
  .navbar {
    max-width: 93%;
  }

  .navbar-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    position: relative;
  }

  .navbar-burger {
    display: block;
    order: 1;
  }

  .left-logo {
    order: 2;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
  }

  .right-logo {
    order: 3;
  }

  .navbar-menu {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
    background: white;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    border-radius: 0 0 15px 15px;
    padding: 10px 0;
    z-index: 999;
  }

  .navbar-menu.is-active {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .navbar-menu .navbar-item {
    width: 100%;
    text-align: center;
    padding: 10px;
    border-bottom: 1px solid #ddd;
  }

  .navbar-menu .navbar-item:last-child {
    border-bottom: none;
  }
}
</style>
