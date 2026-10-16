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

**4. [Pertanyaan refleksi keempat]**

Jawaban: [Karena initComponents() merupakan kode yang dibuat otomatis oleh GUI Builder
NetBeans. Jika diedit langsung, perubahan bisa tertimpa ketika tampilan diubah melalui tab
Design. Kode tambahan seperti event dan method dapat ditulis di luar blok initComponents(), misalnya pada constructor, event handler, atau method bantuan.]

**5. [Pertanyaan refleksi kelima]**

Jawaban: [Karena FlatLightLaf perlu dipasang terlebih dahulu agar tampilan komponen Swing
menggunakan tema FlatLaf sejak awal form dibuat. Jika dipanggil setelah form dibuat,
tampilan awal form bisa belum menggunakan tema yang diinginkan.]


## P04 – Layout Manager dan Desain Form

### 1. Hasil Praktikum

#### a. Tampilan Awal Form

Screenshot berikut menunjukkan tampilan awal form sebelum diperlebar.

![Tampilan Awal Form](p04-layout-manager/screenshots/tampilanAwal.png)

#### b. Tampilan Form Setelah Diperlebar

Screenshot berikut menunjukkan tampilan form setelah ukurannya diperlebar.

![Tampilan Form Setelah Diperlebar](p04-layout-manager/screenshots/sesudah-dilebarkan.png)

### 2. Perancangan Layout

#### a. Sketsa Tahap 1

![Sketsa Tahap 1](p04-layout-manager/screenshots/sketsa-tahap1.jpeg)

#### b. Tabel Rancangan Tahap 2

![Tabel Rancangan Tahap 2](p04-layout-manager/screenshots/tabelRancangan.png)

#### c. Design Navigator

![Tampilan Design Navigator](p04-layout-manager/screenshots/tampilan-design-navigator.png)

#### d. Hasil penilaian teman - Elvira Eri Saputri - 2410010461

Penilaian dilakukan untuk memeriksa tampilan Form Anggota Perpustakaan berdasarkan kriteria yang terdapat pada modul Praktikum P04. Pemeriksaan meliputi susunan label, pengelompokan isian, penggunaan placeholder, kesesuaian komponen, posisi tombol, jarak antar komponen, tampilan saat ukuran jendela berubah, serta penggunaan Layout Manager.

![Hasil Penilaian Teman](screenshots/tabel-penilaian.png)

**Saran Perbaikan:**

Tambahkan placeholder pada isian yang memerlukan format pengisian agar memudahkan pengguna saat mengisi form.

### 3. Jawaban Eksperimen Praktikum 2

#### Eksperimen 1 – FlowLayout

Jawaban: FlowLayout mengatur komponen secara berurutan dari kiri ke kanan. Jika ruang pada baris tidak cukup, komponen akan berpindah ke baris berikutnya. Posisi komponen juga dapat diatur, misalnya rata tengah menggunakan `FlowLayout.CENTER`.

#### Eksperimen 2 – GridLayout

Jawaban: GridLayout membagi area menjadi baris dan kolom dengan ukuran sel yang sama. Jika jumlah baris diatur menjadi 0 dan jumlah kolom menjadi 2, komponen akan disusun dalam dua kolom. Untuk sembilan tombol, susunannya menjadi lima baris dengan satu sel tersisa pada baris terakhir.

#### Eksperimen 3 – BoxLayout

Jawaban: BoxLayout menyusun komponen secara vertikal atau horizontal sesuai arah yang ditentukan. Ukuran dan posisi komponen dapat dipengaruhi oleh ukuran komponen serta pengaturan alignment. Jarak antarkomponen dapat diatur agar tampilan lebih rapi.

### 4. Jawaban Eksperimen Praktikum 4

#### Eksperimen 1 – Weight X

Jawaban: Nilai `weightx` menentukan bagaimana ruang horizontal tambahan dibagikan kepada komponen. Jika `weightx` bernilai 0, komponen tidak mendapatkan bagian ruang horizontal tambahan berdasarkan nilai tersebut.

#### Eksperimen 2 – Posisi formPanel

Jawaban: Penempatan `formPanel` pada bagian `NORTH` membuat panel berada di bagian atas container. Jika ditempatkan pada bagian `CENTER`, panel berada di area tengah dan dapat memanfaatkan ruang yang tersedia sesuai pengaturan layout.

#### Eksperimen 3 – Minimum Size

Jawaban: Pengaturan ukuran minimum memengaruhi ukuran terkecil yang dapat digunakan oleh komponen atau panel. Jika batas ukuran minimum dihilangkan, ukuran komponen dapat menyesuaikan aturan layout dan ukuran container, sehingga tampilannya bisa berubah.

### 5. Refleksi Bagian G

**1. Apa perbedaan FlowLayout, BorderLayout, dan GridLayout?**

Jawaban: FlowLayout menyusun komponen secara berurutan dari kiri ke kanan. BorderLayout membagi container menjadi lima bagian, yaitu North, South, East, West, dan Center. GridLayout menyusun komponen dalam bentuk baris dan kolom dengan ukuran sel yang sama.

**2. Apa yang terjadi jika jumlah baris pada GridLayout diatur menjadi 0?**

Jawaban: Jika jumlah baris diatur menjadi 0, jumlah baris akan menyesuaikan jumlah komponen berdasarkan jumlah kolom yang ditentukan.

**3. Apa fungsi weightx dan weighty pada GridBagConstraints?**

Jawaban: `weightx` mengatur pembagian ruang horizontal tambahan, sedangkan `weighty` mengatur pembagian ruang vertikal tambahan kepada komponen.

**4. Mengapa pengaturan layout penting dalam pembuatan antarmuka?**

Jawaban: Pengaturan layout membantu menyusun komponen agar rapi dan teratur. Layout juga membantu tampilan menyesuaikan ukuran container sehingga antarmuka lebih mudah digunakan.

**5. Apa fungsi Design Navigator pada NetBeans?**

Jawaban: Design Navigator membantu melihat susunan komponen yang terdapat pada form. Dengan fitur ini, komponen lebih mudah ditemukan dan dipilih saat merancang antarmuka menggunakan GUI Builder.

### Deklarasi Penggunaan AI p04

Dalam pengerjaan praktikum ini, saya menggunakan AI sebagai alat bantu untuk memahami materi, mencari referensi penjelasan, dan membantu menyusun dokumentasi pada README. Seluruh proses pengerjaan dan penyesuaian program dilakukan sesuai dengan materi praktikum yang dipelajari.

