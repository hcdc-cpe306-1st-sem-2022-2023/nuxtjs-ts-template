<template>
  <div>Karl Anthony</div>
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
