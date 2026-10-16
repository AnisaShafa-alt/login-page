Tugas Pendahuluan Modul 5
Pemrograman Web – Ganjil 2026/2027
“Bootstrap”

Nama: Anisa Shafa Salsabila
NIM: 103092400078
Kelas: IT-07-01

1.	Pengertian Bootstrap [10 poin] 
Jelaskan apa itu Bootstrap dan apa kegunaannya!
Jawaban:
  Bootstrap: framework CSS yang digunakan untuk mempermudah pembuatan tampilan website. Bootstrap menyediakan berbagai class, komponen, &
fitur yang siap digunakan, seperti tombol, navbar, form, & card.
Bootstrap juga membantu membuat tampilan website yang responsif sehingga dapat menyesuaikan ukuran layar komputer maupun handphone.

2.	Memasang Bootstrap [10 poin]  
Ada beberapa cara untuk mengimpor / menggunakan Bootstrap pada project. Sebutkan cara-caranya!
Jawaban:
- Pakai CDN, yaitu dengan menambahkan link Bootstrap CSS & JavaScript dari internet ke file HTML
- Download Bootstrap, dengan cara mengunduh file CSS & JavaScript Bootstrap, kemudian menyimpannya di folder project
- Menggunakan package manager, contohnya npm, untuk memasang Bootstrap ke dalam project

3.	Grid dan Breakpoint [10 poin] 
Jelaskan mengenai class grid dan kegunaan breakpoint!
Jawaban:
  Grid Bootstrap: sistem untuk mengatur tata letak halaman website menggunakan baris (row) & kolom (col)
Sistem grid Bootstrap menggunakan 12 kolom sehingga lebar dan posisi elemen dapat diatur sesuai kebutuhan
  Breakpoint: batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada perangkat yang berbeda
Dengan breakpoint, tata letak website dapat berubah sesuai ukuran layar, misalnya dari tampilan komputer menjadi tampilan handphone

4.	Class Bootstrap [10 poin] 
Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya!
Jawaban:
- container: Mengatur area konten agar memiliki lebar yang sesuai
- row: Membuat baris dalam sistem grid Bootstrap
- col: Membuat kolom untuk mengatur tata letak elemen
- btn: Membuat tampilan tombol
- navbar: Membuat navigasi pada website
- card: Membuat kotak konten yang dapat berisi teks, gambar, / elemen lainnya
- form-control: Mengatur tampilan input pada form
- text-center: Membuat teks menjadi rata tengah
  
5.	Gambar Responsif [10 poin] 
Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar perangkat?
Jawaban:
Agar gambar pada website responsif, bisa memakai class img-fluid pada elemen gambar
Class ini membuat gambar menyesuaikan lebar elemen / wadahnya dan tetap mempertahankan rasio ukuran gambar
Contoh penggunaan:
<img src="gambar.jpg" class="img-fluid" alt="Gambar">
Dengan menggunakan class tersebut, gambar dapat menyesuaikan ukuran layar perangkat tanpa menjadi terlalu lebar atau terdistorsi

6.	Membuat Tampilan dengan Bootstrap [50 poin] 
Buat tampilan halaman login Ruang Baca pada file index.html dengan memanfaatkan class Bootstrap, seperti gambar berikut. 
• Navbar memuat nama Ruang Baca di kiri serta menu Beranda, Tentang, dan Bantuan di kanan. 
• Form login memuat judul, input Username, input Password, checkbox Ingat saya, tombol Masuk, dan tautan Lupa password?.
• Gunakan komponen serta utility Bootstrap untuk mengatur tata letak, warna, jarak, lebar, dan bayangan sesuai contoh. 
• Gunakan grid Bootstrap agar form tetap terbaca pada layar kecil. Contoh tampilan ponsel disertakan sebagai acuan. Fokus soal adalah tampilan menggunakan Bootstrap. Tidak perlu membuat autentikasi akun, penyimpanan data login, atau layanan pemulihan password.
