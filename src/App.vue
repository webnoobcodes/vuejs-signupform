<template>
  <div id="app">
    <RegisterForm />
  </div>
</template>

<script>
import RegisterForm from './components/RegisterForm.vue'

export default {
  name: 'app',
  components: {
    RegisterForm
  }
}
</script>

<style lang="scss">
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');
  
  body {
    margin: 0;
    padding: 0;
  }
</style>
