Sistem Penjadwalan Lab Otomatis untuk Sekolah

Deskripsi Proyek

Proyek ini adalah sistem penjadwalan otomatis untuk keperluan laboratorium di sekolah. Sistem ini mencakup fitur absensi guru, manajemen data guru, data kelas, data user, data mata pelajaran (matpel), dan jadwal otomatis berdasarkan kebutuhan dan ketersediaan.

Fitur Utama

1. Absensi Guru

- Guru dapat melakukan absensi harian secara digital.
- Sistem mencatat waktu absen guru.

2. Manajemen Data Guru

- Pendaftaran dan pengelolaan data guru.
- Informasi lengkap seperti nama, nomor identitas, dan informasi kontak.
- Edit dan hapus data guru.

3. Manajemen Data Kelas

- Pendaftaran dan pengelolaan data kelas.
- Informasi kelas, jumlah siswa, dan ruang kelas.
- Tambah, edit, dan hapus data kelas.

4. Manajemen Data User

- Pendaftaran dan manajemen akun pengguna (admin, guru, staf, dll.).
- Hak akses yang berbeda untuk setiap tipe pengguna.
- Reset password dan manajemen akun pengguna.

5. Manajemen Data Mata Pelajaran (Matpel)

- Pendaftaran dan pengelolaan data mata pelajaran.
- Informasi matpel, tingkat kelas, dan guru yang mengajar.
- Edit dan hapus data matpel.

6. Jadwal Otomatis

- Sistem menghasilkan jadwal otomatis berdasarkan ketersediaan guru dan ruang kelas.
- Otomatis menangani konflik jadwal dan memberikan solusi alternatif.

Persyaratan Sistem

- PHP 7.0 atau versi lebih tinggi
- MySQL Database
- Web Server
- Browser web yang mendukung HTML dan JavaScript

Instalasi

1. Clone repositori ini ke dalam direktori web server Anda.
   git clone https://github.com/AldiNugroho10/Kelompok-47-_-Sistem_Jadwal_Otomatis
2. Impor skema basis data yang disediakan di dalam direktori `database`.
   mysql -u username -p silabsmk_backend < database/schema.sql

3. Konfigurasi koneksi basis data pada file `config.php`.

4. Akses aplikasi melalui browser web:
   http://localhost/jadwal_laboratorium

Penggunaan

1. Daftar atau masuk ke dalam sistem dengan akun sesuai jabatan.
2. Isi absensi harian jika Anda adalah seorang guru.
3. Kelola data guru, kelas, mata pelajaran, dan user melalui menu administrasi.
4. Sistem akan menghasilkan jadwal otomatis berdasarkan parameter yang diatur.

