# AudioHub Demo

Edisi demo AudioHub untuk macOS: routing audio dengan fitur terbatas. Versi 0.3.0.

## Unduh dan pasang

1. Unduh **AudioHub-Demo-0.3.0.pkg** dari [Releases](https://github.com/khincc00/AudioHub_DEMO/releases/latest).
2. Klik dua kali file `.pkg`, lalu masukkan password admin.
3. Installer memasang dua hal:
   - `AudioHub Demo.app` ke folder Applications.
   - Driver perangkat virtual **AVHub v2** ke `/Library/Audio/Plug-Ins/HAL`. Perangkat **avhub_virtual1** (VC 1/2) dipakai di demo.
4. Jika VC 1/2 belum muncul, restart Mac.

Paket ini sudah ditandatangani Developer ID. Jika macOS memblokir karena belum dinotarisasi, buka **System Settings → Privacy & Security**, lalu pilih **Open Anyway**.

## Yang bisa dipakai

- Matriks routing, maksimal **8 route aktif**.
- Perangkat virtual **VC 1/2** (avhub_virtual1). Dipilih otomatis saat tersedia.
- Gain, mute, pan, solo, dan meter.

## Terkunci di edisi demo

Fitur berikut tampil di antarmuka, tetapi terkunci (ditandai gembok):

- VC 3/4 dan Loopback
- Tangkap audio per aplikasi
- Efek dan dinamika: gate, EQ, kompresor, delay, limiter, dan Audio Unit
- Rekaman
- Preset dan template

## Persyaratan

- macOS 13.0 atau lebih baru.
- Akses mikrofon diminta macOS saat input dipakai.

## Berlangganan

Untuk membuka semua fitur, beli edisi lengkap di:
http://lynk.id/khincc/y856pq2k9w9p/checkout

Info lebih lanjut: [khincreator.com](https://khincreator.com) · Situs resmi: [audiohub.khincreator.com](https://audiohub.khincreator.com)

## Lisensi

Lihat [LICENSE](LICENSE).
