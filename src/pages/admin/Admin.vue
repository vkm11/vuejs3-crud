<template>
  <Nav />
  <div class="wrapper">
    <div class="left-content">
      <SideBar />
    </div>
    <div class="right-content">
      <router-view />
    </div>
  </div>
</template>

<script>
import Nav from "@/components/Nav";
import SideBar from "@/components/SideBar";
export default {
  name: "Admin-vue",
  components: {
    Nav,
    SideBar,
  },
};
</script>

<style>
</style>