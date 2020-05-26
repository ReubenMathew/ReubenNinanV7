<template>
    
    <div class="">
        
        <div class="z-0 flex flex-wrap bgimg min-h-screen bg-fixed bg-cover bg-center">

            <div class="self-center py-4 text-left">   
                <NameCard class=""/>
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