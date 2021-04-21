<template>
<div class="wrapper">
      <Sidebar/>
      <div class="main-panel" data-scroller="true" data-prevent-mouse-scroll="true">
      <Header/>
      <div class="content" style="">
      <Explore/>
      <Deadflow/>
      <Graveyard/>
      <Alertsbox/>
    </div>
    </div>
    <Innermodals/>
    <ConfrenceRoom/>
</div>
</template>

<script>
import Header from './Header.vue'
import Sidebar from './Sidebar.vue'
import Explore from './Explore.vue'
import Deadflow from './Deadflow.vue'
import Graveyard from './Graveyard.vue'
import Alertsbox from './alertsbox.vue'
import Innermodals from './Innermodals.vue'
import ConfrenceRoom from './ConfrenceRoom.vue'

export default {
  name: 'Index',
  components: {
    Header,
    Sidebar,
    Explore,
    Deadflow,
    Graveyard,
    Alertsbox,
    Innermodals,
    ConfrenceRoom
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
