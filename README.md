# IF25-22017 — Pengembangan Aplikasi Mobile

Mata kuliah ini mempelajari pengembangan aplikasi mobile multiplatform menggunakan **Kotlin Multiplatform (KMP)** dan **Compose Multiplatform**. Mahasiswa belajar membuat aplikasi yang berjalan di Android dan iOS dengan satu codebase, termasuk integrasi dengan sistem cerdas (AI).

Kelas ini **tanpa UTS**. Pertemuan 1 sampai 10 adalah materi dengan latihan yang diobservasi setiap pertemuan. Pertemuan 11 sampai 16 adalah proyek kelompok yang dinilai lewat tes lisan, ditutup Demo Day di jadwal UAS.

## Identitas Mata Kuliah

| DATA | DEKSRIPSI |
|---|---|
| Nama | Pengembangan Aplikasi Mobile |
| Kode | IF25-22017 |
| Rumpun | Rekayasa Perangkat Lunak dan Sistem Informasi |
| Bobot (Teori - Praktikum) SKS | 3 (3-0) SKS |
| Semester | Ganjil/Genap |
| Matakuliah Syarat | IF25-21012, IF25-21009 |
| Team Teaching | Muhammad Habib Algifari, S.Kom., M.T.I. |

## Capaian Pembelajaran

**CPL05** — Mampu menganalisis dan menerapkan konsep rekayasa perangkat lunak untuk pengembangan sistem cerdas secara profesional.

| CPMK | Deskripsi | CPL didukung |
|---|---|---|
| CPMK0501 | Mahasiswa mampu menerapkan konsep pemrograman untuk pengembangan perangkat lunak | CPL05 |
| CPMK0502 | Mahasiswa mampu menjelaskan konsep pemrograman untuk pengembangan perangkat lunak | CPL05 |
| CPMK0503 | Mahasiswa mampu menerapkan teknologi sistem cerdas dalam pengembangan perangkat lunak | CPL05 |

## Materi Pembelajaran / Pokok Bahasan

Intro KMP, Setup Environment, Hello World; Advanced Kotlin (Coroutines, Flow); Compose Multiplatform Basics; State Management (MVVM, ViewModel); Navigasi Antar Layar, Passing Data; Networking (Ktor Client, JSON); Local Data Persistence; Platform Specific Code; Sensor; Integrasi Sistem Cerdas (AI API); Testing dan Dependency Injection.

## Jadwal Pertemuan

Kolom **Minggu RPS** menunjukkan minggu RPS yang menjadi sumber setiap pertemuan. Karena tidak ada UTS, minggu RPS 9 sampai 11 dimajukan menjadi pertemuan 8 sampai 10.

### Bagian 1: Materi (Pertemuan 1–10)

| Pertemuan | Minggu RPS | CPMK | Topik | Asesmen | Bobot |
|---|---|---|---|---|---|
| 1 | 1 | CPMK0502 | Kontrak kuliah, kenalan dengan KMP, dan setup environment | Observasi: environment dan Hello World KMP | 4% |
| 2 | 2 | CPMK0501, CPMK0502 | Model data, Coroutines, dan Flow | Observasi: Coroutines dan Flow | 4% |
| 3 | 3 | CPMK0501 | Dasar Compose Multiplatform | Observasi: UI terstruktur dengan Compose | 4% |
| 4 | 4 | CPMK0501 | State dan MVVM | Observasi: MVVM pada aplikasi catatan | 4% |
| 5 | 5 | CPMK0501 | Navigasi antar layar dan passing data | Observasi: navigasi dengan passing data | 4% |
| 6 | 6 | CPMK0501 | Networking REST API dengan Ktor | Observasi: data REST API beserta keadaan memuat dan error | 4% |
| 7 | 7 | CPMK0501 | Penyimpanan lokal dan offline-first | Observasi: data lokal yang bertahan offline | 4% |
| 8 | 9 | CPMK0501 | Fitur khusus platform (expect/actual, permissions, Koin) | Observasi: fitur platform di Android dan iOS | 4% |
| 9 | 10 | CPMK0503 | Integrasi AI dengan Gemini | Observasi: fitur AI di aplikasi; tugas laporan proyek dibagikan | 4% |
| 10 | 11 | CPMK0502 | Testing, Dependency Injection, dan Debugging | Observasi: test dan DI | 4% |

### Bagian 2: Proyek Kelompok (Pertemuan 11–16)

| Pertemuan | Minggu RPS | CPMK | Topik | Asesmen | Bobot |
|---|---|---|---|---|---|
| 11 | 12 | CPMK0501, CPMK0502 | Sprint 1: perencanaan, arsitektur, dan CI | Formatif, menyiapkan tes lisan 1 | — |
| 12 | 12 | CPMK0501, CPMK0502 | Sprint 2: fitur utama dan code review | Tes lisan 1: perencanaan dan fitur utama | 10% |
| 13 | 13 | CPMK0501 | Fitur lanjutan dan performa | Tes lisan 2: fitur lanjutan | 5% |
| 14 | 14 | CPMK0501 | UI/UX, aksesibilitas, dan testing | Tes lisan 3: stabil dan terdokumentasi | 5% |
| 15 | 15 | CPMK0501, CPMK0502, CPMK0503 | Rilis, dokumentasi, dan persiapan demo | Formatif, gladi Demo Day | — |
| 16 | 15 (jadwal UAS) | CPMK0501, CPMK0502, CPMK0503 | **Demo Day** | Tes lisan final: demo, live code review, dan tanya jawab | 35% |

Laporan hasil proyek (5%) dibagikan di pertemuan 9 dan dikumpulkan sebelum pertemuan 16.

Proyek kelompok sudah dikerjakan sejak pertemuan 1 lewat checkpoint mingguan. Checkpoint tidak masuk nilai, tetapi menjadi bekal tes lisan.

## Penilaian

| Kriteria | CPMK0503 | CPMK0501 | CPMK0502 | Total Bobot |
|---|---|---|---|---|
| Observasi (Praktik), individu, pertemuan 1–10 | 4 | 26 | 10 | 40 |
| Laporan Hasil Proyek, kelompok | 5 | 0 | 0 | 5 |
| Tes Lisan (Tugas Kelompok), pertemuan 12–16 | 0 | 35 | 20 | 55 |
| **Total Bobot per CPMK** | **9** | **61** | **30** | **100** |

### Rincian tes lisan

| Asesmen | Pertemuan | Kriteria | CPMK | Bobot |
|---|---|---|---|---|
| Tes lisan 1 | 12 | Perencanaan dan repository (dinilai per anggota) | CPMK0502 | 5% |
| | | Fitur utama berfungsi | CPMK0501 | 5% |
| Tes lisan 2 | 13 | Fitur lanjutan terintegrasi | CPMK0501 | 5% |
| Tes lisan 3 | 14 | Aplikasi stabil dan terdokumentasi | CPMK0501 | 5% |
| Tes lisan final | 16 | Kelengkapan fitur | CPMK0501 | 8% |
| | | Kualitas kode | CPMK0501 | 6% |
| | | Kelancaran demo | CPMK0501 | 6% |
| | | Presentasi (dinilai per anggota) | CPMK0502 | 5% |
| | | Tanya jawab kode (dinilai per anggota) | CPMK0502 | 10% |
| Laporan hasil proyek | sebelum 16 | Desain prompt dan evaluasi keluaran AI | CPMK0503 | 5% |

Setiap kriteria dinilai dengan rubrik empat level: **Sangat baik** (85–100), **Baik** (70–84), **Cukup** (55–69), dan **Kurang** (di bawah 55). Anggota tanpa commit bermakna di bagian yang dinilai mendapat level Kurang pada kriteria kelompok. Rubrik lengkap ada di slide setiap pertemuan dan di dokumen RPS.

## Pustaka

**Utama:**

1. Dokumentasi KMP

**Pendukung:**

2. Panduan Proyek
3. Android Studio
4. Dokumentasi Kotlin
5. Dokumentasi API OpenAI/Gemini

## Media Pembelajaran

- **Software:** Framework Kotlin Multiplatform, Android Studio, GitHub, YouTube, dan lain-lain
- **Hardware:** Mobile Device, Komputer Lab, dan Laptop

## Struktur Repo

### Slide

Folder `Slide/` berisi slide PDF untuk kontrak kuliah dan ke-16 pertemuan:

| File | Pertemuan |
|---|---|
| `00 Kontrak Kuliah PAM IF25-22017.pdf` | 1, bagian pembuka |
| `P1 Kenalan dengan KMP dan Siapkan Alat.pdf` | 1 |
| `P2 Model Data, Coroutines, dan Flow.pdf` | 2 |
| `P3 Dasar Compose Multiplatform.pdf` | 3 |
| `P4 State dan MVVM.pdf` | 4 |
| `P5 Navigasi Antar Layar.pdf` | 5 |
| `P6 Networking REST API dengan Ktor.pdf` | 6 |
| `P7 Penyimpanan Lokal dan Offline-first.pdf` | 7 |
| `P8 Fitur Khusus Platform.pdf` | 8 |
| `P9 Integrasi AI dengan Gemini.pdf` | 9 |
| `P10 Testing, Dependency Injection, dan Debugging.pdf` | 10 |
| `P11 Sprint 1 Perencanaan, Arsitektur, dan CI.pdf` | 11 |
| `P12 Sprint 2 Fitur Utama, Code Review, dan Tes Lisan 1.pdf` | 12 |
| `P13 Fitur Lanjutan, Performa, dan Tes Lisan 2.pdf` | 13 |
| `P14 UI-UX, Aksesibilitas, dan Tes Lisan 3.pdf` | 14 |
| `P15 Rilis dan dokumentasi.pdf` | 15 |
| `P16 Demo Day.pdf` | 16 |

Seluruh slide memakai aplikasi kelas yang sama, **LaporKampus**, sebagai contoh berjalan dari pertemuan ke pertemuan.

### Hands-on materi (Pertemuan 1–10)

Setiap folder `P{n} - {Topik} - Hands-on/` berisi proyek **Kotlin Multiplatform + Compose Multiplatform** nyata (modul `composeApp` dengan `commonMain`/`androidMain`/`iosMain`/`desktopMain`), dengan 3 latihan dan solusinya per pertemuan. Latihan inilah yang diobservasi untuk nilai observasi praktik.

| Folder | Pertemuan | Topik |
|---|---|---|
| `P1 - Pengenalan MK dan Setup Environment - Hands-on/` | 1 | Intro KMP, setup environment, expect/actual, Compose dasar |
| `P2 - Advanced Kotlin Coroutines Flow - Hands-on/` | 2 | Advanced Kotlin, Coroutines & Flow (proyek Kotlin/JVM biasa) |
| `P3 - Compose Multiplatform Basics - Hands-on/` | 3 | Layout, LazyColumn, custom component |
| `P4 - State Management MVVM - Hands-on/` | 4 | ViewModel, StateFlow, UDF |
| `P5 - Navigasi Antar Layar - Hands-on/` | 5 | NavHost, passing data, Bottom Navigation |
| `P6 - Networking REST API - Hands-on/` | 6 | Ktor Client, JSON, Repository Pattern |
| `P7 - Local Data Storage - Hands-on/` | 7 | SQLDelight, offline-first |
| `P8 - Platform Specific Features - Hands-on/` | 8 | expect/actual lanjutan, permissions, Koin DI |
| `P9 - Integrasi AI API - Hands-on/` | 9 | Integrasi Gemini, prompt, layar chat |
| `P10 - Testing dan DI - Hands-on/` | 10 | Unit test, test doubles, Koin DI |

Pertemuan 11 sampai 16 tidak punya hands-on materi baru, karena latihannya dikerjakan langsung di repository proyek kelompok.

Catatan:

- Proyek `P1, P3–P10` tidak menyertakan folder `iosApp/` (proyek Xcode). Lihat README masing-masing folder untuk cara menambahkannya via [kmp.jetbrains.com](https://kmp.jetbrains.com).
- Proyek belum di-build atau diverifikasi penuh, karena lingkungan pembuatannya tidak punya Android SDK atau Xcode. Lakukan Gradle sync di Android Studio sebelum dipakai di kelas.

**Solusi tidak ikut di-commit.** Setiap folder hands-on punya subfolder atau modul `solusi/` (atau `handson{n}-solusi/`) berisi jawaban lengkap. Folder ini di-`.gitignore` di tiap proyek, jadi mahasiswa yang clone repo hanya mendapat soal `latihan/`. Jawaban dipegang dan dibagikan terpisah oleh pengajar.

### Materi suplemen: Kotlin Dasar

`Kotlin Dasar/` berisi 13 pertemuan slide dan hands-on Kotlin dasar (Kotlin/JVM biasa, bukan KMP) untuk memperkuat fondasi Kotlin. Materi ini dipakai mandiri di tiga pertemuan awal, sebelum materi inti KMP makin dalam:

`P1 - Introduction to Kotlin`, `P2 - Object-Oriented Programming`, `P3 - Generics`, `P4 - Collections and co.`, `P5 - Functional Programming`, `P6 - Parallel and Concurrent Programming`, `P7 - Asynchronous Programming in Kotlin`, `P8 - Exceptions`, `P9 - Testing`, `P10 - Build Systems`, `P11 - The Java Virtual Machine and the Kotlin Compiler`, `P12 - Reflection (JVM)`, `P13 - Backend Development Basics`.

Masing-masing punya folder `P{n} - {Topik} - Hands-on/` (modul `handson{n}-latihan` dan `handson{n}-solusi`). Solusinya juga di-gitignore.

### Lainnya

- `RPS_MK_IF25-22017.pdf` — Rencana Pembelajaran Semester lengkap, sumber data capaian, bobot, dan indikator di atas.
