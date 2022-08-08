<script setup lang="ts">
</script>

<template>
  <div class="container">

    <div class="left">
      <img class="logo" src="@/assets/logo.png" alt="">
      <p>YouTube</p>
    </div>

    <div class="middle">
      <input type="text">
      <button> </button>
    </div>

    <div class="right">
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
    </div>

  </div>
</template>

<style>
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.left {
  display: flex;
  align-items: center;
  justify-content: center;
}

.logo {
  width: 100px;
}

.middle {
  display: flex;
}

.right {
  display: flex;
}
</style>
