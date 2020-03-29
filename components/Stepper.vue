<template>
  <v-stepper non-linear>
    <v-stepper-header  class="headline pa-5">
      Select the Student Age group.
    </v-stepper-header>
    <v-stepper-step color="teal" editable step="1">
      Elementary
    </v-stepper-step>
  <v-divider></v-divider>
    <v-stepper-content step="1">
      <v-card dark color="teal" class="mb-12 pa-2" elevation="11">
        <link-prevue
          url="https://childrensmuseums.blog/2020/03/24/virtual-activities-for-families/?fbclid=IwAR2Pmk-oYds-UWU3gcWtlFjtzCCp5EwRI_EP54dAweHnK1XM1-bvnUrtFiM"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
   
        <link-prevue
          url="https://www.timeout.com/london/news/the-national-theatre-is-going-to-stream-a-free-play-every-thursday-night-032620?fbclid=IwAR1ckv8x85t1KZ3bjNbYDaEyct-LAJjfSVQA0rL98cGrXszioQykY59Vc00"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.facebook.com/events/2753792541516326/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
         <link-prevue
          url="https://axis.org/free-family-night-guide?fbclid=IwAR1-3w4phU_6Bz-uSWP9KdYmSLMxkXY9ztMhYPvtiW--hVW8N5fMo9dGXz0"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
          <link-prevue
          url="https://www.dreambox.com/at-home?utm_source=facebook&utm_medium=og&utm_campaign=covid&fbclid=IwAR0U53kRMU-heiBmEkwElUqKZzCr9LVoJsHTfYJoe1bsezBCvdiVMlBWsow"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
      </v-card>
    </v-stepper-content>

    <v-stepper-step color="teal" editable step="2">Middle School</v-stepper-step>

    <v-stepper-content step="2">
      <v-card dark color="teal" class="mb-12 pa-2" elevation="11">

        <link-prevue
          url="https://www.timeout.com/london/news/the-national-theatre-is-going-to-stream-a-free-play-every-thursday-night-032620?fbclid=IwAR1ckv8x85t1KZ3bjNbYDaEyct-LAJjfSVQA0rL98cGrXszioQykY59Vc00"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>

         <link-prevue
          url="https://learn.unity.com/course/create-with-code-live"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
      </v-card>
    </v-stepper-content>

    <v-stepper-step color="teal" editable  step="3">High School</v-stepper-step>

    <v-stepper-content step="3">
    <v-card dark color="teal" class="mb-12 pa-2" elevation="11">
<link-prevue
          url="https://www.edx.org/school/harvardx"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://pro.codecademy.com/learn-from-home/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>

    </v-card>
    </v-stepper-content>

    <v-stepper-step color="teal" editable  step="4">College</v-stepper-step>
    <v-stepper-content step="4">
    <v-card dark color="teal" class="mb-12 pa-2" elevation="11">

      <link-prevue
          url="https://blog.coursera.org/coursera-together-free-online-learning-during-covid-19/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>

        <link-prevue
          url="https://pro.codecademy.com/learn-from-home/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
                </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
              </div>
            </div>
          </template>
        </link-prevue>
    </v-card>
    </v-stepper-content>

    <v-stepper-step color="teal" editable  step="5">Fitness</v-stepper-step>
    <v-stepper-content step="5">
      <v-card dark color="teal" class="mb-12 pa-2" elevation="11">
        <link-prevue
          url="https://www.cbsnews.com/news/coronavirus-free-online-workout-gyms-live-stream-classes-during-outbreak/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.t3.com/us/news/free-online-fitness-class"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://theknow.denverpost.com/2020/03/27/free-online-workout-classes-coronavirus/235760/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.fastcompany.com/90481514/these-free-online-exercise-offers-will-help-keep-you-fit-and-sane-during-the-coronavirus-pandemic"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
      </v-card>
    </v-stepper-content>

     <v-stepper-step color="teal" editable  step="6">Virtual tours</v-stepper-step>
    <v-stepper-content step="6">
     <v-card dark color="teal" class="mb-12 pa-2" elevation="11">
         <link-prevue
          url="https://childrensmuseums.blog/2020/03/24/virtual-activities-for-families/?fbclid=IwAR2Pmk-oYds-UWU3gcWtlFjtzCCp5EwRI_EP54dAweHnK1XM1-bvnUrtFiM"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                <br></br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.cnn.com/style/article/what-to-do-at-home-streaming-art-museums-concerts-coronavirus-trnd/index.html"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.tasteofhome.com/article/free-virtual-tours/"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
        <link-prevue
          url="https://www.travelandleisure.com/attractions/museums-galleries/museums-with-virtual-tours"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>

        <link-prevue
          url="https://www.refinery29.com/en-us/2020/03/9576127/free-virtual-tours-online"
        >
          <template slot-scope="props">
            <div class="card">
              <div class="card-block">
               </br>
                <h4 class="card-title">{{ props.title }}</h4>
                <p class="card-text">{{ props.description }}</p>
                
                <v-btn
                  outlined
                  v-bind:href="props.url"
                  class="btn"
                  target="_blank"
                  >{{ props.title }}</v-btn
                >
                </br>
                
              </div>
            </div>
          </template>
        </link-prevue>
     </v-card>
    </v-stepper-content>

  </v-stepper>
</template>
<script>
import LinkPrevue from "link-prevue";
export default {
  data() {
    return {};
  },
  components: {
    LinkPrevue
  },
  methods: {
    onClick(prevue) {
      console.log(
        "click",
        prevue.images,
        prevue.title,
        prevue.url,
        prevue.description
      );
    }
  }
};
</script>
