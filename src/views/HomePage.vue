<!-- Template: Page completa de Ionic donde se muestra de forma estructurada en header, content y footer la interfaz de la aplicación. -->

<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title class="ion-text-center">Ionic - Trabajo Inicial - Aplicaciones móviles (Híbridas) - UAH</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-grid>
        <ion-row>
          <ion-col size="6" offset="3">
            <h1 class="ion-text-center">Album example</h1>
          </ion-col>
          <ion-col size="6" offset="3">
            <h3 class="ion-text-center">Something short and leading about the collection below—its contents, the
              creator, etc. Make it short and sweet,
              but not too short so folks don't simply skip over it entirely.</h3>
          </ion-col>
        </ion-row>
        <ion-grid>
          <ion-row class="ion-justify-content-center">
            <ion-col size="auto">
              <ion-button color="primary" fill="solid">Main call to action</ion-button>
            </ion-col>
            <ion-col size="auto">
              <ion-button color="secondary" fill="solid">Secondary action</ion-button>
            </ion-col>
          </ion-row>
        </ion-grid>
        <ion-row>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <CardComponent />
          </ion-col>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <CardComponent />
          </ion-col>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <CardComponent />
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
    <ion-footer>
      <ion-toolbar>
        <ion-title class="ion-text-center">Jorge Romero - jorge.romeroc@edu.uah.es</ion-title>
      </ion-toolbar>
    </ion-footer>
  </ion-page>
</template>

<!-- Script: Elemento script (de tipo Composition API en Vue 3) que importa los componentes de Ionic necesarios y el componente Card -->

<script setup lang="ts">
import { IonButton, IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonFooter, IonGrid, IonCol, IonRow } from '@ionic/vue';
import CardComponent from '@/views/CardComponent.vue';
</script>

<!-- Style: Estilos CSS3 del Single-File Component que solo aplican a los titulos h1 y h3 de este componente -->

<style scoped>
h1,
h3 {
  margin: 0;
  padding: 10px;
  color: #8c8c8c;
}
</style>
