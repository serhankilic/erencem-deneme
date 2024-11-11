<script setup>
</script>
<template>
  <div class="footer-container">
    <div class="upside">
      <div class="links">
        <div class="page link-column">
          <p>Page</p>
          <a href="#">Home</a>
          <a href="#">Search</a>
          <a href="#">Blog</a>
          <a href="#">About Us</a>
        </div>
        <div class="features link-column">
          <p>Features</p>
          <a href="#">Find Hotels</a>
          <a href="#">Book Hotels</a>
          <a href="#">Reviews</a>
        </div>
        <div class="cookies link-column">
          <p>Cookies</p>
          <a href="#">Data Collect</a>
          <a href="#">Terms</a>
          <a href="#">Privacy</a>
          <a href="#">Laws</a>
        </div>

      </div>
      <div class="offer">
        <div class="details">
          <div class="main-offer">
            <p>Don't Wanna<br>Miss Our Offers?</p>
          </div>
          <div class="offer-description">
            <p>You guys better subscribe to <br>our daily news letter</p>
          </div>
        </div>
        <div class="form">
          <input type="email" placeholder="Your email@mail.com" required>
        </div>
        <div class="subscribe">
          <input type="button" required value="Subscribe" />
        </div>
      </div>
    </div>

  </div>
</template>
<style>
* {
  margin: 0;
  padding: 0;
}
.footer-container {
  padding: 10px 40px;
  width: 1500px;
  height: 400px;
  margin: 50px auto auto;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  .upside {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    .links {
      width: 600px;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      .link-column {
        display: flex;
        flex-direction: column;
        row-gap: 10px;
        align-items: flex-start;
        p {
          font-size: 30px;
          font-weight: 600;
        }
        a {
          color: black;
          text-decoration: none;
          font-weight: 400;
          font-size: 24px;
          color: gray;
          transition: 0.3s color;
          &:hover {
            color: black;
          }
        }
      }
    }
    .offer {
      width: 700px;
      height: 300px;
      padding: 0 30px;
      border-radius: 30px;
      background-color: #f1f0f0;
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      .details {
        width: 700px;

        display: flex;
        flex-direction: row;
        justify-content: space-between;
        .main-offer {
          max-width: 400px;
          max-height: 100px;
          p {
            font-size: 30px;
            font-weight: 600;
          }
        }
        .offer-description {
          min-width: 300px;
          max-height: 100px;
          align-content: center;
          p {
            font-size: 18px;
            color: gray;
          }
        }
      }
      .form {
        input {
          border: none;
          width: 450px;
          height: 50px;
          background-color: transparent;
          border-bottom: 1px solid gray;
          font-size: 20px;
          padding-left: 10px;
          font-family: "Open Sans", sans-serif;
          &:focus-within {
            outline: none;
          }
        }
      }
      .subscribe {
        input {
          width: 200px;
          height: 50px;
          background-color: black;
          color: white;
          font-family: "Open Sans", sans-serif;
          font-size: 20px;
          font-weight: 300;
          border-radius: 40px;
          cursor: pointer;
        }
      }
    }
  }
}
</style>