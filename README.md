# 🌍 Peta Jalan Desa Tanimulya, Kecamatan Ngamprah, Kabupaten Bandung Barat

## 📌 Deskripsi Proyek
Repositori ini berisi data **GeoJSON** yang merepresentasikan **jaringan jalan (LineString)** di wilayah **Desa Tanimulya, Kecamatan Ngamprah, Kabupaten Bandung Barat**.  
File ini dibuat sebagai bagian dari tugas pemetaan digital yang berfokus pada visualisasi **infrastruktur jalan** dalam satu wilayah administrasi (desa/kelurahan) menggunakan format **GeoJSON**.

Tujuan utama dari proyek ini adalah untuk memetakan jalan-jalan utama di Desa Tanimulya dalam format standar terbuka yang dapat digunakan pada berbagai platform GIS (seperti QGIS, ArcGIS, atau Leaflet JS).

---

## 🗺️ Detail Dataset

- **Nama Wilayah:** Desa Tanimulya  
- **Kecamatan:** Ngamprah  
- **Kabupaten:** Bandung Barat  
- **Provinsi:** Jawa Barat  
- **Tipe Data:** GeoJSON (FeatureCollection)  
- **Jenis Geometri:** LineString (Poliline)  
- **Jumlah Jalan:** 6 ruas jalan  
- **Koordinat Sistem:** WGS84 (EPSG:4326)

---

## 🧭 Metodologi Pembuatan

1. **Identifikasi Wilayah:**  
   Menentukan batas administratif Desa Tanimulya berdasarkan peta resmi dari BPS dan Google Maps.

2. **Pengambilan Data Koordinat:**  
   Koordinat jalur jalan diambil dengan bantuan **Google Maps** dan **OpenStreetMap**.

3. **Pembuatan GeoJSON:**  
   Jalur jalan dikonversi ke format **GeoJSON** dengan tipe geometri `LineString` menggunakan QGIS dan editor GeoJSON.io.

4. **Validasi Data:**  
   Data diuji dengan membuka file di QGIS untuk memastikan garis sesuai dengan jalur sebenarnya dan format valid sesuai standar GeoJSON.

---

## 📁 Struktur Repository

