<template>
  <div class="header-bar">
    <h1 class="logo">
      <router-link to="{ name: 'homepage'}">豆瓣</router-link>
    </h1>
    <ul>
      <li>
        <router-link>电影</router-link>
      </li>
      <li>
        <router-link>图书</router-link>
      </li>
      <li>
        <router-link>广播</router-link>
      </li>
      <li>
        <router-link>小组</router-link>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'header-bar'
}
</script>
<style>
  .header-bar {
    position: fixed;
    top:0;
    left: 0;
    width: 100%;
    height: 4.8rem;
    border-bottom:.1rem solid #f3f3f3;
    background-color: #fff;
  }
</style>
