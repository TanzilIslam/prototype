<template>
  <div class="product-card">
    <v-card>
          <v-row>
      <v-col cols="12" sm="12" md="8" lg="8" offset-md="2" offset-lg="2" offset-xl="2"  xl="8">
        <v-row class="align-center py-15">
          <v-col cols="12" sm="12" md="3" lg="3" xl="3">
            <v-img
            height="362"
            contain
              :src="require('@/assets/image.png')"
            ></v-img>
          </v-col>
          <v-col cols="12" sm="12" md="9" lg="9" xl="9">
            <v-row class="justify-center">
              <v-col  cols="10" offset-md="1" offset-lg="1" offset-xl="1">
                <div class="title">
                  Finasteride <span class="active">active</span>
                </div>
                <div class="desc">
                  For personalised advice, you are welcome to arrange a video
                  consultation with a trained consultant; or to use our live
                  assistance for guidance while browsing online.
                </div>
                <div class="mt-4">
                  <v-btn class="treatment mr-2 mb-4"
                    ><div class="treatment-text">View treatment details</div>
                    <v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn
                  >
                  <v-btn class="history mb-4"
                    ><div class="history-text">Change personal details</div>
                    <v-icon class="ml-3">mdi-deskphone</v-icon></v-btn
                  >
                </div>
              </v-col>
              
            </v-row>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.product-card {
  
  /* filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25)); */
  /* margin-bottom: 80px; */
  margin-top: 13px;

}
.title {
  font-family: "Inter";
  font-style: normal;
  font-weight: normal;
  font-size: 28px;
  line-height: 34px;
  color: #2a2a2a;
}
.active {
  border: 0.5px solid #aca7a7;
  box-sizing: border-box;
  border-radius: 1px;
  font-family: "Inter";
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 15px;
  /* identical to box height */
  text-align: center;
  color: #092673;
  margin-left: 10px;
  padding: 5px 10px;
}
.desc {
  margin-top: 20px;
  font-family: "Inter";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 27px;
  /* or 169% */

  color: #2a2a2a;
}
.treatment {
  border: 0.5px solid #7a7a7a;
  /* filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25)); */
  padding: 30px 20px !important;
}
.treatment-text {

  font-family: "Inter";
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 27px;
  /* identical to box height, or 180% */
  width: 245px !important;

  color: #2a2a2a;
}
.history {
  border: 0.5px solid #7a7a7a;
  box-sizing: border-box;
  /* filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25)); */
  padding: 30px 20px !important;
}
.history-text {

  font-family: "Inter";
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 27px;
  /* identical to box height, or 180% */
  color: #2a2a2a;
}
</style>
