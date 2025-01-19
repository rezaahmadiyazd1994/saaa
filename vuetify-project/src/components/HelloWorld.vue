<template>
  <v-responsive class="border rounded" max-height="300">
    <v-app>
      <v-app-bar>
        <v-img
          height="40"
          src="/favicon.png"
          position="absolute"
        ></v-img>
      </v-app-bar>

      <v-navigation-drawer>
        <v-list>
          <v-list-item title="Navigation drawer"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main>
        <v-container>
          <h1>محتوی اصلی</h1>
        </v-container>
      </v-main>
    </v-app>
  </v-responsive>
</template>
