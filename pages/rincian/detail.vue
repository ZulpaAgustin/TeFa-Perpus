<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <div class="icon mt-4">
                    <nuxt-link to="/buku/rekomen">
                        <svg xmlns="http://www.w3.org/2000/svg" width="57" height="40" fill="currentColor" class="bi bi-arrow-left-square-fill text-white" viewBox="0 0 16 16">
                            <path d="M16 14a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2zm-4.5-6.5H5.707l2.147-2.146a.5.5 0 1 0-.708-.708l-3 3a.5.5 0 0 0 0 .708l3 3a.5.5 0 0 0 .708-.708L5.707 8.5H11.5a.5.5 0 0 0 0-1" />
                        </svg>
                    </nuxt-link>
                    <h2 class="text-center my-4">Atomic Habits - James Clear</h2>
                </div>
            </div>
        </div>

        <div class="row">
            <div class="col-4 text-white d-flex flex-column justify-content-center">
                <h4>Detail Buku:</h4>
                <h5>Pengarang: James Clear</h5>
                <h5>Jumlah Halaman: 356</h5>
                <h5>Tanggal Terbit: 15 September 2019</h5>
                <h5>Penerbit: Gramedia Pustaka Umum</h5>
                <h5>Rak: 12</h5>
            </div>
            <div class="col-4 d-flex flex-column justify-content-center align-items-center">
                <div class="mb-5">
                    <div class="card-body">
                        <img src="~/assets/img/atom.jpg" class="img-thumbnail" />
                    </div>
                </div>
            </div>
            <div class="col-4 d-flex flex-column justify-content-center align-items-center">
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Meminjam</button>
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Membaca Buku</button>
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Mengembalikan</button>
            </div>
        </div>

        <div class="row text-white">
            <div class="col">
                <h4>Deskripsi:</h4>
                <h5>Melalui Atomics Habits James Clear memberikan paparan teori bahwa kebiasaan remeh yang dilakukan setiap hari dapat menghasilkan sesuatu yang luar biasa. Kegiatan-kegiatan seperti bangun lebih cepat lima menit atau berolahraga ringan setiap
            hari dapat membentuk kebiasaan baik dan menghentikan kebiasaan buruk. Oleh karena itu, kebiasaan-kebiasaan remeh tersebut dikenal sebagai atomic habits atau kebiasaan atom. Clear menjelaskan bahwa kebiasaan buruk yang terus berulah terjadi
            bukan karena seseorang tidak ingin berubah, melainkan karena sistem perubahan yang salah. Ketika sistem perubahan dilakukan secara benar, maka individu dapat memperoleh ke tingkat produktivitas yang baru. Paparan motivasi dalam Atomic
            Habits tidak hanya didasari dari rangkaian kata penyemangat, melainkan lewat teori-teori ilmiah. Melansir dari Goodreads, sang penulis dikenal dengan kemampuannya menyaring topik kompleks menjadi perilaku sederhana yang mudah diterapkan.
            Clear juga mampu memanfaatkan ide-ide dari ilmu biologi, psikologi, hingga saraf untuk membuat panduan yang mudah dipahami dan mudah dipraktikan menjadi kebiasaan baik. Selain itu, buku Atomic Habits juga dilengkapi dengan kisah inspiratif
            dan menghibur dari para peraih medali emas olimpiade, CEO perusahaan besar, seniman, ilmuwan, hingga komedian.
                </h5>
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