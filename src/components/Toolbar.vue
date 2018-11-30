<template>
  <v-toolbar color="light-blue darken-4" dark fixed>
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>CNFM</v-toolbar-title>
    <v-toolbar-items>
      <v-btn flat>
        <v-icon class="mr-2">grade</v-icon>Projects
      </v-btn>
    </v-toolbar-items>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat to="/">Home</v-btn>
      <v-btn flat to="/about">About</v-btn>
      <v-btn flat to="/register">Register</v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>
<script>
export default {

};
</script>

<style>
</style>
