<template>
  <ion-page>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="HomePage" href="/tabs/HomePage">
          <ion-icon src="images/home.svg"/>
          <ion-label>Homepage</ion-label>
        </ion-tab-button>
          
        <ion-tab-button tab="ListKolam" href="/tabs/ListKolam">
          <ion-icon src="images/pond.svg"/>
          <ion-label>List Kolam</ion-label>
        </ion-tab-button>
        
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonTabBar, IonTabButton, IonTabs, IonLabel, IonIcon, IonPage, IonRouterOutlet } from '@ionic/vue';


export default defineComponent({
  name: 'TabsPage',
  components: { IonLabel, IonTabs, IonTabBar, IonTabButton, IonIcon, IonPage, IonRouterOutlet },
});
</script>
<style>
.template{
  font-style: 'Poppins';
};
</style>
