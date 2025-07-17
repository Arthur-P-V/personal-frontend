<script setup lang="ts">
import PostItem from '@/components/PostItem.vue';

</script>

<template>
  <div class="home bg-forest">
    <div class="container">
      <div class="row">
        <div class="col-8 intro-text">
          <div class="row">
            <h1>Hi, I'm Arthur :) </h1>
            <h3>I like computers and stuff</h3>
          </div>
          <div class="row">
            <h1>Posts Carousel</h1>

            <div id="postCarousel" class="carousel slide">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <PostItem />
                </div>
                <div class="carousel-item">
                  <PostItem />
                </div>
                <div class="carousel-item">
                  <PostItem />
                </div>
              </div>
              <button class="carousel-control-prev bg-chili" type="button" data-bs-target="#postCarousel" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next bg-chili" type="button" data-bs-target="#postCarousel" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>

          </div>
          <div class="row">
            <h1>Images Carousel</h1>
          </div>

        </div>
        <div class="col-4">
          <img src="../Me.jpg" style="width:max-content;">
        </div>
      </div>

    </div>
  </div>

</template>


<style>
  .home {
    min-height:100vh;
    display:flex;
  }
  h1 {
    font-size: 72pt;
  }
  .intro-text {
    text-align:center;
    padding-top: 25vh;
    padding-bottom: 25vh;

  }
</style>
