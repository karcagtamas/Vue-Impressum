<template>
  <v-col cols="12">
    <h1>Szabadidős tevékenység</h1>
    <v-row align="center" justify="center">
      <v-timeline>
        <v-timeline-item color="purple darken-2">
          <v-card class="elevation-2">
            <v-col>
              <v-card-text>Jedlik Diákönkormányzat tagja vagyok 2014 óta. Az itt végzet munkám közbe rengeteget tanultam a programok szervezéséről és lebonyolításáról és mind eközben megtapasztaltam milyen csapatban dolgozni, illetve vezetőnek lenni. A mai napig segédkezem kisebb-nagyob rendezvények lebonyolításában, mint például gólyatábor vagy egy 24 órás rendezvény</v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <v-card class="elevation-2">
            <v-col>
              <v-card-text>A NICSI JUDO CLUB tagja voltam 2005 és 2015 között. Megtanultam az évek során a nyugodtság és a pontosság fogalmát, és ezeket minden edzésen gyakorlom, hogy fent tudjam tartani magamban a testi és lelki harmóniát.</v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <v-card class="elevation-2">
            <v-col>
              <v-card-text>A Jedlik LEGO Robot Programozás csoport tagja voltam 2015 és 2017 között. Sok tapasztalatot szereztem a LEGO NXT, illetve a LEGO EV3 robotok programozása közben és több versenyen is részt vettem, amiken tudtam fejleszteni a probléma megoldó képességemet.</v-card-text>
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
export default class Freetime extends Vue {}
</script>
<style>
h1 {
  text-align: center;
  color: black;
}
</style>