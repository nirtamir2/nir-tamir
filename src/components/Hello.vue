<template>
  <section>
    <v-layout column wrap class="my-5" align-center>
      <v-flex xs12 sm4 class="my-3">
        <div class="text-xs-center">
          <h2 class="headline">I love to learn by code</h2>
          <h2 class="headline">
            <v-icon class="black--text">face</v-icon>
            <v-icon class="red--text">favorite</v-icon>
            <v-icon class="purple--text">fa-arrow-right</v-icon>
            <v-icon class="blue--text">book</v-icon>
            <v-icon class="green--text">fa-money</v-icon>
            <v-icon class="orange--text">code</v-icon>
          </h2>
          <span class="subheading">
            and more ⚽
          </span>
          <!-- <h2 class="headline">😃 I love to learn by code 👨‍💻
                      <br> 😃 💙 💡 📘 💻 👨‍💻
                    </h2>
                    <span class="subheading">
                      and I like to to other things too ⚽
                    </span> -->
        </div>
      </v-flex>
      <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout row wrap align-center>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">color_lens</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Material Design</div>
                </v-card-title>
                <v-card-text>
                  Create a visual language that synthesizes classic principles of good design with the innovation and possibility of technology and science. Develop a single underlying system that allows for a unified experience across platforms and device sizes. Mobile precepts are fundamental, but touch, voice, mouse, and keyboard are all ﬁrst-class input methods.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">flash_on</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Top Technologies</div>
                </v-card-title>
                <v-card-text>
                  I am using the best technologies available. I love to learn and discover new technologies every time in order to make the development easier to code and maintain. I belive it gives more opportunities as the time goes, and also gives important experience. New technologies also apply more capabilites to the software. </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">build</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">High Standarts</div>
                </v-card-title>
                <v-card-text>
                  If a job need to be done - why not doing it right? I believe in high standarts and clean code because it makes live easier and pleasent. Nobody wants to read code that his author didn't care about it when code. Even when I know i can do better - I want that the next person who looks at my code will feel that I tried to make his live easier. I will never stop learning and improving my craft.
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  name: 'hello'
}
</script>

