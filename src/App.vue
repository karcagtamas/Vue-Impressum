<template>
  <v-app>
    <!-- :style="{ backgroundImage: 'url(' + require('@/assets/bg-light.jpg') + ')' }" -->
    <div class="card-image">
      <Navigator></Navigator>
      <Main></Main>
    </div>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';
import Navigator from './components/Navigator.vue';
import Main from './components/Main.vue';

@Component({ components: { Navigator, Main } })
export default class App extends Vue {}
</script>
<style>
.card-image {
  background-size: cover;
  background-position: center;
  opacity: 50%;
}
* {
  font-family: 'Josefin Sans', sans-serif;
}
</style>
