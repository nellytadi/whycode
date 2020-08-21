<template>
  <div>
    <Header />
    <Banner />
    <Features />
    <!--<CallToAction />-->
    <!--<CallToActionTwo />-->
    <Testimonial />
    <Brands />
    <Counter />
    <Screenshots />

    <Faq />
    <Contact />
    <!--<BlogHome />-->
    <Subscribe />
    <Footer />
  </div>
</template>
<script>
  import Header from "~/components/Header.vue";
  import Banner from "~/components/Banner.vue";
  import Features from "~/components/Features.vue";
//  import CallToAction from "~/components/CallToAction.vue";
  import Testimonial from "~/components/Testimonial.vue";
  import Brands from "~/components/Brands.vue";
  import Counter from "~/components/Counter.vue";
  import Screenshots from "~/components/Screenshots.vue";
  import Contact from "~/components/Contact.vue";
  import Faq from "~/components/Faq.vue";
  import Subscribe from "~/components/Subscribe.vue";
  import Footer from "~/components/Footer.vue";
  export default {
    components: {
      Header,
      Banner,
      Features,
     // Video,
//      CallToAction,
//      CallToActionTwo,
      Testimonial,
      Brands,
      Counter,
      Screenshots,
      Contact,
      Faq,
//      BlogHome,
      Subscribe,
      Footer,

    },
    head(){
      return {
        title: "Why Code | Home"
      }
    }
  }
</script>
