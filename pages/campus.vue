<template>
    <div>
      
        <v-bottom-navigation :elevation="0">
          <NuxtLink to="/campus/create">
            <v-btn>
  
              <span>Create</span>
              <v-icon>mdi-plus-circle-outline</v-icon>
  
            </v-btn>
          </NuxtLink>
          <NuxtLink to="/campus/list">
            <v-btn>
  
              <span>List</span>
              <v-icon>mdi-view-list</v-icon>
            </v-btn>
          </NuxtLink>
        </v-bottom-navigation>
     
  
      <NuxtChild />
    </div>
  </template>
  
  <script>
  
  </script>