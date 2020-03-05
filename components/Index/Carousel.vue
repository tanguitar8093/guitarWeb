<template>
  <section class="container-fluid">
    <div class="row">
      <div class="col-md-12">
        <div
          id="carouselExampleIndicators"
          class="carousel slide"
          data-ride="carousel"
        >
          <ol class="carousel-indicators">
            <li
              data-target="#carouselExampleIndicators"
              data-slide-to="0"
              class="active"
            ></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active" style="z-index:-1">
              <img
                class="d-block w-100"
                src="image/show1.jpg"
                alt="First slide"
                style="width: 100%;"
                height="700"
              />
            </div>
            <div class="carousel-item" style="z-index:-1">
              <img
                class="d-block w-100"
                src="image/show4.jpg"
                alt="Second slide"
                width="1800"
                height="700"
              />
            </div>
            <div class="carousel-item" style="z-index:-1">
              <img
                class="d-block w-100"
                src="image/show5.jpg"
                alt="Third slide"
                width="1800"
                height="700"
              />
            </div>
          </div>
          <a
            class="carousel-control-prev"
            href="#carouselExampleIndicators"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExampleIndicators"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
</style>
