<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://marketplace.canva.com/MADGvzS3QfY/6/screen_2x/canva-brown-monkey-toy-MADGvzS3QfY.jpg">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <h1 style="background-color: rgba(140, 103, 90, 0.7);
        width: 100%;
        padding-top : 10px;
        padding-left : 10px;
        padding-bottom: 10px;">Talking about products and services (Present simple: questions)
      </h1>
    </v-layout>
  </v-img>

  <div style=" border-color:#402B24; border-style: solid; border-width: 2px;">
  </div>
  <h3  class = "border white--text" >Today's topic</h3>
  <div style = "padding : 16px;">

    <p>
      A salesman from a company called Fun Farm is talking to a potential customer at a trade fair.
    </p>

   <p>
      <li style="list-style-type: none;">Woman: So you make plastic animals.</li>
      <li style="list-style-type: none;">Representative: That's right. All life-size. Cows, horses, sheep...</li>
      <li style="list-style-type: none;">Woman: They're very realistic... Oh, and they move! </li>
      <li style="list-style-type: none;">Rep: Their heads move. They make sounds, if you just touch them...</li>
      <li style="list-style-type: none;">Woman: Oh!</li>
      <li style="list-style-type: none;">Rep: They don't walk! Our customers prefer them to stay in one place.</li>
      <li style="list-style-type: none;">Woman: Yes, right. So who are your customers? Where do you sell these things?</li>
      <li style="list-style-type: none;">Rep:       We sell a lot to fun parks, shopping centres, playgrounds... Children all over the world love them.
                                         We export to twenty-five countries.</li>
      <li style="list-style-type: none;">Woman: Really? I manage a small fun park in Germany. It's for children up to twelve years old.</li>
      <li style="list-style-type: none;">Rep:       Well, there are perfect for that age. We have a lot of customers in Germany. We work with a company called DDA,
                                         in Frankfurt. They install our products, and look after maintenance and after-sales service for all our German
                                         customers.</li>
      <li style="list-style-type: none;">Woman: Right. So what country are you from?</li>
      <li style="list-style-type: none;">Rep: From Canada. We have a factory near Montreal. We manufacture all our products there.</li>
      <li style="list-style-type: none;">Woman: Oh, I see... Can I just...?</li>
      <li style="list-style-type: none;">Rep:    Sure</li>
   </p>

      <div style="margin-left: -18px; margin-right: -18px; margin-top: 10px; border-color:#402B24; border-style: solid; border-width: 2px;">
      </div>
      <h3 class = "border white--text" style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px; margin-top: 0px; background-color:#402B24;">Exercise</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>
            What does Fun Farm manufacture?
          </li>
          <li>
            What's the woman's job?
          </li>
          <li>
            Where does Fun Farm make its products?
          </li>
        </ol>

        <p>
           Talk about the products and services of a company you know well.
        </p>

      </div>

      <div style="margin-left: -18px; margin-right: -18px; margin-top: 10px; border-color:#402B24; border-style: solid; border-width: 2px;">
      </div>
      <h3 class = "border white--text" style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px; margin-top: 0px; background-color:#402B24;">Self Study</h3>
      <div style="padding : 16px;">


          <p>
            Notes
          </p>

        <p>

          <v-container grid-list-md text-xs-left>
            <v-layout row wrap>


              <v-flex xs12>
                <v-card light color="#F2CBBD">
                  <v-card-text class="px-10">
                <p>
                  Be - <b>Is</b> the trade fair in Montreal?<br />
                  &emsp;&emsp;Where <b>are</b> your offices?
                </p>
                <p>
                  Other verbs – When <b>does</b> the fair start?<br />
                  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;<b>Do</b> they make computers?
                </p>
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>

        </p>

      </div>


    </div>


  </v-layout>
</v-container>
</v-layout>
</v-container>
</div>



</template>



<script>
export default {

  props: ['fontSize'],

  data(){

    return{


    }

  },


  beforeMount(){


  },

  methods:{


  },

  watch:{

    fontSize(current, old){

      console.log(current, 'current')
      console.log(old, 'previous')


    }
  }
}
</script>

<style scoped lang="css">

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}

li{


}

body{

  font-size: 16px;
}

.border:before {
  content: "";
  width: 0px;
  height: 0px;
  border-style: solid;
  border-width: 40px 40px 0px 0px;
  transform: rotate(180deg);
  border-color: transparent#402B24 transparent transparent;
  position: absolute;
  top: 0px;
  margin-left: 190px;
}
.border {
  position: relative;
  left: 0px;
  width: 200px;
  height: 40px;
  background:#402B24;
  padding-left: 10px;

}
.profile {
  background-color: rgba(0, 0, 0, 0);
  width: 100%;
  padding-top : 330px;
  padding-left : 10px;
  padding-bottom: 10px;
}


</style>
