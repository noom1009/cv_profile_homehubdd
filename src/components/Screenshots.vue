<template>
  <section id="gallery" class="wrapper">
    <div class="container">
      <h2 class="animation-box wow bounceIn animated">SCREENSHOTS</h2>
      <div class="virticle-line"></div>
      <div class="circle"></div>
      <div class="row">
        <div class="col-xs-12">
          <div
            id="screenshots"
            class="owl-carousel owl-theme carousel slide"
            style="opacity: 1; display: block"
            data-bs-ride="carousel"
          >
            <div class="owl-wrapper-outer carousel-inner">
              <div
                class="owl-wrapper"
                style="width: 4560px; left: 0px; display: block"
              >
                <div class="owl-item carousel-item active" style="width: 228px">
                    <img
                      src="img/1.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/2.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/3.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/4.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/1.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/2.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/3.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/4.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/1.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
                <div class="owl-item carousel-item" style="width: 228px">
                    <img
                      src="img/2.jpg"
                      class="img_res wow animated zoomIn animated"
                      alt=""
                      style="visibility: visible; animation-name: zoomIn"
                    />
                </div>
              </div>
            </div>
          </div>
          <div class="customNavigation row">
            <a
              class="btn prev gallery-nav wow animated bounceInLeft carousel-control-prev"
              data-bs-target="#screenshots"
              data-bs-slide="prev"
              ><i class="fa fa-chevron-left"></i
            ></a>
            <a
              class="btn next gallery-nav wow animated bounceInRight carousel-control-next"
              data-bs-target="#screenshots"
              data-bs-slide="next"
              ><i class="fa fa-chevron-right"></i
            ></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.img_resize {
  max-width: 200px;
  visibility: visible;
  animation-name: zoomIn;
  animation-fill-mode: both;
  vertical-align: middle;
  border: 0;
}
</style>