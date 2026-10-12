# Pertemuan 07 Fungsi Python
Nama: Hitana Rifa Pranaja

NIM: 2225250077

Kelas: 3A

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular

## Cara Menjalankan Program
### Latihan
```bash
python3 latihan/01_salam.py
python3 latihan/02_luas_persegi_panjang.py
python3 latihan/03_jumlah_n.py
python3 latihan/04_statistik_sederhana.py
python3 latihan/05_scope.py
```
### Praktik
```bash
python3 praktik/utilitas_matematika.py
```

## Struktur Fungsi

1. `luas_persegi_panjang(p, l)`: Menghitung luas persegi panjang dengan mengalikan panjang dan lebar, lalu mengembalikan hasilnya.
2. `luas_segitiga(a, t)`: Menghitung luas segitiga dengan rumus 0.5 × alas × tinggi, lalu mengembalikan hasilnya.
3. `jumlah_n(n)`: Menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan `for`, lalu mengembalikan hasilnya.
4. `faktorial(n)`: Menghitung faktorial bilangan n menggunakan perulangan `for`, lalu mengembalikan hasilnya.
5. `tampilkan_menu()`: Menampilkan pilihan operasi matematika kepada pengguna.
6. **Program utama**: Menerima pilihan dan input pengguna, memanggil fungsi sesuai pilihan, memvalidasi input jumlah dan faktorial agar bilangan bulat nonnegatif, serta menampilkan hasil perhitungan.

## Hasil Pengujian

| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40 | Berhasil |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Berhasil |
| Jumlah 1 sampai n | n=10 | 55 | 55 | Berhasil |
| Faktorial | n=5 | 120 | 120 | Berhasil |
| Faktorial | n=0 | 1 | 1 | Berhasil |

## Refleksi

Bagian perhitungan luas persegi panjang menjadi lebih sederhana karena rumusnya dipisahkan ke fungsi luas_persegi_panjang(p, l). Program utama hanya perlu memanggil fungsi tersebut tanpa menulis ulang rumus perhitungannya.

## Sumber
- Bahan_Ajar_Pertemuan_07
- chatGPT ai
