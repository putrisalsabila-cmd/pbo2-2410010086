# pbo2-2410010086

## P01 – Pengenalan PBO 2

### 1. Hasil Keluaran Program

#### a. Program HaloPBO2

Program `HaloPBO2` dibuat sebagai latihan awal untuk menampilkan keluaran program Java.

**Screenshot keluaran program:**

![Screenshot HaloPBO2](p01-halo-java/screenshot/outputHaloPbo2.png)

#### b. Program KartuMahasiswa

Program `KartuMahasiswa` dibuat untuk menampilkan informasi kartu mahasiswa melalui program Java.

**Screenshot keluaran program:**

![Screenshot HaloPBO2](p01-halo-java/screenshot/kartuMahasiswa.png)

### 2. Riwayat Commit Git

Riwayat commit digunakan untuk melihat perubahan yang telah disimpan pada repository.

**Screenshot hasil perintah `git log --oneline`:**

![Screenshot HaloPBO2](p01-halo-java/screenshot/gitLog--.png)

Screenshot menunjukkan riwayat commit repository dengan minimal dua commit.


## P02 – Perpustakaan Mini

### 1. Hasil Keluaran Program

#### a. Pencarian dan peminjaman Buku Skripsi 

Screenshot berikut menunjukkan keluaran program ketika melakukan pencarian buku dengan judul `Skripsi`.

![Hasil Pencarian Buku Skripsi](p02-perpustakaan-mini/dokumentasi/outputpo2.png)


### 2. Jawaban Eksperimen Praktikum 6

#### Eksperimen 1
Jawaban: [Terjadi error karena Koleksi merupakan abstract class, sehingga tidak dapat dibuat objek secara langsung menggunakan new. Koleksi harus diturunkan terlebih dahulu oleh class seperti Buku atau Majalah.]

#### Eksperimen 2
Jawaban: [Jika @Override masih ada, akan terjadi error pada compiler karena hitungdenda tidak sama dengan method hitungDenda yang ada pada interface. Jika @Override dihapus, error anotasi memang hilang, tetapi class Buku tetap tidak memenuhi method hitungDenda dari interface, sehingga tetap bermasalah.]

#### Eksperimen 3
Jawaban: [Saat program dijalankan, akan terjadi IllegalArgumentException dengan pesan "Judul tidak boleh kosong", karena constructor Koleksi melakukan validasi bahwa judul koleksi tidak boleh kosong.]

#### Eksperimen 4
Jawaban: [Hal tersebut melanggar encapsulation dan aturan bisnis peminjaman, karena status koleksi dapat diubah langsung dari luar class tanpa melalui method pinjam() atau kembalikan(). Seharusnya perubahan status dikendalikan oleh class Koleksi.]


## P03 – Komponen GUI

### 1. Hasil Form Pemesanan Tiket Travel

#### a. Tema Terang

Screenshot berikut menunjukkan tampilan Form Pemesanan Tiket Travel saat dijalankan menggunakan tema terang.

![Form Pemesanan Tiket Travel - Tema Terang](p03-komponen-gui/screenshot/modeTerang.png)

#### b. Tema Gelap

Screenshot berikut menunjukkan tampilan Form Pemesanan Tiket Travel saat dijalankan menggunakan tema gelap.

![Form Pemesanan Tiket Travel - Tema Gelap](p03-komponen-gui/screenshot/modeGelap.png)

### 2. Tampilan Design FormTiketTravel

Screenshot berikut memperlihatkan tab Design pada `FormTiketTravel`, termasuk jendela Navigator yang menampilkan komponen form.

![Design FormTiketTravel dengan Navigator](p03-komponen-gui/screenshots/tampilanDesign.png)

### 3. Refleksi Bagian G

**1. [Pertanyaan refleksi pertama]**

Jawaban: [Isi jawaban singkat sesuai pertanyaan.]

**2. [Pertanyaan refleksi kedua]**

Jawaban: [Isi jawaban singkat sesuai pertanyaan.]

**3. [Pertanyaan refleksi berikutnya, jika ada]**

Jawaban: [Isi jawaban singkat sesuai pertanyaan.]
