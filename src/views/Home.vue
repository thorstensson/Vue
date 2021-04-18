<template>
  <div>
    <div id="hero" class="hero-home is-fullheight">

      <v-vanta></v-vanta>

      <div class="hero-body">
        <div class="container container-home">
          <p class="title is-3 is-size-4-mobile is-size-3-tablet">Hello, I'm Thomas.</p>
          <h2 class="subtitle is-size-2-mobile is-size-1-tablet">
            A <del>freelance</del> designer & developer <br />
            looking for a new home.
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VVanta from "@/components/VVanta";

export default {
  name: "home",

  components: {
    VVanta,
  },
};
</script>

