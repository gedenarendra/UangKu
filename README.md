# 💰 DompetKu - Personal Finance PWA

![Project Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20PWA%20%7C%20Mobile-orange?style=for-the-badge)

**DompetKu** adalah aplikasi pencatat keuangan minimalis berbasis web (PWA) yang dirancang dengan pendekatan *Mobile-First*. Aplikasi ini memungkinkan pengguna mencatat pemasukan dan pengeluaran secara **Offline-First**, sehingga data tetap aman dan tersimpan meski tanpa koneksi internet, dan akan otomatis tersinkronisasi ke Cloud saat kembali online.

---

## ✨ Fitur Unggulan

🚀 **Offline Support (PWA)**
Dibangun dengan Service Worker dan Firestore Persistence. Aplikasi dapat dibuka dan digunakan sepenuhnya tanpa internet, berkat caching aset statis dan database lokal.

🔐 **Secure Authentication**
Login aman menggunakan **Google OAuth** via Firebase Authentication.

📱 **Mobile-First & Responsive**
Desain UI yang dioptimalkan untuk perangkat mobile, menangani *safe-area* (poni iPhone), dan animasi transisi yang halus layaknya aplikasi Native.

⚡ **Zero Build Setup**
Tidak perlu `npm install` atau `webpack`. Menggunakan React 18 & Tailwind CSS via CDN untuk pengembangan yang super cepat dan ringan.

📊 **Real-time Sync**
Data transaksi disinkronisasi secara *real-time* antar perangkat menggunakan Cloud Firestore.

---

## 🛠️ Tech Stack

Aplikasi ini dibangun menggunakan teknologi modern yang ringan:

| Komponen | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React_18-20232A?style=flat&logo=react&logoColor=61DAFB) | Library UI utama (via CDN) |
| **Styling** | ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) | Utility-first framework (via CDN) |
| **Backend** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) | Auth, Firestore Database, & Hosting |
| **Icons** | ![Lucide](https://img.shields.io/badge/Lucide-F05032?style=flat&logo=lucide&logoColor=white) | Ikon vector yang ringan dan modern |

---

## 📸 Screenshots

<p align="center">
  <img src="https://via.placeholder.com/300x600?text=Login+Screen" alt="Login Screen" width="200" />
  <img src="https://via.placeholder.com/300x600?text=Home+Dashboard" alt="Dashboard" width="200" />
  <img src="https://via.placeholder.com/300x600?text=Add+Transaction" alt="Add Transaction" width="200" />
</p>

---

## 🚀 Cara Menjalankan (Installation)

Karena proyek ini menggunakan CDN, kamu tidak perlu menginstal `node_modules`. Cukup butuh **Local Web Server**.

### 1. Clone Repository
```bash
git clone [https://github.com/username/dompetku.git](https://github.com/username/dompetku.git)
cd dompetku
