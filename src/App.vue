<template>
  <div id="app">
    <Header/>
    <Outstaffing/>
    <ItSpecialist/>
    <Resources/>
    <OurAdvantages/>
    <Form/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/header/Header";
import Outstaffing from "@/components/outstaffing/Outstaffing";
import ItSpecialist from "@/components/itSpecialist/ItSpecialist";
import Resources from "@/components/resources/Resources";
import OurAdvantages from "@/components/ourAdvantages/OurAdvantages";
import Form from "@/components/form/Form";
import Footer from "@/components/footer/Footer";
import Vue from 'vue';
import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';

Vue.use(ElementUI);
export default {
  name: 'App',
  components: {
    Header,
    Outstaffing,
    ItSpecialist,
    Resources,
    OurAdvantages,
    Form,
    Footer,
  }
}
</script>

<style>

body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "G TEesti Pro Display", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  position: relative;
  overflow: hidden;
}

@media only screen and (max-width: 768px) {
  #app {
    overflow: visible;
  }
}
</style>
