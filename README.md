# 💖 Happy National My Girl Day

Website sederhana dan romantis untuk **National My Girl Day**.

Fitur utama:

- 🌱 Siram bunga sampai mekar
- 💌 Surat cinta interaktif
- 🎁 Pilihan hadiah PAP atau VN Kiss
- ❤️ Hujan emoji romantis
- 🎵 Musik latar
- 📱 Tampilan responsif untuk HP
- 🌐 Siap dipasang di GitHub Pages

## Struktur File

Pastikan isi repository seperti ini:

```text
.
├── index.html
├── pacar.jpg
├── musik.mp3
└── README.md
```

### File yang perlu kamu tambahkan sendiri

`pacar.jpg`  
Foto yang ingin ditampilkan di halaman utama.

`musik.mp3`  
Musik romantis yang ingin diputar sebagai background.

Nama kedua file tersebut harus sama persis dengan yang ada di atas, termasuk huruf besar/kecil.

## Cara Upload ke GitHub

1. Buat repository baru di GitHub.
2. Upload `index.html`, `README.md`, `pacar.jpg`, dan `musik.mp3`.
3. Commit semua file ke branch `main`.
4. Buka **Settings** repository.
5. Masuk ke menu **Pages**.
6. Pada bagian **Build and deployment**, pilih:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. Klik **Save**.

Setelah GitHub Pages selesai melakukan deployment, website bisa dibuka melalui alamat seperti:

```text
https://USERNAME.github.io/NAMA-REPOSITORY/
```

Contoh:

```text
https://namakamu.github.io/my-girl/
```

## Mengganti Isi Surat

Buka `index.html`, lalu cari bagian:

```html
<div id="surat-box" class="surat-box">
```

Kamu bisa mengganti semua isi paragraf di dalam bagian tersebut sesuai pesan yang kamu inginkan.

## Mengganti Pilihan Hadiah

Cari bagian:

```html
onclick="pilihHadiah('PAP Ganteng Kamu 📸')"
```

dan:

```html
onclick="pilihHadiah('VN Kiss Kamu 💋')"
```

Ganti teks di dalam tanda kutip sesuai hadiah yang kamu mau.

## Catatan Musik

Browser modern biasanya tidak mengizinkan musik autoplay sebelum pengguna melakukan interaksi.

Karena itu, website ini mulai mencoba memutar musik setelah tombol **Siram Bunga** ditekan. Ini memang sengaja dibuat agar lebih kompatibel dengan browser HP.

## GitHub Pages

Website ini hanya menggunakan:

- HTML
- CSS
- JavaScript

Jadi tidak membutuhkan Node.js, database, atau server tambahan.

---

Made with ❤️ for someone special.
