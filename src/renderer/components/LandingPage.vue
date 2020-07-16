<template>
  <v-app-bar color="secondary">
    <v-toolbar-title color="white">Stream Ino</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-menu left bottom>
      <template v-slot:activator="{ on }">
        <v-btn icon v-on="on">
          <v-icon>mdi-dots-vertical</v-icon>
        </v-btn>
      </template>
    </v-menu>
  </v-app-bar>
</template>

<script>

export default {
}
</script>

<style scoped>
</style>
