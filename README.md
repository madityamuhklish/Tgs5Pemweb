# Portofolio Static - M. Aditya Mukhlish

Website portofolio pribadi berbasis **HTML, CSS, JavaScript** murni (tanpa backend/PHP).  
Siap di-deploy ke **Vercel**.

## 🗂 Struktur File

```
portofolio-static/
├── index.html    ← halaman utama + semua fitur
├── style.css     ← semua styling
├── todo.js       ← floating to-do widget
└── foto.jpg      ← taruh foto profil kamu di sini
```

## ✅ Fitur

- **CRUD Project** — tambah, edit, hapus project lewat modal (data tersimpan di localStorage)
- **Inbox Pesan** — form Contact tersambung ke kotak pesan di navbar
- **To-Do Widget** — floating button pojok kanan bawah
- **Responsive** — mobile-friendly

## 🖼 Foto Profil

Taruh foto kamu di folder root dengan nama **`foto.jpg`** (atau `foto.png`, `foto.jpeg`). Kalau belum ada, akan tampil avatar inisial "MA".

> Karena Vercel itu static hosting, foto harus ikut di-commit ke GitHub.

---

## 🚀 Cara Deploy ke Vercel

### Langkah 1 — Push ke GitHub

```bash
cd portofolio-static
git init
git add .
git commit -m "Portofolio static - HTML CSS JS"
git branch -M main
git remote add origin https://github.com/madityamukhlish/NAMA-REPO.git
git push -u origin main
```

### Langkah 2 — Deploy ke Vercel

1. Buka **[vercel.com](https://vercel.com)** → login dengan akun GitHub
2. Klik **"Add New Project"**
3. Pilih repository portofolio kamu
4. Settings biarkan default (Framework Preset: **Other**)
5. Klik **"Deploy"**
6. Tunggu ~1 menit → dapat link `https://namamu.vercel.app` ✅

### Langkah 3 — Update (kalau ada perubahan)

```bash
git add .
git commit -m "Update portofolio"
git push
```
Vercel otomatis re-deploy setiap ada push baru ke GitHub.

---

## 📸 Untuk Screenshot Tugas

1. Buka `index.html` di browser (atau pakai link Vercel setelah deploy)
2. Screenshot: halaman utama lengkap
3. Screenshot: modal Tambah Project (isi form)
4. Screenshot: project baru muncul di grid
5. Screenshot: modal Edit Project
6. Screenshot: setelah project dihapus
7. Screenshot: isi form Contact → kirim → notif sukses
8. Screenshot: modal Inbox Pesan (pesan masuk)
9. Tempel semua ke Word → export PDF
