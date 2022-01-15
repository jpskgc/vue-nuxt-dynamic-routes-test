<template>
  <div>
    <div>test</div>
    <div>{{ id }}</div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component
export default class Page extends Vue {
  id = this.$route.params.id
}
</script>
