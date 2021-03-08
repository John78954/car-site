<template>
    <div>
        <mdb-footer color="blue" class="font-small pt-4 mt-4">
            <div class="footer-copyright text-center py-3">
            <mdb-container fluid>
                &copy; 2021 Copyright: <a href="https://www.techproart.com"> Techproart.com </a>
            </mdb-container>
            </div>
        </mdb-footer>
    </div>
</template>

<script>
  import { mdbFooter, mdbContainer } from 'mdbvue';
  export default {
    name: 'Footer',
    components: {
      mdbFooter,
      mdbContainer
    }
  }
</script>

<style scoped>

</style>