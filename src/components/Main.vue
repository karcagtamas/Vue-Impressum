<template>
  <div>
    <div id="denethor"></div>
    <v-card class="mx-auto" :raised="true">
      <v-img src="../assets/raven.jpg" class="white--text" height="200px" width="300px" id="img">
        <v-card-title class="align-end fill-height">Karcag Tamás</v-card-title>
      </v-img>
      <v-card-text>I'm card text</v-card-text>
    </v-card>
  </div>
</template>
</template>
<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component({})
export default class Main extends Vue {}
</script>

<style scoped>
#img {
  margin: 1rem;
}
#denethor {
  height: 100px;
  clear: both;
}
</style>