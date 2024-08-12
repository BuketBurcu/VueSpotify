<template>
  <div class="home">
    <div class="container-fluid">
      <div class="row">
        <div class="col-3 mt-3"><HomeSetting></HomeSetting></div>
        <div class="col-9 mt-3"><NavBar></NavBar></div>
      </div>
      <div class="row">
        <div class="col-3 mt-3"><Setting></Setting></div>
        <div class="col-9 mt-3" style="overflow-x: hidden">
          <MainPage></MainPage>
        </div>
        <div v-if="category" class="col-9 mt-3" style="overflow-x: hidden">
        
        </div>
      </div>
      <div class="row">
        <div>
          <Footer></Footer>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Setting from "../components/Setting.vue";
import HomeSetting from "../components/HomeSetting.vue";
import MainPage from "../components/MainPage.vue";
import Footer from "../components/Footer.vue";
import Category from "../components/Category.vue";

export default {
  name: "HomeView",
  components: { NavBar, Setting, HomeSetting, MainPage, Footer, Category },
  GetData() {
    text = this.$refs.MainPage;
    console.log(text);
  },
};
</script>
