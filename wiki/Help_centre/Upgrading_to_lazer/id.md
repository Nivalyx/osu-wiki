---
tags:
  - game client
  - klien permainan
---

# Beralih ke lazer

osu!(lazer) merupakan versi rilisan utama osu! yang akan datang. Versi ini merupakan hasil jerih payah tim kami selama bertahun-tahun dalam menciptakan osu! yang lebih modern, canggih, dan sepenuhnya baru.

Pada saatnya nanti, apabila semuanya telah siap, osu!(lazer) akan dirilis sebagai pembaruan khusus yang akan menggantikan versi osu! yang saat ini digunakan. Pembaruan ini hanya akan dikeluarkan apabila waktunya dirasa telah tepat oleh **para pemain**, dan versi osu! sebelumnya akan tetap didukung hingga sebagian besar pemain telah beralih ke osu!(lazer).

"lazer" sendiri merupakan nama sementara yang nantinya tidak akan lagi digunakan setelah lazer beralih fungsi menjadi rilisan utama. Demi kenyamanan bersama, ke depannya artikel ini akan menyebut osu!(lazer) sebagai "lazer" dan osu!(stable) sebagai "stable".

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
| Playlists (user-curated leaderboards) | ![No][false] | ![Yes][true] |
| Updating beatmaps with online changes | ![Partial][partial][^map-only] | ![Yes][true][^all-files] |

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

So you've decided you want to give lazer a shot? Great!

You can find it for download [here](https://github.com/ppy/osu#running-osu). In the near future, you will be able to switch to lazer from stable (from the `Release stream` setting) and find the download link on the osu! website.

## Pertanyaan yang umum diajukan

### Proses migrasi

#### Apakah stable akan dipensiunkan? Apakah saya akan diharuskan untuk berpindah?

Stable tidak akan dipensiunkan selama masih ramai peminat. Setidak-tidaknya, stable masih akan tetap didukung selama beberapa tahun setelah lazer dirilis.

#### Dapatkah saya mengimpor seluruh data saya dari stable ke lazer?

Currently, beatmaps, skins, scores, replays and collections can be imported into lazer. Of note, **settings are not yet imported** so you will need to set them up from scratch.

#### If I import my beatmaps to lazer, will it use double the disk space?

If you have both lazer and stable on the same drive, [hard links](/wiki/Client/Release_stream/Lazer/File_storage#via-hard-links) are used to avoid using extra disk space.

In all other cases, importing beatmaps will use double the disk space.

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

Scores will show under "recently played" but not in "best performance" yet.

#### If I set a score on lazer, will it give performance points?

Scores will already have performance points calculated (you can see this in the "recently played" section of your profile), but it will not contribute to the total value yet.

#### Does lazer use ScoreV2?

Lazer currently uses a new experimental score implementation which is similar to ScoreV2 but not the same. This is still in development and we are looking for more feedback on how it feels in various contexts (solo play, leaderboards, tournaments etc.)

<!-- lint ignore no-heading-punctuation -->

#### I prefer the classic scoring display, where scores get really big.

You can actually change the `Score display mode` setting to `Classic` to get back the explosive style of scoring game-wide! It won't be a perfect match, but will give you the same feel of classic scoring and be applied everywhere you'd expect it to be.

#### If I set a score on lazer, will it remain forever?

While we will try to preserve as many scores as possible, we **offer no guarantee that scores will remain indefinitely**. At any point we may choose to wipe a subset or all scores in order to preserve game balance.

#### Will scores set on stable eventually show in lazer?

Yes. Once we finish balancing the combination of lazer and stable scores, both will be visible.

#### Apakah seluruh mod akan diikutsertakan ke dalam papan peringkat?

For now, scores of all mod combinations appear on leaderboards. Whether scores will give performance points with all mods (and if they do, whether there will be a bonus or penalty applied) is still in discussion.

#### I don't like the new gameplay mechanics. Can I restore the old gameplay mechanics like on stable?

Please try applying the "classic" mod, which will restore much of the old behaviour that you are used to. Also make sure to check the settings offered by classic mod, as it will let you further customise your experience and also understand what changes are being applied (as they are all listed there).

### Skinning and UI

#### Something is behaving differently to stable and I don't like it!

Please run the setup wizard at the top of settings and go through the settings on the `Behaviour` screen. A lot of the common settings which have defaults changed are listed here. There's also a single button you can press to apply the old behaviours as a starting point for your lazer journey.

#### Will old skins eventually work in song select and results screens?

We'll do our best to bring back as much of this as we can without blocking new functionality. This will come later on.

#### Can I use my skin cursor in the menus as well?

We will likely bring back support for this in the future due to popular demand.

### Performa

#### Mengapa saya tidak dapat menjalankan lazer tanpa batasan FPS?

Above a certain threshold there is no reason to run at higher frame rates. Lazer employs various new technologies to ensure the lowest latency is achievable without requiring high frame rates. This will continue to improve going forward as we still have a few improvements left to implement.

Lazer polls for input at 1000 Hz regardless of FPS limiter, which is why the maximum limiter setting will also limit to 1000 FPS.

If you are curious about how this affects input latency and test your own perception, please run the built-in "latency certifier" at the bottom of settings.

#### If input is only polled at 1000 Hz, what about my 8000 Hz gaming mouse?

The operating system will still poll at the higher rate, although benefits are proven to be negligible. Polling at such high rates can have unforeseen overheads, and we recommend limiting devices to 1000 Hz for system stability.

#### Lazer performs worse than stable for me. What gives?

While on most modern hardware we see lazer outperform stable, there are always edge cases when each user has a different hardware configuration. In our short-term roadmap, we are looking to support DirectX (aka "compatibility mode" on stable) and Vulkan, which both have better driver support than OpenGL across all hardware. Once this is implemented, performance on hardware like Intel integrated chipsets will improve greatly.

### Providing feedback

#### A feature that I depend on is missing! / Something has changed and I don't like it. / I have found a bug, what's the best way to report it?

There's a very high chance we are already aware of this and tracking it for future implementation! Please search the [issue tracker](https://github.com/ppy/osu/issues) and [discussions page](https://github.com/ppy/osu/discussions). If you can't find any matching threads, feel free to [open a discussion](https://github.com/ppy/osu/discussions/new).

Do note that we are already tracking over 1,000 issues of varying priorities, and it may take us some time to fix issues that only affect a small number of users.

### Lainnya

#### Mengapa "lazer" dinamakan demikian?

Karena "cutting-edge" tidak dirasakan cukup "tajam".

#### Mengapa butuh waktu yang sangat lama sebelum lazer dapat menggantikan stable sebagai versi rilis utama?

While osu! may seem like a simple game, there are hundreds on hundreds of features and systems that users have come to rely on. Depending on who you ask, lazer may have been in a fully playable state for years now, or it may be missing countless features.

Another area which has taken a huge amount of effort is historical preservation — making sure that beatmaps behave exactly as they should, including edge cases that weren't originally planned for. osu! is a vibrant ecosystem and users have taken liberty to extend the game far beyond its planned extents, and we are trying our best to embrace and support this going forward.

Finally, unlike the last iteration, we are putting in the time and diligence to ensure the code base will serve us well into the future. We have done the groundwork to allow new features to come online at blazing speed going forward. This will include new UI components, new ways to skin the game, new multiplayer systems and let's not forget the ability to load and play all your existing beatmaps on completely new game modes (a.k.a. rulesets)!

#### What comes next?

We have a huge backlog of user-requested features and improvements that we will continue to push out at the speed of light. For those that have joined us recently and haven't experienced the momentum of osu! development, prepare to be in for a surprise.

#### Bagaimana caranya untuk mengakses folder lagu saya?

lazer tidak memiliki folder lagu! Kami merancang lazer sedemikian rupa karena hal ini memungkinkan kamu untuk dapat memuat ulang daftar beatmap tanpa harus menekan `F5` (karena beatmap tidak akan pernah rusak) dan mengurangi penggunaan ruang hard disk hingga 20-40%. Kamu dapat membaca penjelasan lebih lanjut seputar teknologi penyimpanan berkas yang kami gunakan [pada tautan berikut](/wiki/Client/Release_stream/Lazer/File_storage).

Apabila kamu perlu untuk mengubah sesuatu pada beatmap, mohon gunakan editor. Ke depannya, editor lazer akan dapat digunakan untuk mengakses isi folder beatmap secara langsung dari dalam permainan, yang memungkinkan kamu untuk menggunakan sarana eksternal dalam hal pembuatan beatmap.

#### Berhubung kini "osu!direct" tersedia bagi seluruh pemain, apakah para supporter akan mendapatkan keuntungan baru?

Untuk saat ini, filter tertentu pada laman daftar beatmap masih hanya tersedia bagi para supporter.

There are also some additional benefits already:

- Para supporter dapat membuat playlist dengan jangka waktu yang lebih panjang

We do intend to look into new benefits in the future, but our focus is currently on feature parity with stable so please use your supporter tag purchase as a way to... support the game's development!

#### Apabila saya berbuat curang pada lazer, apakah saya akan dihukum?

Ya.

#### Apabila saya menemukan pemain yang berbuat curang pada lazer, bagaimana caranya bagi saya untuk melapor?

Laporkan mereka melalui fitur pengiriman laporan sebagaimana pada umumnya.

#### Di mana saya dapat membeli item permainan tertentu?

osu! tidak menganut sistem mikrotransaksi. Apabila kamu ingin menghabiskan uangmu untuk hal yang demikian, kamu berada pada permainan yang salah.

### Catatan

[^wine]: Using wine.
[^compatibility-mode]: DirectX via compatibility mode.
[^coming-soon]: Coming soon.
[^dll]: Manually via `.dll` files.
[^share-files]: Beatmaps and skins will share files and save on disk space.
[^gameplay-only]: Gameplay only.
[^online]: Via online retrieval.
[^normalisation]: This brings beatmap custom combo colours to the same brightness level.
[^hold-for-hud]: Hold `Ctrl` to view the HUD momentarily while it's hidden.
[^offset-calibration-stable]: Adjustable manually via key bindings.
[^offset-calibration-lazer]: When retrying a beatmap, you can calibrate the offset based on your last play.
[^can-disable]: Can be disabled.
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
