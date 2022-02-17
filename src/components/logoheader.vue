<template>
  <nav>
    <div class="container">
      <img class="logo-client" src="../assets/screen_0/navBar_img0.png" alt="">
      <div class="div_header"></div>
      <h1>Gestão do Tempo</h1>
      <img class="img_ampulheta" src="../assets/screen_0/navBar_img1.png">
    </div>
  </nav>
</template>

<style lang="scss" scoped>
//  @import '';

  nav {
    z-index: 9999;
    margin: 0 auto;
    height: 80px;
    width: 100%;
    position: fixed;
  }

  .container {
    display: flex;
    align-items: center;
    width: 100%;
    height: 80px;
    background-color: black;
    
    .div_header{
      position: relative;
      background-color: #ffb500;
      height: 60px;
      width: 2px;
      margin-left: 2%;
    }
  }

  h1 {
    font-size: 40px;
    color: #ffb500;
    margin-left: 2%;
  }

  .img_ampulheta{
    position: absolute;
    right: 5%;
  }

  .logo-client{
    display: flex;
    margin-left: 3%;
  }
</style>
