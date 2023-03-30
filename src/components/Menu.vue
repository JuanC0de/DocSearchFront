<script>
export default {
  name: "MenuComponent",
  /********* Componentes  ********/

  /********* Data Variables  ********/
  data: () => ({
      items: [
        { title: 'Paciente' },
        { title: 'Médico' },
      ],
    }),
};
</script>

<template>
    <v-card
      color=""
      flat
      height="400px"
      rounded="0"
    >
    <v-toolbar class="pa-3"
    dark
    prominent
    image="">
    <!-- <v-app-bar-nav-icon></v-app-bar-nav-icon> -->

    <v-toolbar-title>Vuetify</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-menu>
      <template v-slot:activator="{ props }">
        <v-btn
          color="cyan_lighten"
          v-bind="props"
        >
          Registrese
        </v-btn>
      </template>
      <v-list>
        <v-list-item
          v-for="(item, index) in items"
          :key="index"
          :value="index"
        >
          <v-list-item-title>{{ item.title }}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>

    <v-btn class="v-btn" variant="tonal">
      <router-link to="Home2">Home</router-link>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-dots-vertical</v-icon>
    </v-btn>
  </v-toolbar>
    </v-card>
</template>
