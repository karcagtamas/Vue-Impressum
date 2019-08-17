<template>
  <v-app>
    <Navigator></Navigator>
    <Main></Main>
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
