<template>
  <v-app>
    <v-app-bar
      app
      color="indigo lighten-3"
      dark
    >
      <div class="d-flex align-center">
        <h2 class= h2 >Pet's Donation </h2>
        
    
      </div>

      <v-spacer></v-spacer>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
