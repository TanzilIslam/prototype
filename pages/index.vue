<template>
<div >
  <v-row>
    <v-col cols="12" sm="12" md="3" lg="3" xl="3" offset-md="1" offset-lg="1" offset-xl="1">
       <p class="welcomm-text ml-4">Welcome Rob</p>
  <v-btn class="change-personal-detail-button ml-4"><div class="change-personal-detail-button-text">Change personal details</div> <v-icon class="ml-3">mdi-deskphone</v-icon></v-btn>
    </v-col>
  </v-row>
  <div class="table mt-10">
    <v-img  class="grap" :src="require('@/assets/graph.png')">
    </v-img>
  </div>
  <div>
    <product-card />
      <product-card />
  </div>
</div>
</template>
<script>
  export default {
    
  }
</script>

<style scoped>
.welcomm-text{
  margin-top: 183px;
width: 181px;
height: 34px;
font-family: "Inter";
font-style: normal;
font-weight: normal;
font-size: 28px;
line-height: 34px;
color: #2A2A2A;
}
.change-personal-detail-button{
  width: 299px;
height: 59px !important;
border: 0.5px solid #7A7A7A;
box-sizing: border-box;

}
.change-personal-detail-button-text{

height: 27px;


font-family: "Inter";
font-style: normal;
font-weight: 600;
font-size: 14px;
line-height: 27px;
/* identical to box height, or 180% */
color: #2A2A2A;

}
.grap{
  height: 174px;

}
</style>