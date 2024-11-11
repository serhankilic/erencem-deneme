<script setup>
</script>
<template>
<div class="links">
  <div class="left-side">
    <a href="#" class="logo">Hanstays</a>
  </div>
  <div class="right-side">
    <a href="#" class="header-link active">Home</a>
    <a href="#" class="header-link">Search</a>
    <a href="#" class="header-link">Blog</a>
    <a href="#" class="header-link">About Us</a>
    <a href="#" class="header-button">Sign in</a>
    <a href="#" class="header-button register">Register</a>
  </div>
</div>
</template>
<style scoped>
a{
  text-decoration: none;
  color: white;
  font-size: 20px;
}
.links{
  max-width: 1500px;
  display: flex;
  margin:0 auto ;
  padding-top: 35px;
  justify-content: space-between;
  .left-side{
    .logo{
      font-size: 36px;
      font-weight: 500;
    }
  }
  .right-side{

    .header-link{
      margin: 0 20px;
      font-weight: 300;
      opacity: 60%;
      border-bottom: 1px solid transparent;
      transition: .3s all;
      &:hover{
        opacity: 100%;
        border-bottom: 1px solid white;
      }
    }
    .active{
      opacity: 100%;
      border-bottom: 1px solid white;
    }
    .header-button{
      padding: 10px 25px;
      margin: 0 5px;
      border: 1px solid white;
      border-radius: 25px;
      font-weight: 400;
      font-size: 22px;
      background-color: rgba(0, 0, 0, .1);
      transition: .3s all;
      &:hover{
        background-color: rgba(0, 0, 0, .3);
      }
    }
    .register{
      background-color: white;
      color:black;
      transition: 0.3s all;
      &:hover{
        background-color: rgba(0, 0, 0, .3);
        color: white;
      }
    }
  }
}
</style>