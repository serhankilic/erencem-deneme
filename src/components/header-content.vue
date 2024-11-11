<script setup>
</script>

<template>
  <div class="container">
    <section class="big-area">
      <div class="big-text">
        <p>
          Stay Quietly,
        </p>
        <p>
          With No Worries
        </p>
      </div>
      <div class="small-text">
        <p>Welcome to our hotel booking platform, where your travel experience becomes easier and more enjoyable. With our platform, you can discover the perfect accommodation for your stay worldwide.</p>
      </div>
    </section>
    <section class="small-area">
      <div class="description-text">
        <div class="first-description">
          <div class="numbers">
            <p>12k+</p>
          </div>
          <div class="small-description">
            <p>Satisfied Visitors</p>
          </div>
        </div>
        <div class="second-description">
          <div class="numbers">
            <p>4.5k+</p>
          </div>
          <div class="small-description">
            <p>Amazing TourGuide</p>
          </div>
        </div>
        <div class="thirth-description">
          <div class="numbers">
            <p>2k+</p>
          </div>
          <div class="small-description">
            <p>Special Travel Trip</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped>
.container{
  padding-top: 70px;
  position: relative;
  width: 1500px;
  height: 520px;
  margin: auto;
  display: flex;
  flex-direction: row;
  .big-area{
    width: 80%;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    .big-text{
      font-family: "Poppins", sans-serif;
      font-size: 8rem;
      font-weight: 600;
      color: white;
      line-height: 11.5rem;
      text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);

    }
    .small-text{
      width: 80%;
      font-size: 24px;
      color: white;
      text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
    }
  }
  .small-area{
    width: 20%;
    .description-text{
      padding-top: 35px;
      height: 90%;
      width: 100%;
      font-family: "Poppins", sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      color: white;
      .numbers{
        font-size: 4rem;
        font-weight: 500;
        text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
      }
      .small-description{
        font-size: 24px;
        font-weight: 300;
        text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
      }
    }
  }
}
</style>
