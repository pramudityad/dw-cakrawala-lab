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

## Panduan bacaan

Buku utama: Kazil & Jarmul (2016), *Data Wrangling with Python* (O'Reilly). Catatan penting:
buku ini ditulis sebelum pandas jadi standar — Ch. 1–8 pakai Python murni, Ch. 9 pakai agate —
jadi gunakan bersama McKinney (2022), *Python for Data Analysis* (3rd ed.) untuk bagian pandas.

| Sesi | Topik | Kazil & Jarmul | McKinney (pandas) |
| :---: | :---- | :---- | :---- |
| 1 | Pengantar wrangling & pipeline | Preface, Ch. 1 | — |
| 2 | Tabular + pandas dasar | Ch. 2–3 | Ch. 5 |
| 3 | Outlier & duplikasi | Ch. 7, 9 | Ch. 5+ |
| 4 | Missing data | Ch. 7 (tipis) | Ch. 5+ |
| 5 | Normalisasi, scaling, encoding | Ch. 8 | Ch. 7 |
| 6 | Reshaping (pivot, melt, stack/unstack) | — | Ch. 8 |
| 7 | String & datetime | Ch. 7 (*RegEx*), Ch. 2 | Ch. 11 |
| 9 | Join, merge, concat | Ch. 9 (join, agate) | Ch. 8 |
| 10 | Agregasi & group-by | Ch. 9 | Ch. 10 |
| 11 | Integrasi CSV, JSON, API, basis data | Ch. 3–6, 13 (11–12 opsional) | — |
| 12 | Validasi & kualitas data | Ch. 6, 7 | — |
| 13 | Otomasi alur persiapan | Ch. 8, 14 | — |
| 14 | Reproducibility & dokumentasi | Ch. 8 (*Testing*), Ch. 9 | — |
| 15 | Studi kasus end-to-end | Ch. 6 (case studies), Ch. 10, 15 | — |

Kode resmi gratis semua bab buku: [jackiekazil/data-wrangling](https://github.com/jackiekazil/data-wrangling)
(per-chapter + dataset; sebagian script perlu penyesuaian versi library).

## Referensi

- Kazil, J., & Jarmul, K. (2016). *Data Wrangling with Python*. O'Reilly Media.
- McKinney, W. (2022). *Python for Data Analysis* (3rd ed.). O'Reilly Media.
