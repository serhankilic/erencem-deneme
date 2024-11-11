<script setup>
</script>
<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <div class="container">
    <div class="cards">
      <div class="left-card">
        <p class="room-info">Oasis Sands Resort <br>
          Homestays</p>
        <div class="location">
          <p>Karaköy, İstanbul</p>
          <div class="stars">
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
          </div>
          <p class="rate-amount">
            (245 Visitors)
          </p>
        </div>
        <div class="hidden-content">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab at blanditiis cumque dignissimos doloribus et eum exercitationem fugit hic incidunt officia, omnis perferendis praesentium quam tempore tenetur, vel, voluptatem voluptatibus!</p>
        </div>
        <div class="arrow">
          <a href="#"><img src="/icons/arrow-right.svg" alt="" class="right-arrow"></a>
        </div>
        <div class="bg"></div>

      </div>
      <div class="right-cards">
        <div class="right-up right">
          <p class="room-info">Bruhan Castle <br>
            Luxury Hotel</p>
          <div class="location">
            <p>Rio, Brazil</p>
            <div class="details">
              <div class="stars">
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star"></span>
              </div>
              <p class="rate-amount">
                (140 Visitors)
              </p>
            </div>
          </div>
          <div class="hidden-content">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque cupiditate ipsa, labore laborum officia reprehenderit.</p>
          </div>
          <div class="arrow">
            <a href="#"><img src="/icons/arrow-right.svg" alt="" class="right-arrow"></a>
          </div>
          <div class="bg"></div>
        </div>
        <div class="right-down right">
          <p class="room-info">Maria Suite <br>
            Bungalov</p>
          <div class="location">
            <p>Madrid, Spain</p>
            <div class="details">
              <div class="stars">
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star"></span>
              </div>
              <p class="rate-amount">
                (290 Visitors)
              </p>
            </div>
          </div>
          <div class="hidden-content">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque cupiditate ipsa, labore laborum officia reprehenderit.</p>
          </div>
          <div class="arrow">
            <a href="#"><img src="/icons/arrow-right.svg" alt="" class="right-arrow"></a>
          </div>
          <div class="bg"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
*{
  font-family: "Open Sans", sans-serif;
}
.container{
  padding: 30px 0;
  position: relative;
  max-width: 1500px;
  margin: auto;
  .cards{
    width: 100%;
    height: 700px;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    .left-card  {
      width: 1000px;
      height: 700px;
      border-radius: 10px;
      z-index: 5;
      display: flex;
      flex-direction: column;
      position: relative;
      cursor: pointer;

      .bg {
        width: 100%;
        height: 100%;
        background-image: url("/HotelRoom-3.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        z-index: 1;
        position: relative;
        border-radius: 35px;
        border: 2px solid transparent;
        transition: .4s all ease-in-out;
          &:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            width: 100%;
            background: rgba(0, 0, 0, 0.15);
            border-radius: 30px;
          }
        }
        p {
          position: absolute;
          padding-top: 400px;
          padding-left: 20px;
          color: white;
          font-size: 3rem;
          font-weight: 600;
          z-index: 10;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          transition: 0.45s all;
        }
        .location{
          position: absolute;
          width: 100%;
          display: flex;
          flex-direction: column;
          height: 100px;
          p{
            top: 230px;
            z-index: 4;
            font-size: 1.7rem;
          }
          .rate-amount{
            top:233px;
            left: 370px;
            font-weight: 400;
            font-size: 22px;
            opacity: 75%;
            transition: .3s all ease-in-out;
          }
          .stars{
            top: 637px;
            left: 285px;
            position: absolute;
            z-index: 4;
            scale: 130%;
            .fa-star{
              margin: 1px;
              color: gray;
            }
            .checked {
              color: white;
            }
          }

        }
        .hidden-content{
          position: absolute;
          display: flex;
          flex-direction: column;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          p{
            width: 600px;
            font-size: 22px;
            font-weight: 300;
            color: transparent;
            transition: .35s all ease-in-out;
          }
        }
        .arrow{
          position: absolute;
          z-index: 5;
          top: 650px;
          scale: 300%;
          right: 30px;
        }
        &:hover{
          p.room-info{
            padding-top: 200px;
          }
          .bg{
            filter: blur(2px);
          }
          .rate-amount{
            opacity: 100%;
          }
          .hidden-content{
            p{
              color: white;

            }
          }
        }
      }
    }
    .right-cards {
      display: flex;
      justify-content: space-between;
      row-gap: 30px;
      flex-direction: column;
      height: 700px;
      .right {
        width: 470px;
        height: 325px;
        background-color: darkgray;
        border-radius: 30px;
      }
      .right-up {
        cursor: pointer;
        p.room-info {
          position: absolute;
          z-index: 2;
          color: white;
          font-size: 24px;
          font-weight: 600;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          transition: 0.45s all;
          top: 200px;
          right: 280px;
        }
        .location {
          top: 280px;
          right: 150px;
          position: absolute;
          display: flex;
          flex-direction: column;
          z-index: 3;
          width: 300px;
          white-space: nowrap;
          p{
            color: white;
            font-size: 20px;
            font-weight: 500;
            text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          }
          .stars{
            padding-left: 5px;
            padding-top: 3px;
            scale: 115%;
            .fa-star{
              margin: 1px;
              color: gray;
            }
            .checked {
              color: white;
            }
          }
          .details{
            display: flex;
            flex-direction: row;
            p{
              padding-left: 10px;

            }
            .rate-amount{
              color: white;
              opacity: 75%;
              transition: .4s all ease-in-out;
            }
          }
        }
        .hidden-content {
          top: 180px;
          right: 50px;
          position: absolute;
          display: flex;
          flex-direction: column;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          z-index: 5;
          p{
            max-width: 400px;
            font-size: 18px;
            font-weight: 300;
            color: transparent;
            transition: .35s all ease-in-out;
          }
        }
        .arrow {
          position: absolute;
          z-index: 5;
          top: 315px;
          right: 30px;
          scale: 225%;
        }
        &:hover {
          p.room-info{
            top: 95px;
          }
          .bg{
            filter: blur(2px);
          }
          .details{
            .rate-amount{
              opacity: 100%;
            }
          }
          .hidden-content{
            p{
              color: white;
            }
          }
        }
        .bg{
          width: 100%;
          height: 100%;
          background-image: url("/HotelRoom-2.jpg");
          background-repeat: no-repeat;
          background-size: cover;
          background-position: center;
          z-index: 1;
          position: relative;
          border-radius: 35px;
          border: 2px solid transparent;
          transition: .4s all ease-in-out;
          &:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            width: 100%;
            background: rgba(0, 0, 0, 0.15);
            border-radius: 30px;
          }
        }
      }
      .right-down {
        cursor: pointer;
        p.room-info {
          position: absolute;
          z-index: 2;
          color: white;
          font-size: 24px;
          font-weight: 600;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          transition: 0.45s all;
          top: 570px;
          right: 315px;
        }
        .location {
          top: 660px;
          right: 150px;
          position: absolute;
          display: flex;
          flex-direction: column;
          z-index: 3;
          width: 300px;
          white-space: nowrap;
          p{
            color: white;
            font-size: 20px;
            font-weight: 500;
            text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          }
          .stars{
            padding-left: 5px;
            padding-top: 3px;
            scale: 115%;
            .fa-star{
              margin: 1px;
              color: gray;
            }
            .checked {
              color: white;
            }
          }
          .details{
            display: flex;
            flex-direction: row;
            p{
              padding-left: 10px;

            }
            .rate-amount{
              color: white;
              opacity: 75%;
              transition: .4s all ease-in-out;
            }
          }
        }
        .hidden-content {
          top: 560px;
          right: 50px;
          position: absolute;
          display: flex;
          flex-direction: column;
          text-shadow: 0 0 18px rgba(0, 0, 0, 0.42);
          z-index: 5;
          p{
            max-width: 400px;
            font-size: 18px;
            font-weight: 300;
            color: transparent;
            transition: .35s all ease-in-out;
          }
        }
        .arrow {
          position: absolute;
          z-index: 5;
          top: 695px;
          right: 75px;
          scale: 225%;
        }
        &:hover {
          p.room-info{
            top: 470px;
          }
          .bg{
            filter: blur(2px);
          }
          .details{
            .rate-amount{
              opacity: 100%;
            }
          }
          .hidden-content{
            p{
              color: white;
            }
          }
        }
        .bg{
          width: 100%;
          height: 100%;
          background-image: url("/HotelRoom-1.jpg");
          background-repeat: no-repeat;
          background-size: cover;
          background-position: center;
          z-index: 1;
          position: relative;
          border-radius: 35px;
          border: 2px solid transparent;
          transition: .4s all ease-in-out;
          &:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            width: 100%;
            background: rgba(0, 0, 0, 0.15);
            border-radius: 30px;
          }
        }
      }
    }
  }

</style>