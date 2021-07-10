# Mahasiswa Tugas Akhir

adalah aplikasi / website yang menampung masalah, kendala, dan keluhan mahasiswa semester akhir

# Tujuan 

Aplikasi ini mengumpulkan masalah masalah umum yang dihadapi mahasiswa dalam menyelesaikan tugas akhir / Skripsi mereka, lalu mengkategorikan masalah masalah yang mirip, sehingga diharapkan dengan masalah<sup>2</sup> yang terkumpul ini, _(semoga)_ dapat kita menentukan solusinya.

# Privasi

Aplikasi ini menyimpan masalah dan keluhana mahasiswa sehingga bisa saja data yang diinputkan adalah sesuatu yang sensitif dan bersifat privasi. sehingga aplikasi ini mengutamakan privasi pengguna, dan keamanan pengguna.

❌⚠️

Data yang berada pada _database_ produksi TIDAK BOLEH digunakan untuk kepentingan publik, atau diperjual belikan.

# Batasan

Batasan pembuatan aplikasi ini adalah:
sistemnya menggunakan `PHP laravel`@8.^ * dan frontendnya `Vue JS`@2.^ *
dan database awalnya menggunakan SQL dimana localnya `Mysql` dan productionnya `PostgreSql`

Untuk sementara hanya menyediakan formulirnya saja

_*) melambangkan versi_



# _UserFlow_

Jadi _user flow_ ini artinya alur yang akan dilalui oleh pengguna baik pengguna umum, pengguna member, dan pengguna admin dan pengembang

## Pengguna

1. Pengguna dapat mengunjungi halaman awal yang langsung tersedia formulir masalah mahasiswa semester akhir tersebut
2. Pengguna juga ingin dapat melihat data pengguna yang sudah terkumpul pada aplikasi, dengan begini pengguna akan lebih mempercayai aplikasi
3. pengguna juga ingin dapat melihat informasi pertanggungjawaban atas data yang diberikan, dengan begitu pengguna akan lebih yakin datanya akan aman
4. pengguna dapat mengubah atau menghapus data yang pernah diinputnya
5. pengguna dapat memberikan saran dan masukan terhadap aplikasi
6. pengguna dapat menginputkan data secara anonim
7. pengguna ingin mendapatkan solusi atau rekomendasi secara otomatis dari masalahnya, jika masalahnya adalah masalah umum, misalkan sistem merekomendasikan si pengguna atau iklan yang ada pada sistem
8. pengguna juga dapat melihat kontak penanggung jawab agar dapat menghubungi
9. Pengguna dapat membuat story
10. Pengguna dapat menginput formulir secara anonim

## Admin

1. Admin dapat melihat dan mengelola data yang diinput oleh pengguna
2. Admin dapat menambah moderator
3. Admin dapat mengelola kotak saran
4. Admin dapat dapat login menggunakan google OAuth

# Developer

## Kontribusi

Kamu juga bisa bergabung dalam pengembangan aplikasi ini:

### Sebelum memulai

dengan memahami SALAH SATU dasar dibawah:

`Git` (agar dapat berkolaborasi dengan repository ini) 

1. `PHP`
2. `CSS` atau pre-pocessor css `SASS` / `SCSS`
3. `HTML`
4. `Javascript`
5. Konsep `MVC` (_Model_, _View_, _Controller_)
6. `Laravel`
7. `Vue`
8. `Composer` dan Package Manager NodeJs (npm)
9. Konsep `PBO` (Pemrograman berorientasi objek)

dengan alat dan bahan:

1. Komputer kamu sudah terinstall Composer
2. Komputer kamu sudah terinstall Git
3. Komputer kamu sudah terinstall `PHP`@7.3.* dan `Mysql` atau `XAMPP` terbaru <small>_(sejak 10 juli 2021)_</small>
4. Komputer kamu sudah terinstall `NodeJs` (Opsional, kalau kamu tidak ingin mengubah bagian viewnya atau _frontend_-nya)
5. Texteditor apa saja

### Memulai

untuk memulai project ini di perangkat atau komputer kamu

1. buka cmd atau command line

tentukan lokasi projectnya akan diletakan:
dengan perintah:

```cli
$ cd /lokasi/project/project/kamu
```

atau jika kamu pengguna windows dan tidak familiar dengan perintah cmd dapat melakukannya dengan cara,
buka folder project kamu pada bagian address bar explorer ketikan:

```cli
cmd
```

2. clone project ini ke perangkat kamu

ketikan perintah ini pada cmd yang sedang terbuka

**copy atau ketik tanpa `$`
```cli
$ git clone https://github.com/agriedd/semesterakhir.git semesterakhir
```
tunggu sampai prosesnya berakhir (proses ini membutuhkan koneksi internet)

3. masuk kedalam file project pada cmd

ketikan perintah:
```cli
$ cd semesterakhir
```

4. install package php
```cli
$ composer install
```
5. copy .env.example ke .env

copy berkas `.env.example` dan paste sebagai berkas dengan nama yang berbeda yaitu: `.env`

6. generate key
```cli
$ php artisan key:generate
```

7. storage link
```cli
$ php artisan storage:link
```

8. konfigurasi .env

buka dan ubah file .env


