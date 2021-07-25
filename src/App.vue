<template>
  <div id="app">
      <Header></Header>
      <MusicSearch></MusicSearch>
      <MusicContent></MusicContent>
  </div>
</template>

<script>
import Header from './components/header/Header.vue'
import MusicContent from './components/musicContent/musicContent.vue'
import MusicSearch from './components/musicSearch/MusicSearch.vue'

export default {
  name: 'App',
  
  components: {
    Header,
    MusicContent,
    MusicSearch
  }
}
</script>

<style>
@import './assets/css/setting.css';
@import './assets/css/style.css';
</style>
