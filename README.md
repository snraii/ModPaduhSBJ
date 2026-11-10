# Advance Booking Alert V3 — Live OCR prototype

## Fungsi
- Pilihan minimum RM20, RM30, RM40, RM50, RM60, RM70, RM80, RM90 atau RM100+.
- Tiada penapis lokasi: seluruh Sabah.
- Pengguna memulakan sesi Screen Capture secara manual.
- ML Kit OCR membaca teks skrin dan cuba mengesan nilai RM pada skrin Booking Planner / Advance Booking.
- Amaran tempatan apabila tambang melepasi nilai minimum.
- Tiada auto-accept, auto-tap, atau interaksi dengan kawalan Grab.

## Bina
1. Buka projek ini dengan Android Studio versi terkini.
2. Sync Gradle (internet diperlukan untuk memuat turun ML Kit).
3. Sambung telefon dan Build > Build APK(s).
4. Pasang APK, buka aplikasi, pilih minimum tambang.
5. Tekan MULA LIVE SCAN dan benarkan rakaman skrin melalui dialog Android.
6. Tukar ke Grab Driver > Booking Planner > Advance Booking.
7. Untuk berhenti, kembali ke aplikasi dan tekan HENTIKAN LIVE SCAN.

## Had dan privasi
- Ini prototaip kod sumber, bukan APK siap bina atau diuji pada Infinix GT 30 Pro.
- OCR mungkin tersalah baca atau terlepas tambang; uji dengan teliti dan jangan bergantung sepenuhnya pada alert.
- Grab Booking Planner mesti kelihatan pada skrin. Tiada imbasan jika halaman itu tidak dipaparkan.
- Android akan memaparkan indikator/notifikasi sesi rakaman skrin.
- Imej skrin diproses pada peranti melalui ML Kit; projek ini tidak menghantar imej ke pelayan.
- Rakaman skrin boleh menangkap maklumat peribadi yang muncul pada paparan. Hentikan sesi apabila tidak diperlukan.
- Semak terma Grab dan undang-undang setempat sebelum menggunakan alat pemantauan skrin.
- Jangan gunakan ketika memandu. Berhenti di tempat selamat sebelum melihat telefon.
