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

![Design FormTiketTravel dengan Navigator](p03-komponen-gui/screenshot/tampilanDesign.png)

### 3. Refleksi Bagian G

**1. [Pertanyaan refleksi pertama]**

Jawaban: [Top-level container adalah wadah utama untuk menampilkan sebuah aplikasi,
contohnya JFrame. Intermediate container digunakan untuk mengelompokkan komponen
lain, contohnya JPanel. Sedangkan atomic component adalah komponen yang langsung
digunakan untuk menerima input atau menampilkan informasi, contohnya JButton atau
JLabel.
]

**2. [Pertanyaan refleksi kedua]**

Jawaban: [Karena JRadioButton yang berada dalam ButtonGroup yang sama hanya dapat
memilih satu pilihan pada satu waktu. Contohnya pada pilihan jenis kelamin, pengguna
hanya bisa memilih Laki-laki atau Perempuan, bukan keduanya sekaligus.]

**3. [Pertanyaan refleksi ketiga]**

Jawaban: [JComboBox lebih cocok digunakan ketika pilihan yang tersedia cukup banyak
sehingga lebih hemat tempat, misalnya pilihan program studi atau kota tujuan. Sedangkan
JRadioButton lebih cocok jika pilihannya sedikit dan ingin ditampilkan langsung, seperti
pilihan kelas tiket Ekonomi, Bisnis, dan Eksekutif.]

**3. [Pertanyaan refleksi keempat]**

Jawaban: [Karena initComponents() merupakan kode yang dibuat otomatis oleh GUI Builder
NetBeans. Jika diedit langsung, perubahan bisa tertimpa ketika tampilan diubah melalui tab
Design. Kode tambahan seperti event dan method dapat ditulis di luar blok initComponents(), misalnya pada constructor, event handler, atau method bantuan.]

**3. [Pertanyaan refleksi kelima]**

Jawaban: [Karena FlatLightLaf perlu dipasang terlebih dahulu agar tampilan komponen Swing
menggunakan tema FlatLaf sejak awal form dibuat. Jika dipanggil setelah form dibuat,
tampilan awal form bisa belum menggunakan tema yang diinginkan.]
