<template>
  <div class="common-layout">

    <el-container>

      <el-header>
        <Header />
      </el-header>

      <el-main>
        <Carousel />
        <Card />
      </el-main>

      <Footer />


    </el-container>

  </div>
</template>

<script>
import Header from "@/components/Header";
import Carousel from "@/components/Carousel";
import Footer from "@/components/Footer";
import Card from "@/components/Card";
export default {
  name: "Container",
  components: {
    Card,
    Footer,
    Carousel,
    Header
  }
}
</script>

<style>
header.el-header{
  padding: 0;
}
.el-header,
.el-footer {
  background-color: #b3c0d1;
  color: var(--el-text-color-primary);
  text-align: center;
  line-height: 60px;
  margin: 0;
}

.el-main {
  background-color: #e9eef3;
  color: var(--el-text-color-primary);
  text-align: center;
  /*line-height: 160px;*/
}

</style>
