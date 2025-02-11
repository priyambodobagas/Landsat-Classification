# Klasifikasi Citra Landsat 8 dengan QGIS

## Deskripsi
Proyek ini melakukan klasifikasi citra Landsat 8 untuk mengidentifikasi berbagai kelas penggunaan lahan seperti badan air, vegetasi, pemukiman, dan lahan terbuka menggunakan Quantum GIS (QGIS). Data citra diunduh dari USGS dan diproses untuk menghasilkan peta klasifikasi.

## Struktur Folder
```
📂 Landsat_Classification
├── 📂 data                # Berisi citra Landsat 8 yang digunakan
├── 📂 results             # Hasil klasifikasi dalam format raster/vector
├── 📂 scripts             # Skrip pemrosesan jika ada
├── 📂 docs                # Dokumentasi dan penjelasan proyek
└── README.md              # Informasi tentang proyek
```

## Langkah-langkah
1. **Unduh Data** - Citra Landsat 8 diperoleh dari USGS Earth Explorer.
2. **Preprocessing** - Melakukan pemotongan area studi.
3. **Klasifikasi** - Menggunakan metode klasifikasi di QGIS untuk membagi area ke dalam beberapa kelas.
4. **Analisis Hasil** - Mengevaluasi hasil klasifikasi.

## Hasil
- Peta klasifikasi dalam format raster dan vektor.
- Visualisasi hasil klasifikasi di QGIS.

## 📹 Video
[![Tonton di YouTube](https://img.youtube.com/vi/QQjrBBhSGtA/0.jpg)](https://www.youtube.com/watch?v=QQjrBBhSGtA)

## Cara Menggunakan Repository Ini
1. Clone repository ini dengan perintah:
   ```sh
   git clone <URL_REPO>
   ```
2. Buka folder proyek dan akses data hasil klasifikasi.
3. Gunakan QGIS untuk melihat dan menganalisis hasil klasifikasi.
