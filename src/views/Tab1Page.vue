<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>

  
      <ion-item>
        <ion-checkbox slot="start" disabled="true"></ion-checkbox>
        <ion-label>I agree to the terms and conditions</ion-label>
      </ion-item>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
  IonCheckbox,
  IonItem,
  IonLabel,
} from "@ionic/vue";
import { add } from "ionicons/icons";
import ExploreContainer from "@/components/ExploreContainer.vue";
</script>
