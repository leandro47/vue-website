<template>
    <div>
        <div>
            <div class="container">
                <div class="row mt-5">
                    <h3>
                        Voce esta vendo as noticias do : {{championship}}
                    </h3>
                </div>
            </div>
        </div>
        <HcodeSectionBanner />
        <HcodeSectionNews />
        <div class="container">
            <div class="row my-club mt-5">
                <div class="col-6">
                    <h2>Seu clube é: {{myClub}}</h2>
                </div>
                <div class="col-6">
                    <hcodeInput v-model="myClub"/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import HcodeSectionBanner from './HcodeSectionBanner'
import HcodeSectionNews from './HcodeSectionNews'
import HcodeInput from './HcodeInput'


export default {
    components: {
        HcodeSectionBanner,
        HcodeSectionNews,
        HcodeInput
    },
    data(){
        return {
            myClub: 'Hcode Treinamentos'
        }
    },
    props:{
        championship: String
    }
}
</script>

<style scoped>

</style>