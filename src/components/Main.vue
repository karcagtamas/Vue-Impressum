<template>
  <v-container fluid>
    <div>
      <div id="denethor"></div>
      <Personal></Personal>
      <Education></Education>
      <WorkPlaces></WorkPlaces>
      <Competitions></Competitions>
    </div>
  </v-container>
</template>
<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';
import Personal from './Personal.vue';
import WorkPlaces from './WorkPlaces.vue';
import Education from './Education.vue';
import Competitions from './Competitions.vue';

@Component({ components: { Personal, WorkPlaces, Education, Competitions } })
export default class Main extends Vue {}
</script>

<style scoped>
#img {
  margin: 1rem;
}
#denethor {
  height: 40px;
  clear: both;
}
h1 {
  text-align: center;
  color: black;
}
</style>