<script>
import AppHeader from './components/AppHeader.vue';
import AppFeatures from './components/AppFeatures.vue';
import AppYoutubeLink from './components/AppYoutubeLink.vue';
import AppVideos from './components/AppVideos.vue';
import AppJoin from './components/AppJoin.vue';
import AppTraining from './components/AppTraining.vue';
import AppArticles from './components/AppArticles.vue';
import AppTestimonial from './components/AppTestimonial.vue';
import AppLinks from './components/AppLinks.vue';
import AppHighlighted from './components/AppHighlighted.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  components:{
    AppHeader,
    AppFeatures,
    AppYoutubeLink,
    AppVideos,
    AppJoin,
    AppTraining,
    AppArticles,
    AppTestimonial,
    AppLinks,
    AppHighlighted,
    AppFooter,

  },

  data(){
    return{

    }
  },
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppFeatures></AppFeatures>
  <AppYoutubeLink></AppYoutubeLink>
  <AppVideos></AppVideos>
  <AppJoin></AppJoin>
  <AppTraining></AppTraining>
  <AppArticles></AppArticles>
  <AppTestimonial></AppTestimonial>
  <AppLinks></AppLinks>
  <AppHighlighted></AppHighlighted>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './styles/general.scss';
</style>
