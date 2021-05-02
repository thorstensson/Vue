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
        backgroundColor: 0x0F1108,
        color: 0x99290A,
        minHeight: 200.0,
        minWidth: 200.0,
        opacity:.1,
        p5: p5,
      },
    };
  },
};
</script>