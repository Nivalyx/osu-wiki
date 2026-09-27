# Nilai SEV

SEV adalah sistem pengukuran internal yang digunakan oleh [Nomination Assessment Team](/wiki/People/Nomination_Assessment_Team) (*NAT*) untuk menilai seberapa relevan suatu [penganuliran nominasi](/wiki/Beatmap_ranking_procedure#nomination-resets) terhadap hasil evaluasi dari [Beatmap Nominator](/wiki/People/Beatmap_Nominators) (*BN*) yang bersangkutan. Pengukuran ini terbagi ke dalam dua nilai, yang masing-masingnya ditampilkan sebagai *Obviousness* (kejelasan) dan *Severity* (keparahan). Kejelasan memiliki rentang nilai dari 0 ke 2 dan keparahan dari 0 ke 3, yang membuat sistem ini praktis untuk digunakan.

Berhubung nilai SEV hanya digunakan sebagai bahan dokumentasi dan acuan internal untuk keperluan evaluasi BN, nilai ini hanya bisa dilihat oleh para anggota NAT.

## Kejelasan dan keparahan

::: alert-notice
**Pemberitahuan**
Penganuliran nominasi yang dilakukan untuk memperbaiki hal-hal yang dianggap tidak bermasalah apabila tidak diperbaiki akan selalu diberikan nilai 0/0. Hal ini dilakukan agar orang-orang tidak merasa berkecil hati untuk bisa memberikan mod dan menyempurnakan beatmap yang ada di kategori [Qualified](/wiki/Beatmap/Category#qualified).
:::

**Kejelasan** mengacu kepada seberapa mudah suatu masalah bisa ditemukan.

| Nilai | Arti | Penjelasan |
| :-: | :-- | :-- |
| 0 | Tidak kentara | Berlaku apabila suatu masalah terlalu samar atau rinci untuk bisa terus-menerus ditemukan. |
| 1 | Bisa ditemukan dengan pengalaman | Memerlukan pengetahuan/pengalaman/ketelitian untuk bisa ditemukan. Pada umumnya tidak bisa ditemukan oleh pengecekan alat atau pengguna biasa, mis. masalah timing/metadata. |
| 2 | Bisa ditemukan dalam sekejap mata | Sesuatu yang kemungkinan akan bisa ditemukan oleh pengguna biasa, atau yang tidak akan terlewat apabila diperiksa dengan alat. |

**Keparahan** mengacu kepada seberapa berpengaruh suatu masalah terhadap permainan.

| Nilai | Arti | Penjelasan |
| :-: | :-- | :-- |
| 0 | Sepele | Tidak memengaruhi atau hanya sedikit memengaruhi permainan. |
| 1 | Patut diperhatikan | Memengaruhi permainan secara negatif, namun tidak signifikan. |
| 2 | Cela desain sedang | Memengaruhi permainan pada tingkatan yang pada umumnya bisa dirasakan oleh pengguna biasa, mis. jump yang besar di tingkat kesulitan yang rendah. Dalam prakteknya, hal ini sering kalinya disebabkan oleh kombinasi dari beberapa hal yang gamblang, seperti suatu pola yang terlalu sulit untuk dibaca atau lonjakan tingkat kesulitan (*difficulty spike*) yang berlebihan. |
| 3 | Cela desain fatal | Memengaruhi permainan hingga pada tingkatan yang dianggap mengacaukan, mis. dua objek permainan di waktu yang bersamaan. |

Berikut ini adalah contoh dari masing-masing nilai SEV dan bagaimana nilai ini kurang lebihnya diartikan oleh para evaluator:

| SEV | Penjelasan |
| :-- | :-- |
| 0/0 | Penganuliran ini tidak signifikan dan diabaikan dalam evaluasi. |
| 0/1 | Terjadi kesalahan, tapi karena kesalahan ini tidak mudah untuk ditemukan, sulit untuk menyalahkan BN atas kesalahan ini. |
| 1/0 | Bukan masalah yang berarti, walau bisa diperbaiki apabila BN yang bersangkutan lebih teliti. |
| 1/1 | Terjadi kesalahan yang bisa diperbaiki apabila BN yang bersangkutan lebih teliti. |
| 1/2 | Sering kalinya berarti bahwa ada banyak hal yang salah, walau semuanya butuh pengalaman untuk bisa ditemukan dengan mudah. |
| 2/0 | Terdapat beberapa kesalahan yang gamblang pada pengaturan beatmap, seperti metadata, yang karena satu dan lain hal sampai terlewatkan. |
| 2/1 | Terdapat beberapa kesalahan yang gamblang pada permainan beatmap itu sendiri, seperti hitsound yang hilang, yang terlewatkan. |
| 2/2 | Terdapat masalah fatal yang mencakup sebagian besar beatmap, seperti jump yang besar di tingkat kesulitan yang rendah, yang terlewatkan. |
| 2/3 | Terdapat masalah sangat fatal yang sulit untuk dilewatkan, seperti dua objek permainan di waktu yang bersamaan, yang terlewatkan. |

## Kegunaan

Nilai SEV digunakan dalam [proses evaluasi Beatmap Nominator](/wiki/People/Nomination_Assessment_Team/Evaluations), yang dibobotkan terhadap jumlah nominasi yang diberikan oleh masing-masing BN.

Kesalahan adalah hal yang lumrah, dan satu atau dua kesalahan akan membantu seseorang untuk belajar. Meski begitu, apabila kesalahan ini terlalu sering terjadi, atau apabila kesalahan yang sama terus diulang-ulang, maka hal ini adalah suatu masalah. Inilah mengapa evaluasi yang diberikan tidak terpaku kepada nilai-nilai SEV secara individu, tetapi lebih melihat situasi yang ada secara garis besar dari kasus per kasus.

## Alasan penganuliran umum

*Data ini mencakup 90% dari semua penganuliran nominasi yang terjadi.*

Berikut ini adalah daftar lengkap dari berbagai alasan di balik dianulirkannya suatu nominasi beserta dengan nilai SEV-nya masing-masing. Data ini didasarkan pada statistik semua nilai SEV yang tercatat di mode permainan osu! antara bulan Februari 2020 hingga April 2021, dengan disertai persentase yang menunjukkan seberapa sering suatu masalah terjadi.

Daftar ini tidak mencakup semua alasan penganuliran yang ada, dan para anggota NAT bisa jadi menilai nominasi yang dianulir dengan alasan yang sama dengan nilai yang berbeda, tergantung dari konteksnya.

### Metadata

*Mencakup 22% dari semua penganuliran >0/0, dan 30% dari semua penganuliran yang ada.*

Penganuliran metadata *tidak pernah* memiliki nilai keparahan di atas 0, karena kesalahan metadata tidak memengaruhi permainan sedikit pun.

- **0/0:** (70%)
  - Menambahkan tag untuk Featured Artist yang baru diumumkan
  - Menambahkan nama pemilik tingkat kesulitan tamu ke daftar tag karena perubahan nama pengguna
  - Menambahkan tag yang lebih rinci tapi tidak diwajibkan oleh kriteria ranking
  - Penganuliran yang disebabkan oleh diterapkannya peraturan baru
  - Perubahan nama tingkat kesulitan
- **1/0:** (23%)
  - Kesalahan pengurutan nama artis teromanisasi
  - Kesalahan romanisasi dan kapitalisasi kecil
  - Perbaikan 1 karakter yang salah tulis, salah eja, dll.
  - Tag genre/bahasa yang tidak ditulis
- **2/0:** (5%)
  - Nama pemilik tingkat kesulitan tamu yang tidak ditulis dalam tag
  - Kolom Unicode yang tidak diisi
  - Nama artis/judul/sumber lagu yang salah

### Mapping

*Mencakup 23% dari semua penganuliran >0/0, dan 10% dari semua penganuliran yang ada.*

Penganuliran yang disebabkan oleh masalah mapping sangat jarang memiliki nilai kejelasan 2, karena kesalahan mapping memerlukan pengetahuan mapping/modding yang baik untuk bisa dikenali dengan mudah.

- **0/0:** (46%)
  - Segala perubahan dari sesuatu yang sebelumnya sudah dinilai tidak bermasalah, terlepas dari jumlah perubahan yang dilakukan:
    - Memperbaiki stack yang tidak tertumpuk sempurna (yang tidak memengaruhi keterbacaan suatu map)
    - Menyesuaikan beberapa pattern untuk memperbaiki bagian buildup
    - Remapping an acceptable difficulty entirely because the mapper was unsatisfied with it
- **1/1:** (28%)
  - Common mapping mistakes that negatively impact the map to a notable degree
    - Unwarranted difficulty spikes (as in not fitting the song)
    - Dense rhythms/high spacing in calm sections
    - Overmapping in a way that is introduced/executed poorly
    - Mapping a big stream over multiple distinct [layers](/wiki/Music_theory/Layer) and sounds
- **1/2:** (14%)
  - Same reasons as for 1/1, but more severe; typically a combination

### Timing

*Mencakup 15% dari semua penganuliran >0/0, dan 8% dari semua penganuliran yang ada.*

- **0/0:** (20%)
  - Menyesuaikan titik pratinjau/waktu kiai
  - Menambahkan timing point untuk mengakomodir mod Nightcore
  - Menggunakan BPM yang digandakan/setengahnya
  - Offset yang sedikit salah
    - Untuk timing yang sederhana, batas kesalahan < 6 ms
    - Untuk timing yang kompleks, batas kesalahan < 10 ms
- **1/0:** (11%)
  - Birama ketukan yang salah
- **1/1:** (49%)
  - Offset yang salah
    - Untuk timing yang sederhana, batas kesalahan ~6–12 ms
    - Untuk timing yang kompleks, batas kesalahan ~10+ ms

### Berkas

*Mencakup 13% dari semua penganuliran >0/0, dan 10% dari semua penganuliran yang ada.*

Resets related to beatmap files almost never have a severity above 0, as they usually do not affect gameplay. An exception is using storyboarded hitsounds as replacement for active ones.

- **0/0:** (64%)
  - Any change made from an already acceptable/rankable state, for example:
    - Improving the audio from 128 kbps to 192 kbps
    - Any harmless changes to the background, storyboard, or skin
    - Inappropriate background(s) (where it is not obvious)
- **1/0:** (19%)
  - Using audio that has been encoded upwards from a lower bitrate
  - Using hitsound samples that affect gameplay negatively in the default skin
- **2/0:** (6%)
  - Unused file(s)
  - Missing video on some difficulties
  - Content that is obviously inappropriate

### Snapping

*Mencakup 9% dari semua penganuliran >0/0, dan 4% dari semua penganuliran yang ada.*

- **0/0:** (11%)
  - AiMod incorrectly detecting an object less than 2 ms off as unsnapped
  - Slightly mis-snapped slider end that tools cannot detect
- **1/0:** (21%)
  - Mis-snaps that hardly affect gameplay
    - Slightly mis-snapped slider end that tools could help find
    - An object being off by only a few milliseconds
- **1/1:** (42%)
  - Mis-snaps that are difficult to notice when playing, but sometimes cause 100s
- **1/2:** (8%)
  - Mis-snaps that notably affect gameplay
    - Mis-snaps that always cause 100s, sometimes 50s, or even note locks
    - Mis-snaps causing abnormal spacing to following/previous notes
    - A mis-snap part of a stream, burst, or triple (that cannot be a simplification)

### Hitsounding

*Mencakup 7% dari semua penganuliran >0/0, dan 11% dari semua penganuliran yang ada.*

- **0/0:** (73%)
  - Adding a few missing hitsounds
  - Removing a few misplaced hitsounds
- **1/0:** (14%)
  - Generally lacking hitsounds
  - Bad hitsounding, e.g. unwarranted claps/snares/cymbals on every beat or similar
- **1/1:** (6%)
  - Silenced active objects

## History

- SEV ratings were introduced in 20 May 2020 and were publicly visible.<!-- internal reference: https://discord.com/channels/316154420591067136/316586967171203075/712448434770018424 -->
- In 16 December 2023, SEV ratings were deprecated in favor of a simpler impact system that assigned a "minor", "notable" or "severe" label to each reset.<!-- internal reference: https://discord.com/channels/90072389919997952/299846395031060480/1184280021448273930 -->
- The SEV rating system was reintroduced on 19 April 2025<!-- internal reference: https://discord.com/channels/90072389919997952/299846395031060480/1363112346272272484 --> following concerns about impact ratings being too vague. However, it was not made public again given its main purpose is to serve as internal documentation.
