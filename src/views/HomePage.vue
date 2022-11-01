<template>
  <ion-page>
    <ion-list>
      <ion-row>
        <ion-title>Home</ion-title>
      </ion-row>
      </ion-list>
    <ion-content>
          <ion-grid>
            <ion-row>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Kolam 
                    </ion-card-subtitle>
                    <ion-card-title>
                      10
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Kolam Aktif 
                    </ion-card-subtitle>
                    <ion-card-title>
                      8
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
            </ion-row>
            <ion-row>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Ikan Hidup 
                    </ion-card-subtitle>
                    <ion-card-title>
                      182 Ekor
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Ikan mati 
                    </ion-card-subtitle>
                    <ion-card-title>
                      89 Ekor
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
            </ion-row>
            <ion-row>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Panen 2022 
                    </ion-card-subtitle>
                    <ion-card-title>
                      109 Kg
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-subtitle>
                      Total Pakan
                    </ion-card-subtitle>
                    <ion-card-title>
                      223 Kg
                    </ion-card-title>
                  </ion-card-header>
                </ion-card>
              </ion-col>
            </ion-row>
            </ion-grid>
            <ion-title>
              TOTAL BERAT IKAN
            </ion-title>
            <div class='ikan'>
              <ion-grid>
                <ion-row>
                  <ion-col>
                    <ion-card color = 'dark'>
                      <img src="images/lele.jpg">
                      <Ion-card-header>
                        <ion-card-title>IKAN LELE</ion-card-title>
                        <ion-card-subtitle color = 'secondary'>
                          <span style='color: #6cb5ec; display: inline-block'>
                            200 Kg
                          </span>
                        </ion-card-subtitle>
                      </Ion-card-header>
                    </ion-card>
                  </ion-col>
                  <ion-col>
                    <ion-card color = 'dark'>
                      <img src="images/nila.jpg">
                      <Ion-card-header>
                        <ion-card-title>IKAN NILA</ion-card-title>
                        <ion-card-subtitle color = 'secondary'>
                          <span style='color: #6cb5ec; display: inline-block'>
                            200 Kg
                          </span>
                        </ion-card-subtitle>
                      </Ion-card-header>
                    </ion-card>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </div>
            <ion-title>
              KUALITAS AIR
            </ion-title>
            <ion-grid>
              <ion-row>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-title>
                      pH
                    </ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-card-subtitle>
                      Normal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                    <ion-card-subtitle>
                      Abnormal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                  </ion-card-content>
                </ion-card>
              </ion-col>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-title>
                      DO
                    </ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-card-subtitle>
                      Normal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                    <ion-card-subtitle>
                      Abnormal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                  </ion-card-content>
                </ion-card>
              </ion-col>
            </ion-row>
            </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle,} from '@ionic/vue';


export default  defineComponent({
  name: 'HomePage',
  components: { IonPage, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle,}
});
</script>
<style>
.template{
  font-style: 'Poppins';
};
</style>
