DESKRIPSI PROJECT PELATIHAN 2

Judul: Klasifikasi Citra Satelit dan Visualisasi Spasial

Dalam mini project ini, peserta melakukan analisis spasial terhadap citra satelit wilayah Jakarta dengan dua pendekatan: klasifikasi berbasis machine learning (Random Forest) dan 
segmentasi berbasis unsupervised learning (K-Means). 

Tujuannya adalah untuk memetakan risiko atau tutupan lahan secara lebih informatif dan interaktif.

Proyek ini mencakup empat tahapan utama:

1. Klasifikasi Spasial: Melatih model Random Forest menggunakan data vektor (shapefile) dan menghasilkan peta prediksi kategori.
2. Segmentasi Citra: Menerapkan algoritma K-Means pada citra Landsat untuk membentuk wilayah homogen berdasarkan spektral.
3. Visualisasi Interaktif: Menggabungkan hasil klasifikasi dan segmentasi dalam peta interaktif menggunakan Folium.
4. Evaluasi & Analisis: Mengevaluasi performa model Random Forest dan membandingkannya dengan hasil segmentasi K-Means.


Data yang digunakan:

• Data supervised - random forest : processed_jkt.shp

• Data unsupervised - kmeans :landsat8_dki_jakpus_2017.tif
