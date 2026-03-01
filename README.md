# Mini-projectPBW-1    
# Personal Portfolio Website 💻✨

| Nama                  | NIM         | Kelas               |
|-----------------------|------------|---------------------|
| Vebronia Vitania Lusi | 2409116112 | Sistem Informasi C  |

---

<details open>
<summary><b>📌 Deskripsi Aplikasi</b></summary>
<br>

Website **Personal Portfolio** adalah website berbasis **HTML, CSS, dan Bootstrap 5** yang menampilkan profil pribadi, informasi tentang diri, sertifikat, dan kontak.

Website ini dibuat untuk memahami:

- Struktur dasar HTML  
- Styling menggunakan CSS  
- Pemanfaatan Bootstrap 5  
- Penerapan desain modern (Glassmorphism / Premium UI)  
- Responsive Design  

</details>

---

# 🖼 Tampilan Website

---

<details>
<summary><b>🏠 1. Home Page</b></summary>
<br>

<div align="center">

<img width="1919" height="890" src="https://github.com/user-attachments/assets/91b19eea-33d9-45dc-85f0-f4f6f6bfd97f"/>

</div>

<p align="center">
<b><em>Halaman Home</em></b><br>
Menampilkan Hero Section yang berisi foto profil, nama lengkap, dan deskripsi singkat.
</p>

</details>

---

<details>
<summary><b>👩‍💻 2. About Me</b></summary>
<br>

<div align="center">

<img width="1917" height="887" src="https://github.com/user-attachments/assets/19c7d6da-0240-4f02-885c-e15504945bda"/>

</div>

<p align="center">
<b><em>Halaman About Me</em></b><br>
Berisi deskripsi singkat tentang latar belakang dan minat di bidang teknologi dengan desain glass effect.
</p>

</details>

---

<details>
<summary><b>📜 3. Certificates</b></summary>
<br>

<div align="center">

<img width="1919" height="891" src="https://github.com/user-attachments/assets/36bbb512-6f36-4fdb-b790-46644b6e4737"/>

</div>

<p align="center">
<b><em>Halaman Certificates</em></b><br>
Menampilkan daftar sertifikat dalam bentuk card menggunakan Bootstrap Grid System.
</p>

</details>

---

# 🧩 Penjelasan Setiap Section

---

<details>
<summary><b>1️⃣ Navbar</b></summary>
<br>

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

</details>

---

<details>
<summary><b>2️⃣ Hero Section</b></summary>
<br>

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

</details>

---

<details>
<summary><b>3️⃣ About Section</b></summary>
<br>

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

</details>

---

<details>
<summary><b>4️⃣ Certificates Section</b></summary>
<br>

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

</details>

---

<details>
<summary><b>5️⃣ Contact Section</b></summary>
<br>

**Fungsi:**  
Menampilkan informasi kontak seperti email dan media sosial.

Menggunakan container Bootstrap dan custom CSS agar konsisten dengan desain.

</details>

---

<details>
<summary><b>🛠 Teknologi yang Digunakan</b></summary>
<br>

- HTML5  
- CSS3  
- Bootstrap 5  
- Google Fonts  
- Responsive Web Design  

</details>

---

<details>
<summary><b>📂 Struktur Folder</b></summary>
<br>

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

</details>

---

<details>
<summary><b>🎯 Tujuan Project</b></summary>
<br>

Project ini dibuat sebagai:
- Tugas Mini Project 1 PAB  
- Implementasi HTML & CSS  
- Penerapan Bootstrap 5  
- Latihan membuat website portfolio modern  

</details>

---
