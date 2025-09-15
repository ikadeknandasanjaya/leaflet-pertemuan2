# 🗺️ Peta Kampus PSTI Universitas Udayana

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://kampusjimbaranmarker.netlify.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

> **Interactive Campus Map** untuk Program Studi Teknologi Informasi, Universitas Udayana - Jimbaran, Bali

## 🚀 Live Demo

**🌐 [Kunjungi Peta Interaktif](https://kampusjimbaranmarker.netlify.app/)**

## 📸 Screenshots

### Desktop View
![Desktop Screenshot](screenshots/desktop-view.png)
*Tampilan desktop dengan sidebar legend dan peta interaktif*

### Mobile View
![Mobile Screenshot](screenshots/mobile-view.png)
*Responsive design untuk perangkat mobile*

### Map Markers
![Map Markers](screenshots/map-markers.png)
*Custom icons untuk berbagai kategori lokasi*

### Popup Information
![Popup Info](screenshots/popup-info.png)
*Detail informasi lokasi dalam popup yang modern*

## ✨ Features

### 🎯 **Core Features**
- **Interactive Map** dengan Leaflet.js
- **31 Lokasi** kampus dan sekitarnya
- **8 Kategori** lokasi yang berbeda
- **Custom Icons** untuk setiap jenis lokasi
- **Responsive Design** untuk semua perangkat

### 🎨 **Modern UI/UX**
- **Glassmorphism Design** dengan backdrop blur
- **Gradient Background** yang stunning
- **Smooth Animations** dan transitions
- **Dark Mode Toggle** (coming soon)
- **Fullscreen Mode** untuk pengalaman immersive

### 🗺️ **Map Features**
- **OpenStreetMap** sebagai base layer
- **Zoom Controls** dan navigation
- **Scale Bar** untuk referensi jarak
- **Click to Zoom** pada marker
- **Coordinate Display** di title bar

## 📊 Data Lokasi

| Kategori | Jumlah | Icon | Warna |
|----------|--------|------|-------|
| 🏛️ Universitas & Rektorat | 1 | `fa-university` | Purple |
| 🏢 Fakultas | 8 | `fa-building-columns` | Red |
| 🎓 Program Studi | 7 | `fa-graduation-cap` | Blue |
| 📚 Perpustakaan & Lab | 2 | `fa-book` | Green |
| 🍽️ Tempat Makan | 4 | `fa-utensils` | Orange |
| 🚌 Transportasi | 2 | `fa-bus` | Dark Gray |
| 📍 Tempat Umum | 3 | `fa-map-marker-alt` | Gray |
| 🏥 Fasilitas Kesehatan | 2 | `fa-hospital` | Pink |

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Struktur semantic
- **CSS3** - Custom styling dan animations
- **JavaScript** - Interactive functionality
- **Tailwind CSS** - Modern utility-first CSS framework
- **Google Fonts** - Typography (Inter)

### Map & Icons
- **Leaflet.js** - Interactive maps library
- **OpenStreetMap** - Map tiles
- **Font Awesome 6** - Icon library

### Deployment
- **Netlify** - Static site hosting
- **Git** - Version control

## 🏗️ Project Structure

```
leaflet-pertemuan2/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── screenshots/        # Screenshot images
│   ├── desktop-view.png
│   ├── mobile-view.png
│   ├── map-markers.png
│   └── popup-info.png
└── .git/              # Git repository
```

## 🚀 Getting Started

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Internet connection untuk CDN resources

### Installation

1. **Clone repository**
   ```bash
   git clone https://github.com/username/leaflet-pertemuan2.git
   cd leaflet-pertemuan2
   ```

2. **Open in browser**
   ```bash
   # Buka file index.html di browser
   open index.html
   # atau
   python -m http.server 8000  # untuk local server
   ```

3. **Deploy to Netlify**
   - Drag & drop folder ke Netlify dashboard
   - Atau connect dengan GitHub repository

## 📱 Responsive Design

Website ini fully responsive dan optimal untuk:
- 📱 **Mobile** (320px - 768px)
- 📱 **Tablet** (768px - 1024px)  
- 💻 **Desktop** (1024px+)

## 🎯 Usage

### Navigation
- **Zoom In/Out** dengan mouse wheel atau touch
- **Pan** dengan drag pada peta
- **Click Marker** untuk melihat detail lokasi
- **Center Button** untuk kembali ke view awal
- **Fullscreen** untuk mode layar penuh

### Legend
- **Click Legend Item** untuk highlight effect
- **Hover** untuk smooth transitions
- **Color Coding** untuk identifikasi cepat

## 🤝 Contributing

Kontribusi sangat welcome! Untuk berkontribusi:

1. Fork repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 👨‍💻 Author

**[Your Name]**
- 🎓 Program Studi Teknologi Informasi
- 🏛️ Universitas Udayana
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- **Universitas Udayana** - Data lokasi kampus
- **OpenStreetMap** - Map data © OpenStreetMap contributors
- **Leaflet.js** - Amazing mapping library
- **Font Awesome** - Beautiful icons
- **Tailwind CSS** - Utility-first CSS framework
- **Netlify** - Free hosting platform

## 📈 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/username/leaflet-pertemuan2)
![GitHub last commit](https://img.shields.io/github/last-commit/username/leaflet-pertemuan2)
![GitHub issues](https://img.shields.io/github/issues/username/leaflet-pertemuan2)
![GitHub stars](https://img.shields.io/github/stars/username/leaflet-pertemuan2?style=social)

---

<div align="center">
  <strong>🗺️ Dibuat dengan ❤️ untuk Tugas GIS - September 2025</strong>
  <br>
  <a href="https://kampusjimbaranmarker.netlify.app/">View Live Demo</a>
</div>
