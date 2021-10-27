<template>
<div >
  <div class="mt-4 mb-4 ml-14">
    <p class="welcomm-text ">Welcome Rob</p>
  <v-btn class="change-personal-detail-button"><div class="change-personal-detail-button-text">Change personal details</div> <v-icon class="ml-3">mdi-deskphone</v-icon></v-btn>
  </div>
  <div class="table mt-4">
    <v-img :src="require('@/assets/graph.png')">
    </v-img>
  </div>
</div>
</template>
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
.table img {
  height: 174px;

}
</style>