<template>
    <div>
        <mdb-container>
            <section class="text-center my-5">
            <h2 class="h1-responsive font-weight-bold text-center my-5">Used Cars</h2>
            <p class="grey-text text-center w-responsive mx-auto mb-5">Explore and find your favorite used car!</p>
            <mdb-row>
                <mdb-col lg="3" md="6" class="mb-lg-0 mb-4">
                <mdb-card cascade narrow ecommerce>
                    <mdb-view overlay="white-slight" cascade>
                    <img id="corolla" src="../assets/toyota-car-site.jpg" waves top alt="sample photo"/>
                    </mdb-view>
                    <mdb-card-body class="text-center" cascade>
                    <a href="" class="grey-text">
                        <h5>Toyota</h5>
                    </a>
                    <mdb-card-title>
                        <strong>
                        <a href="">Corolla</a>
                        </strong>
                    </mdb-card-title>
                    <!-- <ul class="rating">
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon far icon="star"></mdb-icon>
                        </li>
                    </ul> -->
                    <mdb-card-text>Neque porro quisquam est, qui dolorem ipsum quia dolor sit.</mdb-card-text>
                    <mdb-card-footer color="white" textColor="black" class="px-1">
                        <span class="float-left font-weight-bold">
                        <strong>$20,000</strong>
                        </span>
                        <span class="float-right">
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to cart
                            </div>
                            <mdb-icon slot="reference" icon="shopping-cart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Share
                            </div>
                            <mdb-icon slot="reference" icon="share-alt" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a class="active">
                            <mdb-tooltip trigger="hover" class="active" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Added to watchlist
                            </div>
                            <mdb-icon slot="reference" icon="heart" class="ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        </span>
                    </mdb-card-footer>
                    </mdb-card-body>
                </mdb-card>
                </mdb-col>
                <mdb-col lg="3" md="6" class="mb-lg-0 mb-4">
                <mdb-card cascade narrow ecommerce>
                    <mdb-view overlay="white-slight" cascade>
                    <img id="old-honda" src="../assets/honda-old-cheap-car-site.jpg" waves top alt="sample photo"/>
                    </mdb-view>
                    <mdb-card-body class="text-center" cascade>
                    <a href="" class="grey-text">
                        <h5>Honda</h5>
                    </a>
                    <mdb-card-title>
                        <strong>
                        <a href="">Old</a>
                        </strong>
                    </mdb-card-title>
                    <!-- <ul class="rating">
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                    </ul> -->
                    <mdb-card-text>Neque porro quisquam est, qui dolorem ipsum quia dolor sit.</mdb-card-text>
                    <mdb-card-footer color="white" textColor="black" class="px-1">
                        <span class="float-left font-weight-bold">
                        <strong>$1,000</strong>
                        </span>
                        <span class="float-right">
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to cart
                            </div>
                            <mdb-icon slot="reference" icon="shopping-cart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Share
                            </div>
                            <mdb-icon slot="reference" icon="share-alt" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to watchlist
                            </div>
                            <mdb-icon slot="reference" icon="heart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        </span>
                    </mdb-card-footer>
                    </mdb-card-body>
                </mdb-card>
                </mdb-col>
                <mdb-col lg="3" md="6" class="mb-lg-0 mb-4">
                <mdb-card cascade narrow ecommerce>
                    <mdb-view overlay="white-slight" cascade>
                    <img id="small-pickup" src="../assets/ram-dodge-truck-small-pickup-silver-car-site.jpg" waves top alt="sample photo"/>
                    </mdb-view>
                    <mdb-card-body class="text-center" cascade>
                    <a href="" class="grey-text">
                        <h5>Ram</h5>
                    </a>
                    <mdb-card-title>
                        <strong>
                        <a href="">Dodge Truck</a>
                        </strong>
                    </mdb-card-title>
                    <!-- <ul class="rating">
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star-half-alt"></mdb-icon>
                        </li>
                    </ul> -->
                    <mdb-card-text>Neque porro quisquam est, qui dolorem ipsum quia dolor sit.</mdb-card-text>
                    <mdb-card-footer color="white" textColor="black" class="px-1">
                        <span class="float-left font-weight-bold">
                        <strong>$5,000</strong>
                        </span>
                        <span class="float-right">
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to cart
                            </div>
                            <mdb-icon slot="reference" icon="shopping-cart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Share
                            </div>
                            <mdb-icon slot="reference" icon="share-alt" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to watchlist
                            </div>
                            <mdb-icon slot="reference" icon="heart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        </span>
                    </mdb-card-footer>
                    </mdb-card-body>
                </mdb-card>
                </mdb-col>
                <mdb-col lg="3" md="6" class="mb-lg-0 mb-4">
                <mdb-card cascade narrow ecommerce>
                    <mdb-view overlay="white-slight" cascade>
                    <img id="orange-camaro" src="../assets/chevrolet-camaro-modern-orange-car-site.jpg" waves top alt="sample photo"/>
                    </mdb-view>
                    <mdb-card-body class="text-center" cascade>
                    <a href="" class="grey-text">
                        <h5>Chevrolet</h5>
                    </a>
                    <mdb-card-title>
                        <strong>
                        <a href="">Camaro</a>
                        </strong>
                    </mdb-card-title>
                    <!-- <ul class="rating">
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon icon="star"></mdb-icon>
                        </li>
                        <li>
                        <mdb-icon far icon="star"></mdb-icon>
                        </li>
                    </ul> -->
                    <mdb-card-text>Neque porro quisquam est, qui dolorem ipsum quia dolor sit.</mdb-card-text>
                    <mdb-card-footer color="white" textColor="black" class="px-1">
                        <span class="float-left font-weight-bold">
                        <strong>$30,000</strong>
                        </span>
                        <span class="float-right">
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Add to cart
                            </div>
                            <mdb-icon slot="reference" icon="shopping-cart" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a>
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Share
                            </div>
                            <mdb-icon slot="reference" icon="share-alt" class="grey-text ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        <a class="active">
                            <mdb-tooltip trigger="hover" :options="{placement: 'top'}">
                            <div class="tooltip">
                                Added to watchlist
                            </div>
                            <mdb-icon slot="reference" icon="heart" class="ml-3"></mdb-icon>
                            </mdb-tooltip>
                        </a>
                        </span>
                    </mdb-card-footer>
                    </mdb-card-body>
                </mdb-card>
                </mdb-col>
            </mdb-row>
            </section>
        </mdb-container>
    </div>
</template>

<script>
  import { mdbContainer, mdbRow, mdbCol, mdbCard, mdbCardBody, mdbCardTitle, mdbCardFooter, mdbCardText, mdbIcon, mdbTooltip, mdbView } from 'mdbvue';
  export default {
    name: 'Ecommerce',
    components: {
      mdbContainer,
      mdbRow,
      mdbCol,
      mdbCard,
      mdbCardBody,
      mdbCardTitle,
      mdbCardFooter,
      mdbCardText,
      mdbIcon,
      mdbTooltip,
      mdbView
  }
}
</script>

<style scoped>
#corolla{
    width: 100%;
}

#old-honda{
    width: 100%;
}

#small-pickup{
    width: 100%;
}

#orange-camaro{
    width: 100%;
}

</style>