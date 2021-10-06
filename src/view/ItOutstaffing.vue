<template>
  <div>
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

export default {
  name: 'ItOutstaffing',
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

<style scoped>
div {
  position: relative;
  overflow: hidden;
}
@media only screen and (max-width: 425px) {
  div {
    overflow: visible;
  }
}
</style>
