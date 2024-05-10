<template>
    <div class="experience mt-4 py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-6 offset-md-3">
                    <h4>Latest News</h4>
                    <ul class="timeline">
                        <li>
                            <a href="http://kafeinarts.vercel.app/">Code With Arif - (Sekarang Menjadi
                                KafeinArts)</a> - 2023 - Saat Ini
                            <p>Saya adalah mentor serta founder dari Code With Arif, CWA adalah sebuah platform belajar
                                online yang menyediakan berbagai macam kursus dan pelatihan dalam bidang ilmu komputer
                                dan teknologi informasi. Platform ini biasanya tersedia dalam powerpoint atau video
                                conference yang memungkinkan pengguna untuk melakukan kegiatan belajar mengajar secara
                                real-time dan juga mendapatkan materi dalam bentuk powerpoint atau portable document
                                format.</p>
                        </li>
                        <li>
                            <a href="http://arca-olive.vercel.app/">Arca Interactive</a> - 2022
                            <p>Sebagai seorang desainer website yang berbakat, Anda telah memiliki pengalaman berharga
                                dalam menciptakan tampilan dan pengalaman pengguna yang menarik di startup Arca
                                Interactive. Dengan keahlian dalam merancang tata letak, grafis, dan elemen-elemen
                                visual, Anda telah berhasil menciptakan website yang estetis dan fungsional. Di Arca
                                Interactive, Anda berperan dalam merancang antarmuka website yang inovatif, memastikan
                                bahwa setiap halaman web yang Anda desain memenuhi standar desain yang tinggi dan
                                menciptakan pengalaman yang memikat bagi pengguna. Dengan dedikasi Anda terhadap desain
                                website, Anda telah memberikan kontribusi yang berarti dalam memperkuat identitas merek
                                dan pengalaman pengguna di startup Arca Interactive..</p>
                        </li>
                        <li>
                            <a href="https://www.guepedia.com/">Guepedia</a> - 2021
                            <p>Sebagai seorang frontend developer, Saya telah memiliki pengalaman yang luas
                                dalam merancang dan mengembangkan antarmuka pengguna yang menarik dan responsif. Dengan
                                keahliannya dalam HTML, CSS, dan JavaScript, Saya telah berhasil menciptakan pengalaman
                                pengguna yang memikat melalui desain visual yang menarik dan fungsionalitas yang
                                intuitif. Dalam setiap proyeknya, Saya selalu berfokus pada menciptakan tampilan yang
                                estetis dan pengalaman pengguna yang optimal.
                            </p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
ul.timeline {
    list-style-type: none;
    position: relative;
}

ul.timeline:before {
    content: ' ';
    background: #d4d9df;
    display: inline-block;
    position: absolute;
    left: 29px;
    width: 2px;
    height: 100%;
    z-index: 400;
}

ul.timeline>li {
    margin: 20px 0;
    padding-left: 20px;
}

ul.timeline>li:before {
    content: ' ';
    background: white;
    display: inline-block;
    position: absolute;
    border-radius: 50%;
    border: 3px solid #22c0e8;
    left: 20px;
    width: 20px;
    height: 20px;
    z-index: 400;
}
</style>