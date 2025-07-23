# TUGAS-DASAR-ALGORITMA-DAN-PEMROGRAMAN-PERTEMUAN-14

# Aplikasi Toko Online

Aplikasi Toko Online adalah sebuah program berbasis teks yang memungkinkan pengguna untuk mengelola inventori barang dan melakukan transaksi belanja. Aplikasi ini memiliki dua peran utama: Admin dan Pelanggan.

## Fitur

### Untuk Admin
- **Tambah Barang Baru**: Menambahkan barang baru ke dalam inventori dengan nama, harga, dan jumlah stok.
- **Lihat Semua Barang**: Menampilkan semua barang yang ada di inventori, dengan opsi untuk mengurutkan berdasarkan nama.
- **Cari Barang**: Mencari barang berdasarkan nama.
- **Update Stok Barang**: Mengupdate jumlah stok untuk barang tertentu.
- **Hapus Barang**: Menghapus barang dari inventori.

### Untuk Pelanggan
- **Lihat & Beli Barang**: Melihat daftar barang yang tersedia dan menambahkannya ke keranjang belanja.
- **Lihat Keranjang & Checkout**: Melihat isi keranjang belanja dan melakukan pembayaran.

## Cara Menjalankan Aplikasi

1. Pastikan Anda memiliki Python terinstal di komputer Anda.
2. Simpan kode program dalam file bernama `toko_online.py`.
3. Jalankan aplikasi dengan perintah berikut di terminal:
   ```bash
   python toko_online.py

## Cara Menggunakan Aplikasi
   Aplikasi ini memiliki dua jenis pengguna: Admin dan Pelanggan.
## A. Untuk Admin (Pengelola Toko)
Sebagai Admin, Anda bertanggung jawab untuk mengelola semua barang yang dijual di toko.
1.	Masuk sebagai Admin:
   •	Saat aplikasi pertama kali dijalankan, pilih opsi 1. Admin dari menu utama.
   •	Tekan Enter untuk melanjutkan.
3.	Menu Admin: Anda akan melihat pilihan-pilihan berikut:
   1.	Tambah Barang Baru: Untuk menambahkan produk baru ke toko Anda.
      Anda akan diminta memasukkan nama barang, harga (gunakan hanya angka, contoh: 5000), dan jumlah stok awal (gunakan hanya angka, contoh: 100).
      Contoh: Masukkan Buku Tulis, lalu 5000, lalu 50. Aplikasi akan otomatis memberikan kode barang unik.
   2.	Lihat Semua Barang (Default): Menampilkan daftar semua barang tanpa diurutkan.
   3.	Lihat Semua Barang (Urutkan A-Z): Menampilkan daftar semua barang yang diurutkan berdasarkan nama (dari A sampai Z).
   4.	Cari Barang: Untuk mencari barang tertentu berdasarkan namanya.
      Masukkan kata kunci nama barang yang ingin Anda cari. Contoh: Buku.
   5.	Update Stok Barang: Jika Anda menerima kiriman stok baru atau ingin menyesuaikan jumlah stok.
      a.	Anda akan diminta memasukkan kode barang (contoh: BRG1678786501 yang muncul saat menambah barang atau melihat daftar).
      b.	Lalu, masukkan jumlah stok terbaru.
   6.	Hapus Barang: Untuk menghapus barang yang sudah tidak dijual lagi.
      a.	Anda akan diminta memasukkan kode barang yang ingin dihapus.
      b.	Anda harus mengetik y (ya) untuk mengonfirmasi penghapusan.
   7.	Kembali ke Menu Utama: Untuk kembali ke pilihan peran Admin/Pelanggan.
   8.	Tips Admin:
      a.	Selalu perhatikan kode barang saat ingin mengupdate atau menghapus, karena kode ini unik untuk setiap barang.
      b.	Tekan Enter setelah setiap operasi untuk melanjutkan ke menu admin.

## B. Untuk Pelanggan (Pembeli)
Sebagai Pelanggan, Anda bisa melihat produk dan melakukan pembelian.
1.	Masuk sebagai Pelanggan:
   •	Saat aplikasi pertama kali dijalankan, pilih opsi 2. Pelanggan dari menu utama.
   •	Tekan Enter untuk melanjutkan.
2.	Menu Pelanggan: Anda akan melihat pilihan-pilihan berikut:
   1.	Lihat & Beli Barang: Menampilkan semua barang yang tersedia di toko dan memulai proses belanja.Daftar barang akan muncul, diurutkan berdasarkan nama.
      a.	Masukkan kode barang dari barang yang ingin Anda beli.
      b.	Masukkan jumlah yang ingin Anda beli.
      c.	Anda bisa mengulangi langkah ini untuk membeli barang lain.
      d.	Jika sudah selesai memilih, ketik selesai (huruf kecil atau besar tidak masalah) dan tekan Enter untuk melanjutkan ke kasir.
   2.	Lihat Keranjang & Checkout: Untuk melihat daftar belanjaan Anda dan melakukan pembayaran.
      a.	Aplikasi akan menampilkan semua barang di keranjang Anda, beserta total harganya.
      b.	Anda akan ditanya apakah ingin melanjutkan pembayaran. Ketik y (ya) untuk konfirmasi.
      c.	Jika pembayaran berhasil, stok barang di toko akan otomatis berkurang.
      d.	Keranjang Anda akan dikosongkan setelah checkout berhasil.
   3.	Kembali ke Menu Utama: Untuk kembali ke pilihan peran Admin/Pelanggan.
   4.	Tips Pelanggan:
      a.	Pastikan Anda memasukkan kode barang yang benar.
      b.	Jika stok tidak cukup, aplikasi akan memberitahu Anda.
      c.	Setelah checkout, Anda bisa memulai sesi belanja baru atau keluar.


