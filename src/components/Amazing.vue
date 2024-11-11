<script setup></script>
<template>
  <div class="container">
    <div class="background-text">
      <span>AMAZING AMAZING AMAZING AMAZING</span>
      <span>AMAZING AMAZING AMAZING AMAZING</span>
    </div>
    <div class="content">
      <p>Our Most Amazing</p>
      <p>Visited Hotel on 2024</p>
      <span class="description">
        Take a look our best choice for the hotels of the year, <br> we pick the hotels from our amazing visitors.
      </span>
    </div>
  </div>
</template>
<style scoped>
.container {
  height: 400px;
  position: relative;
  overflow: hidden;
  font-family: "Open Sans", serif;

}

.background-text {
  position: absolute;
  top: -5%;
  left: 0;
  transform: translateY(-50%);
  font-size: 21rem;
  font-weight: bold;
  color: gray;
  opacity: 10%;
  white-space: nowrap;
  display: flex; /* Kesintisiz akış için flex kullanıyoruz */
  animation: scrollText 60s linear infinite;
  z-index: 1;
}

.background-text span {
  padding-right: 2rem; /* Yazılar arasında boşluk bırakır */
}

.content {
  position: relative;
  z-index: 2;
  margin-top: 80px;
  align-items: center;
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 100%;
  p{
    text-align: center;
    font-size: 4.6rem;
    font-family: "Poppins", sans-serif;
    font-weight: 600;
    line-height: 5.6rem;
  }
  .description{
    font-family: "Poppins", sans-serif;
    margin-top: 1.5rem;
    max-width: 950px;
    text-align: center;
    font-size: 1.6rem;
    font-weight: 400;
    word-spacing: 3px;
    line-height: 2rem;
  }
}

@keyframes scrollText {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100%);
  }
}
</style>