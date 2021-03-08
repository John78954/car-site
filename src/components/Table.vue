<template>
  <div id="table">
    <mdb-tbl bordered>
      <mdb-tbl-head>
        <tr>
          <th>Brand</th>
          <th>Year</th>
          <th>Vehicle</th>
          <th>Price</th>
        </tr>
      </mdb-tbl-head>
      <mdb-tbl-body>
        <tr v-for="car in cars" v-bind:key="car.id">
          <th>{{ car.brand }}</th>
          <td>{{ car.year }}</td>
          <td>{{ car.vehicle }}</td>
          <td>{{ car.price }}</td>
          <!-- <th v-for="value in brands" v-bind:key="value">{{ value }}</th> -->
        </tr>
      </mdb-tbl-body>
    </mdb-tbl>
  </div>
</template>

<script>
  import { mdbTbl, mdbTblHead, mdbTblBody } from 'mdbvue';
  export default {
    name: 'Table',
    components: {
      mdbTbl,
      mdbTblHead,
      mdbTblBody
    },
    data: function() {
        return {
            cars: [
                {
                    brand: "Toyota",
                    year: "2021",
                    vehicle: "Car",
                    price: "$10,000"
                },
                {
                    brand: "Chevy",
                    year: "2021",
                    vehicle: "Car",
                    price: "$30,000"
                },
                {
                    brand: "Ram",
                    year: "2021",
                    vehicle: "Truck",
                    price: "$35,000"
                },
                {
                    brand: "Honda",
                    year: "2021",
                    vehicle: "Motorcycle",
                    price: "$25,000"
                }
            ]
        }
    }
  }
</script>

<style scoped>
#table{
    margin-left: 35%;
    margin-right: 35%;
}

</style>