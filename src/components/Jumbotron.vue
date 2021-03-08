<template>
    <div>
        <mdb-card class="card-image">
            <div class="text-white text-center rgba-stylish-strong py-5 px-4">
            <div class="py-5">
                <h2 class="card-title h2 my-4 py-2">Car Site</h2>
                <p class="mb-4 pb-2 px-md-5 mx-md-5">You think water moves fast? You should see ice. It moves like it has a mind. Like it knows it killed the world once and got a taste for murder. After the avalanche, it took us a week to climb out. Now, I don't know exactly when we turned on each other, but I know that seven of us survived the slide... and only five made it out. Now we took an oath, that I'm breaking now. We said we'd say it was the snow that killed the other two, but it wasn't. Nature is lethal but it doesn't hold a candle to man.</p>
                <router-link to="/used-cars"><mdb-btn tag="a" gradient="peach" icon="clone">Buy a car</mdb-btn></router-link>
            </div>
            </div>
        </mdb-card>
    </div>
</template>

<script>
  import { mdbCard, mdbBtn } from 'mdbvue';
  export default {
    name: 'Jumbotron',
    components: {
      mdbCard,
      mdbBtn
    }
  }
</script>

<style scoped>

.card-image{
  background-image:url("../assets/warehouse-vehicles-car-site.jpg");
  background-repeat: no-repeat;
  margin-left: 25%;
  margin-right: 25%;
  margin-top: 1%;
}

</style>