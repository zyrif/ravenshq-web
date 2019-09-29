<template>
  <div class="logo-container">
    <img alt="RavensHQ logo" src="../assets/logo.png">
  </div>
</template>

<script>
export default {
    name: 'Logo'
}
</script>

<style scoped>
  img {
    display: flex;
    justify-content: center;
    margin: 5% auto;
    width: 23%;
    min-width: 320px;
    vertical-align: middle;
  }
  .logo-container {
    display: flex;
    flex-flow: column;
    height: 100%;
    margin-bottom: 0%;

  }

  @media screen and (max-width: 960px) {
    img {
        min-width: 270px;
    }
    .logo-container {
      margin-top: 10%
    }
  }
  @media screen and (max-width: 600px) {
    img {
        min-width: 230px;
    }
    .logo-container {
      margin-top: 20%
    }
  }

  @media screen and (max-height: 450px) {
    .logo-container {
      margin-top: 10px;
      padding-top: 10px;
      margin-bottom: 0px;
    }
    img {
        min-width: 200px;
    }
  }

  @media screen and (min-height: 1024px) {
    img {
      min-width: 500px;
    }

    .logo-container {
      margin-top: 5%;
    }
  }
</style>