# PENJELASAN PROGRAM SPLTV METODE ELIMINASI GAUSS

## 1. Tujuan Program

Program ini dibuat untuk menyelesaikan Sistem Persamaan Linear Tiga Variabel (SPLTV) menggunakan bahasa pemrograman Python dengan metode Eliminasi Gauss.

## 2. Cell 1 – Judul Program

Kode ini digunakan untuk menampilkan judul program dan identitas mata kuliah.

- `print()` digunakan untuk menampilkan tulisan.
- Garis tanda sama dengan digunakan sebagai pembatas tampilan.
- Nama program ditampilkan agar pengguna mengetahui program yang dijalankan.

## 3. Cell 2 – Memasukkan Matriks

Kode ini digunakan untuk memasukkan koefisien persamaan ke dalam matriks A dan hasil persamaan ke dalam matriks B.

- `A` menyimpan koefisien variabel X, Y, dan Z.
- `B` menyimpan hasil dari setiap persamaan.
- `for baris in A` digunakan untuk menampilkan setiap baris matriks A.
- `print(B)` digunakan untuk menampilkan matriks B.

Persamaan yang digunakan:

1. 2x + y + z = 10
2. x + 2y + z = 11
3. x + y + 2z = 12

## 4. Cell 3 – Proses Eliminasi Gauss

Kode ini digunakan untuk mengubah matriks menjadi bentuk segitiga atas.

- `M` merupakan salinan matriks A.
- `H` merupakan salinan matriks B.
- `n` digunakan untuk menentukan jumlah variabel.
- `for i in range(n)` digunakan untuk melakukan proses eliminasi.
- `if M[i][i] == 0` digunakan untuk memeriksa apakah nilai pivot sama dengan nol.
- `faktor` digunakan untuk menghitung pengali dalam proses eliminasi.
- `M[j][k] -= faktor * M[i][k]` digunakan untuk menghilangkan nilai di bawah pivot.
- `H[j] -= faktor * H[i]` digunakan untuk memperbarui hasil persamaan.

## 5. Cell 4 – Substitusi Mundur

Kode ini digunakan untuk mencari nilai variabel X, Y, dan Z dari baris paling bawah menuju baris paling atas.

- `hasil = [0.0] * n` digunakan untuk menyediakan tempat penyimpanan hasil variabel.
- `for i in range(n - 1, -1, -1)` digunakan untuk menghitung dari bawah ke atas.
- `jumlah` digunakan untuk menyimpan hasil penjumlahan variabel yang sudah diketahui.
- Rumus `(H[i] - jumlah) / M[i][i]` digunakan untuk mendapatkan nilai variabel.

## 6. Cell 5 – Menampilkan Hasil

Kode ini digunakan untuk menampilkan hasil akhir perhitungan.

- `hasil[0]` menampilkan nilai X.
- `hasil[1]` menampilkan nilai Y.
- `hasil[2]` menampilkan nilai Z.
- `print()` digunakan untuk menampilkan hasil ke layar.

## 7. Hasil Akhir

Berdasarkan perhitungan menggunakan metode Eliminasi Gauss, diperoleh:

- X = 2
- Y = 3
- Z = 4

Dengan demikian, program SPLTV berhasil dijalankan dan menghasilkan nilai yang memenuhi ketiga persamaan.

## 8. Kesimpulan

Metode Eliminasi Gauss dapat digunakan untuk menyelesaikan Sistem Persamaan Linear Tiga Variabel. Dengan bantuan Python, proses perhitungan dapat dilakukan secara sistematis dan hasilnya dapat ditampilkan secara otomatis.
