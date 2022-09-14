# bo-zoomer
```txt
zoomer/vue3
```
# 安装
```txt
npm i bo-zoomer
```
# 使用
```vue
<script setup>
// 引入文件
import Zoomer from 'bo-zoomer';
</script>
<template>
  <zoomer
    class="goods-detail-zoomer"
    img-src="图片路径"
  />
</template>
<style>
/* 手动添加类名设置宽高 */
.goods-detail-zoomer {
  width: 400px;
  height: 400px;
}
</style>
```
# *注
```txt
该组件默认无宽高，根据需求手动设置宽高
```
