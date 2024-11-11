<script setup>

</script>

<template>
  <div class="nav-container">
    <div class="logo">
      <img src="../../public/assets/logo.png" alt="logo" class="logo-img">
    </div>
    <nav class="nav-menu">
      <ul class="menu">
        <li class="menu-item">Home</li>
        <li class="menu-item">Why SEO?</li>
        <li class="menu-item">Services</li>
        <li class="menu-item">Team</li>
        <li class="menu-item">Pricing</li>
        <li class="menu-item">Blog</li>
        <li class="menu-item">Contact</li>
      </ul>
    </nav>
    <button class="navbar-button" type="button">
      Enquiry
    </button>
  </div>
</template>

<style scoped>
.nav-container {
  margin: 0 auto;
  max-width: 1200px;
  width: 100%;
  padding: 25px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #fff;
  border-radius: 10px;
}

.logo {
  max-width: 94px;
}

.logo-img {
  width: 100%;
}

.nav-menu {

}

.menu {
  display: flex;
  gap: 30px;
  flex-wrap: nowrap;
  list-style: none;
}

.navbar-button {
  padding: 11px 25px;
  border-radius: 32px;
  background-color: #F4AB00;
  font-size: 13px;
  line-height: 19px;
  color: #fff;
  border: none;
}
</style>