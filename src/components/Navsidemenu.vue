<template>
  <div class="nav-side-menu" id="">

            <div class="menu-list">
                <ul id="menu-content" class="menu-content collapse out h-100">
                    <div class="top-line">
                      <a href="#">Reset</a>
                      <h5>Filter</h5>
                      <a href="javascript:(void);" data-toggle="collapse" data-target="#menu-content" aria-expanded="false">X</a>
                    </div>
                    <li  data-toggle="collapse" data-target="#products" class="collapsed">
                      <a href="#"> Location <span class="arrow"></span></a>
                    </li>
                    <ul class="sub-menu collapse" id="products">
                      <li class=""><a href="javascript:(void);" data-toggle="collapse" data-target="#location-content" aria-expanded="false">Location 1</a></li>
                      <li><a href="javascript:(void);" data-toggle="collapse" data-target="#sort-by-content" aria-expanded="false">Sort by</a></li>
                    </ul>
                    <li data-toggle="collapse" data-target="#sort-by-content" aria-expanded="false">
                      <a href="#"> Sort by <span class="arrow"></span></a>
                    </li>
                    <!-- <ul class="sub-menu collapse" id="service">
                      <li>New Service 1</li>
                    </ul> -->
                    <li data-toggle="collapse" data-target="#round-stage" aria-expanded="false">
                      <a href="#">Round Stage <span class="arrow"></span></a>
                    </li>
                    <!-- <ul class="sub-menu collapse" id="new">
                      <li>New New 1</li>
                    </ul> -->
                    <li data-toggle="collapse" data-target="#verticals" aria-expanded="false">
                      <a href="#">verticals<span class="arrow"></span></a>
                    </li>
                    <!-- <ul class="sub-menu collapse" id="new">
                      <li>New New 1</li>
                    </ul> -->
                    <li data-toggle="collapse" data-target="#types-invest" aria-expanded="false">
                      <a href="#">Types of Inverstment<span class="arrow"></span></a>
                    </li>
                    <!-- <ul class="sub-menu collapse" id="new">
                      <li>New New 1</li>
                    </ul> -->
                    <li data-toggle="collapse" data-target="#round-ulb" class="collapsed">
                      <a href="#">Round<span class="arrow"></span></a>
                    </li>
                    <ul class="sub-menu collapse" id="round-ulb">
                      <li data-toggle="collapse" data-target="#round" aria-expanded="false"><a href="#">Round</a></li>
                      <li data-toggle="collapse" data-target="#round-size" aria-expanded="false"><a href="#">Round Size</a></li>
                    </ul>
                    <li data-toggle="collapse" data-target="#revenue" aria-expanded="false">
                      <a href="#">Revenue: Pre/Post<span class="arrow"></span></a>
                    </li>
                    <!-- <ul class="sub-menu collapse" id="new">
                      <li>New New 1</li>
                    </ul> -->
                    <li><a href="#">Accelerator</a>
                      <div class="sw">
                      <label class="switch">
                        <input type="checkbox" checked>
                        <span class="slider round"></span>
                      </label>
                      </div>
                    </li>
                    <li><a href="#">Lead Investor</a>
                      <div class="sw">
                      <label class="switch">
                        <input type="checkbox" checked>
                        <span class="slider round"></span>
                      </label>
                      </div>
                    </li>
                    <div class="nav-side-last">
                      <div class="sa-filt">
                        <h5>Saved Filter</h5>
                        <div class="sa-filt-but">
                          <button class="">Name 1</button>
                          <button class="s-f">Name 2</button>
                          <button class="s-f">Name 3</button>
                        </div>
                      </div>
                      <div class="sf-apply">
                        <a href="javascript:(void);" class="active" data-toggle="modal" data-target="#name-filter-mod"><button class="">Apply</button></a>
                        <a href="javascript:(void);"><button class="s-f">Save Filter</button></a>
                      </div>
                  </div>
                </ul>
                <ul id="location-content" class="menu-content out h-100 collapse" style="">
                  <div class="top-line">
                    <a href="#">Reset</a>
                    <h5>Filter</h5>
                    <a href="javascript:(void);" data-toggle="collapse" data-target="#location-content" aria-expanded="true" class="">X</a>
                  </div>
                  <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#location-content" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                  <div class="al-loc">
                    <h5>Location</h5>
                    <div class="al-contine d-flex al-cen">
                        <a href="javascript:(void);" class="active">US</a>
                        <a href="javascript:(void);">International</a>
                    </div>
                  </div>
                  <hr>
                  <div class="select-all">
                    <input id="male" type="radio" name="male" title="male"><label for="select">Select All Locations</label>
                  </div>
                  <li data-toggle="collapse" data-target="#region" class="collapsed" aria-expanded="false">
                    <a href="#">Region<span class="arrow"></span></a>
                  </li>
                  <ul class="sub-menu collapse" id="region" style="">
                      <li><input id="select" type="radio" name="male"><label for="select">Select All</label></li>
                      <li><input id="north" type="radio" name="male"><label for="north">North East</label></li>
                      <li><input id="select" type="radio" name="male"><label for="select">Mid-Atlantic</label></li>
                      <li><input id="north" type="radio" name="male"><label for="north">South East</label></li>
                      <li><input id="select" type="radio" name="male"><label for="select">Midwest</label></li>
                      <li><input id="north" type="radio" name="male"><label for="north">Plains</label></li>
                      <li><input id="select" type="radio" name="male"><label for="select">Rocky Mountain</label></li>
                      <li><input id="north" type="radio" name="male"><label for="north">South West</label></li>
                      <li><input id="select" type="radio" name="male"><label for="select">West Coast</label></li>
                  </ul>
                  <li data-toggle="collapse" data-target="#status" class="collapsed">
                    <a href="#">Status<span class="arrow"></span></a>
                  </li>
                  <ul class="sub-menu collapse" id="status" style="">
                    <li><input id="select" type="radio" name="male"><label for="select">Select All</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Alabama</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Alaska</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Arizona</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Arkansas</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">california</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">colorado</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">connecticut</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">delaware</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">florida</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">georgia</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">hawali</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">idaho</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">illinois</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">indiana</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">lowa</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">kansas</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">kenfucky</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Louisiana</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Maine</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">maryland</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">massachusetts</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">michigan</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Minnesota</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Mississipi</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Missouri</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Montana</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Nebraska</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Nevada</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">New Hampshire</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">New Jersey</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">New Mexico</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">New York</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">North Carolina</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">North Dakota</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Ohilo</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Oklahoma</label></li>
                  </ul>
                  <li data-toggle="collapse" data-target="#cities" class="collapsed">
                    <a href="#">CIties<span class="arrow"></span></a>
                  </li>
                  <ul class="sub-menu collapse" id="cities" style="">
                    <li><input id="select" type="radio" name="male"><label for="select">Select All</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Austin</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Boston</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Chicago</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Denver</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Los Angeles</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">New York</label></li>
                    <li><input id="north" type="radio" name="male"><label for="north">Philadelphia</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">San Diego</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">SanJose</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">San Francisco</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Seattle</label></li>
                    <li><input id="select" type="radio" name="male"><label for="select">Washinton D.C</label></li>
                  </ul>
                  <div class="nav-side-last">
                    <div class="sf-apply text-left">
                      <a href="javascript:(void);" data-toggle="modal" data-target="#name-filter-mod" class="text-left"><button class="">Apply</button></a>
                    </div>
                </div>
              </ul>
              <ul id="sort-by-content" class="menu-content out h-100 collapse" style="">
                  <div class="top-line">
                    <a href="#">Reset</a>
                    <h5>Filter</h5>
                    <a href="javascript:(void);" data-toggle="collapse" data-target="#sort-by-content" aria-expanded="true" class="">X</a>
                  </div>
                  <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#sort-by-content" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                  <div class="al-loc">
                    <h5>Sort By</h5>
                    <div class="al-contine d-flex al-cen">
                        <a href="javascript:(void);" class="active">Newest</a>
                        <a href="javascript:(void);">Oldest</a>
                    </div>
                  </div>
                  <div class="nav-side-last">
                    <div class="sf-apply text-left">
                      <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                    </div>
                  </div>
              </ul>
              <ul id="round-stage" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#round-stage" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#round-stage" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Round Stage</h5>
                </div>
                <ul class="sub-menu collapse mt-4 round-st-ul show r-arr-none" id="region" style="">
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="north" type="radio" name="male" title="male"><label for="north">Pre Seed</label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="mid" type="radio" name="male" title="male"><label for="mid">Seed</label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="south" type="radio" name="male" title="male"><label for="south">Series A</label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="m-west" type="radio" name="male" title="male"><label for="m-west">Series B</label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="west" type="radio" name="male" title="male"><label for="west">Growth</label></a></li>
                    <li data-toggle="collapse" data-target="#new" class="collapsed">
                      <a href="#"><input id="m-west" type="radio" name="male" title="male"><label for="m-west">Bridge Round</label></a></li>
                </ul>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                  </div>
                </div>
              </ul>
              <ul id="verticals" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#verticals" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#verticals" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Verticals</h5>
                </div>
                <ul class="sub-menu collapse show mt-4 vert-ul" id="region" style="">
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>3D Printing</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Ad Tech</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Aerospace</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Ag Tech</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Apparel</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Al</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Filter</button></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed"><button>Filter</button></li>
                </ul>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                    </div>
                </div>
              </ul>
              <ul id="types-invest" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#types-invest" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#types-invest" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Types of Inverstment</h5>
                </div>
                <ul class="sub-menu collapse show mt-4 round-st-ul" id="region" style="">
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="north" type="radio" name="male" title="male"><label for="north">Priced</label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="mid" type="radio" name="male" title="male"><label for="mid">Convertible Note
                    </label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="south" type="radio" name="male" title="male"><label for="south">SAFE
                    </label></a></li>
                  <li data-toggle="collapse" data-target="#new" class="collapsed">
                  <a href="#"><input id="m-west" type="radio" name="male" title="male"><label for="m-west">Debt
                  </label></a></li>
                </ul>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                  </div>
                </div>
              </ul>
              <ul id="round" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#round" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#round" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Round</h5>
                  <div class="al-contine d-flex al-cen">
                      <a href="javascript:(void);" class="active">Open</a>
                      <a href="javascript:(void);">Closed</a>
                  </div>
                </div>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                  </div>
                </div>
              </ul>
              <ul id="round-size" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#round-size" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#round-size" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Round Size</h5>
                  <div class="al-contine al-cen round-si-number">
                    <ul>
                      <li><output id="range">500</output>K</li>
                      <li>10M+</li>
                    </ul>
                  </div>
                  <div class="range w-100">
                    <input type="range" name="range" min="1" max="1000" value="500" onchange="range.value=value">
                    <ul>
                      <li>0</li>
                      <li>250 K</li>
                      <li>500 K</li>
                      <li>750 K</li>
                      <li>1000 K</li>
                    </ul>
                  </div>
                </div>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                  </div>
                </div>
              </ul>
              <ul id="revenue" class="menu-content out h-100 collapse" style="">
                <div class="top-line">
                  <a href="#">Reset</a>
                  <h5>Filter</h5>
                  <a href="javascript:(void);" data-toggle="collapse" data-target="#revenue" aria-expanded="true" class="">X</a>
                </div>
                <a href="javascript:(void);" class="single-back" data-toggle="collapse" data-target="#revenue" aria-expanded="true" ><img src="img/arrow-back.svg" alt=""></a>
                <div class="al-loc">
                  <h5>Revenue</h5>
                  <div class="al-contine d-flex al-cen">
                      <a href="javascript:(void);" class="active">Pre-Revenue</a>
                      <a href="javascript:(void);">Post Revenue</a>
                  </div>
                </div>
                <div class="nav-side-last">
                  <div class="sf-apply text-left">
                    <a href="javascript:(void);" data-toggle="modal" data-target="" class="text-left"><button class="">Apply</button></a>
                  </div>
                </div>
              </ul>
            </div>
      </div>
</template>

<script>
export default {
  name: 'Navsidemenu'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
