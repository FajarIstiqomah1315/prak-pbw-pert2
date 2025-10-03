Nama : Fajar Istiqomah
NPM : 4523210045

# Praktikum 1: Aplikasi PHP Dasar - Form Pendaftaran Event
Aplikasi ini dibuat untuk memenuhi tugas praktikum dasar PHP. Aplikasi ini
merupakan form pendaftaran sederhana untuk sebuah event fiktif.

Langkah 1: Membuat File Utama dan Tampilan Form
1. Di dalam folder praktikum1, buat satu file bernama index.php.
   <img width="1366" height="163" alt="image" src="https://github.com/user-attachments/assets/9ce598e3-dff5-4aad-bcf8-d49e16a2a253" />
3. Buka file index.php dan tulis kode HTML berikut untuk membuat form pendaftaran.
    <img width="1345" height="620" alt="image" src="https://github.com/user-attachments/assets/eebe8082-c3c6-4001-979c-0bc0db882f86" />

## Deskripsi & Fitur
<img width="674" height="451" alt="image" src="https://github.com/user-attachments/assets/17e65fb5-9177-4475-af9a-f21d23b865a2" />
Aplikasi ini mencakup implementasi dari beberapa konsep dasar PHP, yaitu:
- **Variabel, Global Variabel, dan Konstanta**: Untuk menyimpan data dan
konfigurasi.
- **Fungsi**: Digunakan untuk modularisasi kode, khususnya untuk validasi.
- **Penanganan Form (POST)**: Menerima dan memproses data yang dikirim dari
form HTML.
<img width="1358" height="666" alt="image" src="https://github.com/user-attachments/assets/dc4e6d24-c44a-4f57-9b31-2e97ce2d013f" />
<img width="1366" height="565" alt="image" src="https://github.com/user-attachments/assets/3d1cc0a1-bbc1-45a5-8e56-e5da58abdba3" />

- **Validasi dengan Regex**: Memastikan format input email dan tanggal
lahir (DD-MM-YYYY) sudah benar.
- **Operasi File**: Menyimpan setiap pendaftar yang valid ke dalam file
`pendaftar.txt`.
- **Menampilkan Data**: Membaca data dari `pendaftar.txt` dan
menampilkannya dalam bentuk tabel.

Langkah 4: Pengujian
1. Buka browser dan akses proyek Anda melalui URL: http://praktikum1.test (jika Laragon
membuatkan virtual host) atau http://localhost/praktikum1/.
2. Coba isi form dengan data yang benar, lalu submit.
3. Coba isi form dengan email atau tanggal yang salah, perhatikan pesan error yang
muncul.
4. Setelah berhasil submit, data Anda akan muncul di tabel di bawah form, dan file
pendaftar.txt akan terbuat di dalam folder praktikum1.

## Tampilan Aplikasi
**Tampilan Awal Form**
*(Letakkan screenshot tampilan form kosong di sini)*
<img width="1361" height="540" alt="image" src="https://github.com/user-attachments/assets/b4f3cb3d-8f74-4a0a-af6d-74c925b80290" />

**Tampilan Setelah Pendaftaran Berhasil**
*(Letakkan screenshot tampilan setelah berhasil submit data di sini)*
<img width="1366" height="640" alt="image" src="https://github.com/user-attachments/assets/64578581-bda3-4c49-8ea0-67641bca5fb8" />

**Contoh Pesan Error Validasi**
*(Letakkan screenshot tampilan saat ada error validasi di sini)*
<img width="1366" height="636" alt="image" src="https://github.com/user-attachments/assets/fd2e47fc-e2f8-4813-b78a-7d4dc55e38b7" />


