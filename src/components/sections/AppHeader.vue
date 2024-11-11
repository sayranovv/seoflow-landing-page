<script setup>
import TheNavbar from "@/components/TheNavbar.vue";
</script>

<template>
  <div class="container">
    <div class="pre-navbar">
      <ul class="contacts-items">
        <li class="contact-item">
          <img src="../../../public/assets/icons/phone.png" alt="phone" class="contact-item-icon" />
          <span class="contact-item-text">+1800-123-4567</span>
        </li>
        <li class="contact-item">
          <img src="../../../public/assets/icons/mail.png" alt="mail" class="contact-item-icon" />
          <span class="contact-item-text">info@brandexponents.com</span>
        </li>
      </ul>
      <ul class="socials-items">
        <li class="social-item"><img src="../../../public/assets/icons/facebook.svg" alt="facebook" class="social-img"></li>
        <li class="social-item"><img src="../../../public/assets/icons/twitter.svg" alt="twitter" class="social-img"></li>
        <li class="social-item"><img src="../../../public/assets/icons/linkedin.svg" alt="linkedin" class="social-img"></li>
        <li class="social-item"><img src="../../../public/assets/icons/pinterest.svg" alt="pinterest" class="social-img"></li>
      </ul>
    </div>
    <TheNavbar />
  </div>
</template>

<style scoped>
.container {
  margin: 0 auto;
  max-width: 1200px;
  width: 100%;
}

.pre-navbar {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 0;
}

.contacts-items {
  list-style: none;
  display: flex;
  gap: 20px;
}

.contact-item {
  display: flex;
  gap: 12px;
}

.contact-item-icon {
  max-width: 28px;
}

.contact-item-text {
  color: #fff;
  font-size: 16px;
  line-height: 28px;
}

.socials-items {
  list-style: none;
  display: flex;
  gap: 15px;
}
</style>