<template>
  <div class="home">
    <div class="img"></div>
    <!-- <img alt="Vue logo" src="../assets/feynman.jpg" /> -->
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue"

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
}
</script>

<style scoped>
.img {
  background-image: url(../assets/feynman.jpg);
  width: 200px;
  height: 200px;
  background-size: cover;
  border-radius: 50%;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.35);
}
.home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
