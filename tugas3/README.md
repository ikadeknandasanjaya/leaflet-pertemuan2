# 🗺️ Tugas 3 — GeoJSON Batas Administratif Bali

> Sistem Informasi Geografis — Kamis, 02 Oktober 2025  
> Praktik: Data Geospasial dalam GeoJSON, integrasi ke Leaflet

## 🎯 Tujuan
- Memahami konsep dasar GeoJSON (Point, LineString, Polygon, Multi*, Feature, FeatureCollection)
- Mengintegrasikan file GeoJSON ke Leaflet dengan `L.geoJSON()`
- Menampilkan batas administratif (kabupaten/kecamatan) dengan style warna berbeda dan popup nama wilayah

## 🚀 Cara Menjalankan
1. Buka folder ini di komputer Anda.
2. Tempatkan file GeoJSON pada folder `geojson/`:
   - `geojson/kabupaten.geojson` — batas kabupaten di Bali
   - `geojson/kecamatan.geojson` — batas kecamatan di Bali
   (Jika nama file berbeda, silakan sesuaikan di kode `index.html` bagian `loadGeoJSON(...)`.)
3. Buka `index.html` langsung di browser, atau jalankan local server:
   ```bash
   python -m http.server 8000
   # lalu akses http://localhost:8000
   ```

## 🧭 Fitur Utama
- 2 basemap: OpenStreetMap dan Carto Light
- Overlay: Batas Kabupaten dan Batas Kecamatan (dari GeoJSON)
- Style otomatis per-wilayah menggunakan fungsi warna deterministik
- Popup pada setiap feature menampilkan nama wilayah
- Legend dinamis (subset contoh nama wilayah)

## 🗂️ Struktur Folder
```
tugas3/
├── index.html            # Halaman peta Leaflet
├── README.md             # Dokumentasi singkat
└── geojson/              # Taruh file GeoJSON di sini
    ├── kabupaten.geojson
    └── kecamatan.geojson
```

## 📥 Sumber Data
Unduh data batas administratif dari:
- Artikel: Unduh GeoJSON 38 Provinsi Indonesia  
  https://rkurniawan.blog/2025/05/01/unduh-file-geojson-batas-administrasi-pemekaran-38-provinsi-indonesia/

Catatan: Periksa lisensi/ketentuan penggunaan data. Nama atribut untuk kabupaten/kecamatan mungkin berbeda; sesuaikan `nameProp` di pemanggilan `loadGeoJSON(url, nameProp, group)`.

## 🧩 Contoh Kode Inti
```html
<script>
// Memuat GeoJSON dan menerapkan style + popup
async function loadGeoJSON(url, nameProp, targetGroup) {
  const res = await fetch(url); const data = await res.json();
  L.geoJSON(data, {
    style: f => ({ color: '#2563eb', weight: 1.5, fillOpacity: .15 }),
    onEachFeature: (f, l) => l.bindPopup(`<b>${f.properties?.[nameProp] || f.properties?.name}</b>`)
  }).addTo(targetGroup);
}
</script>
```

## 🌐 Deploy
- Upload folder ini ke Netlify/GitHub Pages (pastikan file GeoJSON ikut terupload)
- Akses langsung `index.html` secara online

Selamat mengerjakan! ✅
