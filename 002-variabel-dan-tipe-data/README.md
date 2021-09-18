# Variabel dan Tipe Data

## Pengertian

Variabel adalah nama yang terkait dengan lokasi memori di komputer, tempat kita dapat menyimpan suatu nilai/data yang dapat direkayasa.
Data yang disimpan memiliki berbagai macam tipe sesuai dengan perannya masing-masing. Berikut adalah tipe data yang di Javascript:
1. Number -> Untuk menyimpan data angka.
2. String -> Untuk menyimpan data karakter.
3. Boolean -> Untuk menyimpan data benar dan tidak (`true`/`false`).
4. Object -> Untuk menyimpan data objek.
5. Function -> Untuk menyimpan data fungsi.
6. undefined -> Untuk menyimpan data undefined.

## Proses Pembuatan Variabel
Terdapat tiga tahap untuk membuat variabel, yaitu:
1. Deklarasi -> Mendaftarkan variabel ke dalam lingkup yang sesuai.
2. Inisialisasi -> Menyediakan memori untuk variabel.
3. Assignment -> Menetapkan nilai yang spesifik ke dalam variabel.

Contoh:
```javascript
var x; // deklarasi & inisialisasi
x = 10; // assignment
```

## Deklarasi Variabel
Pada javascript, terdapat tiga keyword yang bisa digunakan untuk deklarasi variabel. Keyword itu adalah:
1. var -> Sebaiknya tidak digunakan lagi.
2. const -> Digunakan jika data dari variabel tersebut tidak diubah.
3. let -> Digunakan jika data dari variabel tersebut akan diubah.

Format penulisan deklarasi variabel:
```javascript
var ga boleh pake spasi;
var 1gaboleh;
var boleh1;
var ini_juga_boleh;
var boleh$;
var $_$;
var iniBolehBanget;
var break; // Ini tidak boleh, karena keyword adalah reserved word.
```

## Operator
Terdapat beberapa jenis operator pada javascript, yaitu:
1. Aritmatika -> Operasi matematika (`+`, `-`, `*`, `/`, `%`).
2. Penugasan -> Operasi assignment (`=`, `+=`, `-=`, `*=`, `/=`, `%=`).
3. Perbandingan -> Untuk membanding dua nilai (`==`. `!=`, `===`, `!===`, `>`, `<`, `>=`, `<=`).
4. Logika -> Untuk menentukan logika dari beberapa ekspresi (`&&`, `||`, `!`).
5. String -> Untuk menggabungkan dua buah string (`+`).
6. Kondisional -> Untuk melakukan pengecekan pada sebuah kondisi dan menentukan nilai yang dihasilkan jika kondisinya bernilai `true` atau `false`.
7. Typeof -> Untuk melihat tipe data dari sebuah variabel/nilai (`typeof`).

