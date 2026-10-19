# Implementasi Awal AI dan Citra Satelit untuk Analisis Penyebab Kehilangan Hutan di Indonesia

## Ringkasan

Proyek ini menerapkan tahap awal analisis citra satelit untuk mempelajari klasifikasi penyebab kehilangan hutan di Indonesia. Implementasi menggunakan dataset ForestNet sebagai bahan pembelajaran mengenai persiapan data citra dan klasifikasi berbasis machine learning atau deep learning.

Berbeda dengan sistem pemantauan deforestasi operasional, proyek ini berfokus pada pemeriksaan dataset dan persiapan awal untuk pengembangan model klasifikasi.

## Dataset

- **Nama:** ForestNet
- **Sumber resmi:** https://stanfordmlgroup.github.io/projects/forestnet/
- **Paper:** https://arxiv.org/abs/2011.05479
- **Wilayah data:** Indonesia.
- **Jenis data:** Citra satelit dan anotasi penyebab kehilangan hutan.
- **Kelas utama:** Plantation, Smallholder Agriculture, Grassland/Shrubland, dan Other.

Dataset digunakan untuk mempelajari hubungan antara pola visual citra satelit dan kategori penyebab kehilangan hutan.

## Tujuan

1. Mengakses dataset citra satelit dari sumber resmi.
2. Memeriksa struktur berkas, metadata, dan label.
3. Memahami distribusi kelas pada dataset.
4. Menyiapkan data citra untuk proses klasifikasi.
5. Menjelaskan rancangan pengembangan model CNN atau transfer learning.
6. Mengidentifikasi kebutuhan evaluasi dan validasi model.

## Metode dan tahapan implementasi

- Pengunduhan dan pemeriksaan dataset.
- Audit struktur data dan label.
- Pemeriksaan distribusi kelas.
- Persiapan citra dan anotasi.
- Rancangan pembagian data latih, validasi, dan uji.
- Rancangan klasifikasi menggunakan CNN atau transfer learning.
- Metrik evaluasi yang direncanakan: accuracy, macro-F1, dan confusion matrix.

## Batasan dan penggunaan yang bertanggung jawab

- Notebook saat ini berfokus pada pemeriksaan dataset dan belum menjalankan pelatihan CNN secara lengkap.
- ForestNet menggunakan citra Landsat 8, sehingga tidak boleh diklaim sebagai implementasi langsung Sentinel-1 atau Sentinel-2.
- Kategori label dataset tidak mencakup semua jenis gangguan hutan yang dibahas dalam webinar.
- Klasifikasi model tidak otomatis membuktikan penyebab deforestasi di lapangan.
- Kesalahan klasifikasi tetap mungkin terjadi; hasil analisis perlu dibandingkan dengan informasi pendukung dan validasi lapangan.
- Tidak boleh melaporkan nilai akurasi atau hasil pelatihan sebelum model benar-benar dijalankan dan dievaluasi.
