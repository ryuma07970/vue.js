<template>
  <v-app>
    <v-toolbar 
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
      max-height="60"
    >
      <v-toolber-title>YouTube Curation</v-toolber-title>
      
    </v-toolbar>

    <top />

    <v-toolbar
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-spacer />
      <p>@QuestAcademia</p>
    </v-toolbar>
  </v-app>
</template>

<script>
  import Top from './components/Top.vue'

  export default {
    name: 'App',
    components: {
      Top,
    }
  }
</script>