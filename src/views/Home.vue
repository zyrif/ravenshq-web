<template>
  <div class="container">
    <Logo />
    <Message msg="Building The Nest"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Logo from '@/components/Logo.vue'
import Message from '@/components/Message.vue'

export default {
  name: 'home',
  components: {
    Message,
    Logo
  }
}
</script>

<style scoped>

.container {
  display: flex;
  flex-direction: column;
  height: 100%;
  min-height: 100%;
}

.spacer {
  display: flex;
  flex-direction: column;
  flex: 1;
}

</style>


