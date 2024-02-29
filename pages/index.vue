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