# Instalasi pada macOS

Halaman ini akan menjelaskan cara untuk memasang osu! pada perangkat macOS milikmu secara kasar.

## Persyaratan minimum

- Komputer yang memadai dengan sistem operasi macOS.

## Instalasi osu!

osu! versi macOS diketahui memiliki beberapa *bug* visual minor dan performa permainan yang tidak seoptimal osu! versi lainnya. Permainan kamu mungkin tidak akan berjalan secara sempurna pada awalnya dan Untuk memasang osu! pada perangkat macOS milikmu, ikuti langkah-langkah berikut:

1. Tuju [halaman unduhan Wineskin berikut](https://osu.ppy.sh/community/forums/topics/1106057), lalu unduh dan ekstrak Wineskin versi terbaru yang tersedia.
2. Perbaiki berkas `osu!.app` yang ada dengan aplikasi osu!macOS Agent yang dapat kamu unduh pada [tautan berikut](https://osu.ppy.sh/community/forums/topics/1036678). Kamu juga dapat memperbaiki berkas `osu!.app` melalui Terminal sebagai berikut:
   1. Pindahkan berkas `osu!.app` ke desktop.
   2. Buka Terminal dan salin/ketik perintah berikut pada layar Terminal yang muncul: `xattr -c 'Desktop/osu!.app'`. Apabila sudah, tekan tombol `Return`.
3. Jalankan aplikasi `osu!.app`.
4. Proses instalasi akan berlangsung secara otomatis. Tidak seperti osu! versi Windows, kamu tidak dapat mengubah lokasi pemasangan osu!. Seluruh berkas-berkas permainan, termasuk [beatmap-beatmap](/wiki/Beatmap) and [skin-skin](/wiki/Skin) yang kamu miliki, akan tertanam di dalam berkas `osu.app` tersebut. Untuk dapat melihat berkas-berkas permainan yang ada, klik kanan `osu!.app` dan pilih `Show Package Contents`.
5. Setelah osu! berhasil terpasang, osu! akan terbuka secara otomatis. osu!direct akan kemudian mengunduh beberapa beatmap pengantar yang dapat kamu mainkan.
6. osu! akan meminta kamu untuk masuk atau membuat akun baru.
   - Apabila kamu sudah memiliki akun, silakan masuk.
   - Apabila kamu belum memiliki akun, harap untuk terlebih dahulu membuat akun baru sesuai dengan panduan yang tertera pada artikel [Pendaftaran](/wiki/Registration).

## Penyelesaian masalah (troubleshooting)

Apabila kamu menemui masalah dalam menjalankan osu!, cobalah untuk mengikuti langkah-langkah berikut:

1. Periksa laporan-laporan error yang dihasilkan oleh *osu!macOS Agent*.
   - Apabila kamu menggunakan macOS Catalina versi 10.15.4 atau lebih lawas, cobalah untuk memperbaharui versi macOS yang kamu gunakan atau menonaktifkan [System Integrity Protection](https://developer.apple.com/documentation/security/disabling_and_enabling_system_integrity_protection).
2. Periksa apakah ada berkas-berkas tertentu yang bermasalah dengan menggunakan program pengekstrak "Archive Utility" yang disediakan oleh sistem macOS. Kami tidak menyarankan kamu untuk menggunakan program-program pengekstrak lain karena program-program ini pada umumnya dapat merusak Wineskin.
3. Apabila kamu menggunakan program antivirus, pastikan program antivirus yang kamu gunakan tidak menghalangi osu! untuk dapat berjalan atau menandai berkas-berkas yang dimiliki osu! dan Wine sebagai virus.
4. Apabila kamu masih tetap menemui masalah, buatlah postingan baru di [sub-forum Help](https://osu.ppy.sh/community/forums/5).

## osu!(lazer)

[osu!(lazer)](/wiki/Client/Release_stream/Lazer) merupakan klien osu! masa depan yang saat ini sedang berada dalam pengembangan. Untuk memasang klien ini, ikuti langkah-langkah berikut:

1. Tuju [halaman unduhan osu!(lazer) berikut](https://github.com/ppy/osu/releases/latest), lalu unduh dan ekstrak `osu!.app.zip`.
2. Klik dua kali pada osu! dan pilih `Open` untuk membuka aplikasi.
3. Apabila kamu menemui kotak dialog yang meminta agar osu! dapat menerima input keyboard (*keystroke*):
   1. Klik tombol `Open System Preferences`.
   2. Klik ikon gembok yang terdapat pada pojok kiri bawah layar dan masukkan kata sandimu.
   3. Berikan tanda centang pada *check box* yang berada di samping ikon osu!.
