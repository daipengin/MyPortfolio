<script setup>
  import MainHeader from "@/components/MainHeader.vue";
  import 黒パール from "@/assets/img/page1/main.jpg";
  import ダーク胡蝶 from "@/assets/img/page2/main.jpg";
</script>

<template>
  <MainHeader></MainHeader>

  <h1>作品一覧</h1>
  <div class="wrapper">
    <h2><a href="#/page1"><img class="subimg" :src="黒パール" /><br>黒パール</a></h2>
    <h2><a href="#/page2"><img class="subimg" :src="ダーク胡蝶"  /><br>ダーク胡蝶</a></h2>
  </div>
  
</template>

<style>
.subimg{
  height: 400px;
  width: 400px;
  object-fit: cover;
}
.wrapper {
  display: grid;
  grid-template-columns: 400px 400px;
}
</style>