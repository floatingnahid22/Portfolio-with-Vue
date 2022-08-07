<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-card color="#E1D9D1">
            <v-img src="1.png" contain max-height="500"></v-img>
          </v-card>
        </v-col>
        <v-col cols="6">
          <h4 class="red--text text--darken-4 top">Hello, This is Nahid</h4>
          <h1 class="grey--text">Web Developer</h1>
          <h3 class="white--text">
            Hi, I am a graduate of Computer Science and Engineering program at
            University of Asia Pacific. I prefer to work with proper guidelines
            and practices. I am eager to learn and grow as a person and
            professional. I have a keen interest in JavaScript Development and I
            aspire to learn and work more on it.
          </h3>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="skills">
            <v-col cols="7">
              <h1 class="red--text text--darken-4 mt-4 number">Skills</h1>
            </v-col>
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-language-html5</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">HTML</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-language-css3</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">CSS</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-language-javascript</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">JS</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-language-python</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Python</h3>
                </div>
              </v-col>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-nodejs</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Node.js</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-react</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">React.Js</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-vuejs</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Vue.Js</h3>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3">mdi-git</v-icon>
                  <h3 class="white--text ml-3 mt-4">Git</h3>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="projects">
          <v-col cols="8">
            <h1 class="red--text text--darken-4 mt-4 number">Projects</h1>
          </v-col>
        </v-col>
        <v-col md="3" class="text-end"> </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="3.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> ShoeBrand </v-btn><br />

          <v-btn
            href="https://floatingnahid22.github.io/HTML-CSS-Crash-Course/"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-eye-circle-outline</v-icon>
          </v-btn>
          <v-btn
            href="https://github.com/floatingnahid22/HTML-CSS-Crash-Course"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-github</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> React Quiz App </v-btn
          ><br />
          <v-btn
            href="https://jolly-smakager-e6d8d2.netlify.app/"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-eye-circle-outline</v-icon>
          </v-btn>
          <v-btn
            href="https://github.com/floatingnahid22/React-QuizApp"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-github</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="4.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="5.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Mamma's Recipe </v-btn
          ><br />

          <v-btn
            href="https://mammasrecipe.netlify.app/"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-eye-circle-outline</v-icon>
          </v-btn>
          <v-btn
            href="https://github.com/floatingnahid22/Recipe-App-using-React"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-github</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Book Store </v-btn
          ><br />
          <v-btn
            href="blank"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-eye-circle-outline</v-icon>
          </v-btn>
          <v-btn
            href="https://github.com/floatingnahid22/Book-Store-App-With-MERN-Stack"
            target="_blank"
            color="#A7121D"
            dark
            text
            class="ml-n4"
          >
            <v-icon right>mdi-github</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    Let's work together on<br />your next project
                  </h1>
                  <p class="grey--text">
                    A straightforward, honest, and curious attitude towards the
                    work & the team, with a focus on active listening and
                    problem-solving.
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn
                    tile
                    color="#A7121D"
                    dark
                    class="mt-16"
                    href="https://mail.google.com/mail/u/0/#inbox?compose=new"
                    target="_blank"
                  >
                    Send me an email
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            ></div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import Footer from "../components/Footer.vue";
import NavBar from "../components/NavBar.vue";

export default {
  name: "Home",
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>
