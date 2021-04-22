<template>
<div class="wrapper">
      <Sidebar/>
      <div class="main-panel">
      <Header/>
      <div class="content" style="">
        <div class="graveyard b-grey collapse show">
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
            <div class="grave-boxes d-flex">
            <div class=" w-25">
              <SimpleCard/>
            </div>
            <div class="grave-chat-ri W-75">
                <div class="grave-chat-inr mb-4">
                    <h4>Chat</h4>
                    <nav class="py-3">
                        <div class="nav nav-fill ul-grave-chat" id="nav-tab" role="tablist">
                            <a class="nav-item nav-link active" id="nav-home-tab" data-toggle="tab" href="#nav-home" role="tab" aria-controls="nav-home" aria-selected="true">Recent</a>
                            <a class="nav-item nav-link" id="nav-profile-tab" data-toggle="tab" href="#nav-profile" role="tab" aria-controls="nav-profile" aria-selected="false">All Chats</a>
                            <a class="nav-item nav-link" id="nav-contact-tab" data-toggle="tab" href="#nav-contact" role="tab" aria-controls="nav-contact" aria-selected="false">Team</a>
                        </div>
                    </nav>
                    <div class="tab-content" id="nav-tabContent">
                        <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">
                            <ul>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                            </ul>
                        </div>
                        <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab">
                            <ul>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                            </ul>
                        </div>
                        <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab">
                            <ul>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                                <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="grave-chat-inr">
                    <h4 class="mb-4">Share</h4>
                    <h6>From:</h6>
                    <ul class="py-3">
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                    </ul>
                    <h6>To:</h6>
                    <ul class="py-3">
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                      <li><img src="../assets/img/Profile-Picture.svg"><span class="name">Luke @V1.VC</span></li>
                  </ul>
                </div>
            </div>
        </div>
      </div>
      </div>
    </div>
</div>
</template>

<script>
import '../assets/css/graveyard.css'
import Header from './Header.vue'
import Sidebar from './Sidebar.vue'
import SearchFilter from './SearchFilter.vue'
import SimpleCard from './SimpleCard.vue'

export default {
  name: 'Graveyard',
  components: {
    Header,
    Sidebar,
    SearchFilter,
    SimpleCard
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-panel > .navbar, .wrapper .sidebar {
    background: #191A32 !important;
}
.main-panel {
    background: #031f33;
}
</style>
