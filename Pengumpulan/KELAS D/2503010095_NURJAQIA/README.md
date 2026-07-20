# 2503010095 - NURJAQIA

## Informasi Pribadi
- **NIM** : 2503010095
- **Nama** : NURJAQIA
- **Kelas** : D

## Informasi Ujian
- **Mata Kuliah** : Praktikum Algoritma dan Struktur Data
- **Semester** : Genap 2025/2026
- **Media Submit** : GitHub Pull Request
- **Bahasa** : C++
- **IDE** : Dev C++

---

## DAFTAR ISI
- [Soal 1](#soal-1)
- [Soal 2](#soal-2)

## ANALISIS & PEMBAHASAN SOAL

### Soal 1
Program ini mengimplementasikan konsep struktur data **Stack** (Tumpukan) dan **Queue** (Antrean) dalam studi kasus Sistem Kasir Supermarket.
- **Stack (Riwayat Transaksi):** Menggunakan prinsip LIFO (*Last In First Out*). Fungsi yang diterapkan meliputi `push` untuk menambahkan data transaksi ke tumpukan, `pop` untuk menghapus data terakhir, dan `peek` untuk melihat transaksi paling atas.
- **Queue (Antrian Pelanggan):** Menggunakan prinsip FIFO (*First In First Out*). Fungsi yang diterapkan meliputi `enqueue` untuk menambahkan pelanggan ke dalam antrean, `dequeue` untuk memproses (menghapus) pelanggan dari depan antrean, dan `peek` untuk melihat pelanggan di urutan pertama.
- Program ini menggunakan perulangan `do-while` untuk menyediakan menu interaktif sehingga user dapat memilih operasi yang ingin dijalankan secara berulang.

### Soal 2
Program ini mengimplementasikan **Struct** dan **Array** untuk Sistem Manajemen Buku.
- **Struct `Buku`:** Digunakan untuk mengelompokkan variabel dengan tipe data yang berbeda (`judul`, `pengarang`, `tahunTerbit`, `harga`) ke dalam satu tipe data bentukan.
- **Array of Struct:** Digunakan array `daftarBuku[5]` untuk menyimpan sekumpulan data buku berdasarkan batas maksimal N yang diinputkan pengguna.
- **Logika & Fitur:** Program mampu melakukan input data, menampilkan data dalam bentuk tabel terformat menggunakan `<iomanip>` (`setw`, `left`, dll), menghitung total harga untuk mendapatkan rata-rata, mencari nilai tertinggi (buku termahal), serta menerapkan algoritma *Linear Search* untuk mencari daftar buku berdasarkan tahun terbit.

---

## SUMBER BELAJAR
- Modul Praktikum Algoritma dan Struktur Data
- Modul Struktur Data Dasar (Stack, Queue, Array, Struct)
- Dokumentasi resmi bahasa C++
- Stack Overflow
