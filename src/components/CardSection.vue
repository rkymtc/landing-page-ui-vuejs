<template>
  <section class="design">
    <div class="container">
      <div class="design-wrapper">
        <div class="design-time">
          <div class="time-wrapper">
            <a href="javascript:;" class="time-latest">Latest</a>
            <a href="javascript:;" class="time-popular">Popular</a>
          </div>
        </div>

        <ul class="design-category">
          <li>
            <a href="javascript:;" class="design-category-item is-active"
              >All</a
            >
          </li>
          <li><a href="javascript:;" class="design-category-item">Web</a></li>
          <li>
            <a href="javascript:;" class="design-category-item">Mobile</a>
          </li>
          <li>
            <a href="javascript:;" class="design-category-item">UI Kit</a>
          </li>
          <li><a href="javascript:;" class="design-category-item">Coded</a></li>
        </ul>

        <div class="design-tools">
          <a href="javascript:;" class="design-tools-item">
            <img src="../assets/img/figma.svg" alt="Figma" />
          </a>
          <a href="javascript:;" class="design-tools-item is-active">
            <img src="../assets/img/sketch.svg" alt="Sketch" />
          </a>
          <a href="javascript:;" class="design-tools-item">
            <img src="../assets/img/studio.svg" alt="Studio" />
          </a>
          <a href="javascript:;" class="design-tools-item">
            <img src="../assets/img/adobe-xd.svg" alt="Adobe XD" />
          </a>
          <a href="javascript:;" class="design-tools-item">
            <img src="../assets/img/adobe-ps.svg" alt="Adobe Photoshop" />
          </a>
        </div>
      </div>

      <div class="design-card-wrapper row gy-1 gx-1 gx-lg-0 justify-content-xl-between justify-content-lg-center justify-content-md-between">      
        <div class="design-card col-md-6 col-lg-4  my-4">
          <div class="design-card-image">
            <img
              src="../assets/img/card-first.png"
              alt="design"
              class="design-card-preview"
            />
            <div class="design-card-sketch">
              <img src="../assets/img/sketch.svg" alt="Sketch" />
            </div>
          </div>

          <div class="design-card-detail">
            <div class="card-detail-profile">
              <img src="../assets/img/photo.png" alt="photo" />
              <span>by <strong>Jenny Molla</strong></span>
            </div>

            <div class="card-detail-count">
              <img src="../assets/img/code.svg" alt="photo" />
              <span>25</span>
              <img src="../assets/img/appreciate.svg" alt="photo" />
              <span>25</span>
            </div>
          </div>
        </div>

        <div class="design-card col-md-6 col-lg-4 my-4">
          <div class="design-card-image">
            <img
              src="../assets/img/card-second.png"
              alt="design"
              class="design-card-preview"
            />
            <div class="design-card-sketch">
              <img src="../assets/img/sketch.svg" alt="Sketch" />
            </div>
          </div>

          <div class="design-card-detail">
            <div class="card-detail-profile">
              <img src="../assets/img/photo.png" alt="photo" />
              <span>by <strong>Jenny Molla</strong></span>
            </div>
            <div class="card-detail-count">
              <img src="../assets/img/code.svg" alt="photo" />
              <span>25</span>
              <img src="../assets/img/appreciate.svg" alt="photo" />
              <span>25</span>
            </div>
          </div>
        </div>

        <div class="design-card col-md-6 col-lg-4  my-4">
          <div class="design-card-image">
            <img
              src="../assets/img/card-third.png"
              alt="design"
              class="design-card-preview"
            />
            <div class="design-card-sketch">
              <img src="../assets/img/sketch.svg" alt="Sketch" />
            </div>
          </div>
          <div class="design-card-detail">
            <div class="card-detail-profile">
              <img src="../assets/img/photo.png" alt="photo" />
              <span>by <strong>Jenny Molla</strong></span>
            </div>
            <div class="card-detail-count">
              <img src="../assets/img/code.svg" alt="photo" />
              <span>25</span>
              <img src="../assets/img/appreciate.svg" alt="photo" />
              <span>25</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
@import "../assets/scss/_card.scss";
</style>
