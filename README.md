# Matrix Multiplication - Tugas Kuliah

Repositori ini dibuat untuk memenuhi tugas kuliah yang berkaitan dengan operasi dasar dalam pemrograman Python, khususnya pada topik **perkalian matriks**.

## Deskripsi

File `matrix.py` berisi implementasi sederhana dari perkalian dua matriks berukuran 5x5. Matriks `A` dan `B` didefinisikan secara manual, kemudian dilakukan proses perkalian menggunakan tiga lapis `for-loop` untuk menghasilkan matriks hasil `C`.

### Struktur Matriks
- `A`: Matriks pertama berukuran 5x5
- `B`: Matriks kedua berukuran 5x5
- `C`: Hasil dari perkalian matriks `A` dan `B`

### Cuplikan Kode
```python
for i in range(5):
    for j in range(5):
        for k in range(5):
            C[i][j] += A[i][k] * B[k][j]
```

## Cara Menjalankan
Pastikan Anda memiliki Python terinstal. Untuk menjalankan program:
```bash
python matrix.py
```
Program akan mencetak hasil dari perkalian dua matriks tersebut.
