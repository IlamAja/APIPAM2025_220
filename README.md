# APIPAM2025_220

# Backend Integration (Firebase Serverless)
Proyek ini berbasis Firebase. Jadi, secara teknis saya tidak membangun REST API manual menggunakan framework seperti Express atau Laravel, karena komunikasi data langsung ditangani oleh Firebase SDK di sisi aplikasi mobile.

Alasan penggunaan Firebase:

1. Real-time Data: Sinkronisasi database dilakukan secara instan tanpa perlu polling manual ke API.
2. Firebase Auth: Manajemen user (Login/Register) sudah terintegrasi langsung dengan database keamanan.
3. Firestore: Database NoSQL yang digunakan untuk menyimpan seluruh record aplikasi secara cloud.

Semua konfigurasi endpoint dan aturan akses (security rules) diatur langsung melalui konsol Firebase. Detail integrasi kode, API Key, dan pemanggilan fungsinya bisa dilihat langsung di repository aplikasi utama pada folder data/repository.
