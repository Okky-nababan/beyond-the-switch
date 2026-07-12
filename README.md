# Beyond The Switch — Landing Page Pendaftaran

Website statis untuk pendaftaran seminar **Beyond The Switch**, siap di-deploy gratis lewat GitHub Pages.

## Isi folder
```
index.html          -> halaman utama (semua CSS ada di dalamnya, tidak perlu file terpisah)
assets/
  hero-bg.jpg        -> foto latar hero (pembangkit + kota)
  transformer.jpg    -> foto transformer (cadangan, belum dipakai di halaman)
  city.jpg           -> foto kota malam (latar section pendaftaran)
  speaker.jpg        -> foto Anda (pembicara)
```

## Cara Deploy ke GitHub Pages (tanpa vendor, gratis selamanya)

### Langkah 1 — Buat repository baru
1. Login ke [github.com](https://github.com).
2. Klik tombol **+** di kanan atas → **New repository**.
3. Nama repo, contoh: `beyond-the-switch`.
4. Set ke **Public**.
5. **Jangan** centang "Add a README file" (kita sudah punya).
6. Klik **Create repository**.

### Langkah 2 — Upload file
Cara termudah (tanpa command line):
1. Di halaman repo yang baru dibuat, klik **"uploading an existing file"**.
2. Drag & drop **semua isi folder ini** (`index.html`, `README.md`, dan folder `assets` beserta isinya).
3. Klik **Commit changes**.

> Catatan: pastikan struktur foldernya tetap `assets/nama-file.jpg`, jangan sampai file di dalam `assets` ter-upload ke root repo.

### Langkah 3 — Aktifkan GitHub Pages
1. Di repo, buka tab **Settings**.
2. Di sidebar kiri, klik **Pages**.
3. Pada **Branch**, pilih `main` dan folder `/ (root)`.
4. Klik **Save**.
5. Tunggu 1–2 menit, lalu refresh halaman itu — akan muncul link:
   ```
   https://<username-github-anda>.github.io/beyond-the-switch/
   ```

Link itulah yang bisa Anda pakai sebagai **link pendaftaran resmi** — bisa dipasang di bio Instagram, video iklan, poster, dsb. Jauh lebih profesional dibanding link Google Form mentah.

### (Opsional) Custom domain
Jika suatu saat Anda punya domain sendiri (misal `beyondtheswitch.id` seperti yang tertera di sertifikat), domain itu bisa diarahkan ke GitHub Pages ini lewat menu **Settings → Pages → Custom domain**.

## Mengubah isi halaman
Semua teks ada langsung di `index.html` dalam Bahasa Indonesia biasa (bukan kode rumit) — cari teks yang ingin diubah, edit langsung di GitHub (tombol pensil ✏️ saat membuka file), lalu **Commit changes**. Perubahan otomatis live dalam 1–2 menit.

Bagian yang paling mungkin perlu diupdate:
- **Jadwal**: cari teks `Segera Diumumkan` (muncul 2 kali) → ganti dengan tanggal & waktu final.
- **Link formulir**: cari `docs.google.com/forms/d/e/...` (muncul 2 kali: di `src` iframe dan di link fallback) → ganti jika Anda membuat form baru.

## Menghubungkan ke link pendek (opsional)
Jika ingin link lebih pendek/mudah diingat untuk dicantumkan di poster cetak, gunakan layanan seperti [Bitly](https://bitly.com) atau [TinyURL](https://tinyurl.com) untuk membuat alias yang mengarah ke link GitHub Pages di atas.
