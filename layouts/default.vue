<template>
  <v-app dark>
    <v-app-bar height="72" app flat >
      <v-toolbar-title class="brand-title">MENSCRIPT</v-toolbar-title>
      <v-app-bar-nav-icon class="mr-2" @click.stop="drawer = !drawer" />
      <span class="account"> Account menu</span>
      <!-- <v-img src="~/asstes/black.png"></v-img> -->
    </v-app-bar>
      <v-app-bar class=" d-sm-none" height="72" app flat >
            <v-app-bar-nav-icon  @click.stop="drawer = !drawer" />
      <v-toolbar-title class="brand-title2">MENSCRIPT</v-toolbar-title>

      <!-- <v-img src="~/asstes/black.png"></v-img> -->
    </v-app-bar>
    <v-main class="body-class">
         <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/",
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire",
        },
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js",
    };
  },
};
</script>
<style scoped>
.brand-title {
  margin-left: 32px;
  height: 21px;
  font-family: "Work Sans" !important;
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 21px;
  letter-spacing: 3px;
  color: #2a2a2a;
}
.brand-title {
  margin-left: 10px;
  height: 21px;
  font-family: "Work Sans" !important;
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 21px;
  letter-spacing: 3px;
  color: #2a2a2a;
}
.account {
  height: 18px;

  font-family: "Inter";
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 18px;

  color: #2a2a2a;
}
.body-class{
  background: #f5f5f5;
}
.row{
    margin-right: 0px !important;
  margin-left: 0px !important;

}
</style>
