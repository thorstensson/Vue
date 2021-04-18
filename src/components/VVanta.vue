<template>
  <v-vanta effect="topology" :options="options"></v-vanta>
</template>
 
<script>
import VVanta from "vue-vanta";
import * as p5 from "p5";
export default {
  components: { VVanta },

  data() {
    return {
      options: {
        backgroundColor: 0x0a0a0a,
        color: 0x4b3f72,
        minHeight: 200.0,
        minWidth: 200.0,
        p5: p5,
      },
    };
  },
};
</script>