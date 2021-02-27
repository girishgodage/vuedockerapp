<template>
  <div class="container">
    <img alt="Vue logo" :src="vueImg" class="vueImg">
    <h1 class="title">
      {{msg}}
    </h1>
    <img alt="docker logo" :src="dockerImg" class="dockerImg">
  </div>
</template>

<script>
import './Home.css';
import vueImg from '../assets/logo.png';
import dockerImg from '../assets/docker.png';
export default {
  name: 'Home',
  props: {
    msg: String
  },
  data: () =>{
    return {
      vueImg,
      dockerImg
    }
  }
}
</script>


