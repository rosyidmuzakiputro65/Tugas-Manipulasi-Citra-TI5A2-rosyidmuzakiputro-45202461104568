# Tugas-Manipulasi-Citra-TI5A2-rosyidmuzakiputro-45202461104568


* **Mata Kuliah:** Pengolahan Sinyal Digital
* **Topik Eksperimen:** Operasi Spasial, Point Processing, & Perbaikan Kualitas Citra

## 📝 Deskripsi Singkat Project
Project ini memuat implementasi teknik dasar manipulasi citra menggunakan Python 3, OpenCV, NumPy, dan Matplotlib sesuai dengan panduan tugas individu. Eksperimen meliputi perubahan ruang warna BGR ke RGB, penataan dimensi gambar (resize), teknik pencampuran (image blending), pembalikan kontras (image negative), serta pemetaan intensitas non-linear menggunakan fungsi Logaritma dan Gamma (Power-Law).

## 🛠️ Library yang Digunakan
* `opencv-python` (OpenCV)
* `numpy`
* `matplotlib`

## 🚀 Cara Menjalankan Notebook
1. Pastikan seluruh library telah terinstal:
   ```bash
   pip install -r requirements.txt
   ```
2. Jalankan server jupyter atau buka melalui Google Colab:
   ```bash
   jupyter notebook
   ```
3. Buka file `notebook/image_manipulation.ipynb` dan eksekusi seluruh sel kode dari atas ke bawah.

## 📂 Struktur Folder Proyek
```text
manipulasi-citra-digital/
├── notebook/
│   └── image_manipulation.ipynb
├── images/
│   ├── image1.jpg
│   └── image2.jpg
└── report/
    ├── laporan.pdf
    ├── README.md
    └── requirements.txt
```

## 📊 Kesimpulan Singkat
Eksperimen menunjukkan bahwa operasi matematis sederhana pada tingkat pixel dapat mengubah karakteristik visual citra secara drastis. Transformasi non-linear (Log dan Gamma) sangat efektif untuk koreksi pencahayaan (menerangkan area gelap atau menekan area overexposure) secara jauh lebih fleksibel dibandingkan operasi linear biasa.
