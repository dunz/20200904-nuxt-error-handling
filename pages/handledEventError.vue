<template>
  <BrokenEventHandler />
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import BrokenEventHandler from '../components/BrokenEventHandler.vue'

@Component({
  components: { BrokenEventHandler },
  layout: 'safe',
})
export default class UnhandledRenderErrorPage extends Vue {}
</script>
