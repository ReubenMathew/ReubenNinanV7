<template>
    <div class="">
        <div class="z-0 flex bgimg min-h-screen bg-fixed bg-cover bg-center">
            <div class="z-10 text-left justify-center self-center w-full">
                <div class="">
                    <NameCard class="md:ml-20"/>
                </div>
            </div>
        </div>
    </div>
</template>

<style type="text/css">

@import url('https://fonts.googleapis.com/css?family=Roboto|Nunito');
* {
    font-family: 'Nunito', sans-serif;
}

.bgimg {
    background-image: url('../assets/img/city.jpg');
}

</style>

<script>
import NameCard from './NameCard'

export default {
    components:{
        NameCard,
    }
}
</script>