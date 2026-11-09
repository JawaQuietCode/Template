# Base Bot Repository

Repository ini dibuat sebagai tempat berbagi dan mendokumentasikan berbagai **Base Bot WhatsApp** yang dikembangkan oleh Yowtech, partner, dan contributor.

Tujuan repository ini adalah menyediakan base bot yang dapat digunakan sebagai fondasi project baru, sekaligus menjaga dokumentasi penggunaan setiap base bot tetap berada di satu tempat bersama file base bot-nya.

Setiap developer dapat menambahkan base bot miliknya ke folder masing-masing. Setiap folder developer **wajib memiliki `README.md`** yang menjelaskan cara instalasi, konfigurasi, struktur, dan cara menjalankan base bot tersebut.

## Developer & Partner

- **Developer** : Yowtech
- **GitHub** : [Yowtech](https://github.com/Yowtech)
- **Base Bot** : [`Base-Bot/Yowtech/Base.zip`](Base-Bot/Yowtech/Base.zip)

- **Partner** :
- **GitHub** :
- **Base Bot** :

## Kontribusi Base Bot

Partner atau contributor dapat menambahkan base bot dengan pola berikut:

```text
Base-Bot/<Partner>/Base.zip
Base-Bot/<Partner>/README.md
```

Contoh:

```text
Base-Bot/PartnerName/
├── Base.zip
└── README.md
```

`README.md` wajib berada di dalam folder developer yang sama dengan `Base.zip`. Dokumentasi minimal harus menjelaskan:

- Nama base bot dan developer.
- Tanggal atau versi rilis.
- Dependency yang diperlukan.
- Cara instalasi dan menjalankan bot.
- Konfigurasi yang perlu diubah.
- Struktur dasar base bot.
- Command atau plugin bawaan.
- Catatan lisensi dan kredit bila diperlukan.

## Struktur Repository

```text
README.md
Base-Bot/
└── Yowtech/
    ├── Base.zip
    └── README.md
```

Base bot partner/contributor akan memiliki pola yang sama:

```text
Base-Bot/<Partner>/
├── Base.zip
└── README.md
```

## Aturan Penambahan Base Bot

1. Gunakan satu folder developer untuk satu base bot.
2. Nama file base bot wajib `Base.zip`.
3. Sertakan `README.md` di folder yang sama.
4. Jangan memasukkan session, credential, token, API key, atau data pribadi ke dalam ZIP.
5. Pastikan ZIP dapat diekstrak dan mengikuti instruksi pada README masing-masing.
6. Pertahankan struktur repository agar base bot dari developer lain mudah ditemukan.
