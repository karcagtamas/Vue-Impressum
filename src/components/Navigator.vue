<template>
  <v-app-bar app color="deep-purple accent-4" :elevate-on-scroll="true" dense dark>
    <v-app-bar-nav-icon>
      <v-menu left bottom origin="center center" transition="scale-transition" :offset-x="true">
        <template v-slot:activator="{ on }">
          <v-btn icon v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item href="http://csomormaker.karcags.hu">
            <v-list-item-title>Csömörmaker</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar-nav-icon>
    <v-toolbar-title class="headline text-uppercase">
      <span>Karcag Tamás - karcags.hu</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-magnify</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component({})
export default class Navigator extends Vue {}
</script>

<style>
</style>