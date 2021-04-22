<template>
  <div class="filter-box h-100 collapse"  id="notifications-box" >
        <div class="head-title-box">
          <h4>Alerts</h4>
          <ul class="d-flex">
              <li class="active" data-toggle="collapse" data-target="#pend-mess" aria-expanded="false">Pending</li>
              <li class="" data-toggle="collapse" data-target="#his-mess" aria-expanded="false">History</li>
          </ul>
        </div>
        <div class="alert-mess collapse show" id ="pend-mess">
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-orange" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>Playground</b> would like to add you to their network.</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
              <img src="../assets/img/short-billboard.png">
              <a href="">
                <img src="../assets/img/fullscreen-icon.png"></a>
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-yellow" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>Playground</b> would like to add you to their network.</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
              <img src="../assets/img/short-billboard.png">
              <a href="">
                <img src="../assets/img/fullscreen-icon.png"></a>
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-n-mess.png" class="b-light-blue" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>New Message</b> from Chance Vaccaro</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-n-mess.png" class="b-grey" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>New Message</b> from Chance Vaccaro</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
        </div>
        <div class="alert-mess collapse" id="his-mess" style="">
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-orange" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>Playground</b> would like to add you to their network.</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-yellow" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>Playground</b> would like to add you to their network.</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-n-mess.png" class="b-light-blue" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>New Message</b> from Chance Vaccaro</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-n-mess.png" class="b-grey" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>New Message</b> from Chance Vaccaro</h4>
                <p>1 weak ago</p>
              <div class="alt-cont-im">
                <a class="" href="javascript:void(0);">Accept</a>
                <a class="" href="javascript:void(0);">Decline</a>
              </div>
            </div>
            <div class="ri-box">
            </div>
          </div>
          </div>
      </div>
</template>

<script>
import '../assets/css/alert.scss'

export default {
  name: 'Notificationsbox'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
