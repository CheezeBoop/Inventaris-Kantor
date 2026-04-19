===================================================================
  SISTEM INVENTARIS BARANG KANTOR - Muhammad Firas Syafiq - XII RPL
  BNSP Junior Web Programmer
===================================================================

Aplikasi ini saya buat untuk keperluan uji kompetensi BNSP.
Fungsinya yaitu untuk mencatat barang inventaris kantor
berbasis web satu halaman (single page).

Teknologi yang saya pakai:
- HTML5 untuk struktur halaman
- CSS3 untuk tampilan (custom + Bootstrap 5)
- JavaScript untuk logika program
- Bootstrap 5 lewat CDN biar tampilannya rapi
- XAMPP (Apache) sebagai web server lokal
- VS Code sebagai editor


=================================================================
CARA MENJALANKAN
=================================================================

Yang perlu disiapkan dulu:
- XAMPP sudah terinstall
- VS Code sudah terinstall
- Koneksi internet aktif (buat load Bootstrap CDN)

Langkah-langkahnya:

1. Taruh folder "inventaris-kantor" ini ke dalam folder htdocs
   lokasinya di: C:\xampp\htdocs\

2. Buka XAMPP Control Panel, klik Start di bagian Apache
   tunggu sampai warnanya jadi hijau (Running)

3. Buka browser, ketik di address bar:
   http://localhost/inventaris-kantor/

4. Tekan Enter, aplikasinya langsung kebuka


===================================================================
FITUR YANG ADA
===================================================================

- Tambah barang baru lewat form (nama, jumlah, kategori)
- Data langsung muncul di tabel setelah disimpan
- Hapus barang dengan klik tombol Hapus
- Kalau form ada yang kosong, muncul peringatan otomatis
- Kalau nama dan kategori barang sama persis, jumlahnya
  otomatis ditambah, tidak bikin baris baru
- Tampilan responsive karena pakai Bootstrap 5


===================================================================
STRUKTUR FILE
===================================================================

inventaris-kantor/
  index.html    --> file utama
  README.txt    --> ini


===================================================================
CATATAN
===================================================================

- Data barang akan hilang kalau halaman di-refresh, karena
  datanya disimpan sementara di memori (array JavaScript),
  bukan di database
- Apache di XAMPP harus nyala dulu sebelum dibuka di browser
- Pastikan internet aktif karena Bootstrap diambil dari CDN


===================================================================