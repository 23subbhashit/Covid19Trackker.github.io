<template>
    <div>
        <Jumbo></Jumbo>
        <br>
        <br>
        <Bread></Bread>
        <hr/>
        <Aboutcorona></Aboutcorona>
        <PerDayVisual></PerDayVisual>
        <!--<Carousel></Carousel>-->
        <Content></Content>
        <ProfileCards></ProfileCards>    
    </div>
</template>
<script>
import Jumbo from '@/components/HomePage/Jumbo'
import ProfileCards from '@/components/HomePage/ProfileCards'
import Bread from '@/components/HomePage/Breads/Bread'
import PerDayVisual from '@/components/HomePage/PerDayVisual'
import Aboutcorona from '@/components/HomePage/Aboutcorona'
import Content from '@/components/HomePage/Content'
//import DataCollector from '@/components/DataGathering/DataCollector'
//import ForMap from '@/components/DataGathering/ForMap'
//import Prevention from '@/components/HomePage/Prevention'
//import Carousel from '@/components/HomePage/Carousel'
export default {   
    components : {
        ProfileCards,
        Bread,
        Jumbo,
        PerDayVisual,
        Aboutcorona,
        Content,
        //ForMap
        //Prevention,
        //Carousel,
    }
}
</script>