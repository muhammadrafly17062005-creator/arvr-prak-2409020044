<<<<<<< HEAD
# Praktikum AR/VR Pertemuan 1 - Scene Perkenalan Diri

Nama : MUHAMMAD RAFLY
NIM  : 2409020044
Link demo: https://github.com/muhammadrafly17062005-creator/arvr-prak-2409020044.git

Project ini berisi scene WebXR perkenalan diri menggunakan A-Frame 1.7.1.

---

## Jawaban Pertanyaan Refleksi

1. **Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?**
   Dalam sistem koordinat 3D A-Frame, posisi kamera *default* berada di titik `(0, 1.6, 0)` dan secara bawaan menghadap ke arah sumbu Z negatif. Oleh karena itu, semua objek yang ingin ditampilkan langsung di depan pandangan mata pengguna saat halaman dimuat harus diletakkan pada koordinat Z bernilai negatif.

2. **Mengapa WebXR hanya aktif pada HTTPS atau localhost?**
   WebXR memerlukan standar keamanan *Secure Context* karena mengakses data sensor hardware sensitif seperti *gyroscope*, *tracking* posisi kepala, hingga kamera/layar VR. Peramban web secara ketat memblokir WebXR pada koneksi non-HTTPS (HTTP biasa) untuk mencegah potensi celah keamanan dan penyalahgunaan data privasi pengguna.

3. **Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame dengan bahasa Anda sendiri.**
   - **WebXR Device API**: API tingkat rendah bawaan peramban (*browser*) yang berfungsi menjembatani komunikasi langsung antara peramban dengan perangkat keras VR/AR.
   - **three.js**: *Library* JavaScript grafik 3D yang mengolah kalkulasi matematika 3D, *rendering* grafik, pencahayaan, dan material WebGL ke GPU.
   - **A-Frame**: *Framework* tingkat tinggi berbasis HTML yang membungkus three.js menjadi tag deklaratif (seperti `<a-scene>`, `<a-box>`), sehingga pembuatan dunia 3D/VR dapat dilakukan dengan mudah tanpa menulis kode JavaScript/WebGL yang kompleks dari awal.
=======
# arvr-prak-2409020044
>>>>>>> 928eb98c1e0964d0dc1abac7727b93ab0008ff9b
