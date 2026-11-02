# Tugas Hands-On 3 – Pandas Lanjutan

## Identitas Mahasiswa

- **Nama:** Nazwa Khoerunnisa
- **NIM:** 23552011093
- **Mata Kuliah:** Artificial Intelligence
- **Studi Kasus:** #05 Employee Attrition (HR Analytics)

## Deskripsi Tugas

Tugas Hands-On 3 ini merupakan penerapan materi Pandas Lanjutan untuk melakukan pengolahan dan analisis data menggunakan Python. Pengerjaan meliputi proses membaca dataset, memeriksa kualitas data, melakukan pembersihan data, menganalisis informasi yang terdapat dalam dataset, serta mempersiapkan data untuk kebutuhan pemodelan *machine learning*.

## Studi Kasus yang Dipilih

Studi kasus yang dipilih adalah **Employee Attrition (HR Analytics)** dengan dataset `case5_employee_attrition.csv` yang terdiri dari 1.200 baris data.

Kasus ini membahas data karyawan untuk mengidentifikasi status *attrition*, yaitu apakah seorang karyawan keluar dari perusahaan atau tetap bekerja.

- **Jenis permasalahan:** Klasifikasi biner
- **Kolom target:** `keluar_perusahaan`
- **Keterangan target:** Ya = keluar, Tidak = bertahan

## Tahapan Pengerjaan

Beberapa tahapan yang dilakukan dalam tugas ini meliputi:

1. Memuat dataset dan melihat informasi awal menggunakan `shape`, `info()`, dan `describe()`.
2. Melakukan pemeriksaan kualitas data, meliputi duplikasi, missing value, outlier, dan tipe data.
3. Melakukan pembersihan data berdasarkan hasil pemeriksaan.
4. Melakukan analisis data menggunakan `groupby`, transformasi data, dan pivot table untuk memperoleh temuan terkait employee attrition.
5. Melakukan persiapan data untuk pemodelan menggunakan pembagian data latih dan data uji, serta `ColumnTransformer`.
6. Menyimpan hasil pengolahan data dan laporan kualitas data dalam format CSV.

## Link Google Colab

Notebook pengerjaan dapat diakses melalui tautan berikut:

[**Buka Notebook Tugas Hands-On 3 – Employee Attrition**](https://colab.research.google.com/drive/1L3vsU1b6mBMZUOvHMZelV2gM26IPz0hv#scrollTo=ed5a99bd)

## Struktur Folder Pengumpulan

```text
tugas-hands-on-3/
├── README.md
├── notebook.ipynb
├── data/
│   └── case5_employee_attrition.csv
├── output/
│   ├── data_bersih.csv
│   └── kamus_data.csv
└── laporan_kualitas.csv
```

## Keterangan File

- **README.md**: Berisi identitas, deskripsi tugas, studi kasus yang dipilih, dan informasi pengerjaan.
- **notebook.ipynb**: File notebook yang berisi kode dan proses pengerjaan menggunakan Google Colab.
- **data/**: Berisi dataset asli yang digunakan dalam pengerjaan.
- **output/**: Berisi hasil pembersihan data dan kamus data.
- **laporan_kualitas.csv**: Berisi laporan perbandingan kualitas data sebelum dan sesudah proses pembersihan.

---

**Tugas Hands-On 3 – Pandas Lanjutan**  
Studi Kasus #05 Employee Attrition (HR Analytics)