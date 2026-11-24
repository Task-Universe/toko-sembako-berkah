# Web Pemantauan Stok Toko Sembako (JL. Naskah 2)
### Proyek Semester - Computer Engineering Department, Politeknik Negeri Sriwijaya

Aplikasi web ini dirancang untuk memantau ketersediaan stok bahan pokok dan kebutuhan harian secara real-time, dapat diakses langsung oleh pembeli (warga sekitar) serta dikelola dengan mudah oleh pemilik toko kelontong.

---

### Fitur Utama:
1. **Peniadaan Kode Produk**: Tampilan bersih dan natural tanpa kode teknis barang.
2. **4 Kategori dengan Tepat 6 Item Kunci**:
   - **Kebutuhan Pokok / Sembako** (Beras Ramos 5kg, Minyak Goreng 2L, Gula Pasir 1kg, Telur Ayam Karpet, Tepung Terigu 1kg, Mie Goreng Instan).
   - **Minuman & Seduhan** (Air Galon 19L, Air Botol 600ml, Teh Melati Isi 25, Kopi Renceng Hitam, Susu Kental Manis, Kopi Semendo Bubuk 250g).
   - **Obat-obatan & P3K** (Paracetamol 500mg, Obat Flu/Sakit Kepala, Minyak Kayu Putih 60ml, Minyak Angin Roll-on, Tablet Sakit Maag, Plester Luka).
   - **Bumbu Dapur & Penyedap** (Garam Kasar, Kaldu Penyedap, Kecap Manis 550ml, Bumbu Racik Nasi Goreng, Lada Bubuk, Saus Sambal).
3. **Dual Status (Dus & Satuan)**: Barang seperti Mie Instan dan Air Botol dipantau ketersediaan dus dan satuannya secara terpisah.
4. **Tampilan Horizontal & Responsif**: Berjejer rapi ke kanan (hingga 6–10 kolom pada layar lebar).
5. **Mode Pemilik Toko (dengan Login)**: Username `tokosembako`, password `admin123`. Stok bisa diubah dengan `[+]` `[-]` atau ketik angka langsung. Tombol berubah jadi **Keluar (Log Out)** untuk kembali ke mode pelanggan.
5b. **Foto Produk**: Tampil di bawah label status (Tersedia/Menipis/Habis). Pemilik dapat mengganti dengan foto asli lewat tombol *Ganti Foto*.
6. **Bilingual (Indonesia & English)**: Memudahkan saat presentasi mata kuliah bahasa Inggris.

---

### Cara Menjalankan:
1. Ekstrak file zip ini ke folder komputer Anda.
2. Buka file `index.html` langsung dengan browser apa saja (Google Chrome, Edge, Firefox, Safari).
3. Tidak memerlukan instalasi server atau dependensi tambahan.

### Foto Produk Sendiri
Masukkan foto ke folder `foto/` dengan nama `<nomor>.jpg` (lihat `foto/BACA-SAYA.txt`), contoh `101.jpg` untuk Beras Ramos. Foto tampil di bawah label status. Kalau belum ada, tampil gambar emoji.
Di bbawah kartu (mode pelanggan) muncul keterangan **Bisa Dibeli** atau **Stok Kosong**.

### Tambah Barang Baru
Di Mode Pemilik klik **Tambah Barang Baru** (kategori, nama, harga, satuan, stok awal, batas minimum, foto opsional). Barang bisa dihapus dengan ikon tempat sampah di foto. Teks "Live" di header sudah dihapus.
