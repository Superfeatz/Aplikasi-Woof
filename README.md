| Nama  | NRP         |
|--------|------------|
| Muhammad Hafidz Harridil Mahali | 5025221030 |

# 🐶 Aplikasi Woof

Selamat datang di repositori **Woof**!
Aplikasi ini merupakan hasil dari pembelajaran saya sebagai mahasiswa dalam memahami dan menerapkan **Material Design** menggunakan **Jetpack Compose** di Android Studio.

## 📱 Deskripsi

Woof adalah aplikasi sederhana yang menampilkan daftar anjing lengkap dengan nama, usia, dan foto mereka. Proyek ini dikembangkan untuk memahami prinsip desain UI modern di Android seperti:

* Menggunakan **Composable Functions**.
* Menerapkan **Material Design 3**.
* Menerapkan tema terang dan gelap secara dinamis.
* Mengelola data melalui model `data class`.

## 🎨 Teknologi yang Digunakan

* **Jetpack Compose** - Framework modern deklaratif untuk membangun UI di Android.
* **Material3** - Desain system terbaru dari Google.
* **Kotlin** - Bahasa pemrograman utama Android saat ini.

## 🚀 Fitur Utama

* Tampilan daftar (list) anjing dengan gambar, nama, dan usia.
* Top App Bar dengan logo dan judul aplikasi.
* Responsif terhadap tema terang dan gelap.
* Desain UI berbasis komponen **Card**, **LazyColumn**, dan **Scaffold**.

## 🧩 Struktur File Penting

* [`MainActivity.kt`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/src/main/java/com/example/woof/MainActivity.kt): Entry point aplikasi dan pengatur UI.
* [`Dog.kt`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/src/main/java/com/example/woof/data/Dog.kt): Model data untuk setiap anjing.
* [`Theme.kt`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/src/main/java/com/example/woof/ui/theme/Theme.kt): Pengaturan tema terang dan gelap.
* [`strings.xml`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/src/main/res/values/strings.xml): Sumber teks lokal.
* [`colors.xml`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/src/main/res/values/colors.xml): Definisi warna.
* [`build.gradle.kts`](https://github.com/Superfeatz/Aplikasi-Woof/blob/master/app/build.gradle.kts): Konfigurasi proyek Android.

## 📸 Preview Tampilan

> 🖼️ Aplikasi menampilkan daftar anjing dengan gaya Material Design.
> Gunakan `@Preview` di Android Studio untuk melihat tampilan Light dan Dark Theme langsung dari editor!

## 🛠️ Cara Menjalankan

1. Clone repositori ini.
2. Buka dengan Android Studio.
3. Jalankan pada emulator / perangkat fisik.
4. Pastikan `minSdk` adalah 24 atau lebih.

```bash
git clone https://github.com/Superfeatz/Aplikasi-Woof.git
```

