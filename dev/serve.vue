<script>
import Vue from 'vue';
import { DcComponentsSample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    DcComponentsSample,
  }
});
</script>

<template>
  <div id="app">
    <dc-components-sample />
  </div>
</template>
