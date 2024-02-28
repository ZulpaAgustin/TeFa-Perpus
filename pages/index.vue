<!-- <template>
  <div class="container-fluid">
    <div class="icon">
      <nuxt-link to="/pengunjung/tambah">
        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="80" fill="currentColor" class="bi bi-person-vcard-fill text-white" viewBox="0 0 16 16">
          <path
            d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2zm9 1.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 0-1h-4a.5.5 0 0 0-.5.5M9 8a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 0-1h-4A.5.5 0 0 0 9 8m1 2.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1h-3a.5.5 0 0 0-.5.5m-1 2C9 10.567 7.21 9 5 9c-2.086 0-3.8 1.398-3.984 3.181A1 1 0 0 0 2 13h6.96q.04-.245.04-.5M7 6a2 2 0 1 0-4 0 2 2 0 0 0 4 0"
          />
        </svg>
      </nuxt-link>
    </div>
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung/" style="text-decoration: none">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>Riwayat Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>

      <div class="col-lg-6">
        <nuxt-link to="/buku/rekomen" style="text-decoration: none">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>Rekomendasi Buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div> -->
<!-- bagian new book -->
<!-- <div class="oval">
      <span class="badge text-bg-light">Buku Terbaru</span>
    </div> -->

<!-- card -->
<!-- <div class="row row-cols-1 row-cols-md-5 g-5 mt-4 justify-content-center">
      <div class="col">
        <div class="card h-100">
          <nuxt-link to="~/assets/img/atom.jpg">
            <img src="~/assets/img/buku.jpg" class="card-img-top" alt="..." />
          </nuxt-link>

          <div class="card-body">
            <h5 class="card-title">Berani Tidak Disukai</h5>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="~/assets/img/buku.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Berani Tidak Disukai</h5>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="~/assets/img/buku.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Berani Tidak Disukai</h5>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="~/assets/img/buku.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">Berani Tidak Disukai</h5>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
    </div>
  </div>
</template> -->

<!-- <style scoped>
.card {
  height: 250px;
  box-shadow: 1px 1px 10px #424242;
}
.card.bg-pengunjung {
  background-image: url("../assets/img/bg-home-kunjungan.jpg");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  color: #ffffff;
}
.card.bg-buku {
  background: url("../assets/img/bg-home-cari-buku.jpg") no-repeat center center;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  color: #ffffff;
}
.oval {
  font-size: 30px;
}
.container-fluid {
  background-color: #4377de;
}
</style> -->

<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-6">
        <img src="~/assets/img/HH.jpg" alt="" />
      </div>
      <div class="col-lg-6 mt-5">
        <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
        <form class="mt-5">
          <div class="mb-4">
            <input type="text" class="form-control form-control-lg rounded-5" placeholder="Nama" />
          </div>
          <div class="mb-4">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="">Keanggotaan</option>
              <option value="Siswa">Siswa</option>
              <option value="Guru">Guru</option>
              <option value="Staf">Staf</option>
              <option value="Umum">Umum</option>
            </select>
          </div>
          <div class="mb-4">
            <div class="row">
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2">
                  <option value="">Tingkat</option>
                  <option value="10">10</option>
                  <option value="11">11</option>
                  <option value="12">12</option>
                </select>
              </div>
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2">
                  <option value="">Jurusan</option>
                  <option value="PPLG">PPLG</option>
                  <option value="TJKT">TJKT</option>
                  <option value="TBSM">TBSM</option>
                  <option value="DKV">DKV</option>
                  <option value="TOI">TOI</option>
                </select>
              </div>
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2">
                  <option value="">Kelas</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                </select>
              </div>
            </div>
          </div>
          <div class="mb-4">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="">Keperluan</option>
              <option value="Baca">Membaca Buku</option>
              <option value="Pinjam">Pinjam Buku</option>
              <option value="Kembalikan">Kembalikan Buku</option>
            </select>
          </div>
          <div class="d-grid gap-2 d-md-flex justify-content-md-end">
            <nuxt-link to="/pengunjung/">
              <button type="submit" class="btn btn-light btn-lg rounded-5 px-5 me-md-2 mt-4">Kirim</button>
            </nuxt-link>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-color: #4377de;
}
h2 {
  color: #fff;
}
</style>
