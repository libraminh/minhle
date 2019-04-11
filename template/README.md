# UI Component

## Masthead

<a :href="$withBase('/minhle-library.html#masthead-fullscreen')" class="martech-heading-link">
  <img :src="$withBase('/images/masthead-banner.png')" class="w-100" alt="">
</a>

``` html
<div class="masthead-fullscreen">
  <div class="container">
    <div class="d-flex align-items-center justify-content-between masthead-header">
        <a href="#" class="masthead-logo-link">
          <img src="./images/cd-logo.png" alt="" class="header-logo">
        </a>
        <a href="#" class="btn-header">Sign of for free</a>
      </div>
      <h2 class="masthead-heading">Data Learning Centre</h2>
      <div class="my-5 d-flex flex-column flex-sm-row justify-content-center align-items-center masthead-btns">
        <a href="#" class="masthead-btn btn--white">See Coaurses</a>
        <a href="#" class="masthead-btn btn--white">Find out more</a>
      </div>
      <div class="masthead-content-wrap">
        <div class="masthead-content-heading">
          <p>Data is transforming how our competitors approach problems, by empowering them to respond to actionable and even predicted data. How about you?</p>
        </div>
        <div class="masthead-content-text">
          <p>Is your business looking at using the power of data points to your advantage? In 2019, data has become a sustained area of focus among businesses (your competitors included) - but how many are actually doing it right? Most of us know that data can be gathered, presented then acted upon, but what next? What if we told you, it could predict what’s to come, before it happens. Learn and explore the future of data with us, today.</p>
        </div>
      </div>
    </div>
  </div>
</div>
```

``` css
.masthead-fullscreen {
  background: url(../images/dlc-bg.jpg);
  padding-bottom: 105px;
  padding-top: 10px;
  background-position: top left;
  background-size: cover;
  background-repeat: no-repeat;
}
.masthead-fullscreen .header-logo {
  width: 167px;
}
.masthead-heading {
  color: #fff;
  font-size: 60px;
  line-height: 60px;
  text-align: center;
  margin-top: 120px;
  margin-bottom: 0;
}
.masthead-btn {
  color: #0a0a0a;
  font-size: 14px;
  line-height: 18px;
  border-radius: 50px;
  padding: 10px 40px;
  margin-right: 15px;
  text-transform: uppercase;
  transition: all .2s ease-in-out;
}
.masthead-btn:hover {
  color: #fff !important;
  background: #f44a2d !important;
}
.masthead-btn:last-child {
  margin-right: 0;
}
.btn--white {
  background: #fff;
}
.btn-header {
  color: #fff;
  font-size: 14px;
  line-height: 18px;
  border: 2px solid #51555b;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  border-radius: 50px;
  padding: 10px 30px;
  transition: all .2s ease-in-out;
}
.btn-header:hover {
  color: #0a0a0a;
  background: #fff;
  border-color: #fff;
}
.masthead-content-heading {
  color: #fff;
  font-size: 38px;
  line-height: 48px;
  text-align: center;
}
.masthead-content-heading p {
  margin-bottom: 30px;
}
.masthead-content-text {
  color: #fff;
  font-size: 14px;
  line-height: 24px;
  font-family: Rubik-Regular, sans-serif;
  text-align: center;
}
@media (max-width: 1200px) {
  .center-wrap {
    padding: 0 15px;
  }
}
@media (max-width: 768px) {
  .masthead-heading {
    font-size: 50px;
    line-height: 58px;
  }
  .masthead-btn {
    font-size: 12px;
  }
  .masthead-content-heading {
    font-size: 32px;
    line-height: 42px;
  }
  .masthead-content-text {
    font-size: 12px;
    line-height: 22px;
  }
}
@media (max-width: 576px) {
  .masthead-btn {
    margin-right: 0;
    margin-bottom: 20px;
  }
  .masthead-btn:last-child {
    margin-bottom: 0;
  }
  .btn-header {
    font-size: 10px;
    padding: 7px 12px;
    text-align: center;
  }
}
```

## Component

<a :href="$withBase('/minhle-library.html#exam-martech')" class="martech-heading-link">
  <img :src="$withBase('/images/exam-01.png')" class="w-100" alt="">
</a>

``` html
<div class="container">
  <div class="row py-5 align-items-center martech-heading-wrap p-100">
    <div class="col-md-6">
      <h2 class="martech-heading-box-title">Discover Martech.</h2>
      <p class="martech-heading-box-content">
        The Marketing Technology (Martech) series, is a set of articles 
        that talk about the power of Martech, and how it can help (and 
        is helping) marketers and teams keep up in the ever-evolving 
        digital landscape. The articles are listed below.
      </p>
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
      <a href="" class="martech-heading-link">
        <img src="./images/heading-banner.jpg" class="w-100" alt="">
      </a>
    </div>
  </div>
</div>
```

## Particle background

<a :href="$withBase('/minhle-library.html#particles-js')" class="martech-heading-link">
  <img :src="$withBase('/images/particle-bg.gif')" class="w-100" alt="">
</a>

``` html
<div class="dlc-login">
  <div id="particles-js"></div> 

  <div class="container">
    <div class="dlc-login-wrap d-flex flex-column flex-md-row justify-content-between align-items-center">
      <div class="col-12 col-sm-12 col-md-8 mb-5 mb-md-0 dlc-login-information">
        <h3 class="dlc-login-title">Already signed up?</h3>
        <h3 class="dlc-login-desc">Access the Data Learning Centre now.</h3>
      </div>
      <div class="col-12 col-sm-12 col-md-4 text-left text-md-right dlc-login-btn-wrap">
        <a href="#" class="masthead-btn btn--white">GET STARTED</a>
      </div>
    </div>
  </div>
</div>
```

``` css
/* DLC LOGIN */
.dlc-login {
  background: #2c28dc;
  padding: 55px 0;
  position: relative;
  overflow: hidden;
}
.dlc-login-wrap {
  position: relative;
  z-index: 10;
}
.dlc-login-title, .dlc-login-desc {
  color: #fff;
  font-size: 38px;
  line-height: 48px;
  letter-spacing: 0.01em;
  margin-bottom: 0;
}
.dlc-login .masthead-btn {
  color: #2c28dc;
  font-size: 16px;
  padding: 13px 25px;
}
@media (max-width: 768px) {
  .dlc-login-title, .dlc-login-desc {
    font-size: 32px;
    line-height: 42px;
  }
  .dlc-login .masthead-btn {
    font-size: 14px;
  }
}
/* Particle Style */
canvas{ display: block; vertical-align: bottom; } /* ---- particles.js container ---- */ #particles-js{ position:absolute; width: 100%; height: 100%; background-color: #2c28dc; background-image: url(""); background-repeat: no-repeat; background-size: cover; background-position: 50% 50%; } /* ---- stats.js ---- */ .count-particles{ background: #000022; position: absolute; top: 48px; left: 0; width: 80px; color: #13E8E9; font-size: .8em; text-align: left; text-indent: 4px; line-height: 14px; padding-bottom: 2px; font-family: Helvetica, Arial, sans-serif; font-weight: bold; } .js-count-particles{ font-size: 1.1em; } #stats, .count-particles{ -webkit-user-select: none; margin-top: 5px; margin-left: 5px; } #stats{ border-radius: 3px 3px 0 0; overflow: hidden; } .count-particles{ border-radius: 0 0 3px 3px; }
#particles-js {
  top: 0;
  left: 0;
}
.particles-js-canvas-el {
  height: auto !important;
}
```

``` js
<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script> 
<script>
  particlesJS("particles-js", {"particles":{"number":{"value":43,"density":{"enable":true,"value_area":1893.9543399174545}},"color":{"value":"#ffffff"},"shape":{"type":"circle","stroke":{"width":0,"color":"#000000"},"polygon":{"nb_sides":4},"image":{"src":"img/github.svg","width":100,"height":100}},"opacity":{"value":0.5,"random":false,"anim":{"enable":false,"speed":1,"opacity_min":0.1,"sync":false}},"size":{"value":5,"random":true,"anim":{"enable":false,"speed":40,"size_min":0.1,"sync":false}},"line_linked":{"enable":true,"distance":150,"color":"#ffffff","opacity":0.4,"width":1},"move":{"enable":true,"speed":10,"direction":"none","random":false,"straight":false,"out_mode":"out","bounce":false,"attract":{"enable":false,"rotateX":600,"rotateY":1200}}},"interactivity":{"detect_on":"canvas","events":{"onhover":{"enable":true,"mode":"bubble"},"onclick":{"enable":true,"mode":"push"},"resize":true},"modes":{"grab":{"distance":400,"line_linked":{"opacity":1}},"bubble":{"distance":400,"size":40,"duration":2,"opacity":8,"speed":3},"repulse":{"distance":200,"duration":0.4},"push":{"particles_nb":4},"remove":{"particles_nb":2}}},"retina_detect":true});var count_particles, stats, update; stats = new Stats; stats.setMode(0); stats.domElement.style.position = 'absolute'; stats.domElement.style.left = '0px'; stats.domElement.style.top = '0px'; document.body.appendChild(stats.domElement); count_particles = document.querySelector('.js-count-particles'); update = function() { stats.begin(); stats.end(); if (window.pJSDom[0].pJS.particles && window.pJSDom[0].pJS.particles.array) { count_particles.innerText = window.pJSDom[0].pJS.particles.array.length; } requestAnimationFrame(update); }; requestAnimationFrame(update);;
</script>
```

<script>
  export default {
    data() {
      return {
        css: `
          
        `
      }
    },
  }
</script>

<style scoped>

</style>
