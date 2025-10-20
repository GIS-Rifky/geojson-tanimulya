# 🌍 Peta Jalan Desa Tanimulya, Kecamatan Ngamprah, Kabupaten Bandung Barat

## 📌 Deskripsi Proyek

Repositori ini berisi data **GeoJSON** yang merepresentasikan **jaringan jalan (LineString)** di wilayah **Desa Tanimulya, Kecamatan Ngamprah, Kabupaten Bandung Barat**.  
File ini dikembangkan sebagai bagian dari tugas pemetaan digital yang berfokus pada **visualisasi infrastruktur jalan desa** menggunakan format terbuka **GeoJSON**, yang kompatibel dengan berbagai perangkat lunak GIS seperti **QGIS**, **ArcGIS**, atau **Leaflet JS**.

Tujuan utama proyek ini adalah menyediakan dataset terbuka yang menggambarkan kondisi dan jaringan jalan utama di Desa Tanimulya.

---

## 🗺️ Detail Dataset

| Atribut              | Keterangan        |
| -------------------- | ----------------- |
| **Nama Wilayah**     | Desa Tanimulya    |
| **Kecamatan**        | Ngamprah          |
| **Kabupaten**        | Bandung Barat     |
| **Provinsi**         | Jawa Barat        |
| **Tipe Data**        | GeoJSON           |
| **Jenis Geometri**   | LineString        |
| **Jumlah Jalan**     | 6 ruas jalan      |
| **Sistem Koordinat** | WGS84 (EPSG:4326) |

---

## 🚗 Daftar Ruas Jalan

Berdasarkan data `map.geojson`, terdapat **6 ruas jalan** utama yang dipetakan, yaitu:

1. Jl. H. Gofur  
2. Jl. Cibuntu  
3. Jl. Dirawinata  
4. Jl. Somawinata  
5. Jl. Puri Cipageran Indah 2  
6. Jl. Bumi Pakusarakan  

> Setiap fitur memiliki atribut `name` yang menyimpan nama jalan.

---

## 🧭 Metodologi Pembuatan

1. **Identifikasi Wilayah:**  
   Batas administratif Desa Tanimulya ditentukan berdasarkan peta resmi BPS dan Google Maps.

2. **Pengambilan Data Koordinat:**  
   Jalur jalan direkam menggunakan **Google Maps** dan **OpenStreetMap** sebagai referensi.

3. **Pembuatan GeoJSON:**  
   Jalur dikonversi ke format **GeoJSON** bertipe `LineString` menggunakan **QGIS** dan **GeoJSON.io**.

4. **Validasi Data:**  
   File diuji pada QGIS untuk memastikan setiap garis sesuai dengan posisi jalan sebenarnya dan struktur file valid.