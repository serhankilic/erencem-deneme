<script setup>
import FindHotels from "@/components/FindHotels.vue";
</script>
<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <FindHotels />
<div class="container-cards">
  <div class="cards">
    <div class="card card-1">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Emerald Valley Lodge</p>
        <p class="card-location">New Zealand, Australia</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(5126 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
    <div class="card card-2">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Golden Horizon Hotel</p>
        <p class="card-location">New York, USA</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(626 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
    <div class="card card-3">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Whispering Pines Retreat</p>
        <p class="card-location">Malang, Indonesia</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(912 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
    <div class="card card-4">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Paradise Cove Retreat</p>
        <p class="card-location">Tokyo, Japan</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(1276 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
    <div class="card card-5">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Sunset Vista Resort</p>
        <p class="card-location">Sao Paulo, Brazil</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(8126 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
    <div class="card card-6">
      <div class="card-image">
      </div>
      <div class="card-content">
        <p class="card-name">Enchanted Meadows</p>
        <p class="card-location">Istanbul, Turkey</p>
        <div class="visitors">
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="visitors-amount">(1826 Visitors)</p>
        </div>
      </div>
      <div class="buttons">
        <input type="submit" value="Book now" class="book-button" style="width: 390px; height: 50px; outline: none; " >
        <input type="submit" value="" class="message-button" style="width: 50px; height: 50px; outline: none" >

      </div>
    </div>
  </div>
  <div class="button-view">
    <input type="button" placeholder="View More" class="view-more-button" value="View More" style="outline:none;">
  </div>
</div>

</template>

<style>

.container-cards {
  max-width: 1500px;
  margin: auto;
  font-family: "Poppins", sans-serif;
  .cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 sütun */
    grid-template-rows: repeat(2, auto); /* 2 satır */
    gap: 20px; /* Kartlar arasındaki boşluk */
    width: 100%; /* Genişliği isteğine göre ayarlayabilirsin */
    max-width: 1500px; /* Maksimum genişlik */
    margin-bottom: 50px;
    .card {
      width: 450px;
      height: 425px;
      overflow: hidden;
      cursor: pointer;
      .card-image {
        width: 450px;
        height: 275px;
        background-color: red;
        border-radius: 15px;
        transition: 0.3s all;
      }
      .card-content {
        margin-top: 20px;
        .card-name {
          color: black;
          font-size: 28px;
          font-weight: 600;
        }
        .card-location {
          font-size: 22px;
          font-weight: 500;
        }
        .visitors {
          display: flex;
          align-items: center;
          margin-left: 20px;
          margin-top: 10px;
          .stars {
            scale: 150%;
            overflow: hidden;
            margin-right: 30px;
            .checked{
              margin: 1px;
              color: orange;
            }
          }
          .visitors-amount{
            font-size: 20px;
            font-weight: 500;
          }

        }
      }
      .buttons {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 20px;
        opacity: 0;
        transition: .6s all;
        .book-button {
          background-color: black;
          color: white;
          border-radius: 40px;
          font-size: 22px;
          font-weight: 300;
          cursor: pointer;
          &:focus-within{
            color: gray;
          }
        }
        .message-button{
          color: white;
          border: 1px solid gray;
          cursor: pointer;
          border-radius: 50%;
          background-color: white;
        }
      }
    }
    .card-1 {
      .card-image {
        background-image: url("/roomtype-1.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-1:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
    .card-2 {
      .card-image {
        background-image: url("/roomtype-2.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-2:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
    .card-3 {
      .card-image{
        background-image: url("/roomtype-3.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-3:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
    .card-4 {
      .card-image {
        background-image: url("/roomtype-4.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-4:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
    .card-5 {
      .card-image {
        background-image: url("/roomtype-5.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-5:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
    .card-6 {
      .card-image {
        background-image: url("/roomtype-6.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }
    }
    .card-6:hover {
      .card-image {
        height: 200px;
      }
      .buttons{
        opacity: 1;
      }
    }
  }
  .button-view {
    display: flex;
    justify-content: center;
    z-index: 5;
    margin-bottom: 100px;

    .view-more-button {
      width: 350px;
      height: 60px;
      border-radius: 35px;
      border: 2px solid darkgray;
      font-size: 20px;
      font-weight: 600;
      background-color: white;
      cursor: pointer;

    }
  }
}
</style>