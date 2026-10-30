# Absensi Mahasiswa (Flutter)

UTS Mobile Programming (SI34006) – Dosen: Novario Jaya Perdana, S.Kom., M.T.
Topik 9: Aplikasi Absensi Mahasiswa – Kelompok 4

## Anggota

| Nama | NIM | Bagian yang dikerjakan |
|---|---|---|
| Chetrin | 825230185 | Pilih Peran, Dashboard Mahasiswa, Notifikasi, main.dart |
| Tepen | 825240054 | Check-in (mockup QR dan lokasi), Riwayat Kehadiran, Statistik Kehadiran |
| Nando | 825240109 | Dashboard Dosen (Harian, Mingguan, QR Code Kelas), navigasi bawah mahasiswa Data dummy, tema warna, widget |

## Deskripsi

Aplikasi pencatatan kehadiran kuliah dengan dua peran, **Mahasiswa** dan **Dosen**.
Fokus UTS adalah UI/layout; seluruh data memakai data dummy (`lib/data/dummy_data.dart`).
QR scanner dan lokasi hanya mockup tampilan.

## Halaman (sesuai soal topik 9)

| Halaman soal | File |
|---|---|
| Dashboard Mahasiswa: mata kuliah dan status kehadiran | `lib/pages/dashboard_mahasiswa_page.dart` |
| Check-in: mockup QR scanner, lokasi, hasil check-in | `lib/pages/checkin_page.dart` |
| Riwayat Kehadiran (filter per mata kuliah) | `lib/pages/riwayat_page.dart` |
| Statistik Kehadiran: persentase hadir/izin/alpa | `lib/pages/statistik_page.dart` |
| Dashboard Dosen: ringkasan harian/mingguan, QR Code kelas | `lib/pages/dashboard_dosen_page.dart` |
| Tambahan: Pilih Peran, Notifikasi tidak hadir, navigasi bawah | `pilih_peran_page.dart`, `notifikasi_page.dart`, `main_nav_page.dart` |

## Fitur utama (mockup)

1. Absensi lewat QR code / lokasi: tab Check-in (mahasiswa) dan QR Code Kelas (dosen).
2. Statistik kehadiran per mata kuliah: tab Statistik.
3. Notifikasi saat tidak hadir: tab Notifikasi.
4. Dashboard dosen harian dan mingguan.

## Menjalankan

```bash
flutter pub get
flutter run
```

Jalankan di emulator atau HP Android.

## Struktur folder

```
lib/
├── main.dart
├── data/dummy_data.dart
├── pages/
├── theme/app_theme.dart
└── widgets/
```
