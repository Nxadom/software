# NxCode Software

Repository untuk distribusi **NxCode** — installer Windows tidak disimpan di Git karena batas ukuran file GitHub (100 MB).

## Download

### Versi terbaru: 1.0.4

| | Link |
|---|---|
| **Halaman release** | https://github.com/Nxadom/software/releases/tag/v1.0.4 |
| **Download langsung** | https://github.com/Nxadom/software/releases/download/v1.0.4/NxCode-Setup-1.0.4.exe |

Semua release: https://github.com/Nxadom/software/releases

## Instalasi

1. Klik link **Download langsung** di atas, atau buka halaman release dan klik `NxCode-Setup-1.0.4.exe`.
2. Simpan file ke komputer.
3. Jalankan `NxCode-Setup-1.0.4.exe` dan ikuti petunjuk di layar.

## Untuk maintainer — membuat Release baru

Installer `.exe` **jangan** di-commit ke repo (sudah di-ignore lewat `.gitignore`).

1. Buka https://github.com/Nxadom/software/releases
2. Klik **Draft a new release**
3. Tag: `v1.0.5` (contoh) — Title: `NxCode 1.0.5`
4. Attach file installer dari folder lokal
5. Release label: **None** — tunggu upload selesai — klik **Publish release**

Link download otomatis mengikuti pola:

`https://github.com/Nxadom/software/releases/download/<tag>/<nama-file.exe>`

Contoh: `https://github.com/Nxadom/software/releases/download/v1.0.4/NxCode-Setup-1.0.4.exe`