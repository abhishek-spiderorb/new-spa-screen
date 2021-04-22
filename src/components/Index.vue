<template>
<div class="wrapper">
      <Sidebar/>
      <div class="main-panel" data-scroller="true" data-prevent-mouse-scroll="true">
      <Header/>
      <div class="content" style="">
      <Explore/>
      <Deadflow/>
      <Notificationsbox/>
    </div>
    </div>
    <Innermodals/>
    <ConfrenceRoom/>
    <Notifications/>
</div>
</template>

<script>
import Header from './Header.vue'
import Sidebar from './Sidebar.vue'
import Explore from './Explore.vue'
import Deadflow from './Deadflow.vue'
import Notificationsbox from './Notificationsbox.vue'
import Innermodals from './Innermodals.vue'
import ConfrenceRoom from './ConfrenceRoom.vue'
import Notifications from './Notifications.vue'

export default {
  name: 'Index',
  components: {
    Header,
    Sidebar,
    Explore,
    Deadflow,
    Notificationsbox,
    Innermodals,
    ConfrenceRoom,
    Notifications
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
