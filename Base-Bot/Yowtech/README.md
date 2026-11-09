# Yowtech Base Bot

- **Developer** : Yowtech
- **Base File** : `Base.zip`
- **Tanggal Rilis** : 9 November 2026
- **Repository** : [JawaQuietCode/Template](https://github.com/JawaQuietCode/Template)

## Tentang Base Bot

Base bot ini adalah template minimal WhatsApp berbasis Yowtech Baileys fork. Isinya hanya sistem inti dan satu plugin contoh `Ping.js`, sehingga dapat digunakan sebagai fondasi untuk membuat bot baru.

## Isi Sistem

- Core event handler untuk pesan, koneksi, group, presence, reaction, dan penghapusan pesan.
- Dynamic plugin loader dengan hot reload.
- Serialisasi pesan, quoted message, media, command, sender, dan permission.
- Database dasar untuk user, group, OTP, dan settings.
- Pairing code WhatsApp.
- Struktur modular `Cube/Core` dan `Cube/Lib`.

## Instalasi

1. Download `Base.zip` pada folder ini.
2. Ekstrak seluruh isi ZIP ke folder project.
3. Edit `settings.js` dan isi nomor bot, nomor owner, pairing code, serta konfigurasi lainnya.
4. Install dependency:

```bash
npm install
```

5. Jalankan bot:

```bash
npm start
```

## Plugin Bawaan

```text
.ping
.p
```

> Memeriksa respons, latensi, uptime, dan penggunaan memory bot.

Plugin baru dapat ditambahkan ke folder `plugins/`. Sistem akan memuat plugin secara dinamis dan melakukan hot reload ketika file berubah.
