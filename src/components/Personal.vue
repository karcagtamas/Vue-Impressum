<template>
  <v-col cols="12">
    <v-row align="center" justify="center">
      <v-card class="mx-auto" :raised="true" cols="sm">
        <v-img src="../assets/me.jpg" class="white--text" height="auto" width="500px" id="img">
          <v-card-title class="align-end fill-height">Karcag Tamás</v-card-title>
        </v-img>
        <v-card-text>
          <v-list rounded dense flat>
            <v-subheader>SZEMÉLYES ADATOK</v-subheader>
            <v-list-item-group color="primary">
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-account-circle</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Név: Karcag Tamás</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-account-circle</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Születési hely és idő: Győr, 1999. 07. 26.</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-home</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Lakhely: 9081, Győrújbarát László utca 120.</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-phone</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Telefonszám: +36 30 639 0722</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-mail</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>E-mail 1: karcagtamas@gmail.com</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-mail</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>E-mail 2: karcagtamas@outlook.com</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-cloud</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Facebook: tamas.karcag</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-icon>mdi-cloud</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title>Discord: karcagtamas#3271</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list-item-group>
          </v-list>
        </v-card-text>
      </v-card>
    </v-row>
  </v-col>
</template>
<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component({})
export default class Personal extends Vue {}
</script>