<template>
  <!--
  <v-card>
    <v-layout>
      <v-navigation-drawer
        expand-on-hover
        rail
      >
        <v-list>
          <v-list-item
            prepend-avatar="https://randomuser.me/api/portraits/women/85.jpg"
            title="Sandra Adams"
            subtitle="sandra_a88@gmailcom"
          ></v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list density="compact" nav>
          <v-list-item prepend-icon="mdi-folder" title="My Files" value="myfiles"></v-list-item>
          <v-list-item prepend-icon="mdi-account-multiple" title="Shared with me" value="shared"></v-list-item>
          <v-list-item prepend-icon="mdi-star" title="Starred" value="starred"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main style="height: 100%">
  <v-card
  title="Card title"
  subtitle="Subtitle"
  text="..."
  variant="tonal"
  >
  <v-card-actions>
    <v-btn class="bg-red">Click me</v-btn>
  </v-card-actions>
  </v-card>
  <br>
  <v-card
  title="Card title"
  subtitle="Subtitle"
  text="..."
  variant="tonal"
  >
  <v-card-actions>
    <v-btn>Click me</v-btn>
  </v-card-actions>
  </v-card>
  <br>

  <v-card
  title="Card title"
  subtitle="Subtitle"
  text="..."
  variant="tonal"
  >
  <v-card-actions>
    <v-btn class="bg-azulElCielo">Click me</v-btn>
  </v-card-actions>
  </v-card>
      </v-main>
    </v-layout>
  </v-card>
  <br>
-->

<v-card
    color="grey-lighten-1"
    height="115px"
    rounded="0"

  >
    <v-toolbar property>

      <h2 class="bton">DocSearch</h2>

      <v-btn icon="mdi-magnify" variant="tonal">
      </v-btn>

      <v-btn class="v-btn" variant="tonal">
        <router-link to="Home2">Home</router-link>
      </v-btn>

      <v-btn class="v-btn" variant="tonal">
        <router-link to="/AcercaDeNosotros">Acerca de Nosotros</router-link>
      </v-btn>

      <v-btn class="v-btn" variant="tonal">
        <router-link to="/Support">Soporte</router-link>
      </v-btn>

      <v-btn class="v-btn" variant="tonal">
        <router-link to="/">registrarse</router-link>
      </v-btn>

      <v-btn class="v-btn" variant="tonal">
        <router-link to="/IniciarSesion">Iniciar Sesion</router-link>
      </v-btn>
    </v-toolbar>
  </v-card>
</template>

<style>
.v-btn {
  margin: 20px;}

h2 {
  margin-right: 330px;
  margin-left: 30px;}

.v-main {
        background-image: url('@/assets/images/FondHome.jpg');
        background-size: cover;
        background-position: relative;
        min-height: 100vh;
}
</style>

<script>

export default {
  name: 'HomeView',
  props: {
    msg: String
  },
  data: () => ({

    }
),
}


</script>


