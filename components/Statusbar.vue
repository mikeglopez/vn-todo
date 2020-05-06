<template>
  <view class="statusbar" :style="{ backgroundColor: color}" />
</template>

<script>
export default {
  props: ['color']
}
</script>

<style>
.statusbar {
  height: 45px;
}
</style>