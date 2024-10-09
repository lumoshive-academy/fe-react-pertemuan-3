# Media Query
Media Query adalah bagian penting dari CSS yang memungkinkan kita membuat halaman web responsif, yaitu halaman web yang dapat menyesuaikan tampilannya berdasarkan ukuran layar pengguna. Dengan Media Query, kita dapat menulis aturan CSS yang hanya diterapkan pada kondisi tertentu, misalnya pada layar dengan lebar maksimal tertentu.

## Penjelasan untuk masing-masing bagian:

### @media screen and (max-width: 768px):
Artinya, aturan CSS di dalamnya hanya akan diterapkan pada perangkat dengan lebar layar maksimal 768px. Ini biasanya berarti perangkat mobile seperti smartphone dan tablet.

### .header-text h1:
font-size: 3rem; mengubah ukuran font heading utama dari header menjadi lebih kecil (3rem) saat layar lebih kecil dari 768px. Ini penting agar teks tetap terlihat proporsional dan tidak terlalu besar di layar kecil.

### .display-grid:

display: block; mengubah tampilan grid menjadi block saat lebar layar kecil. Ini berguna karena dalam layar kecil, tata letak grid 2 kolom mungkin membuat elemen terlihat terlalu sempit. Dengan mengganti menjadi block, elemen akan ditampilkan satu di atas yang lain.

### .nav-links:

display: none; menyembunyikan tautan navigasi saat layar kecil, karena menu horizontal mungkin tidak terlihat rapi di layar kecil. Biasanya, pada desain responsif, navigasi digantikan oleh menu hamburger di layar kecil.

### .header-text p, .header-text h1:

padding-right: 10px; dan text-align: center; menambahkan padding kecil pada teks dan mengubah perataan teks menjadi di tengah (center). Ini membantu agar teks tidak terlalu rapat ke tepi layar dan tampak lebih rapi pada perangkat kecil.

### .header:

height: 300px; mengubah tinggi dari header menjadi lebih kecil di layar kecil (300px). Hal ini membuat bagian header terlihat proporsional di perangkat mobile yang layarnya lebih pendek.
display: flex; align-items: center; justify-content: center; digunakan untuk menata konten di dalam header agar tetap berada di tengah-tengah (baik secara vertikal maupun horizontal) meskipun ukuran layar lebih kecil.

### .title, .desc:

text-align: center; menata teks judul dan deskripsi agar berada di tengah, sehingga lebih mudah dibaca di layar kecil.

### .company-list:

justify-content: center; menata daftar logo perusahaan agar berada di tengah layar saat layar lebih kecil.

### .service-card:

height: auto; padding: 20px; mengubah tinggi elemen menjadi otomatis (auto) agar sesuai dengan konten yang ditampilkan. Padding juga ditambahkan agar konten tidak terlalu menempel ke tepi.

### .service-content:

position: static; text-align: center; membuat posisi konten di dalam service-card menjadi statis (tidak menggunakan positioning absolute lagi) dan menata teksnya agar berada di tengah.

### .contact-form:

padding-left: 0; menghilangkan padding kiri dari form kontak untuk memastikan tampilannya lebih baik dan proporsional di layar kecil.
