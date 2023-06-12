<!-- Template: Componente HTML de tipo Card, de Ionic, que será utilizado en HomePage varias veces para representar una tarjeta responsiva. -->

<template>
    <ion-card>
        <img alt="Thumbnail" src="https://ionicframework.com/docs/img/demos/card-media.png" />
        <ion-card-content>
            This is a wider card with supporting text below as a natural lead-in to additional content.
            This content is a little bit longer.
        </ion-card-content>
        <ion-grid>
            <ion-row>
                <ion-col size="8">
                    <ion-button fill="outline">View</ion-button>
                    <ion-button fill="outline">Edit</ion-button>
                </ion-col>
                <ion-col size="4">
                    <p class="ion-text-end">9 min</p>
                </ion-col>
            </ion-row>
        </ion-grid>
    </ion-card>
</template>

<!-- Script: Elemento script (de tipo Composition API en Vue 3) que importa los componentes de Ionic necesarios. -->

<script setup lang="ts">
import { IonCard, IonCardContent } from '@ionic/vue';
</script>

<!-- Style: Estilos CSS3 del Single-File Component que solo aplican a los párrafos este componente. -->

<style scoped>
p {
    margin: 0;
    padding: 10px;
    color: #8c8c8c;
    font-size: 18px;
    text-align: end;
}
</style>