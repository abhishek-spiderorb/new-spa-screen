<template>
  <nav class="navbar navbar-expand-sm right-container">
          <img src="../assets/img/main-logo.png" class="res-top-logo">
            <button class="navbar-toggler navbar-toggler-right ml-auto" type="button" data-toggle="collapse" data-target="#navb">
              <i class="fa fa-bars" aria-hidden="true"></i>
            </button>
            <div class="collapse navbar-collapse" id="navb">
              <div class="head-r-l-box">
                  <a class="navbar-brand" href="javascript:void(0)"><img src="../assets/img/calender.svg"></a>
                  <a class="navbar-brand" href="javascript:void(0)" data-toggle="collapse" data-target="#top-right-alert" aria-expanded="false"><img src="../assets/img/bell.svg"><span class="show-count b-yellow">5</span></a>
                  <a class="navbar-brand" href="javascript:void(0)"><img src="../assets/img/chart.svg"><span class="show-count b-yellow"></span></a>
              </div>
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link" data-toggle="modal" data-target="#connect-link" href="javascript:void(0)">
                    <img src="../assets/img/connect-link-top.svg" alt="image"></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="javascript:void(0)" data-toggle="collapse" data-target="#view-invest" aria-expanded="false">
                      <div class="pp-box">
                          <img src="../assets/img/Profile-Picture.svg">
                          <p>Luke Frydenger</p>
                      </div>
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link click" href="javascript:void(0)"><img src="../assets/img/hamberger.svg" alt="image"></a>
                </li>
              </ul>
            </div>
        </nav>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
