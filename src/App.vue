<template>
  <div id="app">
    <PaymentComponent />
  </div>
</template>

<script>
import PaymentComponent from './components/PaymentComponent.vue';

export default {
  name: 'App',
  components: {
    PaymentComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
