# JeKahf Multi Tech — Android project

Aplikasi Android offline untuk administrasi usaha service elektronik.

## Fitur fondasi
- Database lokal Room/SQLite: customer, pekerjaan service, sparepart/stok, dan pengingat.
- Pengurangan stok otomatis saat sparepart dipakai pada pekerjaan.
- Pembuatan invoice PDF menggunakan Android PdfDocument.
- Tidak memerlukan akun atau koneksi internet untuk fungsi inti.

## Cara membangun APK
1. Ekstrak ZIP ini.
2. Buka folder `JeKahfMultiTech` melalui Android Studio (versi yang mendukung Android Gradle Plugin 8.7).
3. Tunggu Gradle Sync selesai.
4. Pilih **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. APK debug akan berada di `app/build/outputs/apk/debug/app-debug.apk`.

## Catatan
Ini adalah proyek sumber Android Studio, bukan APK yang sudah dikompilasi/ditandatangani. Build pertama memerlukan Android Studio dan internet untuk mengunduh dependensi Gradle. Setelah terpasang, data aplikasi disimpan lokal di perangkat. Cadangkan data sebelum menghapus aplikasi atau membersihkan penyimpanan.

Pengingat memakai notifikasi Android. Pada Android 13+, izinkan notifikasi saat diminta. Jadwal alarm dapat dibatasi oleh penghemat baterai/perizinan perangkat.
