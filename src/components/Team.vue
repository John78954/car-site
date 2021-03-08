<template>
  <mdb-container>
    <section id="team-section" class="text-center">
      <h2 class="h1-responsive font-weight-bold my-5">About Car Sites</h2>
      <p class="grey-text w-responsive mb-5 mx-auto">Do you see any Teletubbies in here? Do you see a slender plastic tag clipped to my shirt with my name printed on it? Do you see a little Asian child with a blank expression on his face sitting outside on a mechanical helicopter that shakes when you put quarters in it? No? Well, that's what you see at a toy store. And you must think you're in a toy store, because you're here shopping for an infant named Jeb.</p>
      <mdb-row>
        <mdb-col id="john" md="4" class="mb-md-0 mb-5">
          <img tag="img" src="../assets/john-pena.jpg" class="rounded z-depth-1-half img-fluid" alt="Sample avatar"/>
          <h4 class="font-weight-bold black-text my-4">John Pena</h4>
          <h6 class="text-uppercase black-text mb-3">Front-end Developer</h6>
          <mdb-btn tag="a" floating size="sm" class="mx-1 mb-0 btn-email">
            <mdb-icon icon="envelope"/>
          </mdb-btn>
          <mdb-btn tag="a" floating size="sm" class="mx-1 mb-0 btn-li">
            <mdb-icon fab icon="linkedin"/>
          </mdb-btn>
          <mdb-btn tag="a" floating size="sm" class="mx-1 mb-0 btn-git">
            <mdb-icon fab icon="github"/>
          </mdb-btn>
        </mdb-col>
      </mdb-row>
    </section>
  </mdb-container>
</template>

<script>
  import { mdbContainer, mdbRow, mdbCol, mdbIcon, mdbBtn } from 'mdbvue';
  export default {
    name: 'Team',
    components: {
      mdbContainer,
      mdbRow,
      mdbCol,
      mdbIcon,
      mdbBtn
    }
  }
</script>

<style scoped>
  .avatar {
    max-width: 200px;
  }
  #john{
      margin-left: 32%;
  }
</style>