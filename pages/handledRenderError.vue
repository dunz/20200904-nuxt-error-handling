<template>
  <RenderError />
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import RenderError from '../components/RenderError.vue'

@Component({
  components: { RenderError },
  layout: 'safe',
})
export default class UnhandledRenderErrorPage extends Vue {}
</script>
