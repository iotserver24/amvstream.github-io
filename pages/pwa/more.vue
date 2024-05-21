<!-- eslint-disable vue/no-multiple-template-root -->
<template>
  <v-container>
    <v-breadcrumbs style="padding: 0; margin-bottom: 1rem">
      <template #prepend>
        <v-icon size="small" icon="mdi-home"></v-icon>
      </template>
      <v-breadcrumbs-item title="Home" to="/pwa"></v-breadcrumbs-item>
      <v-breadcrumbs-divider></v-breadcrumbs-divider>
      <v-breadcrumbs-item title="More"></v-breadcrumbs-item>
    </v-breadcrumbs>
    <div class="pb-4">
      <h1>More</h1>
    </div>
    <v-list lines="two">
      <v-list-item>
        <template #prepend>
          <img src="/icon.png" style="display: flex; width: 100px; height: 100%" />
        </template>
        <v-list-item-title>AnimeVerse</v-list-item-title>
        <v-list-item-subtitle>Made by R3AP3R editz</v-list-item-subtitle>
      </v-list-item>
      <v-list-item>
        <v-list-item-title>AnimeVerse</v-list-item-title>
        <v-list-item-subtitle>{{ new Date().getFullYear() }} ©AnimeVerse</v-list-item-subtitle>
      </v-list-item>
    </v-list>
    <v-divider class="my-4"></v-divider>
    <v-list lines="two">
      <v-list-item title="About us" target="_blank" href="/about"></v-list-item>
    </v-list>
  </v-container>
</template>
