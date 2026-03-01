# Mini-projectPBW-1
# Mini-Project1-PAB  
# Personal Portfolio Website 💻✨

| Nama                  | NIM         | Kelas               |
|-----------------------|------------|---------------------|
| Vebronia Vitania Lusi | 2409116112 | Sistem Informasi C  |

---

## Deskripsi Aplikasi

Website **Personal Portfolio** adalah website berbasis **HTML, CSS, dan Bootstrap 5** yang menampilkan profil pribadi, informasi tentang diri, sertifikat, dan kontak.

Website ini dibuat untuk memahami:
- Struktur dasar HTML
- Styling menggunakan CSS
- Pemanfaatan Bootstrap 5
- Penerapan desain modern (Glassmorphism / Premium UI)
- Responsive Design

---

# 🖼 Tampilan Website

---

## 🏠 1. Home Page

<div align="center">

<!-- GANTI LINK DI BAWAH INI DENGAN SCREENSHOT KAMU -->
<img src="LINK_SCREENSHOT_HOME" width="900"/>

</div>

<p align="center">
<b><em>Halaman Home</em></b><br>
Menampilkan Hero Section yang berisi foto profil, nama lengkap, dan deskripsi singkat.
</p>

---

## 👩‍💻 2. About Me

<div align="center">

<!-- GANTI LINK DI BAWAH INI DENGAN SCREENSHOT KAMU -->
<img src="LINK_SCREENSHOT_ABOUT" width="900"/>

</div>

<p align="center">
<b><em>Halaman About Me</em></b><br>
Berisi deskripsi singkat tentang latar belakang dan minat di bidang teknologi dengan desain glass effect.
</p>

---

## 📜 3. Certificates

<div align="center">

<!-- GANTI LINK DI BAWAH INI DENGAN SCREENSHOT KAMU -->
<img src="LINK_SCREENSHOT_CERTIFICATE" width="900"/>

</div>

<p align="center">
<b><em>Halaman Certificates</em></b><br>
Menampilkan daftar sertifikat dalam bentuk card menggunakan Bootstrap Grid System.
</p>

---

# 🧩 Penjelasan Setiap Section

---

## 1️⃣ Navbar

**Fungsi:**  
Sebagai navigasi utama untuk berpindah antar section.

**Kode utama:**
```html
<nav class="navbar navbar-expand-lg fixed-top">
```

**Penjelasan:**
- `navbar-expand-lg` → Responsive
- `fixed-top` → Navbar tetap di atas saat scroll
- Efek glass menggunakan `backdrop-filter`

---

## 2️⃣ Hero Section

**Fungsi:**  
Menampilkan identitas utama pemilik website.

**Kode utama:**
```html
<section class="hero-section">
```

**Efek hover foto:**
```css
.profile-img:hover {
  transform: scale(1.05);
}
```

---

## 3️⃣ About Section

**Fungsi:**  
Menjelaskan profil singkat dan minat.

**Kode utama:**
```html
<div class="glass-section">
```

**Efek glass:**
```css
background: rgba(255,255,255,0.08);
backdrop-filter: blur(14px);
border-radius: 20px;
```

---

## 4️⃣ Certificates Section

**Fungsi:**  
Menampilkan sertifikat dalam bentuk card.

**Grid Layout:**
```html
<div class="row">
  <div class="col-md-4">
```

**Hover image:**
```css
.cert-img:hover {
  transform: scale(1.05);
}
```

---

## 5️⃣ Contact Section

**Fungsi:**  
Menampilkan informasi kontak seperti email dan media sosial.

Menggunakan container Bootstrap dan custom CSS agar konsisten dengan desain.

---

# 🛠 Teknologi yang Digunakan

- HTML5
- CSS3
- Bootstrap 5
- Google Fonts
- Responsive Web Design

---

# 📂 Struktur Folder

```text
mini_project1_pab/
│
├─ index.html
├─ style.css
├─ assets/
│  ├─ images/
│  │  ├─ profile.jpg
│  │  ├─ certificate1.jpg
│  │  └─ certificate2.jpg
│
└─ README.md
```

---

# 🎯 Tujuan Project

Project ini dibuat sebagai:
- Tugas Mini Project 1 PAB
- Implementasi HTML & CSS
- Penerapan Bootstrap 5
- Latihan membuat website portfolio modern

---
