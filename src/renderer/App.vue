<template>
  <div id="app">
    <base-header></base-header>
    <router-view></router-view>
  </div>
</template>

<script>
import BaseHeader from '@/components/base-header';
export default {
  name: 'apiman',
  components: {
    BaseHeader,
  },
};
</script>

<style>
  #app {
    margin: 10px;
  }
</style>
