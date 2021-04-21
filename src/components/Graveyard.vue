<template>
    <div class="collapse">
        <Navsidemenu/>
        <div class="ex-line d-flex ali-cen pb-3">
                <div class="explore-points">
                    <ul>
                        <li><h4>Deadflow (12)</h4></li>
                        <li class="active"><a href="">All</a></li>
                        <li class=""><a href="">Fund One</a></li>
                        <li class=""><a href="">Fund Two</a></li>
                        <li class=""><a href="">Fund Three</a></li>
                    </ul>
                </div>
                <div class="search-filter">
                    <form class="form-inline my-2 my-lg-0 mx-auto">
                        <button class="btn my-2 my-sm-0" type="button"><img src="img/filter.png"></button>
                      <input class="form-control mr-sm-2" type="text" placeholder="Search">
                    </form>
                </div>
            <SearchFilter/>
            </div>
            <div class="ex-tab my-sm-5 ">
                <ul>
                    <li><button class="btn" type="button">New (3)</button></li>
                    <li><button class="btn" type="button">Active (3)</button></li>
                    <li><button class="btn" type="button">Requested (2)</button></li>
                    <li><button class="btn" type="button">Following (2)</button></li>
                    <li class="active"><button class="btn" type="button">Graveyard (3)</button></li>
                </ul>
            </div>
            <div class="gr-box-line d-flex d-fl-wr">
            <div class="grave">
                <div class="im-box">
                <img class="logo declined-logo" src="../assets/img/bilboard-logo.png" alt="Logo">
                </div>
                <div class="bot-line-div"></div>
                <a href="#" class="action-red resurrect-button" data-toggle="collapse" data-target="#n" aria-expanded="false"> See File</a>
            </div>
            </div>
      </div>
</template>

<script>
import '../assets/css/graveyard.scss'
import Navsidemenu from './Navsidemenu.vue'
import SearchFilter from './SearchFilter.vue'

export default {
  name: 'Graveyard',
  components: {
    Navsidemenu,
    SearchFilter
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
