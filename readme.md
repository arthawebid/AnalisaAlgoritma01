Berikut adalah studi kasus baru yang serupa format dan tingkat kesulitannya untuk siswa kelas X PPLG (Pengembangan Perangkat Lunak dan Gim), tetapi dengan topik aplikasi yang berbeda (tidak menggunakan kalkulator):

---

# STUDI KASUS PROYEK: APLIKASI DAFTAR BELANJA DIGITAL (SMK-SHOP)

## Latar Belakang Proyek

Sebuah kelompok siswa kelas X PPLG di SMKN 2 Kuta Selatan mendapatkan proyek untuk merancang spesifikasi kebutuhan perangkat lunak berupa aplikasi **Daftar Belanja Digital Berbasis Web** bernama **SMK-Shop**. Aplikasi ini dirancang berjalan di peramban web (*browser*) pada HP atau laptop tanpa memerlukan server dan basis data eksternal.

Tim ini beranggotakan 5 orang dengan pembagian peran yang telah disepakati:

* **Andi** berperan sebagai **Client** (pengguna yang akan memesan dan menilai aplikasi).
* **Budi** sebagai *Lead Analyst* (SA 1).
* **Citra** sebagai *Interviewer* (SA 2).
* **Dina** sebagai *Scribe / Notulen* (SA 3).
* **Eko** sebagai *Modeler & Documenter* (SA 4 & SA 5).

---

## Hasil Wawancara Awal (Sesi 1)

Berdasarkan wawancara antara SA 2 dan Client, diperoleh spesifikasi kebutuhan dasar (*baseline needs*) sebagai berikut:

1. **Pengelolaan Barang:** Pengguna dapat menambahkan nama barang, jumlah barang, dan menghapus barang dari daftar belanja.


2. **Kategori & Harga:** Pengguna dapat memasukkan perkiraan harga satuan barang dan menghitung total harga keseluruhan belanja secara otomatis.
3. **Penyimpanan Lokal:** Karena aplikasi berbasis web tanpa database server, data daftar belanja sementara disimpan di penyimpanan peramban (*Local Storage*).


4. **Penanganan Kesalahan:** Sistem harus menampilkan peringatan jelas jika pengguna mencoba memasukkan jumlah barang berupa huruf atau angka negatif (input tidak valid).



---

## Permintaan Tambahan (Sesi 2 - Change Management)

Setelah melihat draf pertama dan hasil analisis dari tim pembuat, Client mengajukan beberapa kebutuhan tambahan (*additional needs*):

* **KT-01:** Fitur *Checklist* centang otomatis pada barang yang sudah dibeli agar tidak ada barang yang terlewat.
* **KT-02:** Fitur ekspor daftar belanja menjadi file teks (`.txt`) agar bisa dibagikan via WhatsApp.
* **KT-03:** Penambahan Mode Gelap (*Dark Mode*) untuk kenyamanan mata saat berbelanja di malam hari.

---

## Tugas / Pertanyaan untuk Siswa PPLG:

1. **Analisis Kebutuhan (Informatika & Bahasa Indonesia):** Buatlah daftar Kebutuhan Fungsional (`KF-01`, `KF-02`, dst.) dan Kebutuhan Tambahan (`KT-01`, `KT-02`, `KT-03`) lengkap dengan status dan prioritasnya ke dalam format tabel lampiran SRS!


2. **Pemodelan Sistem (Informatika):** Buatlah rancangan *Flowchart* sederhana untuk alur penambahan barang ke dalam daftar belanja hingga validasi input harga!


3. **Dokumentasi (Bahasa Inggris):** Susunlah petunjuk penggunaan aplikasi (*User Guide*) berbahasa Inggris untuk fitur penambahan barang menggunakan struktur *Procedure Text* (Goal, Materials, Steps) dengan kata urutan (*first, next, then, finally*)!
