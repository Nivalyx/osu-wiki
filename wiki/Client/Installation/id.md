# Instalasi

*Lihat juga: [Instalasi osu! pada perangkat MacOS](/wiki/Client/Installation/macOS)*

Halaman ini akan menjelaskan cara untuk menjalankan osu! pada perangkat Windows milikmu. Apabila kamu butuh panduan lebih lanjut, kamu dapat menonton [video tutorial berikut](https://www.youtube.com/watch?v=0V5GwzmMhpU) yang ditayangkan pada kanal YouTube [osu!academy](/wiki/Community/Video_series/osu!academy).

## Persyaratan sistem minimum

- .NET framework 4+ (installer osu! akan secara otomatis meminta kamu untuk mengunduh komponen ini; apabila kamu tidak diminta, kamu dapat mengunduhnya [di sini](https://www.microsoft.com/id-id/download/details.aspx?id=48130))
- Kartu grafis yang memadai.

## Memasang osu!

1. Buka [halaman unduhan](https://osu.ppy.sh/home/download) dan unduh installer osu!.
2. Jalankan installer yang beru saja diunduh.
3. Pada saat installer sedang berjalan, kamu akan memiliki waktu sepuluh detik untuk mengubah lokasi pemasangan osu!.
   - Apabila kamu ingin mengubahnya, klik teks yang ada di bawah kata `Hi!` dan pilih lokasi pemasangan yang baru.
   - osu! akan dipasang pada lokasi beru yang dipilih setelah hitungan mundur ini berakhir.
4. Setelah proses instalasi rampung, osu! akan menjalankan dirinya secara otomatis. osu!direct akan kemudian mengunduh beberapa beatmap pengantar untuk kamu mainkan.
5. Terakhir, osu! akan meminta kamu untuk masuk atau membuat akun baru.
   - Apabila kamu sudah memiliki akun, silakan masuk.
   - Apabila kamu belum memiliki akun, ikuti petunjuk yang tertera pada [Pendaftaran](/wiki/Registration).

## Penyelesaian masalah

Apabila kamu menggunakan Windows 7 64-bit, kamu mungkin akan menemui beberapa masalah dalam memasang osu! dengan benar. Cobalah untuk memasang .NET Framework versi 64-bit secara terpisah apabila program ini tidak tersedia dalam paket installer osu!. [Unduh .NET Framework versi 64-bit di sini](https://download.microsoft.com/download/2/0/e/20e90413-712f-438c-988e-fdaa79a8ac3d/dotnetfx35.exe)

---

**Apabila installer osu! terus-menerus menampilkan pesan error dalam proses pemasangan, kamu dapat mencoba hal-hal berikut:**

- Cobalah untuk memasang ulang .NET Framework versi terbaru. [Kamu dapat mengunduh .NET Framework versi terbaru di sini.](https://dotnet.microsoft.com/download)
- Bersihkan PC kamu! Pindai komputermu dengan antivirus dan bersihkan registry-nya. Program yang disarankan untuk membersihkan isi komputer secara umum adalah CCleaner. Pindai berkas komputer dan registry kamu. Installer osu! bisa saja gagal dijalankan dikarenakan ada entri registry osu! dari salinan osu! terdahulu yang masih belum terhapus sepenuhnya dalam sistem kamu.

## Menambahkan beatmap

*Lihat juga: [Beatmap](/wiki/Beatmap)*

Terdapat dua cara untuk menambahkan beatmap, yaitu dengan mengunduh melalui situs web osu! atau menggunakan osu!direct (yang memerlukan [osu!supporter](/wiki/osu!supporter)).

### Situs web

1. Masuk ke akunmu dan kunjungi [halaman daftar beatmap](https://osu.ppy.sh/beatmapsets).
2. Cari lagu yang ingin kamu mainkan.
3. Klik `Unduh` untuk menyimpan berkas beatmap ke dalam komputer kamu.
4. Cari dan buka berkas beatmap yang telah kamu unduh, di mana berkas ini memiliki ekstensi `.osz`.
   - Kamu juga dapat menempatkan file beatmap yang telah diunduh langsung ke dalam folder `Songs` pada direktori osu! kamu.
5. osu! akan secara otomatis memuat beatmap yang bersangkutan ke dalam klien permainan.
   - Apabila beatmap gagal termuat, tekan `F5` pada layar [Song Selection](/wiki/Client/Interface#pemilihan-lagu) agar osu! dapat memproses dan memuat ulang semua beatmap yang kamu miliki.

### osu!direct

*Catatan: Kamu harus memiliki osu!supporter tag dan sambungan internet yang aktif untuk dapat menggunakan osu!direct.*

1. Buka osu! dan klik tombol osu!direct yang terletak pada sisi kanan menu utama.
2. Cari lagu yang kamu ingin mainkan.
3. Klik dua kali pada lagu yang dipilih atau klik `Download` pada menu yang muncul di sebelah kanan layar untuk mengunduhnya.
   - Apabila kamu tidak ingin mengunduh video yang disertakan dalam berkas beatmap, klik `DL NoVideo`.
4. Setelah beatmap selesai terunduh, osu! akan secara otomatis memuat beatmap yang bersangkutan ke dalam klien permainan.
   - Apabila beatmap gagal termuat, tekan `F5` pada layar [Song Selection](/wiki/Client/Interface#pemilihan-lagu) agar osu! dapat memproses dan memuat ulang semua beatmap yang kamu miliki.

## Menambahkan skin

*Lihat juga: [Skinning](/wiki/Skinning)*

1. Kunjungi [sub-forum skinning](https://osu.ppy.sh/community/forums/15) dan cari skin yang kamu sukai.
2. Setelah kamu menemukan skin yang kamu sukai, unduh skin tersebut.
3. Tergantung pada bagaimana skinner menyediakan berkas skin mereka, kamu mungkin perlu melakukan hal yang berbeda.
   - Apabila berkas skin disediakan dalam ekstensi `.osk`:
     1. Buka berkas `.osk` tersebut secara langsung atau lakukan *drag-and-drop* terhadap layar osu! yang sedang aktif.
     2. osu! akan secara otomatis memproses dan memuat skin tersebut untukmu.
   - Apabila berkas skin disediakan dalam format data yang terkompresi (`.7z`, `.rar`, `.zip`, dll.):
     1. Ekstrak berkas skin yang telah diunduh.
     2. Pindahkan folder hasil ekstraksi ke dalam folder `Skins` pada direktori osu!.
     3. Apabila osu! sedang aktif, skin akan muncul dalam daftar skin setelah kamu menekan kombinasi tombol `Ctrl` + `Alt` + `Shift` + `S`.
     4. Di dalam osu!, pilih menu [Options](/wiki/Client/Options) dan ketik `Skin` pada layar pencarian yang muncul.
     5. Pilih skin yang telah kamu unduh tersebut pada menu `Skin yang dipakai:`.
