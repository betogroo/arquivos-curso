<template>
  <v-app>
    <v-app-bar>
      <v-app-bar-nav-icon :to="{ name: 'HomeView' }" icon="mdi-home" />
      <v-spacer />
      <div>
        <v-btn :to="{ name: 'HomeView' }">Home</v-btn>
        <v-btn :to="{ name: 'AboutView' }">About</v-btn>
      </div>
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>
