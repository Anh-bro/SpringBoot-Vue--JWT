<script setup>
import {logOut} from "@/net";
import router from "@/router";

function userLogout(){
  logOut(()=>{
    router.push('/')
  })
}
</script>

<template>
  <div>
    <el-button @click="userLogout">退出登录</el-button>
  </div>
</template>

<style scoped>

</style>