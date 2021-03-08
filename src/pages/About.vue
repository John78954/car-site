<template>
    <div>
        <Navbar/>
        <Jumbotwo/>
        <Team/>
        <Footer/>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Jumbotwo from '../components/Jumbotwo.vue'
import Team from '../components/Team.vue'
import Footer from '../components/Footer.vue'

export default {
    name: "About",
    components: {
        Navbar,
        Jumbotwo,
        Team,
        Footer
    }
}
</script>

<style scoped>

</style>