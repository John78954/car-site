<template>
    <div>
        <Navbar/>
        <Ecommerce/>
        <Table/>
        <Footer/>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Ecommerce from '../components/Ecommerce.vue'
import Table from '../components/Table.vue'
import Footer from '../components/Footer.vue'

export default {
    name: "Usedcars",
    components: {
        Navbar,
        Ecommerce,
        Table,
        Footer
    }
}
</script>

<style scoped>

</style>