<template>
  <v-container>
    <v-row justify="center" align="center">
      <v-img src="/icon.png" class="mt-10" contain height="300" width="300" />
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({
  head() {
    return {
      title: 'Home',
    }
  },
})
export default class Index extends Vue {}
</script>
