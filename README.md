# Portfolio V5

Hello everyone! 👋

Let me introduce myself, I'm **Rzky Yovi Attala**. On this occasion, I'd like to share the portfolio website project that I've developed. Built with React and Supabase, featuring a public-facing site and an admin dashboard.

---

## 🛠️ Tech Stack

This project is built using modern web technologies:

*   **Framework:** Vite + ReactJS (Fast, Lightweight, & Component-Based)
*   **Styling Engine:** Tailwind CSS (Utility-first CSS framework)
*   **Backend Engine:** Supabase (Backend for portfolio data, certificates, and realtime comment system)
*   **Animations:** Framer Motion & AOS (Animate On Scroll library)
*   **Icons & UI:** Lucide React, Material UI, & SweetAlert2

---

## 👥 User Roles

| Role | Access |
| --- | --- |
| **Visitor (Public)** | View projects, certificates, and comments — leave a comment |
| **Admin** | Login to dashboard — full CRUD on projects & certificates — delete & pin/unpin comments |

---

## 🚀 Getting Started

### Prerequisites
- Node.js `>= 14.x`
- npm or yarn

### 1. Clone & Install
```bash
git clone [https://github.com/Kyyoa/portokeren.git](https://github.com/Kyyoa/portokeren.git)
cd portokeren
npm install --legacy-peer-deps
```

### 2. Environment Variables
Buat sebuah file bernama `.env` di dalam folder utama (root) proyek ini, lalu masukkan kredensial Supabase milikmu:
```env
VITE_SUPABASE_URL=your-supabase-project-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
```

### 3. Database Setup
Masuk ke Supabase Project → **SQL Editor** → buat **New Query**, lalu jalankan skrip pembuatan tabel database yang dibutuhkan untuk menyimpan data proyek, sertifikat, dan komentar.

### 4. Create Admin Account
1. Masuk ke menu **Authentication → Users → Add User** di dasbor Supabase, lalu salin User ID (UUID) yang dihasilkan.
2. Jalankan perintah SQL ini di SQL Editor (ganti `USER_UUID` dengan ID yang kamu salin):
```sql
INSERT INTO public.profiles (id, username, role)
VALUES ('USER_UUID', 'yovia', 'admin');
```

### 5. Run Locally
```bash
npm run dev
```
Buka `http://localhost:5173` di browser pilihanmu.

---

## 📑 Pages & Features

### Public (Visitor)
*   **Home:** Menampilkan bagian hero, tentang saya, serta daftar keahlian (skills).
*   **Projects:** Daftar karya/proyek yang dilengkapi dengan jendela detail (modal).
*   **Certificates:** Galeri grid responsif untuk menampilkan sertifikat kompetensi.
*   **Comments:** Kolom testimoni pengunjung yang terintegrasi secara *realtime*.

### Admin (Dashboard)
*   **Login Page:** Autentikasi aman menggunakan email & password via Supabase Auth.
*   **Management Panel:** Kontrol penuh (Create, Read, Update, Delete) untuk konten proyek, gambar sertifikat, serta fitur moderasi/pin komentar pengunjung.

---

## 🌐 Credits & Contact

**Rzky Yovi Attala**
*   **GitHub:** [Kyyoa](https://github.com/Kyyoa)
*   **LinkedIn:** [Rizky Yovi Attalla](https://www.linkedin.com/in/rizky-yovi-attalla-49103a410/)

*Special thanks to EkiZR for the original open-source base project.* ⭐
