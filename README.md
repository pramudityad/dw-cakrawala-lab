# Lab Praktikum — Data Wrangling (SDA2138)

Notebook praktikum mata kuliah **Data Wrangling**, Program Studi Sains Data,
Universitas Cakrawala. Satu folder per sesi.

## Isi

```
sesi05/  lab.ipynb           Transformasi data: scaling, encoding (Sesi 5)
         contoh-output.ipynb Contoh pengumpulan parsial — bukan kunci jawaban
sesi06/  lab.ipynb           Reshaping: pivot_table, melt, unstack (Sesi 6)
         contoh-output.ipynb Contoh pengumpulan parsial — bukan kunci jawaban
ecommerce_transactions.csv   Dataset latihan (sintetis, 500 baris)
```

## Cara pakai

1. Unduh `ecommerce_transactions.csv` dari repo ini.
2. Buka `sesiNN/lab.ipynb` di Google Colab (*File → Upload notebook*).
3. Unggah dataset ke Colab (ikon folder di kiri → *Upload*) sebelum menjalankan sel pertama.
4. Kerjakan sesuai arahan pengampu; kumpulkan `.ipynb` di RISE sebelum tenggat di dalam notebook.

## `contoh-output.ipynb`

Contoh notebook yang **berhenti di tengah lab** — sel awal sudah dijalankan dengan
dataset yang sama, jadi angkanya bisa dipakai untuk memeriksa pekerjaanmu. Sisanya
(tabel keputusan, langkah `pivot`/`melt`/`unstack`, pertanyaan penutup) sengaja
dikosongkan: bagian itu tugasmu. **Ini bukan kunci jawaban.**

> Catatan: contoh dicetak dengan pandas 3.x — di Colab (pandas 2.x), dtype kolom
> teks tampil `object`, bukan `str`. Isinya sama.

## Referensi

- Kazil, J., & Jarmul, K. (2016). *Data Wrangling with Python*. O'Reilly Media.
- McKinney, W. (2022). *Python for Data Analysis* (3rd ed.). O'Reilly Media.
