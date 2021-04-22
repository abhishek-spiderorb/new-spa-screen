<template>
<div class="wrapper">
      <Sidebar/>
      <div class="">
      <Header/>
      <div class="" style="">
        <Navsidemenu/>
        <div class="ex-line d-flex ali-cen py-sm-3">
            <div class="blank">
            </div>
            <div class="explore-points">
                <ul>
                    <li><h4>Explore (12)</h4></li>
                    <li class="active"><a href="">Trending (30)</a></li>
                    <li class=""><a href="">Newest</a></li>
                </ul>
            </div>
            <div class="blank">
            </div>
            <SearchFilter/>
        </div>
        <div class="ex-tab py-sm-3">
            <ul>
                <li><button class="btn" type="button">Aerospace</button></li>
                <li class="active"><button class="btn" type="button">E-Comm</button></li>
                <li class=""><button class="btn" type="button">Beauty</button></li>
            </ul>
        </div>
        <SwipeCards/>
      </div>
      </div>
</div>
</template>

<script>
import '../assets/css/explore.scss'
import Header from './Header.vue'
import Sidebar from './Sidebar.vue'
import Navsidemenu from './Navsidemenu.vue'
import SearchFilter from './SearchFilter.vue'
import SwipeCards from './SwipeCards.vue'

export default {
  name: 'Explore',
  components: {
    Header,
    Sidebar,
    Navsidemenu,
    SearchFilter,
    SwipeCards
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
