---
legal: true
---

# Kebijakan privasi osu!

Terakhir diperbarui pada tanggal 16 April 2021. [Lihat riwayat kebijakan ini di sini](https://github.com/ppy/osu-wiki/commits/master/wiki/Legal/Privacy/en.md)

Di samping kebijakan ini, pastikan juga untuk membaca dan memahami [Ketentuan Layanan](/wiki/Legal/Terms) kami.

## Pendahuluan

osu! dijalankan oleh entitas asal Australia (ppy Pty Ltd) dengan rangkaian server yang sebagian besarnya beroperasi dari Amerika Serikat.

osu! menawarkan berbagai jenis layanan kepada pengguna dari hampir setiap negara di seluruh dunia, dengan komunitas yang dinamis dan memungkinkan para penggunanya untuk dapat saling berbagi kreativitas melalui halaman profil pengguna, beatmap (level permainan), forum, pesan pribadi, *in-game chat*, dan komentar pada tayangan ulang.

Untuk dapat menawarkan layanan ini kepada Anda, kami sering kalinya harus mengumpulkan, menyimpan, dan menyebarluaskan informasi yang bersifat pribadi. Kami beritikad untuk menjalankan segala sesuatunya yang ada di osu! setransparan mungkin, dan kebijakan privasi ini merupakan salah satu bentuk upaya kami untuk mewujudkan tujuan tersebut.

Dokumen ini bertujuan untuk menjelaskan informasi apa saja yang kami kumpulkan pada jaringan kami dan dalam penggunaan produk dan layanan kami, bagaimana kami menggunakan informasi tersebut, serta pilihan apa saja yang kami tawarkan kepada Anda untuk mengelola informasi pribadi Anda.

Dengan menggunakan layanan kami, Anda membenarkan bahwa Anda telah membaca dan memahami [Ketentuan Layanan](/wiki/Legal/Terms) dan kebijakan privasi ini, termasuk bagaimana dan mengapa kami menggunakan informasi Anda serta bahwa dengan menggunakan layanan kami, Anda tunduk pada Ketentuan Layanan dan Kebijakan Privasi yang berlaku. Apabila Anda tidak ingin kami mengumpulkan atau memproses informasi pribadi Anda sebagaimana yang dijabarkan pada halaman ini, Anda memiliki beberapa pilihan seperti membatasi informasi apa saja yang dapat kami kumpulkan dari Anda, tidak menggunakan Jaringan kami, atau melepaskan diri dari Produk dan Layanan kami.

## Informasi yang kami kumpulkan

### Saat mendaftarkan akun

Walaupun fungsi tertentu dapat digunakan secara terbatas tanpa akun, sering kalinya para pengguna diharuskan untuk mendaftarkan akun demi menggunakan layanan tertentu. Pada saat Anda mendaftarkan akun, kami menyimpan

- Nama pengguna Anda
- Alamat email Anda
- Kata sandi Anda (bcrypt+salt)
- Alamat IP dan negara Anda

Kecuali nama pengguna dan negara Anda, informasi pribadi ini tidak akan pernah dibagikan secara publik.

### Saat memperbarui profil Anda

Pada saat Anda menyusun profil pengguna milik Anda (yang dapat dilihat oleh seluruh pengguna lainnya), Anda dapat menyertakan informasi berupa

- Lokasi Anda saat ini
- Minat Anda
- Pekerjaan Anda
- Presensi media sosial Anda (twitter, discord, skype, situs web)
- Avatar dan sampul profil Anda
- Tanda tangan Anda

Seluruh kolom di atas akan dapat dilihat secara publik, namun informasi ini akan dapat segera dihapus secara permanen kapan saja melalui [halaman pengaturan](https://osu.ppy.sh/home/account/edit).

### Saat mengunggah konten kiriman pengguna

Pada saat Anda menulis postingan forum, mengobrol pada *in-game chat*, atau mengunggah konten (seperti beatmap) ke dalam layanan kami, Anda secara tegas mempublikasikan segala sesuatunya yang Anda kirimkan. Dalam sebagian besar kasus, konten yang telah terkirim akan dapat disunting dan dihapus sesuai dengan keinginan Anda, namun dalam situasi tertentu hak ini dapat dianulir untuk menjaga relevansi dan kontinuitas layanan kepada basis pengguna kami.

Sebagai contoh, apabila Anda mengunggah suatu beatmap dan beatmap tersebut memperoleh status "ranked", beatmap tersebut akan menjadi dasar bagi para pengguna kami untuk dapat menorehkan skor. Pada titik ini, pilihan untuk menghapus kiriman yang bersangkutan tidak lagi akan tersedia.

### Saat masuk ke dalam permainan

Pada saat Anda menghubungkan diri ke layanan kami melalui klien permainan osu!, sebuah kode *string* yang spesifik bagi klien Anda akan dikirimkan untuk membantu kami dalam mengidentifikasi lingkungan permainan Anda. Kode ini dihasilkan berdasarkan kombinasi nomor pengenal yang diperoleh dari konfigurasi perangkat keras dan perangkat lunak Anda, yang kemudian di-*hash* sedemikian rupa agar tidak lagi mengandung informasi pribadi yang dapat diidentifikasi (namun tetap dapat digunakan untuk melacak entri masuk Anda ke dalam layanan kami).

Tujuan utama kami dalam melangsungkan proses ini adalah untuk mewujudkan sistem peringkat yang adil dan untuk membantu kami mengamankan akun Anda apabila akun ini diakses dari lokasi yang tidak dikenal. Kode ini bersifat pribadi dan hanya akan disimpan selama yang dibutuhkan. Di samping itu, kode ini juga tidak dapat dipindahtangankan dan tidak memiliki arti di luar ekosistem osu!.

### Saat bermain dan mengirimkan skor

Pada saat Anda menyelesaikan suatu sesi permainan (baik berhasil ataupun gagal), rincian performa Anda akan secara otomatis dikirimkan ke dalam server kami. Bagian skor dari rincian ini meliputi data tayangan ulang permainan, yang dapat ditampilkan secara publik pada Papan Peringkat Global dan Profil Pengguna Anda serta tidak dapat dihapus atau dimodifikasi.

### Anti-cheat

osu! mengandung kode *executable* khusus yang digunakan untuk mendeteksi penggunaan perangkat lunak illegal (*cheat software*). Tujuan dari sistem *anti-cheat* osu! ini adalah untuk menjaga lingkungan permainan yang adil dan kompetitif bagi semua, tanpa memengaruhi performa permainan ataupun privasi pengguna.

- Pendeteksian *cheat* berlangsung pada perangkat Anda, di mana dalam prosesnya osu! tidak akan mengirimkan data yang tidak dibutuhkan ke server kami.
- Apabila *anti-cheat* menemukan bahwa Anda bertindak curang, maka temuan ini, beserta dengan rangkaian bukti dalam bentuk diagnostik dan metadata permainan, akan dikirim ke server kami untuk diverifikasi. Apabila Anda tidak bertindak curang, tidak akan ada data *anti-cheat* yang akan dikirimkan.
- Bahkan pada saat suatu *cheat* terdeteksi, sistem kami akan sebisa mungkin tidak mengirim informasi apa pun ke luar ekosistem osu! yang dapat digunakan untuk mengidentifikasi Anda secara pribadi.
- Metadata yang dikirimkan hanya akan disimpan pada server kami selama masih digunakan. Pada umumnya, data ini akan disimpan selama beberapa jam hingga beberapa hari selagi kami menganalisa konten yang dilaporkan.
- Proses analisa sebagian besar dilakukan secara otomatis. Metadata permainan yang dikirim tidak dapat dilihat oleh anggota tim layanan dukungan kami dan hanya dapat diakses melalui sistem keamanan yang berlapis. Hanya para admin server *database* yang dapat melihat metadata permainan yang terkait.

Kami menghormati dan menghargai privasi Anda, di mana fitur *anti-cheat* ini tidak kami tujukan untuk menimbulkan rasa takut bagi mereka yang telah bermain secara adil.

### Pencatatan informasi

Kami menggunakan sistem pencatatan kesalahan (*error logging*) yang mengumpulkan berbagai informasi seputar teknis dan penggunaan layanan pada saat Anda berada di dalam layanan kami. Hal-hal ini dapat meliputi alamat IP Anda, nama pengguna Anda, jenis dan versi browser Anda, pengaturan dan lokasi zona waktu Anda, sistem operasi dan *platform* Anda, serta berbagai rincian lainnya seputar perangkat yang Anda gunakan untuk mengakses layanan kami.

Seluruh data yang terkumpul akan digabungkan dan hanya akan kami simpan selama masih digunakan. Pada umumnya, periode penyimpanan untuk data yang bukan merupakan data gabungan adalah kurang dari satu bulan dengan pengaturan pembersihan otomatis.

## Pengungkapan data pribadi Anda

Kami tidak melakukan pemasaran, pengiklanan, atau pengiriman email yang tidak dikehendaki. Seluruh email yang akan Anda terima dari kami murni merupakan bentuk respon atas segala sesuatunya yang Anda lakukan pada layanan kami (seperti meminta otentikasi dua faktor, membeli produk, atau mengaktifkan pemberitahuan pada sebuah topik diskusi).

Kami dapat membagikan data pribadi Anda kepada pihak ketiga dalam kasus-kasus tertentu yang sangat spesifik sebagai berikut:

- Di mana Anda secara tegas telah menyediakan informasi yang bersangkutan secara publik
- Untuk memenuhi pesanan belanja Anda
- Untuk memproses pembayaran Anda melalui biro-biro pembayaran seperti Paypal dan Xsolla
- Untuk memproses tiket layanan dukungan Anda (kami menggunakan [Enchant](https://enchant.com))
- Untuk meningkatkan layanan kami melalui sistem pencatatan kesalahan (*error logging*) yang berlaku (kami menggunakan [Sentry](https://sentry.io))

## Hak dan kendali Anda

Sebagai seorang pengguna, Anda memiliki hak untuk dapat memindahkan, memperbarui, atau menghapus informasi pribadi Anda. Hal ini dapat dilakukan melalui menu [pengaturan pengguna](https://osu.ppy.sh/home/account/edit) atau fitur "Edit" yang tersedia secara lokal pada fitur-fitur tertentu di situs kami. Apabila Anda ingin mengambil seluruh data akun Anda secara runut, mohon gunakan [API publik](https://github.com/ppy/osu-api/wiki) kami.

Pada umumnya, hasil kiriman pengguna seperti postingan forum dan unggahan beatmap dapat dihapus secara terpisah per masing-masing hasil kirimannya. Anda akan menemui tombol untuk menghapus hasil kiriman yang bersangkutan pada berbagai lokasi yang terkait.

Anda memiliki hak untuk dapat menghapus akun Anda dari layanan kami. Harap diperhatikan bahwa proses ini dilakukan secara manual dan dapat membutuhkan waktu hingga beberapa hari (Anda dapat [menghubungi kami](mailto:privacy@ppy.sh) untuk mengajukan permintaan penghapusan akun). Setelah akun Anda terhapus, sebagian kontribusi publik Anda dapat tetap tersimpan sebagaimana yang tertera pada "Informasi yang kami kumpulkan."

Kami menerapkan kebijakan satu akun per pengguna (*one-account-per-user*) yang ketat untuk menjaga permainan kami tetap adil. Oleh karenanya, setelah akun Anda dihapus, Anda tidak akan dapat kembali lagi ke layanan kami. Untuk menegakkan kebijakan ini, kami akan tetap menyimpan kode *string* pengenal milik akun Anda yang sebagaimana yang tertera pada "Informasi yang kami kumpulkan" bahkan setelah akun Anda dihapus. Layanan penghapusan akun ini sendiri kami tawarkan sebagai suatu [bentuk kepatuhan terhadap undang-undang GDPR](https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/legitimate-interests/when-can-we-rely-on-legitimate-interests/) yang wajib kami ikuti. Meskipun demikian, Anda tidak perlu khawatir karena seluruh informasi dalam proses ini akan di-*hash* secara satu arah dan tidak akan dapat digunakan untuk mengidentifikasi Anda di luar osu! atau di luar konteks penegakan kebijakan ini.

## Cookie

Seperti halnya seisi internet pada umumnya, layanan kami juga menggunakan *cookie*. Kami hanya akan menggunakan *cookie* ini untuk mempertahankan status sesi dan kredensial entri masuk Anda antar berbagai sesi. Apabila Anda tidak dapat menerima keberadaan *cookie*, mohon untuk tidak menggunakan layanan kami.

## Keamanan data

Keamanan merupakan hal yang sangat penting bagi kami. Untuk melindungi informasi pribadi Anda, osu! mengikuti standar keamanan yang baku dalam proses pengolahan, pemindahan, dan penyimpanan data pengguna. Kami menggunakan protokol HSTS untuk memastikan bahwa seluruh situs di domain kami dienkripsi dengan sertifikat TLS. Di samping itu, kami juga menerapkan izin akses yang sangat ketat ke dalam server-server kami, di mana kami hanya akan menyentuh data pribadi Anda apabila dibutuhkan.

Di samping itu, kami juga secara otomatis membersihkan data pengguna yang sudah tidak lagi digunakan dari waktu ke waktu. Kami hanya akan menyimpan data yang dibutuhkan untuk menjalankan kepentingan bisnis kami.

## Pengguna di bawah umur

Layanan osu! tidak diperuntukkan bagi anak-anak yang berusia di bawah 13 tahun. Apabila kami menemukan bahwa seseorang yang berusia di bawah 13 tahun telah mengirimkan informasi pribadinya kepada kami tanpa seizin orang tua/wali mereka, kami akan menghapus informasi tersebut dari sistem kami sesegera mungkin.

## Pengelola data

Hai, saya Dean (yang pada umumnya dikenal sebagai peppy) dan saya merupakan pengelola data Anda. Apabila Anda memiliki kekhawatiran seputar privasi atau ingin menggunakan hak hukum Anda, jangan sungkan untuk menghubungi saya secara langsung melalui alamat email di bawah ini.

**Email**: [privacy@ppy.sh](mailto:privacy@ppy.sh) (Jaminan respons 24 jam)

**Alamat Pos**:

```
Dean Herbert
41 Gregory Street
Wembley, WA, 6014
Australia
```
