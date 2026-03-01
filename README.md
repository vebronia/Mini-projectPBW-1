# Mini-projectPBW-1  
# Personal Portfolio Website 💻✨

| Nama                  | NIM         | Kelas               |
|-----------------------|------------|---------------------|
| Vebronia Vitania Lusi | 2409116112 | Sistem Informasi C  |



<details open>
<summary><b>📌 Deskripsi Aplikasi</b></summary>
<br>

Website **Personal Portfolio** adalah website berbasis **HTML, CSS, dan Bootstrap 5** yang menampilkan profil pribadi, informasi tentang diri, serta sertifikat yang pernah saya peroleh.

Pada bagian Home, saya juga menampilkan username Instagram sebagai identitas digital saya.

Website ini dibuat untuk memahami:

- Struktur dasar HTML  
- Styling menggunakan CSS  
- Pemanfaatan Bootstrap 5  
- Penerapan desain modern (Glassmorphism / Premium UI)  
- Responsive Design  

</details>

<details>
<summary><b>📂 Struktur Folder</b></summary>
<br>

</details>

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


# 🖼 Tampilan Website

---

<details>
<summary><b>🏠 1. Home Page</b></summary>
<br>

<!-- ===== TEMPAT SCREENSHOT HOME ===== -->

<div align="center">

<!-- MASUKKAN SCREENSHOT HOME DI SINI -->
<!-- Contoh:
<img src="LINK_SCREENSHOT_HOME" width="100%">
-->

</div>

<p align="center">
<b><em>Halaman Home</em></b><br>
Menampilkan Hero Section yang berisi foto profil, nama lengkap, deskripsi singkat, serta username Instagram.
</p>

</details>

---

<details>
<summary><b>👩‍💻 2. About Me</b></summary>
<br>

<!-- ===== TEMPAT SCREENSHOT ABOUT ===== -->

<div align="center">

<!-- MASUKKAN SCREENSHOT ABOUT DI SINI -->

</div>

<p align="center">
<b><em>Halaman About Me</em></b><br>
Berisi penjelasan singkat tentang latar belakang dan minat saya di bidang teknologi dengan desain glass effect.
</p>

</details>

---

<details>
<summary><b>📜 3. Certificates</b></summary>
<br>

<!-- ===== TEMPAT SCREENSHOT CERTIFICATE ===== -->

<div align="center">

<!-- MASUKKAN SCREENSHOT CERTIFICATE DI SINI -->

</div>

<p align="center">
<b><em>Halaman Certificates</em></b><br>
Menampilkan daftar sertifikat dalam bentuk card menggunakan Bootstrap Grid System.
</p>

</details>

---

# 🧩 Penjelasan Setiap Section / Fitur

---

<details>
<summary><b>1️⃣ Navbar</b></summary>
<br>

**Fungsi:**  
Navbar saya gunakan untuk navigasi agar pengguna dapat berpindah ke bagian About dan Certificates dengan mudah tanpa harus scroll terlalu jauh.

**Kenapa menggunakan fixed-top?**  
Agar navbar tetap berada di bagian atas saat halaman di-scroll sehingga terlihat lebih modern dan memudahkan navigasi.

**Kode utama:**
```html
<nav class="navbar navbar-expand-lg fixed-top">
```

Saya juga menambahkan efek glass (blur dan transparansi) agar tampilannya lebih premium dan tidak terlihat polos.

</details>

---

<details>
<summary><b>2️⃣ Hero Section (Home)</b></summary>
<br>

**Fungsi:**  
Bagian ini merupakan tampilan pertama saat website dibuka. Di sini saya menampilkan foto profil, nama lengkap, deskripsi singkat, serta username Instagram sebagai identitas digital saya.

Saya menambahkan sedikit efek interaksi pada foto profil agar tampilan tidak kaku dan terasa lebih hidup.

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

Menurut saya, efek kecil seperti ini membuat tampilan lebih interaktif namun tetap clean dan elegan.

</details>

---

<details>
<summary><b>3️⃣ About Section</b></summary>
<br>

**Fungsi:**  
Bagian ini saya gunakan untuk menjelaskan sedikit tentang diri saya, minat saya di bidang teknologi, serta hal-hal yang sedang saya pelajari.

Agar tampilannya tidak terlihat datar, saya menggunakan desain glass effect sehingga terlihat lebih modern dan estetik.

**Kode utama:**
```html
<div class="glass-section">
```

Efek glass dibuat menggunakan kombinasi background transparan dan backdrop blur sehingga memberikan kesan premium.

</details>

---

<details>
<summary><b>4️⃣ Certificates Section</b></summary>
<br>

**Fungsi:**  
Pada bagian ini saya menampilkan sertifikat yang pernah saya peroleh dalam bentuk card agar lebih rapi dan terstruktur.

Saya menggunakan Bootstrap Grid System agar tampilan tetap responsif di berbagai ukuran layar.

**Grid layout utama:**
```html
<div class="row">
  <div class="col-md-4">
```

Saya juga menambahkan efek hover pada card atau gambar agar tidak terlihat monoton dan lebih interaktif.

</details>

---

# 🛠 Teknologi yang Digunakan

- HTML5  
- CSS3  
- Bootstrap 5  
- Google Fonts  
- Bootstrap Icons  

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

<details>
<summary><b>🎯 Tujuan Project</b></summary>
<br>

Project ini dibuat sebagai:

- Tugas Mini Project 1 PAB  
- Implementasi HTML & CSS  
- Penerapan Bootstrap 5  
- Latihan membuat website portfolio modern dengan desain premium dan responsif  

</details>
