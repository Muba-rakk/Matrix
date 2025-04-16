# Matrix Multiplication - Tugas Kuliah

Repositori ini dibuat untuk memenuhi tugas kuliah yang berkaitan dengan operasi dasar dalam pemrograman Python, khususnya pada topik **perkalian matriks**.

## Deskripsi

File `matrix.py` berisi implementasi sederhana dari perkalian dua matriks berukuran 5x5. Matriks `A` dan `B` didefinisikan secara manual, kemudian dilakukan proses perkalian menggunakan tiga lapis `for-loop` untuk menghasilkan matriks hasil `C`.

### Struktur Matriks
- `A`: Matriks pertama berukuran 5x5
```python
A = [
    [1, 2, 3, 4, 5],
    [5, 4, 3, 2, 1],
    [1, 3, 5, 7, 9],
    [9, 7, 5, 3, 1],
    [2, 4, 6, 8, 0]
]
```
- `B`: Matriks kedua berukuran 5x5
```python
B = [
    [0, 1, 2, 3, 4],
    [4, 3, 2, 1, 0],
    [1, 0, 1, 0, 1],
    [1, 2, 3, 4, 5],
    [5, 4, 3, 2, 1]
]
```
- `C`: Hasil dari perkalian matriks `A` dan `B`
```python
C = [
    [38, 48, 58, 68, 78],
    [38, 42, 46, 50, 54],
    [86, 72, 76, 72, 76],
    [74, 70, 66, 62, 58],
    [52, 56, 60, 64, 68]
]
```

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
