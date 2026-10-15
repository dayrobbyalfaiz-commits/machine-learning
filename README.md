# Praktikum Machine Learning - Data Loading

## Deskripsi
Project ini dibuat untuk memenuhi tugas praktikum mata kuliah Machine Learning.
Pada praktikum ini dilakukan proses Data Loading menggunakan Python dan library Pandas.

Dataset yang digunakan adalah dataset Housing Price dengan file:
- train.csv
- test.csv

## Tujuan
- Memahami proses Data Loading menggunakan Python.
- Mengetahui cara membaca file CSV menggunakan Pandas.
- Memahami struktur dan isi dataset.
- Mengetahui jumlah data dan kolom pada dataset.
- Mempersiapkan dataset untuk proses pengolahan selanjutnya.

## Tools yang Digunakan
- Python
- Pandas
- Jupyter Notebook / VS Code

## Proses Praktikum
1. Mengimport library Pandas.
2. Membaca file `train.csv`.
3. Membaca file `test.csv`.
4. Menampilkan beberapa data awal menggunakan `head()`.
5. Mengecek jumlah baris dan kolom dataset.
6. Mempersiapkan dataset untuk tahap analisis dan pengolahan data selanjutnya.

## Contoh Kode

```python
import pandas as pd

train = pd.read_csv("train.csv")
test = pd.read_csv("test.csv")

print("Jumlah data train:", len(train))
print("Jumlah data test:", len(test))

print("Jumlah kolom train:", len(train.columns))
print("Jumlah kolom test:", len(test.columns))

print(train.head())
print(test.head())
