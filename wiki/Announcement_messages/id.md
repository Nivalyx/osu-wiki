---
tags:
  - announce
  - announce usergroup
  - announce user group
  - pengumuman
---

# Pesan pengumuman

![Notifikasi pengumuman](img/notification.png "Pesan notifikasi pengumuman")

**Pesan pengumuman** merupakan jenis pesan khusus yang ditujukan untuk mengirim pesan yang lebih panjang dan terformat kepada banyak pengguna secara bersamaan. Hal-hal utama yang membedakan pesan pengumuman dengan pesan *chat* biasa meliputi:

- Batas jumlah 1024 karakter pada pesan (alih-alih 450 karakter)
- Dukungan sintaks markdown[^note-images] untuk pemformatan teks
- Pengiriman pesan kepada banyak pengguna secara bersamaan
- Kemampuan untuk mengabaikan pengaturan `blokir pesan pribadi dari pengguna yang tidak berada dalam daftar temanmu`
- Pesan yang dikirim hanya akan dapat dibalas oleh para pengguna yang juga memiliki izin untuk mengirimkan pesan pengumuman

## Eligibilitas

Sending and replying to announcement messages through the website requires membership in the [Global Moderation Team](/wiki/People/Global_Moderation_Team), the [Nomination Assessment Team](/wiki/People/Nomination_Assessment_Team), or the announce [user group](/wiki/People/User_group). However, only members of the announce user group are allowed to send chat announcements through the [osu! API v2](https://osu.ppy.sh/docs/index.html#create-channel).

### Mengajukan permintaan

Siapa pun dapat mengajukan permintaan untuk bergabung ke kelompok pengguna Announce dengan mengirimkan email ke alamat [accounts@ppy.sh](mailto:accounts@ppy.sh) dengan subjek `Announce Usergroup Request`. Email ini harus dikirim dari alamat email yang terhubung ke akun osu! pemohon.

Badan email yang dikirim harus mengandung hal-hal berikut:

- Nama akun osu! pemohon.
- Penjelasan yang menguraikan alasan mengapa pengiriman pesan ini dibutuhkan, serta seberapa sering fitur pengumuman ini akan digunakan.

[Tim dukungan akun](/wiki/People/Account_support_team) akan mengkaji permintaan ini dan menginformasikan keputusan mereka kepada pemohon yang bersangkutan.

## Mengirimkan pesan pengumuman

Untuk mengirimkan pesan pengumuman, buka [halaman *chat*](https://osu.ppy.sh/community/chat) dan klik tombol `buat pengumuman`. Pada layar yang terbuka, masukkan nama kanal, deskripsi[^note-desc], daftar penerima, dan isi pesan yang akan dikirim. Terakhir, klik tombol `kirim` untuk mengirim pengumuman.

![Halaman pembuatan pengumuman](img/page.jpg "Halaman pembuatan pesan pengumuman")

## Trivia

- Pesan pengumuman ditujukan sebagai pengganti dari sistem pesan [forum](/wiki/Community/Forum) lawas.
- [Basic implementation](https://github.com/ppy/osu-web/pull/8418) of the announcement system was added to the website on January 26th, 2022. This included the announce user group and the ability to send announcement messages through the API. The user interface for sending chat announcements, alongside allowing moderators to send them, was [added](https://github.com/ppy/osu-web/pull/8747) on June 1st, 2022.
- The announce user group's ID is 47, it has neither a group badge nor a dedicated colour, and its user listing is private.

## Notes

[^note-images]: Pengiriman gambar tidak didukung dalam pesan pengumuman.
[^note-desc]: Tidak seperti kolom lainnya, kolom deskripsi tidak wajib diisi.
