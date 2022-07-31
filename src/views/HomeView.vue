<template>
<div class="pa-5">
    <v-row no-gutters>

       <v-col
        cols="12"
        sm="12"
        md="3"
      >
       <v-card class="mx-auto " outlined color="transparent">
          <div class="text-card-title pa-4 d-inline-flex">
          Ideas  
           <v-img class="bg-white ml-2" width="25" :src="require('../assets/icons/okay.png')"  ></v-img> 
        
        </div>
        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
          <v-row class="d-flex mb-0 mb-0 "  no-gutters>
              <!-- <v-col md="11" sm="11"> 
                 <div class="task-title" >
                      Animate Video
                  </div>
               </v-col>
               <v-col md="1" sm="1" class="ml-auto d-flex">
                 <v-img class="bg-white " width="25" :src="require('../assets/icons/woman.png')"  ></v-img> 
               </v-col>  -->
                  <div>
                      Animate Video
                
                  </div>

                   <div class="ml-auto d-flex">
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/woman.png')"  ></v-img> 
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
          
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
                 </v-row>
         </v-card>

        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                      Writing a script
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
       </v-card>
  
  
      </v-col>

       <v-col
        cols="12"
        sm="12"
        md="3"
      >
         <v-card class="mx-auto " outlined color="transparent">
          <div class="text-card-title pa-4 d-inline-flex">
          To Do  
           <v-img class="bg-white ml-2" width="25" :src="require('../assets/icons/list.png')"  ></v-img> 
        
        </div>
       
        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0" no-gutters>
                  <div>
                     Finiliaze storyboard
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                    Final Cut
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/woman.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
      
       </v-card>

      </v-col>

       <v-col
        cols="12"
        sm="12"
        md="3"
      >
         <v-card class="mx-auto " outlined color="transparent">
          <div class="text-card-title pa-4 d-inline-flex">
          In Progress
           <v-img class="bg-white ml-2" width="25" :src="require('../assets/icons/work-in-progress.png')"  ></v-img> 
        
        </div>

        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                     Finiliaze storyboard
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
    
        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                     Design
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
    

    
        
       </v-card>

      </v-col>

       <v-col
        cols="12"
        sm="12"
        md="3"
      >
         <v-card class="mx-auto " outlined color="transparent">
          <div class="text-card-title pa-4 d-inline-flex">
          Done
           <v-img class="bg-white ml-2" width="25" :src="require('../assets/icons/check.png')"  ></v-img> 
        
        </div>
        <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                     Design
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
    
            <v-card  outlined :elevation="0" class="pa-2 card-task mb-2" >
             <v-row class="d-flex mb-0 mb-0 "  no-gutters>
                  <div>
                     Design
                
                  </div>

                   <div class="ml-auto d-flex">
                     
                     <v-img class="bg-white " width="25" :src="require('../assets/icons/man.png')"  ></v-img> 
                  </div> 
            

          </v-row>
           <v-row class="mt-0">
                  <v-card-actions class="pt-0 pb-1">
                       <v-list-item class="grow">
                          <v-row align="center" justify="end" >
                           <v-icon class="mr-1" color="#d1d1d1">  mdi-comment </v-icon>
                           <span class="subheading mr-2">56</span>
                           <v-icon class="mr-1" color="#d1d1d1" > mdi-tag </v-icon>
                           <span class="subheading mr-2">256</span>
                           <v-icon class="mr-1" color="#d1d1d1">   mdi-share-variant  </v-icon>
                           <span class="subheading">45</span>
                          </v-row>
                        </v-list-item>
                  </v-card-actions>
              
                 </v-row>
         </v-card>
    
       </v-card>

      </v-col>

    </v-row>

 
   <v-dialog
      v-model="dialog"
      scrollable
      max-width="700px"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="primary"
          dark
          v-bind="attrs"
          v-on="on"
        >
          Open Dialog
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
          <v-btn depressed
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

</div>

</template>


<!--script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    name: 'HelloView',

    data: () => ({
      card: [
        {
          text: 'Ideas',
          icon: 'okay.png',
        },

        {
          text: 'Todo',
          icon: 'list.png',
        },

        {
          text: 'In progress',
          icon: 'work-in-progress.png',
        },

        {
          text: 'Done',
          icon: 'work-in-progress.png',
        },
      ],
    }),
  })
</script-->

<style >
body,.text-card-title{
  font-family: 'Raleway', sans-serif !important;
}
.task-title{
  font-size: 13px;
  font-weight: 400;
}

.card-task{

  font-size: 13px;
}

.theme--light.v-text-field--outlined:not(.v-input--is-focused):not(.v-input--has-state) > .v-input__control > .v-input__slot fieldset {
    color: rgb(204 204 204 / 38%);
}

 .v-text-field input {
    font-size: 0.85em
  }
</style>