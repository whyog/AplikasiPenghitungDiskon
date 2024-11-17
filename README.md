# 🚀 Aplikasi GUI Perhitungan Diskon

Selamat datang di proyek ini! 🎉 Proyek ini adalah implementasi GUI berbasis Java untuk menghitung harga akhir setelah diskon, dengan fitur tambahan seperti memasukkan kode kupon diskon, menggunakan `JSlider` untuk memilih persentase diskon, dan menyimpan riwayat perhitungan diskon.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **Nur Yoga Andika** 👋  
- 📚 **NPM:** 2210010652  
- 🎓 **Jurusan:** Teknologi Informasi  
- 🌟 Saya selalu berusaha belajar hal-hal baru dan berbagi apa yang saya pelajari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini atau topik lainnya! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna:
1. Memasukkan **harga asli barang** di `JTextField`.
2. Memilih **persentase diskon** melalui:
   - **JComboBox**: Untuk memilih persentase diskon standar.
   - **JSlider**: Sebagai alternatif untuk memilih persentase diskon.
3. Menekan tombol:
   - **Hitung:** Untuk menampilkan harga akhir setelah diskon dan jumlah penghematan.
   - **Hapus:** Untuk menghapus input dan memulai perhitungan ulang.
   - **Keluar:** Untuk menutup aplikasi dengan mudah.

Aplikasi ini juga menyediakan fitur tambahan seperti:
- Opsi untuk memasukkan kode kupon diskon tambahan.
- Menyimpan **riwayat perhitungan diskon**.

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:
- **JFrame:** Sebagai jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JTextField:** Untuk memasukkan harga asli barang.
- **JComboBox:** Untuk memilih persentase diskon.
- **JSlider:** Alternatif untuk memilih persentase diskon.
- **JButton:** Untuk melakukan tindakan seperti hitung, hapus, dan keluar.

---

## 🔍 Logika Program

1. **Perhitungan Diskon:**
   - Menghitung harga akhir setelah diskon:  
     `Harga Akhir = Harga Asli - (Harga Asli * Persentase Diskon / 100)`
   - Menghitung jumlah penghematan:  
     `Penghematan = Harga Asli * Persentase Diskon / 100`
   
2. **Penanganan Eksepsi:**
   - Memastikan input hanya berupa angka.
   - Menangani kondisi ketika input kosong atau tidak valid.

3. **Riwayat Perhitungan:**
   - Menyimpan data perhitungan sebelumnya dalam daftar untuk dilihat kembali.

---

## 🎯 Events yang Diimplementasikan

1. **ActionListener:**  
   - Untuk tombol **Hitung**, memproses perhitungan diskon.  
   - Untuk tombol **Hapus**, menghapus semua input.
   - Untuk tombol **Keluar**, menutup aplikasi.

2. **ItemListener:**  
   - Mengatur persentase diskon berdasarkan pilihan di `JComboBox`.

3. **KeyAdapter:**  
   - Membatasi input hanya berupa angka di `JTextField`.

4. **ChangeListener:**  
   - Mengatur persentase diskon berdasarkan perubahan nilai pada `JSlider`.

---

## ✨ Variasi

1. Opsi tambahan:
   - Memasukkan kode kupon diskon tambahan untuk penghematan ekstra.
   - Menggunakan `JSlider` sebagai alternatif untuk memilih persentase diskon.
2. Riwayat perhitungan:
   - Menyimpan hasil perhitungan sebelumnya untuk referensi pengguna.
3. Validasi input:
   - Menampilkan pesan kesalahan jika input kosong atau tidak valid.

---

## 🔧 Cara Menggunakan Program

1. Masukkan **harga asli barang** di `JTextField`.
2. Pilih persentase diskon:
   - Gunakan **JComboBox** untuk memilih persentase standar.
   - Atau geser **JSlider** untuk memilih persentase diskon.
3. Tekan tombol:
   - **Hitung:** Untuk melihat hasil harga akhir setelah diskon dan jumlah penghematan.
   - **Hapus:** Bersihkan semua input dan mulai dari awal.
   - **Keluar:** Tutup aplikasi dengan mudah.
4. Jika diaktifkan, masukkan **kode kupon diskon** untuk tambahan penghematan.
5. Riwayat perhitungan dapat dilihat di panel riwayat.

---



