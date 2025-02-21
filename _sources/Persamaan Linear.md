---
title: Persamaan Linear

---

# Sistem Persamaan Linear
## Definisi Sistem Persamaan Linear
Persamaan linear adalah persamaan yang jika digambarkan pada koordinat kartesius akan berbentuk garis lurus. Apabila terdapat lebih dari satu persamaan linear, maka inilah definisi sistem persamaan linear dan rumusnya dipelajari dalam pelajaran Matematika.

Ada dua sistem persamaan linear, yakni sistem persamaan linear dua variabel dan sistem persamaan linear tiga variabel. Sistem persamaan linear dua variabel dapat diselesaikan dengan metode substitusi, eliminasi, campuran antara eliminasi dan substitusi, serta metode grafik.

Rumus atau bentuk umumnya adalah 
ax + by = c, atau ax + by + c = 0.

Keterangan:
a = koefisien dari x

b = koefisien dari y

x dan y = variabel

c = konstanta

Dalam persamaan linear berlaku sifat-sifat persamaan linear sebagai berikut:
1. Nilai persamaan tidak berubah apabila:
Kedua ruas ditambah atau dikurangi dengan bilangan yang sama.
Kedua ruas dikalikan atau dibagi dengan bilangan yang sama.
2. Jika suatu persamaan dipindah ruas, maka:
Penjumlahan berubah menjadi pengurangan.
Perkalian berubah menjadi pembagian.
Berikut ini adalah contoh penerapan sistem persamaan linear dua variabel dalam soal matematika.
Tentukan himpunan penyelesaian sistem persamaan linear berikut menggunakan metode substitusi.

2x + y = 6

3x + y = 4

Langkah 1:

Pilih salah satu persamaan kemudian nyatakan y dalam x.

2x + y = 6, maka y = 6 - 2x

Langkah 2:

Substitusikan y yang diperoleh pada langkah 1 ke persamaan 2.

y = 6 - 2x disubstitusikan ke persamaan 3x + 4y = 4

Maka,

3x + 4y = 4

3x + 4 (6 - 2x) = 4

3x + 24 - 8x = 4

-5x = -20

x = 4

Setelah x diketahui, maka mari temukan nilai y.

y = 6 - 2x

y = 6 - 2 (4)

y = 6 - 8

y = -2

## Solusi Persamaan Linier
### Metode eliminasi
Metode ini bekerja dengan care mengeliminasi (menghilangkan) variabel-variabel di dalam sistem persamaan hingga hanya satu variabel yang tertinggal.

Pertama-tama, lihat persamaan-persamaan yang ada dan coba cari dua persamaan yang mempunyai koefisien yang sama (baik positif maupun negatif) untuk variabel yang sama. Misalnya, lihat persamaan (1) dan (3).Koefisien untuk y adalah 1 dan −1 untuk masing-masing persamaan. Kita dapat menjumlah kedua persamaan ini untuk menghilangkan y dan kita mendapatkan persamaan (4).

![Screenshot 2025-02-18 101749](https://hackmd.io/_uploads/rkN63OWq1l.png)

Perhatikan bahwa persamaan (4) terdiri atas variabel x dan z. Sekarang kita perlu persamaan lain yang terdiri atas variabel yang sama dengan persamaan(4).Untuk mendapatkan persamaan ini, kita akan menghilangkan y dari persamaan (1)dan (2). Dalam persamaan (1) dan (2), koefisien untuk y adalah 1 dan 3 masing-masing. Untuk menghilangkan y, kita kalikan persamaan (1) dengan 3 lalu mengurangkan persamaan (2) dari persamaan (1).

![Screenshot 2025-02-18 103003](https://hackmd.io/_uploads/r1AAA_b51x.png)

Dengan persamaan (4) dan (5), mari kita coba untuk menghilangkan z.

![Screenshot 2025-02-18 103250](https://hackmd.io/_uploads/rkkFyFW91e.png)

Dari persamaan (6) kita dapatkan x = 2. Sekarang kita bisa subtitusikan (masukkan) nilai dari x ke persamaan (4) untuk mendapatkan nilai z.

![Screenshot 2025-02-18 103434](https://hackmd.io/_uploads/H1001YW9ye.png)

Akhirnya, kita substitusikan (masukkan) nila dari x dan z ke persamaan (1) untuk mendapatkan y.

![Screenshot 2025-02-18 103559](https://hackmd.io/_uploads/SyZElKb5Jx.png)

Jadi solusi sistem persamaan linier di atas adalah x = 2, y = 3, z = 4.

### Eliminasi Gauss / Eliminasi Gauss-Jordan
Sistem persamaan liniear yang terdiri atas persamaan-persamaan (1), (2) dan (3) dapat juga dinyatakan dalam bentuk matriks teraugmentasi seperti berikut

![Screenshot 2025-02-18 103827](https://hackmd.io/_uploads/HyhplY-5yg.png)

Dengan melakukan serangkaian operasi baris (Eliminasi Gauss), kita dapat menyederhanakan matriks di atas untuk menjadi matriks Eselon-baris.

![Screenshot 2025-02-18 103919](https://hackmd.io/_uploads/ryvgWFbcye.png)

Kemudian kita bisa substitusikan kembali nilai-nilai yang kita dapat untuk mencari nilai dari semua variabel. Atau, kita juga bisa meneruskan dengan serangkaian operasi baris lagi sehingga matriks di atas menjadi matriks yang Eselon-baris tereduksi (dengan menggunakan Eliminasi Gauss-Jordan).

![Screenshot 2025-02-18 104001](https://hackmd.io/_uploads/HyX7-K-5kl.png)

Dengan melakukan operasi Eliminasi Gauss-Jordan, kita mendapatkan solusi dari sistem persamaan linier di atas pada kolom terakhir: 
x = 2, y = 3, z = 4 .

### Metode grafik
Penyelesaian sistem persamaan linier dengan metode grafik dilakukan dengan cara menggambar garis garis atau bidang planar yang merupakan representasi dari persamaan-persamaan yang ada dalam sistem tersebut. Solusinya adalah koordinat-koordinat yang merupakan titik potong dari garis-garis ataupun bidang-bidang planar itu.

Sebagai contoh, marilah kita lihat sistem persamaan liniear dengan dua variabel berikut ini.

![Screenshot 2025-02-18 104235](https://hackmd.io/_uploads/Bkb6WKWckx.png)

Gambar kedua garis dari persamaan-persamaan di atas.![slm2vargraph](https://hackmd.io/_uploads/Hk7gzYWqke.gif)

Seperti terlihat pada grafik di atas, kedua garis itu bertemu (mempunyai titik potong) pada titik (0,3). Ini adalah solusi dari sistem persamaan linier tersebut, yaitu x = 0, y = 3.

Untuk persamaan linier dengan tiga variabel, solusinya adalah titik pertemuan dari tiga bidang planar dari masing-masing persamaan.

