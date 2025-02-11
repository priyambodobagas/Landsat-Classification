# Klasifikasi Citra Landsat 8 dengan QGIS

## Deskripsi
Proyek ini melakukan klasifikasi citra Landsat 8 untuk mengidentifikasi berbagai kelas penggunaan lahan seperti badan air, vegetasi, pemukiman, dan lahan terbuka menggunakan Quantum GIS (QGIS). Data citra diunduh dari USGS dan diproses untuk menghasilkan peta klasifikasi.

## Struktur Folder
```
📂 Landsat-Classification
├── 📂 data                # Berisi citra Landsat 8 yang digunakan
├── 📂 results             # Hasil klasifikasi dalam format raster/vector
└── README.md              # Informasi tentang proyek
```

## Langkah-langkah
1. **Unduh Data** - Citra Landsat 8 diperoleh dari USGS Earth Explorer.
2. **Preprocessing** - Melakukan pemotongan area studi.
3. **Klasifikasi** - Menggunakan metode klasifikasi di QGIS (SCP-Plugin) untuk membagi area ke dalam beberapa kelas. Algoritma Minimum Distance.
4. **Analisis Hasil** - Mengevaluasi hasil klasifikasi.

## Data Raster
Karena ukuran file yang besar, data raster dapat diunduh dari Google Drive:

📥 [clipped_landsat.tif](https://drive.google.com/file/d/1jACIEIdI0-crveHz-7mDBw2VR-ESx-2g/view?usp=sharing)

## Hasil
- Peta klasifikasi dalam format raster dan vektor.

## 📹 Video
[![Tonton di YouTube](https://img.youtube.com/vi/QQjrBBhSGtA/0.jpg)](https://www.youtube.com/watch?v=QQjrBBhSGtA)

## Cara Menggunakan Repository Ini
1. Clone repository ini dengan perintah:
   ```sh
   git clone <URL_REPO>
   ```
2. Buka folder proyek dan akses data hasil klasifikasi.
3. Gunakan QGIS untuk melihat dan menganalisis hasil klasifikasi.
