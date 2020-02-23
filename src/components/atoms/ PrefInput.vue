<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6" md="3">
      <v-text-field
        label="都道府県を入力"
        prepend-icon="place"
      ></v-text-field>
      </v-col>
  </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue'
import 'material-design-icons-iconfont/dist/material-design-icons.css' // Ensure you are using css-loader

export default Vue.extend({
  name: 'PrefInput',

  data: () => ({
  })
})
</script>
