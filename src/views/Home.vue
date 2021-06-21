<template>
  <div id="home">
    <Header></Header>
    <Image></Image>
  </div>
</template>

<script>
import Header from '../components/home/Header.vue'


export default {
  data() {
    return {}
  },
  components: {
    Header,
    Image
  },
  methods: {}
}
</script>

<style>
#home {
  background-color: #e4e4e4;
}
</style>
