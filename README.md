# Aplikasiku

Katalog publik aplikasi siap instal. Source code setiap aplikasi tetap di repository proyek masing-masing.

## Katalog aplikasi

| Aplikasi | Platform | Halaman unduhan |
|---|---|---|
| SmartMushroom | Android 7.0+ | [SmartMushroom](apps/smartmushroom/) |

## Struktur distribusi

- `main` adalah katalog bersama.
- `apps/<nama-aplikasi>/README.md` adalah halaman unduhan, petunjuk instalasi, dan informasi versi aplikasi tersebut.
- [GitHub Releases](https://github.com/Wahyu2003/aplikasiku/releases) menyimpan file instalasi dan aset pendukung. Setiap aplikasi memakai awalan tag yang unik, misalnya `smartmushroom-test-3-1`.
- Aset aplikasi, seperti APK dan model, dikelompokkan pada release aplikasi terkait, bukan dicampur dengan aplikasi lain.
- APK pengujian bukan rilis produksi.
