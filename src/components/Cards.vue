<template>
    <div id="cards">
        <mdb-container>
            <mdb-row>
                <mdb-card-group deck>
                    <mdb-card>
                        <mdb-view hover>
                            <a href="#!">
                                <img id="honda-van" src="../assets/honda-van-car-site.jpg" alt="Card image cap">
                                <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                            </a>
                        </mdb-view>
                        <mdb-card-body>
                            <mdb-card-title>Vans</mdb-card-title>
                            <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                                card's content.</mdb-card-text>
                            <mdb-btn color="primary">Read more</mdb-btn>
                        </mdb-card-body>
                    </mdb-card>
                    <mdb-card>
                        <mdb-view hover>
                            <a href="#!">
                                <img id="ram-silver" src="../assets/ram-dodge-truck-silver-car-site.jpg" alt="Card image cap">
                                <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                            </a>
                        </mdb-view>
                        <mdb-card-body>
                            <mdb-card-title>Trucks</mdb-card-title>
                            <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                                card's content.</mdb-card-text>
                            <mdb-btn color="primary">Read more</mdb-btn>
                        </mdb-card-body>
                    </mdb-card>
                    <mdb-card>
                        <mdb-view hover>
                            <a href="#!">
                                <img id="toyota-van" src="../assets/toyota-van-car-site.jpg" alt="Card image cap">
                                <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                            </a>
                        </mdb-view>
                        <mdb-card-body>
                            <mdb-card-title>Other</mdb-card-title>
                            <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                                card's content.</mdb-card-text>
                            <mdb-btn color="primary">Read more</mdb-btn>
                        </mdb-card-body>
                    </mdb-card>
                </mdb-card-group>
            </mdb-row>
        </mdb-container>
    </div>
</template>

<script>
	import { mdbContainer, mdbRow, mdbCard, mdbCardBody, mdbCardTitle, mdbCardText, mdbCardGroup, mdbBtn, mdbView, mdbMask } from 'mdbvue';
	export default {
		name: 'Cards',
		components: {
			mdbContainer,
			mdbRow,
			mdbCard,
			mdbCardBody,
			mdbCardTitle,
			mdbCardText,
			mdbCardGroup,
			mdbBtn,
			mdbView,
			mdbMask
		}
	}
</script>

<style scoped>
#cards{
    margin-top: 1%;
}

#honda-van{
    width: 100%;
}

#ram-silver{
    width: 100%;
}

#toyota-van{
    width: 100%;
}

</style>