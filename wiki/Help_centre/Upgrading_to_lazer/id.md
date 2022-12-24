---
tags:
  - game client
  - klien permainan
---

# Beralih ke lazer

osu!(lazer) merupakan versi rilis utama osu! yang akan datang. Versi ini merupakan hasil jerih payah tim kami selama bertahun-tahun untuk menciptakan osu! yang modern, canggih, dan sepenuhnya baru.

Pada saatnya nanti, apabila semuanya telah siap, osu!(lazer) akan dirilis sebagai pembaruan khusus yang menggantikan versi osu! yang saat ini digunakan. Pembaruan ini hanya akan diluncurkan apabila waktunya dirasa telah tepat oleh **para pemain**, dan versi osu! sebelumnya akan tetap didukung hingga sebagian besar pemain telah beralih ke osu!(lazer).

"lazer" sendiri merupakan nama sementara yang nantinya tidak akan lagi digunakan setelah lazer beralih fungsi menjadi versi rilis utama. Demi kenyamanan bersama, ke depannya artikel ini akan menyebut osu!(lazer) sebagai "lazer" dan osu!(stable) sebagai "stable".

## Perbandingan fitur

Berikut merupakan daftar berbagai hal yang membedakan versi lazer **saat ini** dengan stable. Harap diperhatikan bahwa segala sesuatunya yang tertera di bawah ini akan selalu berubah seiring dengan pengembangan lazer dan tanggapan pemain.

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
| Percakapan yang berlangsung secara *real-time* | ![Partial][partial][^stable-chat] | ![Yes][true] |
| Akses kilat ke laman wiki / berita / riwayat pembaruan / peringkat | ![No][false] | ![Yes][true][^online-content] |
| Akses kilat ke laman profil pengguna | ![No][false] | ![Yes][true] |
| Akses kilat ke laman daftar beatmap | ![Partial][partial][^direct-supporter] | ![Yes][true] |
| Ruangan multiplayer tanpa batas ukuran | ![No][false][^multi-room-max] | ![Yes][true] |
| Multiplayer spectating | ![No][false] | ![Yes][true] |
| Countdown timers | ![Partial][partial][^countdown-timers-stable] | ![Yes][true][^countdown-timers-lazer] |
| Queue modes | ![No][false] | ![Yes][true][^queue-modes] |
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
| SV / volume per objek | ![No][false] | ![Yes][true] |
| Rotasi pattern | ![Yes][true] | ![Partial][partial][^editor-precise-rotation] |
| Perubahan skala pattern | ![No][false] | ![Yes][true] |
| Submisi beatmap | ![Yes][true] | ![No][false] |
| Editor storyboard | ![Yes][true] | ![No][false] |
| Kompatibilitas silang | ![Yes][true] | ![Partial][partial][^incompatibilities] |

## Beralih ke lazer

Apakah ini pertama kalinya kamu mencoba lazer? Apabila ya, selamat datang di lazer!

Kamu dapat memperoleh lazer melalui [tautan berikut](https://github.com/ppy/osu#running-osu). Ke depannya, kamu akan dapat beralih ke lazer secara langsung dari dalam permainan (melalui pilihan `Versi rilis` yang terdapat pada menu pengaturan) serta mengunduh lazer dari situs web osu!.

## Pertanyaan yang sering diajukan

### Proses migrasi

#### Apakah stable akan dipensiunkan? Apakah saya akan diharuskan untuk berpindah?

Stable tidak akan dipensiunkan selama masih ramai akan peminat. Setidak-tidaknya, stable masih akan tetap didukung hingga beberapa tahun setelah lazer dirilis.

#### Apakah saya dapat mengimpor seluruh data saya dari stable ke lazer?

Untuk saat ini, kamu hanya dapat mengimpor beatmap, skin, skor, tayangan ulang, dan daftar koleksi yang kamu miliki. Kamu **belum dapat mengimpor pengaturan dari stable ke lazer**, sehingga kamu akan perlu untuk mengatur ulang segala pengaturan yang kamu gunakan dari awal.

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

#### Apabila saya mencetak skor pada lazer, apakah skor tersebut akan muncul pada laman profil saya?

Skormu akan muncul pada kolom "Rekam Jejak Permainan Terkini", namun belum akan muncul pada kolom "Performa Terbaik".

#### Apakah saya akan memperoleh pp dari skor yang saya catatkan pada lazer?

Scores will already have performance points calculated (you can see this in the "recently played" section of your profile), but it will not contribute to the total value yet.

#### Apakah lazer menggunakan sistem perhitungan ScoreV2?

Lazer saat ini menggunakan sistem perhitungan skor khusus yang serupa (namun tidak sama) dengan ScoreV2. Sistem ini masih berada dalam tahap pengembangan dan dapat berubah sewaktu-waktu seiring dengan tanggapan yang kami terima.

<!-- lint ignore no-heading-punctuation -->

#### I prefer the classic scoring display, where scores get really big.

You can actually change the `Score display mode` setting to `Classic` to get back the explosive style of scoring game-wide! It won't be a perfect match, but will give you the same feel of classic scoring and be applied everywhere you'd expect it to be.

#### If I set a score on lazer, will it remain forever?

While we will try to preserve as many scores as possible, we **offer no guarantee that scores will remain indefinitely**. At any point we may choose to wipe a subset or all scores in order to preserve game balance.

#### Apakah skor yang saya catatkan pada stable nantinya juga akan muncul pada lazer?

Yes. Once we finish balancing the combination of lazer and stable scores, both will be visible.

#### Apakah seluruh mod akan diikutsertakan ke dalam papan peringkat?

For now, scores of all mod combinations appear on leaderboards. Whether scores will give performance points with all mods (and if they do, whether there will be a bonus or penalty applied) is still in discussion.

#### I don't like the new gameplay mechanics. Can I restore the old gameplay mechanics like on stable?

Please try applying the "classic" mod, which will restore much of the old behaviour that you are used to. Also make sure to check the settings offered by classic mod, as it will let you further customise your experience and also understand what changes are being applied (as they are all listed there).

### Skinning and UI

#### Terdapat sesuatu yang berperilaku berbeda dengan stable, dan saya tidak menyukainya!

Please run the setup wizard at the top of settings and go through the settings on the `Behaviour` screen. A lot of the common settings which have defaults changed are listed here. There's also a single button you can press to apply the old behaviours as a starting point for your lazer journey.

#### Will old skins eventually work in song select and results screens?

We'll do our best to bring back as much of this as we can without blocking new functionality. This will come later on.

#### Apakah saya dapat menggunakan kursor milik skin saya pada layar menu?

Berhubung fitur ini merupakan salah satu fitur yang banyak diminta, kami kemungkinan akan kembali memperkenalkan fitur ini pada lazer di masa yang akan datang.

### Performa

#### Mengapa saya tidak dapat menjalankan lazer tanpa batasan FPS?

Above a certain threshold there is no reason to run at higher frame rates. Lazer employs various new technologies to ensure the lowest latency is achievable without requiring high frame rates. This will continue to improve going forward as we still have a few improvements left to implement.

Lazer polls for input at 1000 Hz regardless of FPS limiter, which is why the maximum limiter setting will also limit to 1000 FPS.

If you are curious about how this affects input latency and test your own perception, please run the built-in "latency certifier" at the bottom of settings.

#### If input is only polled at 1000 Hz, what about my 8000 Hz gaming mouse?

The operating system will still poll at the higher rate, although benefits are proven to be negligible. Polling at such high rates can have unforeseen overheads, and we recommend limiting devices to 1000 Hz for system stability.

#### Performa lazer saya lebih buruk dari stable. Apa penyebabnya?

While on most modern hardware we see lazer outperform stable, there are always edge cases when each user has a different hardware configuration. In our short-term roadmap, we are looking to support DirectX (aka "compatibility mode" on stable) and Vulkan, which both have better driver support than OpenGL across all hardware. Once this is implemented, performance on hardware like Intel integrated chipsets will improve greatly.

### Memberikan tanggapan

#### Fitur yang selama ini sering saya gunakan belum ada di lazer! / Saya tidak menyukai perubahan yang ada! / Saya menemukan bug. Ke mana saya harus melapor?

There's a very high chance we are already aware of this and tracking it for future implementation! Please search the [issue tracker](https://github.com/ppy/osu/issues) and [discussions page](https://github.com/ppy/osu/discussions). If you can't find any matching threads, feel free to [open a discussion](https://github.com/ppy/osu/discussions/new).

Do note that we are already tracking over 1,000 issues of varying priorities, and it may take us some time to fix issues that only affect a small number of users.

### Lainnya

#### Mengapa "lazer" dinamakan demikian?

Karena "cutting-edge" tidak dirasa cukup "tajam".

#### Mengapa butuh waktu yang sangat lama sebelum lazer dapat menggantikan stable sebagai versi rilis utama?

Walaupun osu! sekilas terlihat seperti permainan yang sederhana, osu! didasari oleh berbagai fitur dan sistem yang jumlahnya tak terhitung. Tergantung dari kacamata masing-masing, lazer dapat dipandang sebagai versi osu! yang telah siap untuk dirilis atau yang masih jauh dari kata rampung.

Another area which has taken a huge amount of effort is historical preservation — making sure that beatmaps behave exactly as they should, including edge cases that weren't originally planned for. osu! is a vibrant ecosystem and users have taken liberty to extend the game far beyond its planned extents, and we are trying our best to embrace and support this going forward.

Finally, unlike the last iteration, we are putting in the time and diligence to ensure the code base will serve us well into the future. We have done the groundwork to allow new features to come online at blazing speed going forward. This will include new UI components, new ways to skin the game, new multiplayer systems and let's not forget the ability to load and play all your existing beatmaps on completely new game modes (a.k.a. rulesets)!

#### Ke arah mana selanjutnya osu! akan dikembangkan?

We have a huge backlog of user-requested features and improvements that we will continue to push out at the speed of light. For those that have joined us recently and haven't experienced the momentum of osu! development, prepare to be in for a surprise.

#### Bagaimana caranya untuk mengakses folder lagu saya?

lazer tidak memiliki folder lagu! Kami merancang lazer sedemikian rupa agar beatmap dapat dimuat ulang tanpa harus menekan `F5` (karena beatmap tidak akan pernah rusak) dan untuk mengurangi penggunaan ruang hard disk hingga 20-40%. Kamu dapat membaca penjelasan lebih lanjut seputar teknologi penyimpanan berkas yang kami gunakan [pada tautan berikut](/wiki/Client/Release_stream/Lazer/File_storage).

Apabila kamu ingin menyunting konten tertentu pada beatmap, mohon gunakan editor. Ke depannya, editor lazer akan dapat digunakan untuk mengakses isi folder beatmap secara langsung dari dalam permainan.

#### Berhubung "osu!direct" kini tersedia bagi seluruh pemain, apakah para supporter akan mendapatkan keuntungan baru?

Untuk saat ini, terdapat beberapa filter pada laman daftar beatmap yang masih hanya dapat diakses oleh pemilik supporter.

Di samping itu, keuntungan berikut juga telah tersedia untuk dinikmati:

- Para supporter dapat membuat playlist dengan jangka waktu yang lebih panjang

Kami tentunya ingin menambahkan berbagai keuntungan lainnya di masa yang akan datang, namun untuk saat ini masih berfokus untuk menyamaratakan kesenjangan fitur yang ada antara stable dan lazer. Oleh karenanya, mohon niatkan pembelian supporter tag kamu untuk... membawa osu! ke arah yang lebih baik!

#### Apabila saya berbuat curang pada lazer, apakah saya akan dihukum?

Ya.

#### Apabila saya menemukan pemain yang berbuat curang pada lazer, bagaimana caranya bagi saya untuk melapor?

Laporkan mereka melalui fitur pengiriman laporan sebagaimana pada umumnya.

#### Di mana saya dapat membeli item permainan tertentu?

osu! tidak menganut sistem mikrotransaksi. Kamu mungkin keliru mengira osu! dengan permainan lainnya.

### Catatan

[^wine]: Dengan menggunakan wine.
[^compatibility-mode]: Dukungan DirectX via mode kompatibilitas.
[^coming-soon]: Akan segera hadir.
[^dll]: Secara manual melalui berkas `.dll`.
[^share-files]: Beatmaps and skins will share files and save on disk space.
[^gameplay-only]: Hanya dalam permainan.
[^online]: Melalui data yang diterima secara online.
[^normalisation]: This brings beatmap custom combo colours to the same brightness level.
[^hold-for-hud]: Hold `Ctrl` to view the HUD momentarily while it's hidden.
[^offset-calibration-stable]: Adjustable manually via key bindings.
[^offset-calibration-lazer]: When retrying a beatmap, you can calibrate the offset based on your last play.
[^can-disable]: Dapat dinonaktifkan.
[^note-lock]: Still exists, but should not interfere.
[^score-reset-balance]: Scores will be reset to ensure balance.
[^score-reset-isolated]: Scores will be reset, currently isolated from stable scores.
[^online-content]: Native access to most online content.
[^direct-supporter]: osu!direct, osu!supporter-only.
[^multi-room-max]: 16 players max.
[^map-only]: Map only.
[^all-files]: All files.
[^editor-precise-rotation]: Missing precise angle rotation.
[^incompatibilities]: Some editor features will cause beatmaps to play incorrectly in stable — will be fixed soon.
[^stable-chat]: Messages can take up to 15 seconds to arrive.
[^countdown-timers-stable]: Set a countdown using a command, no automatic start.
[^countdown-timers-lazer]: Set a countdown from the game UI to automatically start the match.
[^queue-modes]: Turn on to allow anyone in a lobby to queue new beatmaps, a.k.a. "host rotate".

[true]: /wiki/shared/true.png
[false]: /wiki/shared/false.png
[partial]: /wiki/shared/partial.png
