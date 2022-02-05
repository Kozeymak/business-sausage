<template>
  <v-row>
    <v-col>
      <v-img src="require('@/static/left_widget_img.jpg')" alt="" />
      <blockquote class="blockquote">{{aboutText}}</blockquote>
    </v-col>
  </v-row>
</template>

<style scoped>
</style>

<script>
export default {
  name: 'InspirePage',
  computed: {
    aboutText() {
      return this.$store.getters.aboutText;
    }
  }
}
</script>
