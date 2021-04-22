<template>
  <div class="sidebar" data-color="purple" data-background-color="white">
        <div class="logo">
          <a href="javascript:(void);" class="simple-text logo-mini" title="logo">
            <img src="../assets/img/main-logo.png">
          </a>
        </div>
        <div class="side-nav1">
          <ul class="nav">
            <li class="nav-item active  ">
              <a class="nav-link" href="Explore.vue">
                <img src="../assets/img/line-1.png" alt="image" title="Explore">
                <button class="sh-tool">Explore</button>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/telescope.png" alt="image" title="tooltip">
                <button class="sh-tool">Dashboard</button>
              </a>
            </li>
            <hr/>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/waves.svg" alt="image" title="tooltip">
                <button class="sh-tool">Lets Chat</button>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Graveyard">
                <img src="../assets/img/Hand.png" alt="image" title="tooltip">
                <button class="sh-tool">Graveyard</button>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/chat.png" alt="image" title="tooltip">
                <span class="show-count b-yellow">5</span>
                <button class="sh-tool">Favourites</button>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/files.svg" alt="image" title="tooltip">
                <span class="show-count b-yellow">5</span>
                <button class="sh-tool">Favourites</button>
              </a>
            </li>
            <hr/>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/users.svg" alt="image" title="tooltip">
                <button class="sh-tool">Favourites</button>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:(void);">
                <img src="../assets/img/search.svg" alt="image" title="tooltip">
                <button class="sh-tool">Favourites</button>
              </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="javascript:(void);">
                    <img src="../assets/img/blanck-boxes.svg" alt="image" title="tooltip">
                    <button class="sh-tool">Favourites</button>
                </a>
            </li>
          </ul>
        </div>
        <div class="empty">
        </div>
      </div>
</template>

<script>
export default {
  name: 'Sidebar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
