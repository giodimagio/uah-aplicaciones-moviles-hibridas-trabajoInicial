<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Blank</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Blank</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-grid>
        <ion-row>
          <ion-col size="6" offset="3">
            <h1 style="text-align: center;">Album example</h1>
          </ion-col>
          <ion-col size="6" offset="3">
            <h3 style="text-align: center;">Something short and leading about the collection below—its contents, the
              creator, etc. Make it short and sweet,
              but not too short so folks don't simply skip over it entirely.</h3>
          </ion-col>
        </ion-row>
        <ion-grid>
          <ion-row class="ion-justify-content-center">
            <ion-col size="auto">
              <ion-button fill="outline">Main call to action</ion-button>
            </ion-col>
            <ion-col size="auto">
              <ion-button fill="outline">Secondary action</ion-button>
            </ion-col>
          </ion-row>
        </ion-grid>
        <ion-row>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <ion-card>
              <img alt="Thumbnail" src="https://ionicframework.com/docs/img/demos/card-media.png" />
              <ion-card-header>
              </ion-card-header>
              <ion-card-content>
                This is a wider card with supporting text below as a natural lead-in to additional content.
                This content is a little bit longer.
              </ion-card-content>
              <ion-grid>
                <ion-row>
                  <ion-col>
                    <ion-button fill="outline">View</ion-button>
                    <ion-button fill="outline">Edit</ion-button>
                  </ion-col>
                  <ion-col>
                    <p style="text-align: end;">9 min</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card>
          </ion-col>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <ion-card>
              <img alt="Thumbnail" src="https://ionicframework.com/docs/img/demos/card-media.png" />
              <ion-card-header>
              </ion-card-header>
              <ion-card-content>
                This is a wider card with supporting text below as a natural lead-in to additional content.
                This content is a little bit longer.
              </ion-card-content>
              <ion-grid>
                <ion-row>
                  <ion-col>
                    <ion-button fill="outline">View</ion-button>
                    <ion-button fill="outline">Edit</ion-button>
                  </ion-col>
                  <ion-col>
                    <p class="container">9 min</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card>
          </ion-col>
          <ion-col size-xs=12 size-sm=6 size-lg=4>
            <ion-card>
              <img alt="Thumbnail" src="https://ionicframework.com/docs/img/demos/card-media.png" />
              <ion-card-header>
              </ion-card-header>
              <ion-card-content>
                This is a wider card with supporting text below as a natural lead-in to additional content.
                This content is a little bit longer.
              </ion-card-content>
              <ion-grid>
                <ion-row>
                  <ion-col>
                    <ion-button fill="outline">View</ion-button>
                    <ion-button fill="outline">Edit</ion-button>
                  </ion-col>
                  <ion-col>
                    <p>9 min</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>

    </ion-content>

    <ion-footer>
      <ion-toolbar>
        <ion-title>Footer</ion-title>
      </ion-toolbar>
    </ion-footer>
  </ion-page>
</template>

<script setup lang="ts">
import { IonButton, IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import { IonFooter } from '@ionic/vue';
import { IonGrid, IonCol, IonRow } from '@ionic/vue';
import { IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle } from '@ionic/vue';
</script>

<style scoped>
h1,
h3,
p {
  margin: 0;
  padding: 10px;
  color: #8c8c8c;
}

p {
  font-size: 14px;
  text-align: end;
}

#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
