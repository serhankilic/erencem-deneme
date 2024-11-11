<script setup></script>
<template>
  <div class="container">
    <div class="main-content">
      <div class="explore-hotels">
        <p>Exlore Our Best List</p>
        <p>5-Star Hotel!</p>
      </div>
      <div class="find-hotels">
        <p>We understand that every travaler has different preferences. That's why our platforms good.</p>
        <input
          type="search"
          class="search-hotel"
          placeholder="Find Hotel"
          style="width: 550px; height: 50px; outline-color: darkgray"

          >
      </div>
    </div>

  </div>
</template>
<style>
* {
  font-family: "Poppins", sans-serif;
}
.container {
  width: 100%;
  .main-content {
    max-width: 1500px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 50px auto;
    .explore-hotels {
      p{
        font-size: 3em;
        font-weight: 600;
      }
    }
    .find-hotels {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
      p {
        max-width: 600px;
        font-size: 1.4em;
        font-weight: 400;
        color: rgba(72, 72, 72, 0.75);

      }
      .search-hotel {
        margin-top: 20px;
        border-radius: 35px;
        padding-left: 15px;
        font-size: 1.2em;
        border: 1px solid rgba(72, 72, 72, 0.75);
      }
    }
  }
  .bg-find{
    visibility: hidden;
    width: 100%;
    overflow: hidden;
    p{
      top: -100px;
      right: -200px;
      position: absolute;
      font-size: 22rem;
      font-weight: bold;
      color: gray;
      opacity: 10%;
      white-space: nowrap;
      overflow: hidden;
    }
  }
}
</style>