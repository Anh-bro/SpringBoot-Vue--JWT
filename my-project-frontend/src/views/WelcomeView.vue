<script setup>

</script>

<template>
  <div style="width: 100vw;height: 100vh;overflow: hidden;display: flex">
    <div style="flex: 1;background-color: black">
      <el-image style="width: 100%;height: 100%" src="https://img1.imgtp.com/2023/09/23/VFhUvRad.jpg" fit="cover"/>
    </div>
    <div class="welcome-title">
      <div style="font-size: 30px;font-weight: bold;">恨君不似江楼月，南北东西，南北东西，只有相随无别离。</div>
      <div style="margin-top: 10px">遇事不决，可问春风。</div>
      <div style="margin-top: 5px">乘上与平时相反的列车，为了去见从未见过的风景。</div>
    </div>
    <div class="right-card">
      <router-view/>
    </div>

  </div>
</template>

<style scoped>
.welcome-title{
  position: absolute;
  bottom: 30px;
  left: 30px;
  color:white;
  text-shadow:0 0 10px black ;
}
.right-card {
  width: 400px;
  z-index: 1;
  background-color: white;
}
</style>