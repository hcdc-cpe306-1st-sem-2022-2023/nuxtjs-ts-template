<template>
  <v-container>
    <h1>Counter: {{ counter }}</h1>
    <v-btn block depressed elevation="2" large @click="countUp"
      >Increment</v-btn
    >
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
export default class Index extends Vue {
  // data
  counter: number = 0

  // methods
  countUp(): void {
    this.counter++
    console.log('counter value:', this.counter)
  }
}
</script>
