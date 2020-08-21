<template>
    <div>
        <HeaderTwo />
        <PageHeader title="Contact" />

        <Contact />
        <Footer />
    </div>
</template>
<script>
    import HeaderTwo from "~/components/HeaderTwo.vue";
    import PageHeader from "~/components/PageHeader.vue";
    import Contact from "~/components/Contact.vue";
    import Footer from "~/components/Footer.vue";
    export default {
        components: {
            HeaderTwo,
            PageHeader,
            Contact,
            Footer,
        },
        head(){
            return {
                title: "Why Code | Contact"
            }
        }
    }
</script>
