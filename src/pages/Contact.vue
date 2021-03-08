<template>
    <div>
        <Navbar/>
        <Jumbothree/>
        <Form/>
        <Footer/>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Jumbothree from '../components/Jumbothree.vue'
import Form from '../components/Form.vue'
import Footer from '../components/Footer.vue'

export default {
    name: "Contact",
    components: {
        Navbar,
        Jumbothree,
        Form,
        Footer
    }
}
</script>

<style scoped>

</style>