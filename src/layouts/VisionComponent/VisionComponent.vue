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
    }
  }
}
</script>

<template>
  <v-container>
    <v-row>
      <v-col cols="6">
        <v-img
          src="@/assets/images/imgMissionVision/2-vision1.png"
          :alt="title"
          width="90%"
          height="70%"
        />
      </v-col>
      <v-col cols="6">
        <h2>{{ title }}</h2>
        <p>{{ text }}</p>
      </v-col>
    </v-row>
  </v-container>   
</template>