---
tags:
  - help
  - issue
  - problem
  - trouble
  - missing
  - bantuan
  - isu
  - masalah
  - permasalahan
  - kehilangan
---

# Pusat bantuan

Mengalami masalah dengan sesuatu? Kami siap untuk membantumu! Pada halaman ini, kamu dapat menemukan berbagai solusi dari rangkaian masalah yang umum dijumpai. Apabila masalahmu tidak terliput di sini atau terus menjadi-jadi seiring waktunya, kirimkan email kepada kami pada alamat [support@ppy.sh](mailto:support@ppy.sh). Di samping itu, kamu juga dapat meminta bantuan kepada para pengguna lainnya melalui [forum Help](https://osu.ppy.sh/community/forums/5).

## Jenis permasalahan {id=sections}

Silakan pilih jenis permasalahan yang paling menggambarkan masalah yang kamu hadapi untuk menemukan solusi yang sesuai.

| Jenis permasalahan | Topik yang terlingkup |
| :-- | :-- |
| [Akun](/wiki/Help_centre/Account) | osu!supporter, entri masuk dan pemulihan akses, perubahan nama pengguna, data profil |
| [Restriction](/wiki/Help_centre/Account_restrictions) | Segala hal seputar pembatasan akun (*account restriction*): garis besar, proses banding, alasan umum, masa hukuman |
| [Beatmapping dan Editor](/wiki/Help_centre/Beatmapping) | Pengelolaan beatmap, kepemilikan beatmap, sistem kuota beatmap (*beatmap slots*) |
| [Klien](/wiki/Help_centre/Client) | *Bug* dan *crash*, permainan, koneksi, performa |
| [Instalasi dan pendaftaran](/wiki/Help_centre/Installation_and_registration) | Unduhan permainan, pembuatan akun |
| [osu!store](/wiki/Help_centre/Store) | Cendera mata |
| [Larangan turnamen](/wiki/Help_centre/Tournament_bans) | Segala hal seputar larangan turnamen (*tournament ban*): garis besar, alasan umum, masa hukuman |
| [Beralih ke lazer](/wiki/Help_centre/Upgrading_to_lazer) | Proses migrasi menuju [versi osu! utama yang akan datang](/wiki/Client/Release_stream/Lazer) |
| [Situs web](/wiki/Help_centre/Website) | Pemblokiran pengguna, menghubungi layanan dukungan, tampilan situs web |

## Bantu kami memahami masalahmu {id=diagnostics}

### Berkas log {id=log-files}

**Berkas log (*log files*) merupakan berkas rekaman yang mencatat apa-apa saja yang dilakukan oleh klien permainan dari waktu ke waktu secara terperinci. Kami dapat menggunakan berkas ini untuk membantu menentukan hal apa yang menyebabkan masalahmu.**

Walaupun terkesan sepele, berkas ini sangat berguna dan dapat menjadikan masalah yang sangat rumit sekalipun terselesaikan dengan mudah.

Apabila anggota tim layanan dukungan kami memintamu untuk memberikan berkas log ini, berikut merupakan cara untuk memperolehnya:

1. Buka osu!.
2. Klik tombol `Options` yang terdapat pada menu utama atau tekan `CTRL` + `O`.
3. Ketik `release` pada kolom pencarian yang muncul. Kamu akan melihat versi osu! yang sedang kamu gunakan.
4. Pastikan kamu sedang berada pada osu! versi `Eksperimental (Cutting Edge)`.
5. Apabila pada langkah sebelumnya kamu mengganti versi osu! yang kamu gunakan, nyalakan ulang osu! melalui tombol yang muncul pada sisi bawah layar.
6. Klik kembali tombol `Options` dan pilih `Buka folder osu!`.
7. Pada jendela yang terbuka, tuju direktori `Logs`.
8. Pilih berkas log yang dibutuhkan (tim layanan dukungan kami akan memberitahukanmu berkas mana saja yang harus kamu ambil) dan lampirkan berkas ini pada tiket layanan dukungan atau postingan forum yang kamu buat.

### Event Viewer {id=event-viewer}

**Event Viewer merupakan komponen bawaan Windows yang dapat digunakan untuk menelisik rekam kejadian suatu *crash* pada saat osu! tidak merekam data apa pun. Rekaman *crash* ini dapat digunakan untuk menentukan hal apa yang menyebabkan masalahmu.**

Pada saat osu! mengalami *crash* secara tiba-tiba, terkadang osu! tidak memiliki cukup waktu untuk mencatat apa-apa saja yang terjadi. Dalam situasi yang demikian, satu-satunya cara untuk memperoleh berkas rekaman ini adalah melalui Event Viewer.

Apabila anggota layanan dukungan kami memintamu untuk memberikan berkas *crash log* Event Viewer yang kamu miliki, berikut merupakan langkah-langkah yang hendaknya kamu ikuti:

1. Setelah osu! mengalami *crash*, tekan `Win` + `R` untuk membuka kotak dialog Run.
2. Pada kolom pencarian yang tertera, ketik `eventvwr` dan tekan `Enter`. Event Viewer akan terbuka.
3. Pada Event Viewer, tuju sisi kiri layar dan klik `Windows Logs` dan lalu `Application`.
4. Klik `Filter current log` yang ada pada sisi kanan layar.
5. Pada jendela filter yang terbuka, pastikan pilihan `Error` telah tercentang dan klik `OK` setelahnya.
6. Tekan `Ctrl` + `F` dan ketik `osu!` pada kolom pencarian yang tertera. Event Viewer akan mulai mencari berkas *crash log* yang terkait dengan osu!.
7. Tuju tab `Details` dan bentangkan panel `System` dan `Event Data` sebagaimana yang diminta oleh tim layanan dukungan kami.
8. Lampirkan data yang tertera pada kedua panel tersebut pada tiket layanan dukungan (*support ticket*) atau utas forum yang terkait.

### Frame Time Graph {id=frame-time-graph}

**Frame Time Graph merupakan fitur osu! yang memungkinkan kami untuk memperoleh data lebih lanjut seputar berbagai masalah performa yang kamu hadapi.**

Ketika kamu merasa performa klien osu! milikmu menurun, kamu dapat menggunakan Frame Time Graph untuk mendiagnosa dan memberantas masalah yang bersangkutan.

Apabila tim layanan dukungan kami memintamu untuk memberikan tangkapan layar (*screenshot*) atau video yang mencakup Frame Time Graph di dalamnya, berikut merupakan langkah-langkah yang hendaknya kamu ikuti:

1. Buka osu!.
2. Tekan `Ctrl` + `F11` untuk mengakses Frame Time Graph.
3. Tunggu hingga masalah performa yang sedang kamu hadapi terjadi.
4. Ambil tangkapan layar (*screenshot*) dari osu! dengan menekan `Shift` + `F12`. Aksi ini akan secara otomatis mengunggah hasil tangkapan layar yang kamu ambil tersebut ke dalam server osu! dan membukanya pada *browser* yang kamu miliki.
5. Lampirkan URL dari hasil tangkapan layar tersebut pada tiket layanan dukungan (*support ticket*) atau utas forum yang terkait.
6. Nonaktifkan Frame Time Graph dengan kembali menekan Ctrl + F11.
