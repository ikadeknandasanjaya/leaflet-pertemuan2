# 🗺️ Peta Interaktif Batubulan - Sukawati

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

> **Tugas Praktik GIS**: Implementasi Marker, Popup, dan Layer Control dengan Leaflet.js untuk area Batubulan, Sukawati, Gianyar, Bali

## 📋 Informasi Tugas

| Detail | Keterangan |
|--------|------------|
| **Mata Kuliah** | Sistem Informasi Geografis |
| **Tugas** | Marker, Popup, dan Layer Control |
| **Tanggal** | Kamis, 18 September 2025 |
| **Durasi** | 6 hari |
| **Area Fokus** | Desa Batubulan, Kecamatan Sukawati, Gianyar |

## 🎯 Tujuan Pembelajaran

Memahami dan mengimplementasikan:
- ✅ Penambahan multiple markers dengan popup informatif
- ✅ Pembuatan polyline untuk menggambarkan jalur jalan
- ✅ Pembuatan polygon untuk area tertentu
- ✅ Implementasi layer control untuk basemap dan overlay
- ✅ Interaktivitas peta dengan event handling

## 📸 Screenshots

### Desktop View
![Desktop Screenshot](screenshots/desktop-view.png)
*Tampilan lengkap peta interaktif dengan layer control dan info panel*

### Mobile View
![Mobile Screenshot](screenshots/mobile-view.png)
*Responsive design untuk perangkat mobile*

### Layer Control
![Layer Control](screenshots/layer-control.png)
*Fitur layer control untuk mengatur basemap dan overlay*

### Popup Information
![Popup Info](screenshots/popup-info.png)
*Detail informasi lokasi dalam popup yang modern*

## ✨ Fitur Implementasi

### 🎯 **Core Features**
- **7 Interactive Markers** dengan popup detail
- **2 Basemap Options** (OpenStreetMap & Satellite)
- **Polyline Route** jalur rumah ke sekolah
- **Polygon Area** lapangan Batubulan
- **Layer Control** untuk mengatur tampilan
- **Responsive Design** untuk semua perangkat

### 🗺️ **Map Components**

#### 📍 **Markers (7 lokasi)**
| Marker | Koordinat | Jenis | Deskripsi |
|--------|-----------|--------|-----------|
| 🏠 Rumah Pribadi | -8.6104, 115.2596 | Residential | Tempat tinggal di Batubulan |
| 🏛️ Kantor Desa | -8.6125, 115.2537 | Government | Kantor Desa Batubulan |
| 🎓 SD N 6 Batubulan | -8.6112, 115.2592 | Education | Sekolah Dasar Negeri |
| 🎓 SMP N 5 Sukawati | -8.6066, 115.2536 | Education | Sekolah Menengah Pertama |
| 🎓 SMK N 2 Sukawati | -8.6095, 115.2583 | Education | Sekolah Menengah Kejuruan |
| 🏪 Pasar Batubulan | -8.6104, 115.2587 | Commercial | Pasar tradisional |
| 🕉️ Pura Masceti | -8.6103, 115.2591 | Religious | Tempat ibadah Hindu |

#### 🛣️ **Polyline**
- **Rute**: Rumah → SD Negeri 6 Batubulan
- **Jarak**: ± 150 meter
- **Style**: Garis putus-putus merah
- **Fungsi**: Menunjukkan jalur transportasi harian

#### 🏞️ **Polygon**
- **Area**: Lapangan Batubulan
- **Luas**: Area serbaguna masyarakat
- **Style**: Fill biru transparan
- **Fungsi**: Fasilitas olahraga dan kegiatan

## 🛠️ Tech Stack

### Frontend Technologies
- **HTML5** - Struktur semantic dan modern
- **CSS3** - Custom styling dengan animations
- **JavaScript ES6+** - Interactive functionality
- **Tailwind CSS** - Utility-first CSS framework
- **Google Fonts** - Typography (Inter & Orbitron)

### GIS & Mapping
- **Leaflet.js 1.9.4** - Interactive maps library
- **OpenStreetMap** - Primary basemap tiles
- **Esri Satellite** - Satellite imagery basemap
- **Custom Markers** - Styled div icons

### Design System
- **Modern UI/UX** - Clean and professional design
- **Responsive Grid** - Mobile-first approach
- **Color Palette** - Consistent brand colors
- **Typography** - Hierarchical text system

## 🏗️ Project Structure

```
tugas-praktik/
├── index.html              # Main application file
├── README.md               # Project documentation
├── screenshots/            # Screenshot images
│   ├── desktop-view.png
│   ├── mobile-view.png
│   ├── layer-control.png
│   └── popup-info.png
└── assets/                 # Additional resources (if any)
```

## 🚀 Getting Started

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Internet connection untuk CDN resources
- Text editor untuk development

### Installation & Usage

1. **Clone atau Download**
   ```bash
   # Via Git
   git clone [repository-url]
   cd tugas-praktik
   
   # Atau download ZIP dan extract
   ```

2. **Open in Browser**
   ```bash
   # Langsung buka file
   open index.html
   
   # Atau gunakan local server
   python -m http.server 8000
   # Akses: http://localhost:8000
   ```

3. **Development**
   ```bash
   # Edit dengan text editor favorit
   code index.html
   # atau
   vim index.html
   ```

## 📱 Responsive Design

Website ini fully responsive dan optimal untuk:

| Device | Screen Size | Layout |
|--------|-------------|---------|
| 📱 **Mobile** | 320px - 768px | Single column, stacked panels |
| 📱 **Tablet** | 768px - 1024px | Adaptive grid layout |
| 💻 **Desktop** | 1024px+ | Full grid with sidebar |

## 🎮 Interactive Features

### Map Controls
- **Zoom In/Out** - Mouse wheel atau touch gestures
- **Pan** - Drag untuk menggeser peta
- **Layer Control** - Toggle basemap dan overlay
- **Marker Click** - Popup dengan informasi detail

### Layer Management
- **Basemap Selection** - OpenStreetMap vs Satellite
- **Overlay Toggle** - On/off untuk markers, polylines, polygons
- **Dynamic Loading** - Efficient resource management

### User Experience
- **Smooth Animations** - CSS transitions dan transforms
- **Visual Feedback** - Hover effects dan active states
- **Loading States** - Progressive enhancement
- **Error Handling** - Graceful fallbacks

## 🎨 Design Philosophy

### Visual Hierarchy
- **Primary Elements** - Map sebagai focal point
- **Secondary Elements** - Info panels dan controls
- **Supporting Elements** - Status indicators dan footer

### Color System
```css
Primary Colors:
- Blue: #3b82f6 (Interactive elements)
- Red: #dc2626 (Polylines, important markers)
- Green: #10b981 (Success states, home marker)
- Orange: #f59e0b (Facility markers)

Neutral Colors:
- Gray Scale: #f8fafc → #1e293b
- White: #ffffff (Backgrounds)
- Transparent: rgba() values for overlays
```

### Typography
- **Headers**: Inter font, 700-800 weight
- **Body Text**: Inter font, 400-500 weight
- **UI Elements**: Inter font, 500-600 weight
- **Accent**: Orbitron font for special elements

## 📊 Performance Metrics

### Loading Performance
- **Initial Load** - < 2 seconds
- **Map Tiles** - Progressive loading
- **Assets** - CDN optimized delivery
- **JavaScript** - Minified and efficient

### Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🔧 Customization

### Adding New Markers
```javascript
var newMarker = L.marker([lat, lng], {icon: customIcon}).bindPopup(`
    <div class="popup-title">Title</div>
    <div class="popup-description">Description</div>
`).addTo(map);
```

### Creating Custom Icons
```javascript
var customIcon = L.divIcon({
    html: '<div style="background: #color;">Icon</div>',
    iconSize: [32, 32],
    className: 'custom-div-icon'
});
```

### Styling Polylines
```javascript
var polyline = L.polyline(coordinates, {
    color: '#dc2626',
    weight: 4,
    opacity: 0.8,
    dashArray: '10, 5'
});
```

## 📝 Assignment Requirements

### ✅ Completed Requirements

1. **Multiple Markers** - 7 lokasi dengan popup informatif
2. **Polyline Implementation** - Jalur rumah ke sekolah
3. **Polygon Creation** - Area lapangan Batubulan  
4. **Layer Control** - Basemap dan overlay management
5. **Interactive Popups** - Detail informasi setiap lokasi
6. **Responsive Design** - Mobile-friendly interface
7. **Modern UI** - Professional appearance

### 📋 Deliverables

- ✅ File `index.html` dengan semua fitur
- ✅ Screenshot dokumentasi
- ✅ README dokumentasi lengkap
- ✅ Online deployment ready

## 🤝 Contributing

Untuk pengembangan lebih lanjut:

1. Fork repository
2. Create feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open Pull Request

## 📜 License

This project is created for educational purposes as part of GIS coursework.

## 👨‍💻 Author

**I Kadek Nanda Sanjaya**
- 🎓 Mahasiswa Universitas Udayana
- 🏛️ Kampus Jimbaran, Bali
- 📧 Email: nandacomp1075@gmail.com
- 💼 LinkedIn: [My LinkedIn](https://linkedin.com/in/ikdknandasanjaya)

## 🙏 Acknowledgments

- **Universitas Udayana** - Institusi pendidikan
- **Dosen GIS** - Guidance dan requirements
- **OpenStreetMap** - Map data © OpenStreetMap contributors
- **Leaflet.js** - Excellent mapping library
- **Tailwind CSS** - Utility-first CSS framework
- **Esri** - Satellite imagery services
- **Google Fonts** - Typography resources

## 📈 Project Stats

![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-651-blue)
![File Size](https://img.shields.io/badge/File%20Size-22KB-green)
![Markers](https://img.shields.io/badge/Markers-7-orange)
![Basemaps](https://img.shields.io/badge/Basemaps-2-purple)

---

<div align="center">
  <strong>🗺️ Dibuat dengan ❤️ untuk Tugas GIS - September 2025</strong>
  <br>
  <em>Interactive Mapping with Leaflet.js</em>
</div>
