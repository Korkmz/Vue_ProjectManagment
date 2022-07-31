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

          <AddTaskModal></AddTaskModal>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import AddTaskModal from './components/Task/AddTaskModal'

export default Vue.extend({
  name: 'App',
  components: {
    AddTaskModal
  },
  data: () => ({
    //
  }),
});
</script>
