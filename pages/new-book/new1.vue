<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <div class="icon mt-4">
                    <nuxt-link to="/pengunjung/menu">
                        <svg xmlns="http://www.w3.org/2000/svg" width="57" height="40" fill="currentColor" class="bi bi-arrow-left-square-fill text-white" viewBox="0 0 16 16">
                            <path d="M16 14a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2zm-4.5-6.5H5.707l2.147-2.146a.5.5 0 1 0-.708-.708l-3 3a.5.5 0 0 0 0 .708l3 3a.5.5 0 0 0 .708-.708L5.707 8.5H11.5a.5.5 0 0 0 0-1" />
                        </svg>
                    </nuxt-link>
                    <h2 class="text-center my-4">The Sadness Winter in Korea</h2>
                </div>
            </div>
        </div>

        <div class="row">
            <div class="col-4 text-white d-flex flex-column justify-content-center">
                <h4>Detail Buku:</h4>
                <h5>Pengarang: Rizki De</h5>
                <h5>Jumlah Halaman: 462</h5>
                <h5>Tanggal Terbit: 5 Juni 2012</h5>
                <h5>Penerbit: C.V ANDI OFFSET</h5>
            </div>
            <div class="col-4 d-flex flex-column justify-content-center align-items-center">
                <div class="mb-5">
                    <div class="card-body">
                        <img src="~/assets/img/korea.jpg" class="img-thumbnail" />
                    </div>
                </div>
            </div>
            <div class="col-4 d-flex flex-column justify-content-center align-items-center">
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Meminjam</button>
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Membaca Buku</button>
                <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Rak 12</button>
            </div>
        </div>

        <div class="row text-white">
            <div class="col">
                <h4>Deskripsi:</h4>
                <h5>Kebanyakan orang pasti menyukai artis, tapi tidak dengan Park Yoona. Baginya mereka adalah makhluk bermuka dua yang selalu membuat dirinya naik darah. Niatnya untuk mencari inspirasi baru malah terganggu dengan kehadiran makhluk yang paling dibencinya itu. Mereka adalah artis tenar ikon baru Seoul, Ji sun, Jung Yong, dan Kevin.
Di tengah situasi kacau balau itulah Yoona bertemu dengan lelaki misterius. Yoona selalu terhipnotis hingga sanggup melupakan masa lalunya yang kelabu tiap kali bertemu lelaki itu. Lalu diam-diam perasaan cinta lahir. Hanya saja Yoona belum bisa memastikan cinta itu untuk siapa. Apakah untuk Ji sun, Jung Yong, Kevin, atau lelaki misterius itu. Yoona hanya bisa pastikan dia menginginkan cerita cinta yang bahagia. Akankah Yoona mendapatkannya?
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