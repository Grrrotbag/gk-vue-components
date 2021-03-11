<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { GkVueComponentsSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  GkVueComponentsSample,
  // }
});
</script>

<template>
  <div id="app">
    <gk-vue-components-sample />
  </div>
</template>
