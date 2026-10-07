# VoxelLabs Mobile - Official Developer Portal & Universal Legal Suite

Website resmi pengembang game mobile **VoxelLabs Mobile** yang di-host gratis di **GitHub Pages** (`https://voxellabsmobile.github.io/`). 

Dokumen hukum di dalam website ini dirancang bersifat **GENERAL (Universal)**, artinya dapat digunakan sebagai payung hukum untuk **SELURUH game dan aplikasi** yang Anda publikasikan di **Google Play Console** saat ini maupun di masa mendatang (game teka-teki, trivia, arcade, puzzle, aksi, casual, dsb.) tanpa perlu membuat dokumen baru setiap kali merilis game baru.

---

## 📂 Struktur File Website

```text
developer_website/
├── index.html            <- Halaman Utama (Branding Studio, Katalog Game, Fitur, Support Desk)
├── privacy-policy.html   <- Kebijakan Privasi General & Data Safety (Universal untuk SEMUA Game)
├── disclaimer.html       <- Legal Disclaimer General, HAKI & Anti-Trademark Trolling (Perisai Pemerasan)
├── terms.html            <- Ketentuan Layanan General (Terms of Service, Anti-Cheat, Non-Refundable Items)
├── style.css             <- Tema Dark-Arcade Modern, Responsif, Glassmorphism, 100% Mobile Friendly
└── README.md             <- Panduan ini
```

---

## 🛡️ Tiga Lapisan Perlindungan Hukum General (Universal Legal Shield)

### 1. `privacy-policy.html` (Perlindungan Kebijakan Google Play untuk Semua Game)
* **Bersifat Universal (General):** Melindungi semua aplikasi di bawah akun developer **VoxelLabs Mobile**.
* **Kepatuhan Data Safety & Jaringan Iklan (Mediation Ready):** Mendeklarasikan secara transparan pengolahan data lokal, leaderboard cloud (Firestore), analitik crash (Firebase Crashlytics), serta dukungan penuh jaringan iklan dan mediasi: **Google Mobile Ads (AdMob Next-Gen SDK)**, **AppLovin (MAX)**, **Meta Audience Network**, **Vungle (Liftoff Mobile)**, dan **Unity Ads**.
* **Kepatuhan Kebijakan Keluarga & Anak (COPPA & GDPR):** Menjamin kepatuhan standar filter iklan ramah keluarga dengan transmisi flag COPPA otomatis ke jaringan partner.
* **Mekanisme Penghapusan Data Wajib (Account & Data Deletion Policy):** Memenuhi syarat wajib Google Play dengan panduan hapus data lokal (Clear Cache) dan prosedur penghapusan data online leaderboard via email ke `voxellabsmobile@gmail.com` untuk game apa pun.

### 2. `disclaimer.html` (Perlindungan dari Trademark Trolls & Pemerasan Tebusan)
* **Doktrin Nominative Fair Use (Lanham Act 15 U.S.C. § 1115(b)(4)):** Menjelaskan bahwa segala referensi budaya pop, nama karya, atau istilah umum dalam teka-teki/game digunakan murni untuk tujuan identifikasi trivia/hiburan, tanpa mengklaim kepemilikan merek pihak lain.
* **Game Mechanics & Idea-Expression Dichotomy (17 U.S.C. § 102(b)):** Menegaskan bahwa aturan main, mekanisme teka-teki, dan sistem kalkulasi game adalah ide terbuka yang tidak bisa dimonopoli pihak lain.
* **Standar Terbuka Unicode & Font Bebas Lisensi:** Melindungi penggunaan emoji universal dan aset open-source.
* **Klausul Tegas Anti-Pemerasan (*Zero-Ransom & Counter-Claim Policy*):** Menolak segala bentuk tuntutan uang damai dari pihak yang memperkarakan kata-kata generik atau umum (seperti "Emoji", "Trivia", "Puzzle", "Match", "Hero", "Runner", dll.). Memberikan ancaman balik gugatan ganti rugi atas gangguan bisnis (*tortious interference*).
* **Prosedur Safe Harbor 48-72 Jam:** Jika ada pemilik hak cipta sah yang mengajukan keberatan resmi, VoxelLabs Mobile berkomitmen meninjau dan menghapus konten tersebut secara damai dalam 48–72 jam kerja tanpa perlu tuntutan hukum atau denda uang.

### 3. `terms.html` (Ketentuan Layanan Finansial & Operasional)
* **Nilai Moneter Nol (*Zero Real-World Value*):** Menegaskan seluruh item virtual (koin, bintang, hint, nyawa, skin, level pass) di semua game tidak memiliki nilai uang riil dan tidak dapat diuangkan.
* **Larangan Cheating & Modifikasi Binary APK:** Melarang penggunaan bot, auto-clicker, modding APK, dan manipulasi skor server.
* **Batasan Tanggung Jawab & Mediasi Wajib 60 Hari:** Mengharuskan penyelesaian sengketa melalui jalur musyawarah tertulis selama 60 hari terlebih dahulu.

---

## 🚀 Panduan Setup di GitHub Pages (Gratis & 2 Menit Selesai)

1. Buka akun GitHub Anda.
2. Buat repository baru dengan nama persis:
   ```text
   voxellabsmobile.github.io
   ```
3. Pastikan visibility diset **Public**.
4. Upload semua file dari folder `developer_website/` ini:
   - `index.html`
   - `privacy-policy.html`
   - `disclaimer.html`
   - `terms.html`
   - `style.css`
   *(Pastikan file langsung diletakkan di root repository, bukan di dalam subfolder)*.
5. Buka menu **Settings > Pages** di repository GitHub Anda:
   - **Build and deployment Source:** `Deploy from a branch`
   - **Branch:** `main` (atau `master`) -> folder `/(root)` -> Klik **Save**.
6. Website langsung online aktif di:
   - **Portal Resmi Pengembang:** `https://voxellabsmobile.github.io/`
   - **General Privacy Policy:** `https://voxellabsmobile.github.io/privacy-policy.html`
   - **General Disclaimer & IP:** `https://voxellabsmobile.github.io/disclaimer.html`
   - **General Terms of Service:** `https://voxellabsmobile.github.io/terms.html`

---

## 📋 Data untuk Google Play Console (Bisa Dipakai Berulang Kali)

Untuk **setiap game** yang Anda daftarkan di Google Play Console (sekarang maupun nanti), Anda cukup menggunakan link yang sama:

| Menu di Google Play Console | Field Input | Nilai yang Harus Diisi |
| :--- | :--- | :--- |
| **Developer Account Details** | Developer Name | `VoxelLabs Mobile` |
| **Developer Account Details** | Developer Website | `https://voxellabsmobile.github.io/` |
| **Developer Account Details** | Contact Email | `voxellabsmobile@gmail.com` |
| **App Content > Privacy Policy** *(Setiap Game)* | Privacy policy URL | `https://voxellabsmobile.github.io/privacy-policy.html` |
| **Store Settings** *(Setiap Game)* | Website | `https://voxellabsmobile.github.io/` |
| **Store Settings** *(Setiap Game)* | Email | `voxellabsmobile@gmail.com` |
