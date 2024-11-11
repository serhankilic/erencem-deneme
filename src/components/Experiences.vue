<script setup>

</script>

<template>
  <!-- stars link -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <div class="container-experiences">
    <div class="experiences-heading">
      <p>Let's Hear How Their Experiences</p>
      <p>Use Our Platform</p>
    </div>
    <div class="experiences-cards">
      <swiper
          :slidesPerView="3"
          :spaceBetween="30"
          :freeMode="true"
          :pagination="{
      clickable: true,
    }"
          :modules="modules"
          class="mySwiper"
      >
        <swiper-slide><div class="card card-1">
          <div class="commends">
            <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim illo unde voluptates? Corporis, quaerat, voluptatibus! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, nam."</p>
          </div>
          <div class="persons person-1">
            <div class="persons-pic"></div>
            <div class="persons-name">
              <p class="name">Han Kilic</p>
              <p class="country">Turkey</p>
            </div>
          </div>
          <div class="room-card">
            <div class="room-info">
              <p>Harmony Retreat Freshful</p>
              <p>Greeny Hotel</p>
            </div>
            <div class="location">
              <div class="details">
                <p>Istanbul, Turkey</p>
              </div>
              <div class="vote">
                <div class="stars">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star"></span>
                </div>
                <div class="visitors-amount">
                  <p>(215 Visitors)</p>
                  <div class="arrow">
                    <img src="/icons/arrow-right.svg" alt="#">
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
        </swiper-slide>
        <swiper-slide><div class="card card-3">
          <div class="commends">
            <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim illo unde voluptates? Corporis, quaerat, voluptatibus! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, nam."</p>
          </div>
          <div class="persons person-1">
            <div class="persons-pic"></div>
            <div class="persons-name">
              <p class="name">Bruna Brosque</p>
              <p class="country">Brazil</p>
            </div>
          </div>
          <div class="room-card">
            <div class="room-info">
              <p>Ultra High Castle</p>
              <p>Retreat</p>
            </div>
            <div class="location">
              <div class="details">
                <p>Mugla, Turkey</p>
              </div>
              <div class="vote">
                <div class="stars">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star"></span>
                </div>
                <div class="visitors-amount">
                  <p>(812 Visitors)</p>
                  <div class="arrow">
                    <img src="/icons/arrow-right.svg" alt="#">
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div></swiper-slide>
        <swiper-slide><div class="card card-2">
          <div class="commends">
            <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim illo unde voluptates? Corporis, quaerat, voluptatibus! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, nam."</p>
          </div>
          <div class="persons person-1">
            <div class="persons-pic"></div>
            <div class="persons-name">
              <p class="name">Eren Bakir</p>
              <p class="country">Turkey</p>
            </div>
          </div>
          <div class="room-card">
            <div class="room-info">
              <p>Luxury Comfort Stays</p>
              <p>Hotel</p>
            </div>
            <div class="location">
              <div class="details">
                <p>Bauru, Brazil</p>
              </div>
              <div class="vote">
                <div class="stars">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                </div>
                <div class="visitors-amount">
                  <p>(525 Visitors)</p>
                  <div class="arrow">
                    <img src="/icons/arrow-right.svg" alt="#">
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div></swiper-slide>
        <swiper-slide><div class="card card-4">
          <div class="commends">
            <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim illo unde voluptates? Corporis, quaerat, voluptatibus! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, nam."</p>
          </div>
          <div class="persons person-1">
            <div class="persons-pic"></div>
            <div class="persons-name">
              <p class="name">Joe Stinson</p>
              <p class="country">USA</p>
            </div>
          </div>
          <div class="room-card">
            <div class="room-info">
              <p>Kavalali Luxury Suites</p>
              <p>Boutique Hotel</p>
            </div>
            <div class="location">
              <div class="details">
                <p>Istanbul, Turkey</p>
              </div>
              <div class="vote">
                <div class="stars">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star"></span>
                </div>
                <div class="visitors-amount">
                  <p>(315 Visitors)</p>
                  <div class="arrow">
                    <img src="/icons/arrow-right.svg" alt="#">
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div></swiper-slide>
        <swiper-slide><div class="card card-1">
          <div class="commends">
            <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim illo unde voluptates? Corporis, quaerat, voluptatibus! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, nam."</p>
          </div>
          <div class="persons person-1">
            <div class="persons-pic"></div>
            <div class="persons-name">
              <p class="name">Han Kilic</p>
              <p class="country">Turkey</p>
            </div>
          </div>
          <div class="room-card">
            <div class="room-info">
              <p>Harmony Retreat Freshful</p>
              <p>Greeny Hotel</p>
            </div>
            <div class="location">
              <div class="details">
                <p>Istanbul, Turkey</p>
              </div>
              <div class="vote">
                <div class="stars">
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star checked"></span>
                  <span class="fa fa-star"></span>
                </div>
                <div class="visitors-amount">
                  <p>(215 Visitors)</p>
                  <div class="arrow">
                    <img src="/icons/arrow-right.svg" alt="#">
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div></swiper-slide>

      </swiper>
    </div>
  </div>
</template>

<style>
.container-experiences {
  background: #222222;
  margin: auto;
  padding: 100px 30px;
  .experiences-heading {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding-bottom: 90px;
    p {
      font-size: 3rem;
      font-weight: 500;
      color: white;
    }
  }
  .experiences-cards {
    .card {
      width: 500px;
      height: 700px;
      background-color: #323232;
      border-radius: 20px;
      display: flex;
      flex-direction: column;
      .commends {
        margin: 40px 25px;
        height: 170px;
        max-height: 200px;
        overflow: hidden;
        p {
          color: white;
          font-weight: 300;
          font-size: 1.3rem;
        }
      }
      .persons {
        display: flex;
        flex-direction: row;
        margin: 0 25px;
        align-items: center;
        .persons-pic {
          width: 75px;
          height: 75px;
          border-radius: 50%;
          background-color: white;
        }
        .persons-name {
          display: flex;
          flex-direction: column;
          padding-left: 20px;
          row-gap: 5px;
          .name {
            font-size: 20px;
            color: white;
            font-weight: 400;

          }
          .country {
            font-size: 20px;
            color: lightgray;
            font-weight: 300;
          }

        }
      }
      .room-card {
        margin: auto;
        width: 90%;
        height: 40%;
        background-color: transparent;
        border-radius: 25px;
        cursor: pointer;
        .room-info {
          display: flex;
          flex-direction: column;
          margin: 130px 15px 0;
          position: relative;
          z-index: 3;
          p {
            color: white;
            font-size: 24px;
            font-weight: 600;
          }
        }
        .location {
          display: flex;
          flex-direction: column;
          margin: 0 15px;
          position: relative;
          z-index: 3;
          p {
            color: white;
          }
          .details {
            padding-top: 10px;
            p {
              font-size: 18px;
            }
          }
          .vote {
            display: flex;
            flex-direction: row;
            padding-top: 5px;
            white-space: nowrap;

            .stars {
              padding-right: 10px;
              .fa {
                color: darkgray;
                margin: 0 1px;
              }
              .checked {
                color: white;
              }
            }
            .visitors-amount {
              display: flex;
              flex-direction: row;
              justify-content: space-between;
              width: 100%;
              p {
                font-weight: 300;
              }
              img {
                width: 25px;
                scale: 150%;
              }
            }
          }
        }
        &:hover {
          -webkit-box-shadow: 0 0 30px 2px rgba(0,0,0,0.15);
          -moz-box-shadow: 0 0 30px 2px rgba(0,0,0,0.15);
          box-shadow: 0 0 30px 2px rgba(0,0,0,0.15);
          &:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            width: 100%;
            background: rgba(0, 0, 0, 0.55);
            border-radius: 25px;
          }
        }
      }
    }
    .card-1 {
      .room-card {
        background-image: url("/HotelRoom-1.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        border-radius: 25px;
        z-index: 1;
        position: relative;

        &:before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          width: 100%;
          background: rgba(0, 0, 0, 0.25);
          border-radius: 25px;
          transition: .4s all;

        }
      }

    }
    .card-2 {
      .room-card {
        background-image: url("/HotelRoom-2.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        border-radius: 25px;
        z-index: 1;
        position: relative;

        &:before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          width: 100%;
          background: rgba(0, 0, 0, 0.25);
          border-radius: 25px;
          transition: .4s all;

        }
      }

    }
    .card-3 {
      .room-card {
        background-image: url("/HotelRoom-3.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        border-radius: 25px;
        z-index: 1;
        position: relative;

        &:before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          width: 100%;
          background: rgba(0, 0, 0, 0.25);
          border-radius: 25px;
          transition: .4s all;

        }
      }

    }
    .card-4 {
      .room-card {
        background-image: url("/roomtype-1.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        border-radius: 25px;
        z-index: 1;
        position: relative;

        &:before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          width: 100%;
          background: rgba(0, 0, 0, 0.25);
          border-radius: 25px;
          transition: .4s all;

        }
      }

    }
  }
}
.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

</style>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/free-mode';
import 'swiper/css/pagination';

// import required modules
import { FreeMode, Pagination } from 'swiper/modules';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [FreeMode, Pagination],
    };
  },
};
</script>