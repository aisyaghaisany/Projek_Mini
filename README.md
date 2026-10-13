# Program Data Mahasiswa

## Deskripsi
Program Data Mahasiswa adalah aplikasi sederhana berbasis Java yang digunakan untuk memasukkan dan menampilkan data mahasiswa. Program ini menerapkan konsep Object-Oriented Programming (OOP) dengan menggunakan class, object, constructor, method, dan array of objects.

Program ini dapat menginput data dari 3 mahasiswa, berupa nama, NIM, dan nilai, kemudian menampilkan seluruh data beserta keterangan kelulusan masing-masing mahasiswa.

## Fitur Program
- Memasukkan nama mahasiswa.
- Memasukkan NIM mahasiswa.
- Memasukkan nilai mahasiswa.
- Menyimpan data menggunakan array of objects.
- Menampilkan seluruh data mahasiswa.
- Mengecek status kelulusan mahasiswa secara otomatis.
- Menampilkan keterangan **LULUS** jika nilai minimal 60.
- Menampilkan keterangan **TIDAK LULUS** jika nilai kurang dari 60.

## Teknologi yang Digunakan
- **Java** — Bahasa pemrograman yang digunakan.
- **Scanner** — Untuk menerima input dari pengguna.
- **OOP (Object-Oriented Programming)** — Menggunakan class, object, constructor, dan method.

## Struktur Program
- `DataMahasiswa.java` — Berisi class utama dan method `main()` untuk menjalankan program.
- `Mahasiswa` — Class untuk menyimpan dan mengelola data mahasiswa.

## Cara Menjalankan Program

1. Pastikan Java Development Kit (JDK) sudah terpasang di komputer.
2. Simpan kode program dengan nama `DataMahasiswa.java`.
3. Buka terminal atau Command Prompt pada folder tempat file disimpan.
4. Kompilasi program menggunakan perintah:

   ```bash
   javac DataMahasiswa.java
   ```

5. Jalankan program menggunakan perintah:

   ```bash
   java DataMahasiswa
   ```

6. Masukkan nama, NIM, dan nilai untuk 3 mahasiswa sesuai petunjuk yang muncul.

## Aturan Kelulusan
- Nilai ≥ 60: **LULUS**
- Nilai < 60: **TIDAK LULUS**

## Konsep OOP yang Digunakan
- **Class:** `Mahasiswa` dan `DataMahasiswa`.
- **Object:** Objek mahasiswa yang dibuat berdasarkan class `Mahasiswa`.
- **Constructor:** Digunakan untuk mengisi nama, NIM, dan nilai mahasiswa.
- **Method:** `tampilkanData()` untuk menampilkan data dan `cekKelulusan()` untuk menentukan status kelulusan.
- **Array of Objects:** Digunakan untuk menyimpan data 3 mahasiswa.

## Kesimpulan
Program ini membantu pengguna mengelola data sederhana dari 3 mahasiswa dan menentukan status kelulusan berdasarkan nilai yang diperoleh. Program juga menerapkan dasar-dasar pemrograman berorientasi objek (OOP) dalam Java.
