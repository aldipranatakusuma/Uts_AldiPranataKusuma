<template>
        <v-navigation-drawer
          expand-on-hover
          rail
          color="grey"
        >
   
          <v-divider></v-divider>
  
          <v-list density="compact" nav>
            <v-list-item prepend-icon="mdi-folder" title="Home" :to="'/home'"></v-list-item>
            <v-list-item prepend-icon="mdi-account-multiple" title="Dosen" :to="'/dosen-entry'"></v-list-item>
            <v-list-item prepend-icon="mdi-star" title="Mahasiswa" :to="'/mahasiswa-entry'"></v-list-item>
            <v-list-item prepend-icon="mdi-star" title="Ruangan" :to="'/ruangan-entry'"></v-list-item>
          </v-list>
        </v-navigation-drawer>
  
        <v-main style="height: 250px"></v-main>
  </template>