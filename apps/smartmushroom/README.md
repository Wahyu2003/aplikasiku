# SmartMushroom

Aplikasi Android monitoring dan kontrol kumbung jamur tiram.

## Unduhan

- [SmartMushroom 1.0 APK](https://github.com/Wahyu2003/aplikasiku/releases/download/smartmushroom-test-3-1/SmartMushroom.apk) — Android 7.0+, versi pengujian, debug signing.
- [Halaman release SmartMushroom](https://github.com/Wahyu2003/aplikasiku/releases/tag/smartmushroom-test-3-1)

## Model prediksi hujan

Kedua paket model asli telah diperiksa terhadap struktur format SMMODEL v1 (100 pohon Random Forest, 9 fitur, horizon 6 jam). File model masih menunggu unggahan sebagai aset release.

| File | Penggunaan | Ukuran (byte) | SHA-256 |
|---|---|---:|---|
| Cindogo_Kumbung.smmodel | Model lokasi Cindogo Kumbung | 2857530 | `cb0be45ab93c8950961712b3926cce19a8d89899affce23dfab69b51068e58d2` |
| Jember.smmodel | Model lokasi Jember | 3466170 | `60fd9635c4a706e70060613b0c9bc5536216fd5fe502a80445bfe9ee43880c8b` |

## Instalasi

1. Unduh dan instal APK.
2. Unduh model lokasi yang diperlukan setelah tersedia pada release.
3. Pada aplikasi, buka Pengaturan → Model Prediksi Cuaca → IMPORT .SMMODEL.
4. Pilih file asli .smmodel (jangan ekstrak ZIP internal), kemudian aktifkan model dari daftar Model Tersimpan.

Monitoring dan kontrol manual dapat digunakan tanpa model; mode otomatis membutuhkan model aktif. Pengujian kompatibilitas perangkat dan hasil prediksi tetap diperlukan.
