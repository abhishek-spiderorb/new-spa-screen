<template>
  <div class="filter-box confrence-box h-100 collapse" id="confrence-room">
        <div class="head-title-box">
          <h4>Confrence Room</h4>
          <ul class="d-flex">
              <li class="active" data-toggle="collapse" data-target="#pend-mess" aria-expanded="false">Meetings</li>
              <li class="" data-toggle="collapse" data-target="#his-mess" aria-expanded="false">Rooms <span class="b-yellow">new</span></li>
          </ul>
        </div>
        <div class="alert-mess collapse show" id="pend-mess">
            <div class="head-title-box">
                <input type="text" placeholder="Search Messages">
                <h5>Today's Meeting</h5>
                <div class="b-white tod-meet-emp">
                  <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                      <span aria-hidden="true">×</span>
                  </button>
                  <div class="alt-cont">
                      <h4>You have no meetings scheduled for today</h4>
                  </div>
                </div>
                <h5>Tommorow's Meeting</h5>
            </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-yellow" alt="">
            </div>
            <div class="alt-cont">
                <p>11:30 - 12:00 AM</p>
                <h4><b>AYLO</b></h4>
            </div>
            <span class="arrow-right"></span>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-grey" alt="image">
            </div>
            <div class="alt-cont">
                <p>11:30 - 12:00 AM</p>
                <h4><b>SnowGoggles</b></h4>
            </div>
            <span class="arrow-right"></span>
          </div>
          <div class="iner-alt b-white but">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-orange" alt="">
            </div>
            <div class="alt-cont">
                <p>1 weak ago</p>
                <h4><b>Playground</b></h4>
            </div>
            <span class="arrow-right"></span>
          </div>
        </div>
        <div class="alert-mess collapse" id="his-mess">
            <div class="head-title-box">
                <h5>Open Rooms</h5>
                <div class="ex-tab py-sm-3">
                    <ul>
                        <li class="active"><button class="btn" type="button">Newest</button></li>
                        <li><button class="btn" type="button">Oldest</button></li>
                        <li class=""><button class="btn" type="button">Closed Rooms</button></li>
                    </ul>
                </div>
            </div>
          <div class="iner-alt b-white but op-room">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-yellow" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>AYLO</b></h4>
                <p>11:30 - 12:00 AM</p>
            </div>
            <span class="arrow-right"></span>
          </div>
          <div class="iner-alt b-white but op-room">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-grey" alt="image">
            </div>
            <div class="alt-cont">
                <h4><b>SnowGoggles</b></h4>
                <p>11:30 - 12:00 AM</p>
            </div>
            <span class="arrow-right"></span>
          </div>
          <div class="iner-alt b-white but op-room">
            <div class="im">
              <img src="../assets/img/short-playground.png" class="b-orange" alt="">
            </div>
            <div class="alt-cont">
                <h4><b>Playground</b></h4>
                <p>11:30 - 12:00 AM</p>
            </div>
            <span class="arrow-right"></span>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  name: 'ConfrenceRoom'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
