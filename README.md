# CekLaptop

Uji laptop bekas langsung di tempat, dari browser — tanpa install apa pun. Cocok dipakai saat COD sama penjual: buka halamannya di laptop yang mau dibeli, jalankan semua tes, keluar laporan siap dikirim buat bahan nego.

**Live demo:** https://krpx0341.github.io/cek-laptop/

## Fitur

- **Tes interaktif** — dead pixel & backlight bleed, keyboard (termasuk deteksi chattering & rollover), touchpad/klik/scroll, layar sentuh multi-touch, speaker kiri/kanan, mikrofon, webcam, baterai.
- **Checklist manual** — fisik, sistem, legalitas & transaksi.
- **Toolkit lanjutan** — perintah bawaan Windows (battery report, SMART status, dxdiag, dll) dengan tombol salin, plus link unduh resmi tools portable (CrystalDiskInfo, HWiNFO, MemTest86, CPU-Z/GPU-Z).
- **Laporan otomatis** — ringkasan lolos/gagal/dilewati, bisa disalin, dikirim via WhatsApp, atau diunduh sebagai JSON.
- Semua berjalan lokal di browser — tidak ada data yang dikirim ke server mana pun.

## Menjalankan secara lokal

Ini murni file HTML statis, tidak butuh build step:

```bash
git clone https://github.com/krpx0341/cek-laptop.git
cd cek-laptop
# buka index.html langsung di browser, atau jalankan server statis:
python -m http.server 8080
```

## Kontribusi

Kontribusi terbuka untuk siapa saja — lihat [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan singkatnya.

## Lisensi

[GPL-3.0](LICENSE) — bebas dipakai, dimodifikasi, dan didistribusikan ulang, selama turunannya tetap open source di bawah lisensi yang sama.

## Kredit

Dibuat oleh [@menjelangpadam](https://instagram.com/menjelangpadam).
