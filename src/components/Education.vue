<template>
  <v-col cols="12">
    <h1>Tanulmányok</h1>
    <v-row align="center" justify="center">
      <v-timeline>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">Most - 2019</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Egyetem</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                Győri Széchenyi István Egyetem
                <br />Weblap:
                <a href="https://uni.sze.hu/kezdolap">Széchenyi István Egyetem</a>
                <br />
                <v-img src="../assets/egyetem.png" class="white--text" height="auto" width="100%">
                  <v-card-title class="align-end fill-height">Karcag Tamás</v-card-title>
                </v-img>
              </v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2019 - 2018</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Szakközépiskola - OKJ</h2>
            </v-card-title>
            <v-col>
              <v-card-text>Győri Műszaki Szakképzési Centrum Jedlik Ányos Gépipari és Informatikai Szakgimnáziuma, Szakközépiskolája és Kollégiuma - Szoftverfejlesztő szak - 1 éves OKJ-s képzés</v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2018 - 2014</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Szakközépiskola</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                Győri Műszaki Szakképzési Centrum Jedlik Ányos Gépipari és Informatikai Szakgimnáziuma, Szakközépiskolája és Kollégiuma - Szoftverfejlesztő szak - 4 éves érettségi képzés
                <br />Weblap:
                <a href="https://jedlik.eu">Jedlik</a>
                <br />
                <v-img src="../assets/jedlik.png" class="white--text" height="auto" width="100%">
                  <v-card-title class="align-end fill-height">Karcag Tamás</v-card-title>
                </v-img>
              </v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2014 - 2007</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Általános iskola</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                Győrújbaráti II. Rákóczi Ferenc Általános Iskola
                <br />Weblap:
                <a href="https://www.baratisuli.hu">Jedlik</a>
              </v-card-text>
            </v-col>
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
export default class Education extends Vue {}
</script>
<style>
h1 {
  text-align: center;
  color: black;
}
</style>