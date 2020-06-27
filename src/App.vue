<template>
  <div id="app">
        <!-- <run-index></run-index> -->
    
    <tab-bar-menu></tab-bar-menu>
    <router-view></router-view> 
  </div>
</template>

<script>

import RunIndex from './views/RunIndex';
import TabBarMenu from './components/common/TabBarMenu/TabBarMenu'

export default {
  name: 'App',
  components: {
    RunIndex,
    TabBarMenu
  }
}
</script>

<style>
@import './assets/css/base.css';
</style>
