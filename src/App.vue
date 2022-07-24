<template>
  <v-app>
    <v-app-bar
      app
      color="success"
      dark
    >
      <div class="d-flex align-center">
        <v-icon>mdi-thumb-up</v-icon>
        <span class="ml-2 overline">Project Manangent</span>
      </div>

      <v-spacer></v-spacer>

          <v-btn
           color="white"
           class="ma-2 secondary--text"
           >
            <v-icon right dark class="mr-1"> mdi-plus  </v-icon> Add Task
    </v-btn>


    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'App',

  data: () => ({
    //
  }),
});
</script>
