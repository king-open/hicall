<!-- eslint-disable vue/multi-word-component-names -->

<template>
  <div class="nav">
      <router-link to="/money">标记</router-link>
      ｜
      <router-link to="/labels">记账</router-link>
      ｜
      <router-link to="/statistics">统计</router-link>
    </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
.nav{
  border: 1px solid red;
}
</style>
