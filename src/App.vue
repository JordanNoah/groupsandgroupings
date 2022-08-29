<template>
  <v-app>
    <v-main>
      <v-app-bar dense elevation="0">
        <v-spacer></v-spacer>
        <v-avatar color="red" height="40" min-width="40" width="40">
          ju
        </v-avatar>
      </v-app-bar>
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
