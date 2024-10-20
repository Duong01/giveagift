<template>
  <van-config-provider theme="light">
    <router-view> </router-view>
</van-config-provider>
</template>

<script>
export default {
  name: "LayoutPage"
};
</script>

<style>
.van-button--primary {
  color: var(--van-button-primary-color);
  background-color: var(--van-button-primary-background);
}
:root {
  --van-white: #fff;
  --van-blue: #1989fa;
  --van-button-primary-color: var(--van-white);
  --van-button-primary-background: var(--van-primary-color);
}
.van-theme-dark body {
  color: #fff;
  background-color: black;
}
</style>