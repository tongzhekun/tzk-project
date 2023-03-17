<!--
 * @Author: Zhekun Tong 1085702426@qq.com
 * @Date: 2023-03-17 09:27:42
 * @LastEditors: Zhekun Tong 1085702426@qq.com
 * @LastEditTime: 2023-03-17 10:06:21
 * @FilePath: \tzk-project\src\App.vue
 * @Description: 这2是默认设置,1请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
     <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
