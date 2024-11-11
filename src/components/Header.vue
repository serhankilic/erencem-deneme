<script setup>
import NavbarTemplate from "@/components/Navbar-template.vue";
import HeaderContent from "@/components/header-content.vue";
import ReservationBox from "@/components/Reservation-box.vue";

</script>

<template>
<section class="main-area" id="main-area">
  <section class="header-bg">
  </section>
  <nav>
    <navbar-template class="main-navbar" />
  </nav>
<div class="content">
  <header-content class="header_content" />
  <ReservationBox class="reservation-box" />
</div>
</section>
</template>

<style scoped>
* {
  font-family: "Open Sans", sans-serif;
}

.main-area {
  width: 100vw;
  height: 100vh;
  background-image: url("/header-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  &:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background: rgba(0, 0, 0, 0.45);
  }

  nav {
    position: relative;
    z-index: 1;
    .main-navbar{
      z-index: 5;
    }
  }

  .content {
    display: flex;
    flex-direction: column;
    .reservation-box{
      width:100%;
      position: relative;
      z-index: 5;
      margin: 30px auto auto;
    }
  }
}
</style>