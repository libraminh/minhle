<template>
  <div>
    <!-- <a href class="martech-heading-link">
      <img :src="$withBase('/images/exam-01.png')" class="w-100" alt="">
    </a> -->

    <slot>

    </slot>
  </div>

</template>



<script>
  export default {
    data() {
      return {
        rawHtml: 
        `
          <div id="exam-01" class="martech-heading-wrap p-100">
            <div class="martech-heading-box">
              <h2 class="martech-heading-box-title">Discover Martech.</h2>
              <p class="martech-heading-box-content">
                The Marketing Technology (Martech) series, is a set of articles 
                that talk about the power of Martech, and how it can help (and 
                is helping) marketers and teams keep up in the ever-evolving 
                digital landscape. The articles are listed below.
              </p>
            </div>
            <div class="martech-heading-box">
              <a href="" class="martech-heading-link">
                <!-- <img src="./images/heading-banner.jpg" class="w-100" alt=""> -->
              </a>
              <!-- arrow -->
            </div>
          </div>
        `
      }
    },
  }
</script>

<style scoped>

</style>