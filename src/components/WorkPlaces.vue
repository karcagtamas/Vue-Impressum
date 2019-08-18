<template>
  <v-col cols="12">
    <h1>Munkatapasztalatok</h1>
    <v-row align="center" justify="center">
      <v-timeline>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2019.06.01. - Mostanáig</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">GLH Consulting Bt.</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                Szoftverfejlesztői állás.
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi minus, fuga eligendi sit sint quos odio ad quo sed debitis animi. Alias expedita eos accusamus, quos earum voluptatibus cum saepe.
                <br />Weboldal:
                <a href="http://glhconsulting.hu" target="_blank">GLH Consulting Bt.</a>
              </v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2017.09.21 - 2019.05.31.</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Logiscool</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                Programozás és informatika oktatása 8-14 éves gyerekek számára.
                <br />Weboldal:
                <a href="http://logiscool.com" target="_blank">Logiscool</a>
              </v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <span slot="opposite">2016.06.01 - 2016.08.31.</span>
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">AUDI Hungária</h2>
            </v-card-title>
            <v-col>
              <v-card-text>Nyári gyakorlat - Diákmunka - Informatikai feladatok ellátása</v-card-text>
            </v-col>
          </v-card>
        </v-timeline-item>
        <v-timeline-item color="purple darken-2">
          <v-card class="elevation-2">
            <v-card-title class="headline purple darken-2">
              <h2 class="display-1 white--text font-weight-light">Rendezvények szervezése</h2>
            </v-card-title>
            <v-col>
              <v-card-text>
                <v-list rounded dense flat>
                  <v-subheader>CAMLEOT MOZGÁSSÉRÜLT EGYESÜLET</v-subheader>
                  <v-list-item-group color="primary">
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>CAMELOT KUPA: 2016, 2015</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Győr városának felmérése mozgássérült szempontból: 2017, 2016, 2015, 2014</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                  </v-list-item-group>
                  <v-subheader>JEDLIK DIÁKÖNKORMÁNYZAT</v-subheader>
                  <v-list-item-group color="primary">
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Gólyatábor: 2018 (főszervező), 2017 (főszervező), 2016, 2015</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Jedlik Diáknap: 2018 (főszervező), 2017 (főszervező), 2016 (főszervező)</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Jedlik 24 órás röplabda vetélkedő: 2019, 2018, 2017, 2016, 2015</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Jedlik 24 órás foci vetélkedő: 2019, 2018 (főszervező), 2017, 2016, 2015, 2014</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                  </v-list-item-group>
                </v-list>
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
export default class WorkPlaces extends Vue {}
</script>
<style>
h1 {
  text-align: center;
  color: black;
}
</style>