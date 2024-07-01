# decisive-model-with-high-profit-potential-and-low-risk

# Deskripsi Proyek
Kamu bekerja di perusahaan tambang OilyGiant. Nah, tugasmu adalah mencari tempat terbaik untuk mengembangkan 200 titik sumur minyak baru.

Untuk menyelesaikan tugas ini, kamu harus melakukan langkah-langkah berikut:

Baca file dengan parameter yang dikumpulkan dari sumur-sumur minyak di wilayah terpilih: kualitas minyak dan volume cadangannya;
Buat sebuah model untuk memprediksi volume cadangan di sumur-sumur baru;
Pilih sumur minyak yang memiliki nilai estimasi tertinggi;
Pilih wilayah dengan total keuntungan tertinggi dari sumur minyak yang dipilih.
Kamu punya data sampel minyak dari tiga wilayah. Parameter setiap sumur minyak di wilayah tersebut sudah diketahui. Buat sebuah model yang akan membantumu memilih wilayah dengan margin keuntungan tertinggi. Jangan lupa ya, gunakan teknik bootstrapping untuk menganalisis potensi keuntungan dan risiko.

# Deskripsi Data
Data eksplorasi geologi untuk ketiga wilayah disimpan dalam beberapa file:

- id — ID unik sumur minyak
- f0, f1, f2 — tiga fitur titik wilayah (makna spesifiknya sebenarnya tidak penting, tetapi fitur itu sendiri sangat penting)
- product — volume cadangan di dalam sumur minyak (1 unit = 1.000 barel).

Kondisi:

- Hanya regresi linear yang bisa digunakan untuk pelatihan model (sisanya tidak cukup mudah diprediksi).
- Anggaran untuk pengembangan 200 sumur minyak ini adalah 100 juta dolar.
- Satu barel minyak mentah menghasilkan pendapatan sebesar 4,5 dolar. Nah, pendapatan dari satu unit produk adalah $4.500 (volume cadangan ditulis dalam ribuan barel).
- Setelah kamu menganalisis risiko yang ada, pertahankan hanya wilayah yang memiliki risiko kerugian kurang dari 2,5%. Di antara semua yang sesuai dengan kriteria, kamu harus memilih wilayah dengan keuntungan rata-rata tertinggi.
