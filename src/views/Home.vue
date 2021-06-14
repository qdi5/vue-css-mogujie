<template>
  <div class="home">
    <header>css架构</header>
    <a href="http://www.baidu.com">百度</a>
    <input type="text" value="heihei">
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style lang="scss" scoped>
header {
  width: 200px;
  height: 200px;
  background: red;
  color: #fff;
  @include box-center(center, center);
}
  
</style>
