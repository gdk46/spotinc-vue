<template>
  <div id="app">
      <Header></Header>
      <MusicSearch></MusicSearch>
  </div>
</template>

<script>
import Header from './components/header/Header.vue'
import MusicSearch from './components/musicSearch/MusicSearch.vue'

export default {
  name: 'App',
  components: {
    Header,
    MusicSearch
  }
}
</script>

<style>
@import './assets/css/nomarlize-app.css';
@import './assets/css/setting.css';
@import './assets/css/style.css';
</style>
