
<template>
<div class="container-reservation">
  <div class="reservation-content">
    <div class="location input">
      <div class="upside">
        <img src="../../public/icons/location.svg" alt="">
        <label for="location">Location</label>
      </div>
      <div class="downside">
        <input
            type="text"
            v-model="location"
            placeholder="   Type location"
            @focus="openDropdown('location')"
            class="input-box"
        />
        <div v-if="dropdowns.location" class="dropdown">
          <p v-for="(option, index) in locationOptions" :key="index" @click="selectOption('location', option)">
            {{ option }}
          </p>
        </div>
      </div>
    </div>
    <div class="people input">
      <div class="upside">
        <img src="../../public/icons/person.svg" alt="">
        <label for="people">People</label>
      </div>
      <div class="downside">
        <div class="arrow-flex">
          <input
              type="text"
              v-model="person"
              placeholder="   Person"
              @focus="openDropdown('person')"
              class="input-box"
          /> <img src="../../public/icons/down.svg" alt="">
        </div>
        <div v-if="dropdowns.person" class="dropdown">
          <p v-for="(option, index) in personOptions" :key="index" @click="selectOption('person', option)">
            {{ option }}
          </p>
        </div>
      </div>
    </div>
    <div class="check-in input">
      <div class="upside">
        <img src="/icons/calendar.svg" alt="">
        <label for="calendar">Check-in</label>
      </div>
      <div class="downside">
        <input
            id="calendar"
            type="date"
            v-model="checkIn"
            class="input-box"
        />
      </div>
    </div>
    <div class="check-out input">
      <div class="upside">
        <img src="../../public/icons/calendar.svg" alt="">
        <label for="checkout">Check-out</label>
      </div>
      <div class="downside">
        <input
            id="checkout"
            type="date"
            v-model="checkOut"
            class="input-box"
            style=""
        />
      </div>
    </div>
    <div class="search">
      <div class="upside">
      </div>
      <label for="search-button">
        <button class="search-button" id="search-button" type="button">Search</button>
      </label>
    </div>
  </div>
</div>
</template>
<style>
.container-reservation{
  max-width: 1500px;
  height: 200px;
  background-color: white;
  border-radius: 15px;
  .reservation-content{
    display: flex;
    flex-direction: row;
    padding-top: 20px;
    justify-content: space-around;
    .input{
      align-content: center;
      align-items: center;

      .upside{
        height: 50px;
        width: 200px;
        align-content: center;
        text-align: start;
        margin-left: 10px;
        margin-bottom: 5px;
        img{
          scale: 200%;
          align-items: center;
        }
        label{
          height: 100%;
          font-size: 22px;
          margin:0 10px 0;
          color: black;
          font-weight: 500;

        }
      }
      .downside{
        max-width: 200px;
        position: relative;
        .input-box{
          width: 195px;
          height: 75px;
          border: 1px solid transparent;
          border-radius: 10px;
          font-size: 20px;
          text-align: start;
          background-color: #f7f7f7;
          color: #acacac;
        }
        .dropdown {
          position: absolute;
          top: 100%;
          left: 0;
          background-color: #ffffff;
          border: 1px solid #ddd;
          border-radius: 4px;
          box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
          width: 200px;
          margin-top: 5px;
        }

        .dropdown p {
          padding: 8px;
          margin: 0;
          cursor: pointer;
        }

        .dropdown p:hover {
          background-color: #f0f0f0;
        }
        .arrow-flex{
          display: flex;
          flex-direction: row;
          position: relative;
          img{
            position: absolute;
            right: 20px;
            top: 40%;
            scale: 150%;
          }
        }
      }
    }
    .search{
      .search-button{
        width: 200px;
        height: 75px;
        font-size: 22px;
        border-radius: 10px;
        border: none;
        background-color: black;
        color: white;
        cursor: pointer;
      }
      .upside{
        height: 50px;
        width: 200px;
        align-content: center;
        text-align: start;
        margin-left: 10px;
        visibility: hidden;
        margin-bottom: 5px;

      }
    }
  }
}
</style>
<script>
export default {
  data() {
    return {
      location: "",
      person: "",
      checkIn: "",
      checkOut: "",
      dropdowns: {
        location: false,
        person: false,
      },
      locationOptions: ["New York", "Los Angeles", "Chicago"],
      personOptions: ["1 Person", "2 Persons", "3 Persons"],
    };
  },
  methods: {
    openDropdown(type) {
      this.closeAllDropdowns();
      this.dropdowns[type] = true;
    },
    closeAllDropdowns() {
      this.dropdowns.location = false;
      this.dropdowns.person = false;
    },
    selectOption(type, option) {
      this[type] = option;
      this.closeAllDropdowns();
    },
    search() {
      alert(`Searching for: Location - ${this.location}, Person - ${this.person}, Check-in - ${this.checkIn}, Check-out - ${this.checkOut}`);
    }
  },
  mounted() {
    document.addEventListener("click", (e) => {
      if (!this.$el.contains(e.target)) {
        this.closeAllDropdowns();
      }
    });
  },
  beforeDestroy() {
    document.removeEventListener("click", this.closeAllDropdowns);
  },
};
</script>
<script setup lang="ts">
</script>
