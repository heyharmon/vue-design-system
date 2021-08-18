<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { AppButton } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  AppButton,
  // }
});
</script>

<template>
  <div id="app">
    <app-button />
    <app-input />
  </div>
</template>
