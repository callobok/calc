<template>
  <q-page class="row q-ma-lg">
    <ribbon-foundation/>
  </q-page>
</template>

<script lang="ts">
import RibbonFoundation from 'components/RibbonFoundation.vue'
import { Vue, Options } from 'vue-class-component'

@Options({
  components: { RibbonFoundation }
})
export default class PageIndex extends Vue {
}
</script>
