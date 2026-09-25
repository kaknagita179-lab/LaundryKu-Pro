# LaundryKu Pro — Build APK lewat GitHub Actions

Project ini sudah dilengkapi workflow otomatis untuk membuat APK tanpa Android Studio di komputer.

## Cara paling mudah dari HP

1. Buat akun/login di GitHub.
2. Buat repository baru, misalnya `LaundryKu-Pro`.
3. Upload seluruh isi folder project ini ke repository.
4. Buka tab **Actions**.
5. Pilih workflow **Build LaundryKu APK**.
6. Tekan **Run workflow**.
7. Tunggu proses selesai.
8. Buka hasil workflow yang selesai, lalu bagian **Artifacts**.
9. Download **LaundryKu-debug-apk**.
10. Ekstrak ZIP hasil download, lalu file `app-debug.apk` bisa dipasang di Android.

## Catatan
- APK yang dibuat adalah **debug APK**.
- PIN admin bawaan: **1234**.
- Data transaksi tersimpan secara offline di aplikasi.
- Untuk rilis ke Play Store, aplikasi perlu dibuat **release APK/AAB** dengan signing key.
