<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="black white--text py-5 px-5 text-center"
      width="100%"
    >
      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-2">
            <v-btn
              href="https://www.facebook.com/nahidhossain1184"
              target="_blank"
              icon
            >
              <v-icon color="#A7121D">mdi-facebook</v-icon>
            </v-btn>
            <v-btn
              href="https://www.linkedin.com/in/nahid-hossain-66433919b/"
              target="_blank"
              icon
            >
              <v-icon color="#A7121D">mdi-linkedin</v-icon>
            </v-btn>
            <v-btn
              href="https://github.com/floatingnahid22"
              target="_blank"
              icon
            >
              <v-icon color="#A7121D">mdi-github</v-icon>
            </v-btn>
          </v-card-text>
        </v-col>

        <v-col cols="12" sm="4">
          <v-card-text class="pt-2">
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-1 white--text"
              icon
            >
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card-text class="pt-2 mx-1 white--text">
            <v-icon color="#A7121D">mdi-copyright</v-icon>
            Created by Nahid
          </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style></style>
