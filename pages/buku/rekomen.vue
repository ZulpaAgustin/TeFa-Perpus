<template>
  <div style="background-color: #4377de">
    <div class="row">
      <div class="col-lg-12">
        <div class="icon mt-4">
          <nuxt-link to="/pengunjung/menu">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="40" fill="currentColor" class="bi bi-arrow-left-square-fill text-white" viewBox="0 0 16 16">
              <path d="M16 14a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2zm-4.5-6.5H5.707l2.147-2.146a.5.5 0 1 0-.708-.708l-3 3a.5.5 0 0 0 0 .708l3 3a.5.5 0 0 0 .708-.708L5.707 8.5H11.5a.5.5 0 0 0 0-1" />
            </svg>
          </nuxt-link>
          <h2 class="text-center my-4">Rekomendasi Buku</h2>
        </div>
      </div>
    </div>

    <div class="row mt-5">
      <div class="col-3 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <nuxt-link to="/buku/detail">
              <a href="#" class="btn me-5">Buka</a>
            </nuxt-link>
          </div>
        </div>
      </div>

      <div class="col-3 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 mt-4 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 mt-4 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 mt-4 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>

      <div class="col-3 mt-4 d-flex flex-column justify-content-center align-items-center">
        <div class="card" style="width: 20rem">
          <img src="~assets/img/atom.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title text-center">Atomic Habits</h5>
            <a href="#" class="btn me-5">Buka</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* .container-fluid {
  align-content: center;
} */

.cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 0 30;
}
h2 {
  color: #fff;
  font-family: inherit;
}
.btn {
  background-color: #315fb7;
  color: #fff;
}
/* .container-fluid {
  background-color: #4377de;
} */
</style>
