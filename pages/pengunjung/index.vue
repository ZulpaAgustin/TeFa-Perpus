<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">Riwayat Kunjungan</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="Mencari" />
        </div>
        <div class="my-3 text-muted">
          <table class="table">
            <thead>
              <tr>
                <td>No</td>
                <td>Hari/Tanggal</td>
                <td>Nama</td>
                <td>Keanggotaan</td>
                <td>Tingkat</td>
                <td>Kelas</td>
                <td>Keperluan</td>
                <td>Waktu</td>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>1</td>
                <td>Senin,26/02/2024</td>
                <td>Zulpa</td>
                <td>Siswa</td>
                <td>11</td>
                <td>4</td>
                <td>Membaca</td>
                <td>11.30</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
    <div class="d-grid gap-2 d-md-flex justify-content-md-strat">
      <nuxt-link to="/pengunjung/menu">
        <button type="submit" class="btn btn-light btn-lg rounded-5 px-5 me-md-2 mt-4">Menu</button>
      </nuxt-link>
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
