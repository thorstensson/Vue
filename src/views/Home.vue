<template>
  <div>
    <div id="hero" class="hero-home is-fullheight">
      <v-vanta></v-vanta>

      <div class="hero-body">
        <div class="container container-home">
          <p
            class="title is-3 is-size-4-mobile is-size-3-tablet is-size-2-desktop"
          >
            Hi, I'm Thomas
          </p>
          <h2
            class="subtitle is-size-2-mobile is-size-1-tablet is-size-1-desktop"
          >
            A <del>freelance</del><br />Developer<br class="rwd-break" />
            & Designer<br />
            from an island.
          </h2>

          <a class="cssnectar"
            href="https://www.cssnectar.com/"
            title="CSS Nectar - Site of the Day"
            style="
              width: 60px;
              height: 60px;
              position: fixed;

              z-index: 99999;
              text-indent: -9999px;
              background: url(https://cssnectar.com/ribbons/nominee-light.png)
                no-repeat;
            "
            target="_blank"
          ></a>
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

