# 🕵️ tikkepo

> Script Python untuk mengotomatisasi proses penggalian informasi publik dari akun TikTok untuk keperluan **OSINT** (Open Source Intelligence).

---

## 📌 Deskripsi

**tikkepo** adalah alat OSINT berbasis Python yang dikembangkan untuk mengotomatisasi proses penggalian informasi publik dari akun TikTok. Cocok digunakan untuk keperluan riset, investigasi digital, dan pengumpulan data publik secara legal dan etis.

---

## ⚙️ Instalasi

```bash
$ git clone https://github.com/spyschools/tikkepo.git
$ cd tikkepo
```

### Install Dependencies

```bash
$ pip3 install beautifulsoup4
$ pip3 install requests
$ pip3 install argparse
```

---

## 🚀 Penggunaan

```bash
$ python3 tik_stalker_fixed.py -u usernametiktok
```

Ganti `usernametiktok` dengan username TikTok yang ingin kamu telusuri.

**Contoh:**

```bash
$ python3 tik_stalker_fixed.py -u johndoe
```

---

## 📦 Dependencies

| Library | Kegunaan |
|---|---|
| `beautifulsoup4` | Parsing HTML dari halaman TikTok |
| `requests` | Mengirim HTTP request ke server TikTok |
| `argparse` | Parsing argumen dari command line |

---

## ⚠️ Disclaimer

> Alat ini dibuat **hanya untuk tujuan edukasi dan penelitian**. Penggunaan alat ini untuk tujuan ilegal, melanggar privasi orang lain, atau menyalahi syarat layanan TikTok sepenuhnya menjadi **tanggung jawab pengguna**. Pengembang tidak bertanggung jawab atas penyalahgunaan alat ini.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

## 🔗 Repository

[https://github.com/spyschools/tikkepo](https://github.com/spyschools/tikkepo)
