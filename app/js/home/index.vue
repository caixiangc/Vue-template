<template lang="html">
    <div :class="$style.home">
        <h1>Home</h1>
        <h2>这样就打包好了</h2>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" module>
  @import '../../css/reset.scss';
  .home{
    color: red;
    font-size: 80px;
  }
</style>
