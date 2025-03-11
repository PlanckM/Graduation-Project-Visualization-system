<template>
  <div id="cesiumContainer" ref="cesiumContainer"></div>
</template>

<script>
import * as Cesium from "cesium";
import "cesium/Build/Cesium/Widgets/widgets.css"; // 从 node_modules 引入 Cesium 的 CSS
import { onMounted } from 'vue';

// 设置 Cesium 的静态资源路径
window.CESIUM_BASE_URL = "/";

export default {
  setup() {
    onMounted(() => {
      console.log("Cesium Container:", document.getElementById("cesiumContainer"));
      var viewer = new Cesium.Viewer("cesiumContainer");
    });
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#cesiumContainer {
  width: 100vw;
  height: 100vh;
}
</style>