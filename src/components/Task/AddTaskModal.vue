<template>
      <v-dialog
      v-model="dialog"
      scrollable
      max-width="700px"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
           color="white"
           class="ma-2 secondary--text"
          dark
          v-bind="attrs"
          v-on="on"
        >
         <v-icon right dark class="mr-1"> mdi-plus  </v-icon>  Add Task
        </v-btn>
      </template>
      <v-card>
        <v-card-title>  
            <v-icon class="mr-1" color="#d1d1d1">  mdi-plus </v-icon> Add Task</v-card-title>
        <v-divider></v-divider>
        <v-card-text class="pt-2">
         <v-form ref="form" v-model="valid" lazy-validation >
       

            <v-text-field size="sm" label="Title" class="mb-2" hide-details dense outlined required ></v-text-field>
            <v-text-field label="Description" class="mb-2" hide-details dense outlined required ></v-text-field>
            <v-select v-model="select" :items="items" :error-messages="errors" label="User" data-vv-name="select" class="mb-2" hide-details  dense outlined required ></v-select>
            <v-select v-model="select" :items="items" :error-messages="errors" label="Project" data-vv-name="select" class="mb-2" hide-details  dense outlined required ></v-select>
            <v-select v-model="select" :items="items" :error-messages="errors" label="Priority" data-vv-name="select"  class="mb-2" hide-details dense outlined required ></v-select>

         </v-form>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions>

          <v-spacer></v-spacer>
          <v-btn 
            color="blue "
            text
            @click="dialog = false"
          >
            Close
          </v-btn>
          <v-btn color="primary"
          >
            Save
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
</template>