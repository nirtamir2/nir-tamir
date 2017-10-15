<template>
  <section>
    <v-parallax src="./static/stars.jpg" height="600">
      <v-layout column align-center justify-center class="white--text">
        <v-avatar size="125px">
          <img src="static/profileImage.jpg" alt="Nir Tamir">
        </v-avatar>
        <h1 class="white--text mb-2 display-3">Nir Tamir</h1>
        <div class="headline mb-3 text-xs-center">Software Developer</div>
        <span>
          <v-btn icon class="white--text text--darken-4" href="https://github.com/nirtamir2">
            <v-icon large>fa-github</v-icon>
          </v-btn>
        </span>
      </v-layout>
    </v-parallax>
  </section>
</template>
