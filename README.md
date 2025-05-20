# BenerIn

**BenerIn** adalah aplikasi pelaporan kerusakan infrastruktur berbasis R yang dikembangkan menggunakan framework Shiny. Aplikasi ini bertujuan untuk memfasilitasi partisipasi masyarakat dalam pemantauan infrastruktur dan menyampaikan laporan secara real-time kepada pihak berwenang. Melalui visualisasi berbasis peta (heatmap), BenerIn mendukung pengambilan keputusan yang lebih cepat, transparan, dan berbasis data, khususnya dalam konteks ketimpangan infrastruktur di Daerah Istimewa Yogyakarta.

## 🚀 Fitur Utama
- 📍 Pelaporan lokasi infrastruktur rusak dengan deskripsi dan foto
- 📊 Visualisasi data laporan dalam bentuk heatmap interaktif
- 🔔 Notifikasi status pengaduan (terkirim, terverifikasi, ditindaklanjuti)
- 🗂️ Riwayat pengaduan yang tersimpan dan dapat diakses pengguna
- 📥 Integrasi data primer dari masyarakat dengan data sekunder (BPS, World Bank)

## 🛠️ Cara Menjalankan

Pastikan telah menginstall semua dependencies dari `requirements.txt` atau langsung jalankan aplikasi Shiny di R:

```r
# install.packages("shiny")
# install.packages("leaflet")
# install.packages("dplyr")
runApp("app/")
