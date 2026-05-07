# 🏫 Sistem Pengurusan Aset Sekolah

Aplikasi web untuk merekod dan memantau semua aset sekolah — berjalan sepenuhnya di pelayar web, tanpa memerlukan pelayan atau pangkalan data.

## ✨ Ciri-ciri

- 📋 **Rekod Lengkap** — Nama, No. Aset, Kategori, Lokasi, Status, Nilai, Pembekal, No. Siri, Pengguna
- 📊 **Papan Pemuka** — Ringkasan statistik dan status aset terkini
- 🔍 **Cari & Tapis** — Cari mengikut nama, kategori, atau status
- 📈 **Laporan** — Graf taburan status dan analisis mengikut kategori & lokasi
- 💾 **Eksport** — JSON, CSV, atau cetak/PDF
- 📥 **Import** — Muat naik semula data JSON
- 🌐 **Offline** — Berfungsi tanpa internet (data disimpan di browser)

## 🚀 Deploy ke GitHub Pages

1. Fork atau upload fail `index.html` ke repositori GitHub baru
2. Pergi ke **Settings → Pages**
3. Pilih branch `main`, folder `/ (root)`
4. Klik **Save**
5. URL anda: `https://[username].github.io/[repo-name]/`

## 💾 Cara Simpan Data ke GitHub

Untuk backup data ke GitHub:
1. Dalam aplikasi, klik **Eksport → JSON**
2. Fail `assets.json` akan dimuat turun
3. Commit fail tersebut ke repo anda di path `data/assets.json`
4. Untuk pulihkan, guna fungsi **Import** dalam aplikasi

## 📁 Struktur Repo (Cadangan)

```
repo/
├── index.html          ← Aplikasi utama
├── README.md           ← Fail ini
└── data/
    └── assets.json     ← Backup data aset (eksport dari app)
```

---
Dibina untuk kegunaan sekolah di Malaysia 🇲🇾
