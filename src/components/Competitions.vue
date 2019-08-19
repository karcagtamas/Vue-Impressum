<template>
  <v-col cols="12">
    <h1>Versenyek</h1>
    <v-row align="center" justify="center">
      <v-timeline>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2019</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2
                class="display-1 white--text font-weight-light"
              >Országos Szakmai Tanulmányi Verseny (OSZTV) - 2. helyezett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2019</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2
                class="display-1 white--text font-weight-light"
              >EuroSkills 2020 Graz Web Developer - 10. helyezett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2018</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Skills Junior 2018 - 12. helyezett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2017</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2
                class="display-1 white--text font-weight-light"
              >WRO Országos Forduló csapatban - 8.helyezett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2017</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2
                class="display-1 white--text font-weight-light"
              >Zrínyi Ilona Matematika Verseny megyei - 7. helyzett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2016</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">IV. IT Essentials - 10. helyzett</h2>
            </v-card-title>
          </v-card>
        </v-timeline-item>
      </v-timeline>
    </v-row>
  </v-col>
</template>
<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component({})
export default class Competitions extends Vue {}
</script>
<style>
h1 {
  text-align: center;
  color: black;
}
</style>