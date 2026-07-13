# CHANGELOG PERSONAL — Portofolio V5

## 2026-07-13 — Update SEO Meta Tags & Domain Production

### Perubahan
- **Domain Production:** https://portokeren-v5.vercel.app (deployed & live)
- **Fix Typo Nama:** "Rzky" → "Rizky" (dengan "i")
- **Meta Tags:** Update semua Open Graph, Twitter Card, JSON-LD structured data
- **Canonical URL:** Ganti dari ekizr.com ke portokeren-v5.vercel.app
- **Robots.txt:** Update sitemap URL ke domain baru

### File yang Diubah

| # | File | Perubahan |
|---|------|-----------|
| 1 | `index.html` | Meta title, description, keywords, author, Open Graph tags, Twitter Card tags, canonical URL, JSON-LD (nama, jobTitle, url, image, sameAs) |
| 2 | `public/robots.txt` | Sitemap URL → https://portokeren-v5.vercel.app/sitemap.xml |
| 3 | `public/Meta.png` | File gambar diganti (branding "Ekizr" → "Kyyoa") |

### Data yang Diperbaiki di index.html
- Nama: **Eki Zulfar Rachman** → **Rizky Yovi Attalla**
- Title: **Front-End Web Developer** → **Full-Stack Architect**
- Domain: **ekizr.com** → **portokeren-v5.vercel.app**
- Social Media: Hapus Instagram & TikTok, keep GitHub & LinkedIn saja

---

## 2026-07-07 — Penggantian Data Personal

### Data Baru
- **Nama Lengkap:** Rizky Yovi Attalla
- **Brand/Nama Singkat:** Kyyoa
- **Title/Bio:** Full-Stack Architect, AI-Driven Execution.
- **Email:** yoviattalla@gmail.com
- **GitHub:** https://github.com/Kyyoa
- **LinkedIn:** https://www.linkedin.com/in/rizky-yovi-attalla-49103a410/
- **Domain:** https://portokeren-v5.vercel.app (deployed to Vercel)
- **Instagram:** (Dihapus)
- **YouTube:** (Dihapus)
- **TikTok:** (Dihapus)

### File yang Diubah

| # | File | Perubahan |
|---|------|-----------|
| 1 | `src/Pages/Home.jsx` | Nama, title, meta tags, JSON-LD, sosial links (hapus Instagram, ganti GitHub & LinkedIn, hapus domain) |
| 2 | `src/Pages/WelcomeScreen.jsx` | Hapus link ekizr.com, ganti dengan teks brand "Kyyoa" |
| 3 | `src/components/Navbar.jsx` | Logo "Ekizr" → "Kyyoa" |
| 4 | `src/components/Footer.jsx` | Hapus link domain, "EkiZR™" → "Kyyoa™" |
| 5 | `src/components/SocialLinks.jsx` | Hapus Instagram, YouTube, TikTok (+ SVG icon); update LinkedIn & GitHub URL |
| 6 | `src/components/ProjectDetail.jsx` | Nama, fallback GitHub, meta desc, canonical URL dinamis |
| 7 | `src/Pages/Contact.jsx` | Email form → yoviattalla@gmail.com |

### Cara Melanjutkan di Sesi Depan
1. Buka file `CHANGELOG-PERSONAL.md` ini
2. Baca daftar file yang diubah di atas
3. Jika ingin mengubah data lagi, refer ke baris-baris yang disebutkan di atas

---
*Dokumen ini dibuat otomatis oleh AI Agent. Jangan dihapus.*
