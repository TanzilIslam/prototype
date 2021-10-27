<template>
  <v-app dark>
    <v-app-bar height="72" app flat>
      <v-toolbar-title class="brand-title">MENSCRIPT</v-toolbar-title>
      <v-app-bar-nav-icon class="mr-2" @click.stop="drawer = !drawer" />
      <span class="account"> Account menu</span>
      <!-- <v-img src="~/asstes/black.png"></v-img> -->
    </v-app-bar>
    <v-main class="body-class">
         <Nuxt />
    </v-main>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
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
  margin-left: 34px;
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
  background: #e00000;
}
</style>
