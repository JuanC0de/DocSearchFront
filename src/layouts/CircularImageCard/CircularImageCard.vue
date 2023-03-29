<script>
export default {
    props: {
        title: {
            type: String,
            required: true
        },
        text: {
            type: String,
            required: true
        },
        imageAvatar: {
            type: String,
            required: true
        }
    }
}
</script>
<template>
<v-card>
  <v-card-title class="align-center">
    <v-avatar :image="imageAvatar" size="80"></v-avatar>
  </v-card-title>
  <v-card-title>
    {{ title }}
  </v-card-title>
  <v-card-text>
    <p>{{ text }}</p>
  </v-card-text>
</v-card>
</template>
