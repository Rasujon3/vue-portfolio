<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="githubPic.jpg" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="red--text text--darken-4 top">
            Hello Im Ruhul Amin Sujon
          </h5>
          <h1 class="white--text">Web Designer</h1>
          <p class="grey--text">
            I am a Full Stack Web Developer from Dhaka. I started my journey as
            a web developer in 2020. Since then, I have done lots of personal
            projects. I completed MERN Stack course from Bohubrihi & Programming
            Hero. I love to work with React, Firebase, Node Js, MongoDB, Express
            JS and all other related technologies.
          </p>
          <v-btn tile color="#A7121D" dark> About Me </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-palette-swatch</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Web Design</h3>
                  <p class="grey--text ml-3 mt-6">
                    I am comfortable with web design.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark
                    >mdi-shopping</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Web Development</h3>
                  <p class="grey--text ml-3 mt-6">
                    I am comfortable with Web Development (Node JS)
                  </p>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Full Stack Development</h3>
                  <p class="grey--text ml-3 mt-6">
                    I am trying to build some full stack project.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="red--text text--darken-4 mt-4 number">0</h1>
                  <h3 class="white--text mt-4">Years Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">6+</h1>
                        <p class="grey--text">Clients</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">12+</h1>
                        <p class="grey--text">Completed Projects</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">00</h1>
                        <p class="grey--text">Years Experience</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">10</h1>
                        <p class="grey--text">Achievements</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="white--text">FEATURED PROJECTS</h4>
          <p class="grey--text">There is my completed projects</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#A7121D" dark> View All </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="PARTSBAZAR.png" contain max-height=""></v-img>
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
            <v-img src="car2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Parts Bazar </v-btn
          ><br />

          <a
            href="https://github.com/Rasujon3/parts-bazar-client#readme"
            target="_blank"
          >
            <v-btn color="#A7121D" dark text class="ml-n4">
              know more
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
          </a>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4">
            Genius Car Service </v-btn
          ><br />

          <a
            href="https://github.com/Rasujon3/genius-car-services-client#readme"
            target="_blank"
          >
            <v-btn color="#A7121D" dark text class="ml-n4">
              know more
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
          </a>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="DOCTORSPORTAL.png" contain max-height=""></v-img>
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
            <v-img src="laptopVillage2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Doctor Portal </v-btn
          ><br />

          <a
            href="https://github.com/Rasujon3/doctors-portal-client#readme"
            target="_blank"
          >
            <v-btn color="#A7121D" dark text class="ml-n4">
              know more
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
          </a>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Laptop Village </v-btn
          ><br />
          <a
            href="https://github.com/Rasujon3/laptop-village#readme"
            target="_blank"
          >
            <v-btn color="#A7121D" dark text class="ml-n4">
              know more
              <v-icon right>mdi-arrow-right</v-icon>
            </v-btn>
          </a>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="9">
                  <h1 class="white--text">
                    Let's work together on<br />your next project
                  </h1>
                  <p class="grey--text">
                    Email: ruhul.amin.sujon.1997@gmail.com
                  </p>
                </v-col>
                <v-col cols="3">
                  <v-btn tile color="#A7121D" dark class="mt-16">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <!-- <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>Project</v-btn>
              <v-btn text>about</v-btn>
              <v-btn text> contact</v-btn>
            </div> -->
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 90px;
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
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
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
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ce1d2a;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
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
