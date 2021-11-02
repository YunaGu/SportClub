<template>
  <div>
    <container />
  </div>
</template>

<style>
</style>

<script>
// @ is an alias to /src

import Carousel from "@/components/Carousel";
import Header from "@/components/Header";
import Container from "@/components/Container";


export default {
  name: 'Home',
  components: {
    Container,
    Header,
    Carousel

  },

}
</script>
