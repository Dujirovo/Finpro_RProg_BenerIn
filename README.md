# BenerIn

**BenerIn** adalah aplikasi pelaporan kerusakan infrastruktur berbasis R yang dikembangkan menggunakan framework **Shiny**. Aplikasi ini bertujuan untuk meningkatkan partisipasi masyarakat dalam pemantauan dan perbaikan infrastruktur, dengan cara menyediakan platform pelaporan langsung serta visualisasi kondisi infrastruktur dalam bentuk **heatmap**. Fokus utama aplikasi ini adalah wilayah **Daerah Istimewa Yogyakarta**, namun dapat diadaptasi untuk wilayah lain di Indonesia.

Aplikasi ini mendukung pengambilan keputusan berbasis data oleh pihak berwenang dengan mengintegrasikan laporan warga, data statistik resmi (BPS, World Bank), dan peta visualisasi. Pengembangan ini sejalan dengan tujuan SDGs 9 dan SDGs 10 dalam hal pembangunan infrastruktur yang inklusif dan pengurangan ketimpangan wilayah.

---

## 🚀 Fitur Utama
- 📍 **Pelaporan Langsung**: Laporan kerusakan infrastruktur oleh masyarakat, lengkap dengan lokasi dan foto.
- 📊 **Heatmap Interaktif**: Visualisasi wilayah berdasarkan tingkat kerusakan infrastruktur.
- 🔔 **Notifikasi Real-Time**: Update status pengaduan secara langsung ke pengguna.
- 🗂️ **Histori Laporan**: Riwayat pengaduan yang dapat ditelusuri dan diperiksa ulang.
- 📥 **Integrasi Data**: Data primer dari masyarakat dan data sekunder dari BPS/World Bank.

---

## 🧭 Cara Penggunaan Aplikasi

### 🔐 Log In
1. Buka aplikasi **BenerIn**.
2. Masukkan **NIK/No. KTP** pada halaman login.
3. Jika berhasil, pengguna akan langsung diarahkan ke **Home Page**.
4. Jika gagal, akan muncul notifikasi seperti:
   - “No Penduduk tidak ditemukan”
   - “Coba periksa jaringan Anda”

---

### 📝 Fitur Pengaduan
1. Pilih menu **Pengaduan** di Home Page.
2. Jika pengguna sudah pernah melaporkan, akan muncul **histori pengaduan**.
3. Tekan ikon **"+"** untuk membuat pengaduan baru.
4. Isi form pengaduan, meliputi:
   - Lokasi kejadian
   - Tanggal laporan
   - Jenis infrastruktur
   - Deskripsi kerusakan
   - Foto pendukung
5. Tekan tombol **Kirim** untuk mengirim laporan.
6. Laporan akan melalui proses **verifikasi** sebelum masuk ke sistem.

---

### 📂 Melihat Histori Pengaduan
1. Di halaman **Pengaduan**, pilih tanggal laporan untuk melihat detail pengaduan.
2. Informasi yang tersedia:
   - Jenis infrastruktur
   - Lokasi kerusakan
   - Foto pendukung
   - **Status pengaduan**:
     - Terkirim
     - Terverifikasi
     - Sedang Ditindaklanjuti
3. Sistem akan mengirimkan **notifikasi real-time** jika status pengaduan berubah.

---

### 🗺️ Fitur HeatMap
1. Pilih menu **HeatMap** di Home Page.
2. Peta akan menampilkan persebaran kondisi infrastruktur berdasarkan:
   - Laporan masyarakat (pengaduan yang diverifikasi)
   - Data resmi dari instansi seperti BPS
3. Klik titik tertentu pada peta untuk melihat informasi detail:
   - Jenis infrastruktur
   - Jumlah laporan
   - Status pengaduan
   - Foto pendukung (jika tersedia)
4. Warna wilayah menunjukkan tingkat kerusakan:
   - 🔴 **Merah**: Rusak parah
   - 🟡 **Kuning**: Kerusakan sedang
   - 🟢 **Hijau**: Infrastruktur dalam kondisi baik

---

## 🛠️ Teknologi yang Digunakan
- **R Programming**
- **Shiny (Web Framework)**
- **Leaflet (Pemetaan Interaktif)**
- **dplyr, ggplot2** untuk pengolahan dan visualisasi data

---

## 📄 Lisensi
Proyek ini dikembangkan untuk kepentingan akademik dan sosial. Seluruh kode bersifat open-source dan dapat dimodifikasi sesuai kebutuhan. Lisensi: MIT License.

---

## 👥 Tim Pengembang
- Dewi Valentina
- Ghea Puan Maharani Rohmana
- Maria Cira Fedora Nahuway
- Aqilah Shofi Azzahra
- Nashwan Abdurrouuf
- Satrio Dwi Arisetyo
- Hieronimus Yudhit Panduwinarya

Fakultas Ekonomika dan Bisnis, Universitas Gadjah Mada  
Kelas R-Programming, 2025  
Dosen Pengampu: Dr. Lukman Heryawan, S.T., M.T.

