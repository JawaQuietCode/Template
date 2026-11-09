# Yowtech Bot Template

Template bot WhatsApp minimal berbasis Yowtech Baileys fork.

- **Base Bot** : [`Assets/Base-Bot/Yowtech.zip`](Assets/Base-Bot/Yowtech.zip)
- **Developer** : Yowtech
- **At** : 9 November 2026
- **GitHub** : [JawaQuietCode](https://github.com/JawaQuietCode)
- **License** : MIT

## Tentang Template

Template ini berisi sistem dasar bot WhatsApp dari Yowtech yang siap dikembangkan menjadi bot baru. Isi template difokuskan pada sistem inti, tanpa plugin produksi dari SC utama.

Plugin contoh yang disertakan hanya `Ping.js`, sehingga struktur pembuatan plugin dapat dipelajari dan dijadikan dasar untuk plugin berikutnya.

Fitur sistem yang tersedia meliputi:

- Core event handler untuk pesan, koneksi, group, presence, reaction, dan penghapusan pesan.
- Dynamic plugin loader dengan hot reload.
- Serialisasi pesan, quoted message, media, command, sender, dan permission.
- Database dasar untuk user, group, OTP, dan settings.
- Pairing code WhatsApp.
- Struktur folder modular pada `Cube/Core` dan `Cube/Lib`.

## Slot Partner dan Contributor

Repository ini juga menyediakan slot untuk base bot milik partner atau contributor Yowtech. Tambahkan file ZIP mereka ke folder berikut:

```text
Assets/Base-Bot/Partners/<Nama-Partner>.zip
```

Base bot utama tetap berada di:

```text
Assets/Base-Bot/Yowtech.zip
```

## Isi Base Bot

Setelah `Yowtech.zip` diekstrak, tersedia:

```text
Assets/
└── Environment/
Cube/
├── Core/
└── Lib/
database/
plugins/
└── Ping.js
index.js
package.json
settings.js
README.md
```

## Instalasi

1. Download [`Yowtech.zip`](Assets/Base-Bot/Yowtech.zip).
2. Ekstrak isi ZIP ke folder project bot.
3. Edit `settings.js` dan isi nomor bot, nomor owner, pairing code, serta konfigurasi lainnya.
4. Install dependency:

```bash
npm install
```

5. Jalankan bot:

```bash
npm start
```

6. Tambahkan plugin baru ke folder `plugins/`. Sistem akan memuat plugin secara dinamis dan melakukan hot reload ketika file plugin berubah.

## Plugin Contoh

```text
.ping
.p
```

> Memeriksa respons, latensi, uptime, dan penggunaan memory bot.

## Struktur Repository

Repository ini sengaja dibuat sederhana agar dokumentasi, base bot utama, dan base bot partner dapat dibagikan dalam satu tempat:

```text
README.md
Assets/
└── Base-Bot/
    ├── Yowtech.zip
    └── Partners/
        └── <Nama-Partner>.zip
```
