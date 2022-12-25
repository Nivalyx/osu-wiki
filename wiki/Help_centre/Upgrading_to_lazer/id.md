---
tags:
  - game client
  - klien permainan
---

# Beralih ke lazer

osu!(lazer) merupakan versi rilis utama osu! yang akan datang. Versi ini merupakan hasil jerih payah tim kami selama bertahun-tahun dalam menciptakan osu! yang modern, canggih, dan sepenuhnya baru.

Pada saatnya nanti, apabila semuanya telah siap, osu!(lazer) akan dirilis sebagai pembaruan khusus yang menggantikan versi osu! yang saat ini digunakan. Pembaruan ini hanya akan diluncurkan apabila waktunya dirasa telah tepat oleh **para pemain**, dan versi osu! sebelumnya akan tetap didukung hingga sebagian besar pemain telah beralih ke osu!(lazer).

"lazer" sendiri merupakan nama sementara yang nantinya tidak akan lagi digunakan setelah lazer beralih fungsi menjadi versi rilis utama. Agar tidak berbelit-belit, pada artikel ini osu!(lazer) akan disebut sebagai "lazer" dan osu!(stable) akan disebut sebagai "stable".

## Perbandingan fitur

Berikut merupakan daftar berbagai hal yang membedakan versi lazer **saat ini** dengan stable. Harap diperhatikan bahwa segala sesuatunya yang tertera di bawah ini dapat berubah sewaktu-waktu seiring dengan pengembangan lazer ke depannya.

### Kompatibilitas dan performa

| Fitur | stable | lazer |
| :-- | :-- | :-- |
| Dukungan untuk Windows 8.0 atau lebih rendah | ![Yes][true] | ![No][false] |
| Dukungan untuk macOS / Linux | ![Parsial][partial][^wine] | ![Yes][true] |
| Dukungan DirectX / Vulkan | ![Partial][partial][^compatibility-mode] | ![No][false][^coming-soon] |
| Dukungan untuk perangkat mobile | ![No][false] | ![Yes][true] |
| Arsitektur multi-thread| ![No][false] | ![Yes][true] |
| Pemutaran video dengan akselerasi hardware | ![No][false] | ![Yes][true] |
| Skala antarmuka | ![No][false] | ![Yes][true] |
| Ruleset (mode permainan) khusus | ![No][false] | ![Partial][partial][^dll] |
| Sistem penyimpanan berkas tunggal | ![No][false] | ![Yes][true][^share-files] |
| Pengaturan area tablet | ![No][false] | ![Yes][true] |

### Antarmuka dan skinning

| Fitur | stable | lazer |
| :-- | :-- | :-- |
| Dukungan skin | ![Yes][true] | ![Partial][partial][^gameplay-only] |
| Pengelompokan lagu berdasarkan mode dan kategori tertentu | ![Yes][true] | ![No][false] |
| Pengaturan skin / tampilan antarmuka secara langsung dari dalam permainan | ![No][false] | ![Yes][true] |

### Permainan dan skinning

| Fitur | stable | lazer |
| :-- | :-- | :-- |
| Tampilan performance point yang akurat | ![Partial][partial][^online] | ![Yes][true] |
| Preset mod | ![No][false] | ![Yes][true] |
| Pengaturan khusus per mod | ![No][false] | ![Yes][true] |
| Mod "fun" baru | ![No][false] | ![Yes][true] |
| Normalisasi warna kombo[^normalisation] | ![No][false] | ![Yes][true] |
| Tombol untuk memunculkan HUD secara kilat | ![No][false] | ![Yes][true][^hold-for-hud] |
| Kalibrasi offset | ![Partial][partial][^offset-calibration-stable] | ![Yes][true][^offset-calibration-lazer] |
| Jalur slider yang meluruh ketika dimainkan | ![No][false] | ![Yes][true][^can-disable] |
| Mekanisme "note lock" yang tidak merugikan pemain | ![No][false] | ![Yes][true][^note-lock] |
| Warna not osu!mania yang berdasar pada waktu | ![No][false] | ![Yes][true] |

### Sistem online

| Fitur | stable | lazer |
| :-- | :-- | :-- |
| Submisi skor | ![Yes][true] | ![Partial][partial][^score-reset-balance] |
| Papan peringkat beatmap| ![Yes][true] | ![Partial][partial][^score-reset-isolated] |
| Statistik profil | ![Yes][true] | ![Yes][true] |
| Medali | ![Yes][true] | ![No][false] |
| Performance point | ![Yes][true] | ![Partial][partial][^score-reset-isolated] |
| Percakapan yang berlangsung secara real-time | ![Partial][partial][^stable-chat] | ![Yes][true] |
| Akses kilat ke laman wiki / berita / riwayat pembaruan / peringkat | ![No][false] | ![Yes][true][^online-content] |
| Akses kilat ke laman profil pengguna | ![No][false] | ![Yes][true] |
| Akses kilat ke laman daftar beatmap | ![Partial][partial][^direct-supporter] | ![Yes][true] |
| Ukuran ruangan multiplayer yang tidak terbatas | ![No][false][^multi-room-max] | ![Yes][true] |
| Mode spectate untuk pertandingan multiplayer | ![No][false] | ![Yes][true] |
| Waktu hitungan mundur | ![Partial][partial][^countdown-timers-stable] | ![Yes][true][^countdown-timers-lazer] |
| Mode antrian | ![No][false] | ![Yes][true][^queue-modes] |
| Perintah multiplayer | ![Yes][true] | ![No][false] |
| Mode tag co-op | ![Yes][true] | ![No][false] |
| Playlist (papan peringkat yang dikurasi oleh pengguna) | ![No][false] | ![Yes][true] |
| Pembaruan beatmap dari dalam permainan | ![Partial][partial][^map-only] | ![Yes][true][^all-files] |

### Editor

| Fitur | stable | lazer |
| :-- | :-- | :-- |
| Editor osu!taiko | ![No][false] | ![Yes][true] |
| Editor osu!catch | ![No][false] | ![Yes][true] |
| Editor osu!mania | ![Yes][true] | ![Yes][true] |
| Akses ke tingkat kesulitan lain sebagai bahan rujukan | ![Yes][true] | ![No][false] |
| Pengaturan SV / volume per objek | ![No][false] | ![Yes][true] |
| Rotasi pattern | ![Yes][true] | ![Partial][partial][^editor-precise-rotation] |
| Perubahan ukuran pattern | ![No][false] | ![Yes][true] |
| Submisi beatmap | ![Yes][true] | ![No][false] |
| Editor storyboard | ![Yes][true] | ![No][false] |
| Kompatibilitas silang | ![Yes][true] | ![Partial][partial][^incompatibilities] |

## Beralih ke lazer

Apakah ini pertama kalinya kamu mencoba lazer? Apabila ya, selamat datang di lazer!

Kamu dapat memperoleh lazer melalui [tautan berikut](https://github.com/ppy/osu#running-osu). Ke depannya, kamu akan dapat beralih ke lazer dari dalam permainan (melalui pilihan `Versi rilis` yang terdapat pada menu pengaturan) serta mengunduh lazer dari situs web osu! secara langsung.

## Pertanyaan yang sering diajukan

### Proses migrasi

#### Apakah stable akan dipensiunkan? Apakah saya akan diharuskan untuk berpindah?

Stable tidak akan dipensiunkan selama masih ramai akan peminat. Setidak-tidaknya, stable masih akan tetap didukung hingga beberapa tahun setelah lazer dirilis.

#### Apakah saya dapat mengimpor seluruh data saya dari stable ke lazer?

Untuk saat ini, kamu hanya dapat mengimpor beatmap, skin, skor, tayangan ulang, dan daftar koleksi yang kamu miliki. Kamu **belum dapat mengimpor pengaturan dari stable ke lazer**, sehingga kamu harus kembali mengatur ulang segala pengaturan yang kamu gunakan dari awal.

#### Apabila saya mengimpor beatmap yang saya miliki ke lazer, apakah ruang penyimpanan yang digunakan oleh osu! akan berlipat ganda?

Apabila lazer dan stable terinstal pada drive yang sama, kamu tidak perlu khawatir karena osu! menggunakan teknologi [hard link](/wiki/Client/Release_stream/Lazer/File_storage#via-hard-links) untuk menghemat ruang penyimpanan yang tersedia.

Apabila tidak, ruang penyimpanan yang digunakan oleh osu! akan berlipat ganda.

#### Apabila saya menghapus lazer, apakah instalasi stable saya akan rusak?

Tidak.

#### Apabila saya menghapus stable, apakah konten lazer yang saya impor dari stable akan rusak?

Tidak.

#### Apabila saya menginstal lazer, apakah saya dapat kembali ke stable?

Ya, karena lazer berjalan secara terpisah dari stable. Selama kamu tidak menghapus instalasi stable yang telah ada sebelumnya, kamu akan dapat memainkan keduanya.

#### Apakah saya dapat mengimpor data dari lazer ke stable?

Tidak. Fitur ini tidak akan didukung.

Meskipun demikian, kamu dapat mengimpor skor dan beatmap dari lazer menuju stable satu per satu secara manual.

### Permainan dan skor

#### Apabila saya mencetak skor pada lazer, apakah skor yang saya cetak akan muncul pada laman profil saya?

Skormu akan muncul pada kolom "Rekam Jejak Permainan Terkini", namun belum akan muncul pada kolom "Performa Terbaik".

#### Apakah saya akan memperoleh pp dari skor yang saya cetak pada lazer?

Skor yang dicetak pada lazer saat ini telah memiliki perhitungan pp-nya tersendiri (yang dapat kamu lihat di bagian "Rekam Jejak Permainan Terkini" pada laman profilmu). Meskipun demikian, skor ini tidak akan diikutsertakan ke dalam perhitungan pp kamu secara keseluruhan.

#### Apakah lazer menggunakan sistem ScoreV2?

Lazer saat ini menggunakan sistem perhitungan skor khusus yang serupa (namun tidak sama) dengan ScoreV2. Sistem ini masih berada dalam tahap pengembangan dan dapat berubah sewaktu-waktu seiring dengan tanggapan yang kami terima.

<!-- lint ignore no-heading-punctuation -->

#### Saya rindu sistem skor yang lama, dan saya ingin kembali melihat skor saya menembus puluhan bahkan ratusan juta dengan sangat cepat!

You can actually change the `Score display mode` setting to `Classic` to get back the explosive style of scoring game-wide! It won't be a perfect match, but will give you the same feel of classic scoring and be applied everywhere you'd expect it to be.

#### Apabila saya mencetak skor pada lazer, apakah skor tersebut akan tetap ada selama-lamanya?

While we will try to preserve as many scores as possible, we **offer no guarantee that scores will remain indefinitely**. At any point we may choose to wipe a subset or all scores in order to preserve game balance.

#### Apakah skor yang saya cetak pada stable nantinya juga akan muncul pada lazer?

Ya. Setelah kami menyelesaikan proses pembobotan skor antara lazer dan stable, seluruh skor akan muncul pada papan peringkat lazer.

#### Apakah skor dari seluruh mod akan ditampilkan pada papan peringkat lazer?

Untuk saat ini, papan peringkat lazer akan menampilkan skor dari seluruh mod yang ada. Apakah seluruh mod nantinya akan memberikan performance point (dan apabila ya, seberapa besar bonus atau penalti yang akan diberikan kepada masing-masing mod) saat ini masih didiskusikan.

#### Saya tidak suka mekanisme permainan yang ada saat ini. Apakah saya dapat bermain dengan mekanisme permainan yang stable miliki?

Please try applying the "classic" mod, which will restore much of the old behaviour that you are used to. Also make sure to check the settings offered by classic mod, as it will let you further customise your experience and also understand what changes are being applied (as they are all listed there).

Kamu dapat mengaktifkan mod "classic" yang akan memberikan pengalaman bermain yang serupa dengan stable.

### Skinning dan UI

#### Terdapat aspek permainan tertentu yang berperilaku berbeda dengan stable, dan saya tidak menyukainya!

Jalankan panduan pengaturan dasar dan tuju bagian `Perilaku`. Pada layar ini, kamu akan dapat mengatur perilaku bawaan dari berbagai aspek permainan yang telah berubah antara stable dan lazer. Apabila kamu ingin, kamu juga dapat mengatur agar seluruh aspek permainan yang terdapat pada pengaturan ini berperilaku seperti stable hanya dengan sekali klik.

#### Apakah skin lama saya akan dapat digunakan pada layar pemilihan lagu dan hasil permainan?

Kami akan berusaha agar skin lama kamu dapat digunakan tanpa menghalangi kegunaan berbagai fitur baru yang lazer miliki. Dukungan untuk hal ini akan hadir di masa yang akan datang.

#### Apakah saya dapat menggunakan kursor milik skin saya pada layar menu?

Fitur ini saat ini tidak didukung. Meskipun demikian, sehubungan dengan banyaknya permintaan yang telah kami terima, kami kemungkinan juga akan kembali menghadirkan fitur ini di masa yang akan datang.

### Performa

#### Mengapa saya tidak dapat menjalankan lazer tanpa batasan FPS?

Above a certain threshold there is no reason to run at higher frame rates. Lazer employs various new technologies to ensure the lowest latency is achievable without requiring high frame rates. This will continue to improve going forward as we still have a few improvements left to implement.

Lazer polls for input at 1000 Hz regardless of FPS limiter, which is why the maximum limiter setting will also limit to 1000 FPS.

If you are curious about how this affects input latency and test your own perception, please run the built-in "latency certifier" at the bottom of settings.

#### If input is only polled at 1000 Hz, what about my 8000 Hz gaming mouse?

The operating system will still poll at the higher rate, although benefits are proven to be negligible. Polling at such high rates can have unforeseen overheads, and we recommend limiting devices to 1000 Hz for system stability.

#### Performa lazer saya lebih buruk dari stable. Apa penyebabnya?

While on most modern hardware we see lazer outperform stable, there are always edge cases when each user has a different hardware configuration. In our short-term roadmap, we are looking to support DirectX (aka "compatibility mode" on stable) and Vulkan, which both have better driver support than OpenGL across all hardware. Once this is implemented, performance on hardware like Intel integrated chipsets will improve greatly.

### Pemberian tanggapan

#### Fitur yang selama ini sering saya gunakan belum ada di lazer! / Saya tidak menyukai perubahan yang ada! / Saya menemukan bug. Ke mana saya harus melapor?

Telusuri apakah masalahmu telah dilaporkan sebelumnya oleh pengguna lain melalui fitur [pelacak masalah](https://github.com/ppy/osu/issues) dan [laman diskusi](https://github.com/ppy/osu/discussions) pada repositori GitHub osu!. Apabila kamu tidak menemukan laporan yang sesuai, silakan [buat topik diskusi baru](https://github.com/ppy/osu/discussions/new).

Dalam melapor, harap diingat bahwa tim kami dapat melacak hingga beribu-ribu masalah pada setiap waktunya, dan masalah yang menjangkiti banyak pengguna pada umumnya akan lebih diprioritaskan.

### Lainnya

#### Mengapa "lazer" dinamakan demikian?

Karena "cutting-edge" tidak dirasa cukup "tajam".

#### Mengapa butuh waktu yang sangat lama sebelum lazer dapat menggantikan stable sebagai versi rilis utama?

Di balik kesederhanaannya, osu! tidak dapat berjalan tanpa dukungan berbagai fitur dan sistem yang harus ditulis ulang untuk lazer. Proses ini memakan waktu yang tidak sebentar, dan walaupun lazer saat ini telah dapat digunakan, pengembangan lazer masih jauh dari kata rampung.

Another area which has taken a huge amount of effort is historical preservation — making sure that beatmaps behave exactly as they should, including edge cases that weren't originally planned for. osu! is a vibrant ecosystem and users have taken liberty to extend the game far beyond its planned extents, and we are trying our best to embrace and support this going forward.

Finally, unlike the last iteration, we are putting in the time and diligence to ensure the code base will serve us well into the future. We have done the groundwork to allow new features to come online at blazing speed going forward. This will include new UI components, new ways to skin the game, new multiplayer systems and let's not forget the ability to load and play all your existing beatmaps on completely new game modes (a.k.a. rulesets)!

#### Apa yang akan dilakukan oleh tim osu! setelah lazer dirilis?

Kami akan terus menyempurnakan osu! serta menghadirkan berbagai fitur yang telah banyak diminta secara cepat dan tanggap. Apabila kamu sebelumnya belum pernah mengikuti siklus pengembangan osu!, bersiaplah untuk dihadapkan dengan berbagai kejutan.

#### Bagaimana caranya untuk mengakses folder lagu saya?

lazer tidak memiliki folder lagu seperti pada stable! Kami merancang lazer sedemikian rupa agar beatmap yang ada dapat dimuat ulang tanpa harus menekan `F5` (karena beatmap tidak akan pernah rusak) dan agar ruang hard disk yang digunakan dapat dikurangi hingga 20-40%. Kamu dapat membaca penjelasan lebih lanjut seputar teknologi penyimpanan berkas yang kami gunakan [pada tautan berikut](/wiki/Client/Release_stream/Lazer/File_storage).

Apabila kamu ingin menyunting konten tertentu pada beatmap, mohon gunakan editor. Ke depannya, editor lazer akan dapat digunakan untuk mengakses isi folder beatmap secara langsung dari dalam permainan.

#### Berhubung "osu!direct" kini tersedia bagi seluruh pemain, apakah para supporter akan mendapatkan keuntungan baru?

Untuk saat ini, terdapat beberapa filter pada laman daftar beatmap yang masih hanya dapat diakses oleh pemilik supporter.

Di samping itu, keuntungan berikut juga telah tersedia untuk dinikmati:

- Para supporter dapat membuat playlist dengan jangka waktu yang lebih panjang

Ke depannya, kami tentunya ingin menghadirkan berbagai keuntungan lainnya, namun untuk saat ini fokus kami masih harus tertuju pada pengembangan lazer itu sendiri. Oleh karenanya, mohon niatkan pembelian supporter tag kamu untuk... membawa osu! ke arah yang lebih baik!

#### Apabila saya berbuat curang pada lazer, apakah saya akan dihukum?

Ya.

#### Apabila saya menemukan pemain yang berbuat curang pada lazer, bagaimana caranya bagi saya untuk melapor?

Laporkan mereka melalui fitur pengiriman laporan sebagaimana pada umumnya.

#### Di mana saya dapat membeli item permainan tertentu?

osu! tidak menganut sistem mikrotransaksi. Kamu mungkin sedang berpikir tentang permainan yang lain.

### Catatan

[^wine]: Dengan menggunakan wine.
[^compatibility-mode]: Dukungan DirectX via mode kompatibilitas.
[^coming-soon]: Akan segera hadir.
[^dll]: Secara manual melalui berkas `.dll`.
[^share-files]: Beatmap dan skin akan saling berbagi berkas, yang menghemat penggunaan ruang pada hard disk.
[^gameplay-only]: Hanya dalam permainan.
[^online]: Melalui data yang diterima secara online.
[^normalisation]: This brings beatmap custom combo colours to the same brightness level.
[^hold-for-hud]: Tahan `Ctrl` untuk menampilkan manu HUD pada saat disembunyikan.
[^offset-calibration-stable]: Adjustable manually via key bindings.
[^offset-calibration-lazer]: When retrying a beatmap, you can calibrate the offset based on your last play.
[^can-disable]: Dapat dinonaktifkan.
[^note-lock]: Still exists, but should not interfere.
[^score-reset-balance]: Scores will be reset to ensure balance.
[^score-reset-isolated]: Scores will be reset, currently isolated from stable scores.
[^online-content]: Native access to most online content.
[^direct-supporter]: osu!direct, osu!supporter-only.
[^multi-room-max]: Terbatas hanya pada 16 pemain.
[^map-only]: Khusus unutk map.
[^all-files]: Seluruh berkas.
[^editor-precise-rotation]: Missing precise angle rotation.
[^incompatibilities]: Some editor features will cause beatmaps to play incorrectly in stable — will be fixed soon.
[^stable-chat]: Messages can take up to 15 seconds to arrive.
[^countdown-timers-stable]: Set a countdown using a command, no automatic start.
[^countdown-timers-lazer]: Set a countdown from the game UI to automatically start the match.
[^queue-modes]: Turn on to allow anyone in a lobby to queue new beatmaps, a.k.a. "host rotate".

[true]: /wiki/shared/true.png
[false]: /wiki/shared/false.png
[partial]: /wiki/shared/partial.png
