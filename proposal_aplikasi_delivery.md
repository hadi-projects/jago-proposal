
# Proposal Pengerjaan Aplikasi Jago (Delivery Online)

## Deskripsi Singkat
Aplikasi ini adalah sistem delivery online untuk kebutuhan tugas kuliah atau MVP bisnis sederhana. Sistem terdiri dari:
- **Aplikasi mobile Flutter** (untuk customer)
- **Dashboard web** (untuk admin & merchant)
- **Landing page publik**
- **Backend API** di VPS
- **Domain khusus (.com / .my.id)**

---

## Tujuan
Menyediakan sistem delivery online lengkap dan siap online dengan backend API, dashboard, mobile app customer, serta landing page untuk publikasi sistem.

---

## Fitur-Fitur Utama

### 1. Landing Page (Publik)
- Halaman utama sistem (misalnya: www.namadomainmu.com)
- Menampilkan:
  - Deskripsi singkat layanan
  - Link ke aplikasi mobile (download APK)
  - Link login admin/merchant
  - Informasi kontak developer/owner

### 2. Authentication & User Role
- Registrasi & login
- Role:
  - Admin (Web)
  - Merchant (Web)
  - Customer (Flutter App)

### 3. Manajemen Merchant (Admin – Web)
- CRUD merchant
- Aktivasi/deaktivasi
- Statistik transaksi merchant

### 4. Manajemen Produk (Merchant – Web)
- CRUD produk
- Foto, kategori, harga, stok

### 5. Aplikasi Customer (Mobile – Flutter)
- Registrasi & login
- Browsing produk & merchant
- Keranjang, checkout
- Riwayat & pelacakan pesanan
- integrasi maps

### 6. Order Management
- Merchant update status pesanan
- Customer tracking status real-time

### 7. Dashboard Admin (Web)
- Statistik sistem
- Manajemen pengguna & merchant

### 8. Hosting & Domain
- Hosting backend di VPS
- Domain publik (.com atau .my.id)
- Landing page + dashboard + API diakses dari domain

---

## Teknologi yang Digunakan

| Komponen     | Teknologi                   |
|--------------|-----------------------------|
| Mobile App   | Flutter                     |
| Dashboard    | Laravel                     |
| Backend API  | Laravel                     |    
| Database     | MySQL                       |
| Hosting      | VPS + Nginx/Apache          |
| Domain       | .com / .my.id               |
| Landing Page | HTML/CSS/JS or React        |

---

## 📅 Estimasi Waktu Pengerjaan

**Total: 30 hari kerja**

---

## Biaya Pengerjaan

| Komponen                                  | Biaya (Rp)     |
|-------------------------------------------|----------------|
| Pengembangan sistem (web + mobile + API)  | 1.600.000      |
| Landing page                              | Free           |
| Deployment                                | Free           |
| Domain (.com / .my.id)                    | Free           |
| VPS kecil (1 bulan)                       | 200.000        |
| **Total Biaya**                           | **1.800.000**  |


---

## Output yang Diberikan
- APK build Flutter (untuk Android)
- Akses dashboard (admin & merchant)
- Akses source code (Backend, API, Flutter)
- Panduan penggunaan & setup ulang
- 2x revisi minor (fitur/tampilan)

---

## Catatan Tambahan
- Sistem dibuat untuk kebutuhan tugas akhir/ujian, namun arsitekturnya bisa dikembangkan untuk skala lebih besar.
- Jika ingin pembayaran otomatis (payment gateway), fitur ini dapat ditambahkan sebagai add-on.
