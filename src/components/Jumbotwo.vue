<template>
    <div>
        <mdb-jumbotron class="mb-0 text-center">
            <img class="my-4" src="../assets/chevrolet-camaro-modern-silver-car-site.jpg" alt="">
            <a><mdb-mask waves overlay="white-slight"/></a>
        </mdb-jumbotron>
    </div>
</template>

<script>
  import { mdbJumbotron, mdbMask } from 'mdbvue';
  export default {
    name: 'Jumbotwo',
    components: {
      mdbJumbotron,
      mdbMask,
    }
  }
</script>


<style scoped>

</style>