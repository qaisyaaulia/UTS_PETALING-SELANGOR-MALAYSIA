WebGIS ' PETA SEBARAN FASILITAS PENDIDIKAN PETALING, SELANGOR, MALAYSIA
PETA interaktif modern yang dirancang untuk memetakan, menganalisis, dan memvisualisasikan data spasial infrastruktur publik di wilayah Petaling, Selangor, Malaysia. Proyek ini dikembangkan menggunakan kombinasi pemetaan Leaflet.js, pustaka analitik grafik Chart.js, dan pemrosesan heatmap untuk memberikan wawasan spasial yang komprehensif dan responsif.

JUDUL : PETA SEBARAN FASILITAS PENDIDIKAN PETALING, SELANGOR, MALAYSIA
MATAKULIAH : KAPITA SELEKTA - 42
WILAYAH : DAERAH DISTRIK PETALING, SELANGOR, MALAYSIA (termasuk sub-wilayah seperti Shah Alam, Subang Jaya, dan sekitarnya)
TEMA : SEBARAN FASILITAS PUBLIK & ANALISIS KEPADATAN INFRASTRUKTUR
Aplikasi ini berfokus pada 4 pilar sektor utama publik, yaitu  :
1. Pendidikan : Pemetaan dari jenjang usia dini hingga pendidikan tinggi (kindergarten, school, language school, college & university)
2. Kesehatan (Healthcare) : sebaran pusat medis, rumah sakit, klinik, dll
3. Finansial : lokasi institusi perbankan dan pusat keuangan pendukung ekonomi wilayah
4. Lokalitas (Localities): titik landmark penting dan pusat aktivitas lokal masyarakat petaling

Teknologi yang digunakan dalam membangun aplikasi ini ialah menggunakan arsitektur Client-side architecture yang ringan dan cepat dengan stack teknologi, berikut : 
1. HTML5 & CSS3 Kustom : Desain antarmuka modern menggunakan sistem CSS Variables untuk pengaturan tema warna harmonis (kombinasi warna *Baby Pink/Misty Rose* untuk identitas utama).
2. Typography : Mengintegrasikan Outfit Fonts via Google Fonts untuk keterbacaan UI yang bersih dan profesional.
3. Leaflet.js (v1.9.4): Pustaka JavaScript utama berskala industri untuk rendering peta interaktif, manajemen layer GeoJSON, penanganan komponen klik, serta kontrol penjelajahan.
4. Leaflet.heat: Ekstensi plugin khusus Leaflet untuk memproses matriks koordinat menjadi representasi grafis kontur kepadatan (Heatmap Density).
5. Chart.js: Framework grafik responsif yang digunakan untuk menampilkan data statistik tabular ke dalam bentuk visual (Bar Chart untuk rasio antar layer, dan Pie Chart khusus proporsi jenjang pendidikan).
6. Browser Geolocation API: Pustaka bawaan browser untuk melakukan penjejakan titik koordinat pengguna secara *real-time* berbasis GPS.

7. Fitur - fitur utama WebGIS ini, antara lain :
8. 1. Navigasi Multi-Tab Sidebar : Manajemen ruang panel pada sisi kiri yang efisien dengan tambahan pemisah tab 'statistik data', 'analitik visual', dan 'heatmap kepadatan'
   2. pencarian nama secara real-time & filter sub-kategori  : bentuk search bar yang dinamis dalam menyaring nama fasilitas seketika saat diketik, dan dikombinasikan dengan dropdown filter
   3. Counter Statistik Dinamis:** Indikator angka jumlah data yang berubah secara otomatis (*reactive*) mengikuti filter pencarian aktif.
   4. Basemap Switcher Layer Control: Fitur premium di pojok kanan atas yang memungkinkan pengguna beralih antara Peta Kertas Minimalis (CartoDB Voyager) dengan Citra Satelit Asli (Esri World Imagery).
   5. Geolocation Button ("Cari Lokasi Saya"): Tombol melayang yang otomatis mengarahkan peta ke koordinat GPS pengguna saat ini lengkap dengan radius akurasi visual.
   6. Integrasi OpenStreetMap External Link: Tautan dinamis ke situs OpenStreetMap global berdasarkan koordinat bangunan yang sedang dipilih.
