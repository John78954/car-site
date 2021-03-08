<template>
    <div>
        <Navbar/>
        <Jumbotron/>
        <Cards/>
        <Footer />
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Jumbotron from '../components/Jumbotron.vue'
import Cards from '../components/Cards.vue'
import Footer from '../components/Footer.vue'

export default {
    name: "Home",
    components: {
        Navbar,
        Jumbotron,
        Cards,
        Footer
    }
}
</script>

<style scoped>

</style>