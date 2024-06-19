<script>
import Header from './components/Header.vue'
import Maininfo from "@/components/Maininfo.vue";
import Form1 from "@/components/Form1.vue";

export default {
  name: 'App',
  components: {
    Header,
    Maininfo,
    Form1
  }
}
</script>

<template>
  <div id="app">
    <Header />
    <Maininfo />
    <Form1 />
    <router-view />
  </div>
</template>

<style scoped>

</style>
