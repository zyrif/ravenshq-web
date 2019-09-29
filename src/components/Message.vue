<template>
    <div class="message-container">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    name: 'Message',
    props: {
        msg: String
    }
}
</script>

<style scoped>
  h1 {
    font-family: "Anders";
    font-weight: lighter;
    font-size: 4em;
    color: white;
    text-align: center;
    margin: 30px auto 30px auto;
    padding: 0 5% 0 5%;
 }

  @media screen and (max-width: 600px) {
    h1 {
      font-size: 3em;
      padding-top: 5%
    }
  }

  @media screen and (max-height: 450px) {
    h1 {
      margin-top: 10px;
      font-size: 2em;
      margin-bottom: 10px;
      padding-bottom: 10px;
    }
  }

  @media screen and (min-height: 1024px) {
    h1 {
      font-size: 5em;
    }
  }

</style>