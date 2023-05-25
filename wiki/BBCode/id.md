<!--The imagemap button was added to the toolbar in osu-web#9972. When updating this article, keep in mind translating the new "Help" string on Crowdin and updating the editor.jpg file.-->

# BBCode

BBCode merupakan [bahasa *markup*](https://en.wikipedia.org/wiki/Markup_language) yang digunakan pada forum osu! dan forum internet lain pada umumnya. Bahasa ini berfungsi untuk menampilkan tulisan dalam format *rich text* melalui berbagai tag, di mana masing-masing tag memiliki fungsinya tersendiri seperti memformat teks, memberikan atribut, menyematkan konten, dan lain sebagainya. Pada situs web osu!, BBCode digunakan pada berbagai tempat seperti postingan forum, tanda tangan (*signature*), laman pengguna (*user page*), dan kolom deskripsi beatmap.

![Kotak dialog editor post beserta dengan tombol-tombolnya](img/editor-id.jpg "Kotak dialog editor post pada forum osu!")  

## Perilaku

Mengklik tombol markup tanpa menyeleksi teks apa pun akan membuat serangkaian tag terbuka dan tertutup di sekitar teks pada editor postingan. Menyeleksi teks sebelum mengklik tombol markup akan menjadikan teks tersebut diapit oleh tag yang diinginkan.

Pengguna yang ingin menggabungkan pemformatan ke dalam satu bagian teks, dapat melakukannya dengan menempatkan tag BBCode satu sama lain. Namun, urutan dan tingkatan tag yang diinginkan, **wajib kenali** saat digabungkan. Kegagalan menerapkannya akan merusak pemformatan.

Berikut merupakan contoh penulisan tag bersarang yang benar dan salah:

- `[centre][b]teks[/b][/centre]` benar
- `[b][centre]teks[/b][/centre]` salah

## Tag

BBCode, sebagaimana bahasa *markup* lain pada umumnya, digunakan untuk memformat teks dengan menggunakan tag yang ditempatkan di antara sepasang tanda kurung siku (`[]`). Setiap tag terdiri dari tag "pembuka" dan "penutup", di mana tag pembuka ditulis tanpa tanda garis miring (`/`) dan tag penutup ditulis dengan tanda garis miring.

Beberapa tag memiliki argumen tambahan yang dapat dibubuhkan pada tag pembuka dengan menggunakan tanda sama dengan (`=`). Argumen ini digunakan untuk menunjukkan URL, ukuran huruf, atau elemen lain yang berkaitan dengan tag tersebut.

Berikut merupakan daftar tag BBCode yang didukung oleh situs web osu! beserta penjelasannya.  

### Bold

```
[b]teks[/b]
```

Tag `[b]` atau *cetak tebal* digunakan untuk menguatkan teks melalui penggunaan huruf yang dicetak tebal. Ketebalan huruf ini tidak memengaruhi ukuran huruf.

Tombol pada toolbar: ![Tombol Bold](img/bold.png "Bold")

### Italic

```
[i]teks[/i]
```

Tag `[i]` atau *cetak miring* digunakan untuk memberikan penekanan ringan pada teks melalui penggunaan huruf yang dicetak miring.

Tombol pada toolbar: ![Tombol Italic](img/italic.png "Italic")

### Underline

```
[u]teks[/u]
```

Tag `[u]` atau *garis bawah* digunakan untuk memberikan penekanan pada teks melalui penggunaan garis bawah. Garis yang tergambar dapat dipengaruhi oleh tag lain seperti [bold](#bold) dan [italic](#italic).

### Strikethrough

```
[strike]teks[/strike]
```

*Dikenal juga sebagai **strike**.*

Tag `[strike]` atau *coret* digunakan untuk memberikan kesan bahwa teks yang bersangkutan seolah-olah akan dihapus melalui paparan garis horizontal yang "mencoret" teks.

Tombol pada toolbar: ![Tombol Strike](img/strike.png "Strikethrough")

### Colour

```
[color=KODE HEX]teks[/color]
```

*Untuk daftar nama warna yang didukung oleh tag ini, kunjungi laman [X11 color names](https://en.wikipedia.org/wiki/X11_color_names#Color_name_chart)*.

Tag `[color]` atau *pewarnaan* digunakan untuk mewarnai teks dengan warna yang ramah web (*web-safe colours*). Tag ini menggunakan format [kode HEX](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet) dalam pewarnaannya, meskipun warna yang ada juga dapat ditentukan secara langsung melalui nama umumnya seperti "Red" atau "Green". Untuk mewarnai teks, ubah argumen `KODE HEX` pada contoh di atas dengan kode HEX atau nama warna yang sesuai.

Argumen warna pada tag ini tidak ditulis dengan tanda kutip (`"`) serta tidak memiliki nilai *default*. Apabila argumen ini dikosongkan atau apabila warna yang ada ditulis dengan tanda kutip, tag ini tidak akan diuraikan sebagai tag BBCode yang sah.

### Font size

```
[size=UKURAN]teks[/size]
```

Tag `[size]` atau *ukuran huruf* digunakan untuk mengubah ukuran huruf pada teks. Saat ini, terdapat empat ukuran huruf yang didukung oleh situs web osu!: 50, 85, 100, dan 150, atau yang dikenal juga dengan nama "Mungil", "Kecil", "Normal", dan "Besar".

Argumen `UKURAN` pada tag ini tidak ditulis dengan tanda kutip dan hanya dapat diisi dengan salah satu dari empat ukuran huruf yang didukung. Apabila ukuran huruf yang dimasukkan bukan merupakan salah satu dari empat ukuran yang tertera di atas, teks akan ditulis dalam ukuran normal.

Tombol pada toolbar: ![Pengaturan Ukuran Huruf](img/font-size-id.png "Font size")

### Spoiler

```
[spoiler]teks[/spoiler]
```

*Tag ini tidak sama dengan [Spoilerbox](#spoilerbox).*

Tag `[spoiler]` digunakan untuk menutupi teks yang berisi informasi sensitif dengan latar berwarna hitam. Teks yang tertutup oleh spoiler hanya akan dapat dilihat pada saat di-*highlight* oleh pengguna. Apabila digunakan bersamaan dengan tag [`[color]`](#colour), latar hitam yang ada tidak akan terpengaruh, namun teks asli yang ditutupi oleh tag ini akan tetap berubah warna.

Tag ini pada umumnya digunakan untuk menyembunyikan informasi penting/sensitif seputar acara TV, film, atau media lainnya. Terkadang, tag ini juga digunakan untuk memberikan penekanan pada teks atau sebagai guyonan belaka.

### Box

```
[box=NAME]
teks
[/box]
```

*Tag ini tidak sama dengan [Spoilerbox](#spoilerbox).*

Tag `[box]` atau *kotak spoiler* digunakan untuk menyembunyikan teks dan gambar di dalam boks yang dapat dibuka dan ditutup. Pada saat diklik, konten yang terdapat di dalam boks akan tersingkap seperti layaknya pada menu *dropdown*.

Tag ini memiliki argumen `NAME` yang digunakan untuk menentukan judul boks. Apabila argumen ini dikosongkan, tag `[box]` akan menghasilkan kotak spoiler tanpa keterangan judul di dalamnya. Argumen ini tidak ditulis dengan tanda kutip (`"`) dan judul yang tertera akan didahului oleh karakter spasi.

Tag ini pada umumnya digunakan untuk menyembunyikan teks yang panjang dan gambar yang berukuran besar pada postingan forum, terutama pada laman FAQ atau utas forum [skin](/wiki/Skinning).

*Catatan: Pada toolbar, tombol BBCode yang berfungsi untuk membuat kotak spoiler memiliki nama "spoiler box". Meskipun demikian, tombol ini tidak menghasilkan tag `[spoilerbox]`.*

Tombol pada toolbar: ![Tombol Box](img/spoilerbox.png "Box")

### Spoilerbox

```
[spoilerbox]teks[/spoilerbox]
```

Spoilerbox merupakan tag BBCode yang serupa dengan `[box]`, namun tanpa argumen `NAME`. Kotak spoiler yang dihasilkan oleh tag `[spoilerbox]` akan selalu mengusung `SPOILER` sebagai judulnya. Walaupun spoilerbox memiliki tag-nya tersendiri, secara fungsi tag ini identik dengan tag [box](#box).

### Quote

```
[quote="NAME"]
teks
[/quote]
```

Tag `[quote]` atau *kutipan* digunakan untuk menampilkan teks dalam bentuk blok kutipan ("*block quote*") melalui penggunaan indentasi, pewarnaan, cetak tebal, dan pemisahan teks melalui garis vertikal merah muda. Isi dari kutipan ditempatkan di antara tag terbuka dan tertutup, sedangkan argumen `NAME` menentukan penulis kutipan (meskipun ini opsional). Teks di dalam tanda kutip akan membuat spasi dan jeda baris.

*Catatan: Argumen `NAME` pada tag ini wajib ditulis dengan tanda kutip (`"`).*

Kutipan panjang biasanya digunakan dalam tulisan yang lebih formal sebagai pengganti kutipan sebaris ketika biasanya menggunakan tiga baris atau lebih. Bagaimanapun, di dalam forum osu!, tag ini paling sering digunakan untuk membalas komentar pengguna lain, yang dapat dilakukan melalui tombol `Kutip posting untuk balasan` dengan cara menyeret mouse ke area postingan, terletak di kanan atas komentar yang diinginkan (ditampilkan di bawah). Namun, tombol ini **hanya akan muncul jika kursor berada di dekatnya**.

![Tombol Quote reply](img/quotereply.png "Kutip posting untuk balasan")

### Code block

```
[code]
teks
[/code]
```

Tag `[code]` atau *balok kode* digunakan untuk membuat *kode blok yang telah diformat sebelumnya*. Di situs web osu!, tag `[code]` akan memformat teks dalam font monospace di dalam kotak abu-abu semi transparan. Pemformatan teks di dalam kode blok akan memberi tahu editor untuk memperlakukan teks di antara tag tersebut secara harfiah, sehingga mencegah konversi tag atau kode sumber apa pun menjadi sesuatu yang lain.

Di dalam forum osu!, kode blok paling sering digunakan untuk memposting source code untuk [storyboard](/wiki/Storyboard), atau dalam tutorial yang mengharuskan menampilkan sintaks untuk tag, perintah, atau source code.

### Centre

```
[centre]teks[/centre]
```

Tag `[centre]` atau *rata tengah* digunakan untuk meratakan teks ke tengah kotak. Tag ini paling sering digunakan untuk efek gaya dalam judul, tajuk, atau puisi. Jika ditempatkan di dalam atau di sekitar tag [`[quote]`](#quote), teks di dalam blok kutipan akan dipusatkan, tetapi tidak untuk garis gaya dan semacamnya.

### URL

```
[url=LINK]teks[/url]
```

Tag `[URL]` atau *tautan* digunakan untuk mengubah teks biasa menjadi hyperlink yang dapat diklik.

*Catatan: Tag ini tidak diperlukan jika seseorang tidak ingin menggunakan teks hyperlink kustom, karena editor forum mengurai URL yang tepat menjadi link secara otomatis.*

Untuk membuat hyperlink dengan tag `[url]`, pengguna harus menentukan dua argumen: teks yang ditautkan untuk ditampilkan dan URL situs web spesifik yang akan dinavigasikan. Yang pertama harus ditentukan antara tag terbuka dan tertutup, dan yang terakhir harus ditentukan sebagai argumen `LINK`, tanpa tanda kutip (`"`). Jika tidak ada teks yang dimasukkan, teks akan berubah ke default nama URL.

Tombol pada toolbar: ![tombol URL](img/url.png "URL")

### Profile

```
[profile=userid]nama pengguna[/profile]
```

Tag `[profile]` atau *profil* digunakan untuk menautkan halaman profil pengguna osu! dengan menggunakan nama pengguna atau ID pengguna mereka. Penggunaan tag `[profile]` berbeda dengan penggunaan tag [`[url]`](#url), karena tag `[profile]` menampilkan kartu pengguna saat mengarahkan kursor ke tautan yang dibuat oleh tag.

*Catatan: ID pengguna adalah rangkaian angka yang langsung mengikuti `/users/` di akhir URL sebuah halaman profil osu!.*

Jika ditentukan melalui ID penggunanya, teks diantara tag terbuka dan tag tertutup tidak akan diurai dan akan ditampilkan sebagai nama pengguna pengguna sekarang. Namun, jika ditentukan hanya melalui nama pengguna, dan pengguna tersebut mengubah nama pengguna mereka, tautan akan berhenti berfungsi.

### Formatted lists

```
[list=TYPE]
[*]item 1
[*]item 2
[*]item 3
[/list]
```

Tag `[list]` atau *uraian/daftar* digunakan untuk pemformatan berbagai jenis daftar di seluruh forum osu! dengan menggunakan tanda bintang yang diapit tanda kurung (`[*]`) untuk menunjukkan item baru dalam daftar (ditampilkan di atas) secara otomatis. Umumnya, menggunakan tag ini akan menjadikan daftar poin lebih jelas.

Gaya daftar pada poin lainnya dapat diformat dengan menetapkan argumen `TYPE` sebagai `1`, `a`, `A`, `i`, atau `I`, yang akan memformat daftar point sebagai bernomor, berhuruf (huruf kecil), berhuruf (huruf besar), angka romawi (huruf kecil), dan angka romawi (huruf besar).

*Perhatian: Daftar BBCode berformat dapat ditumpuk satu sama lain dan bisa ditempatkan di dalam satu sama lain, meskipun diketahui menyebabkan masalah pada pemformatan.*

Tombol-tombol pada toolbar: ![Tombol daftar](img/list.png "Daftar") ![Tombol numbered list](img/list-numbered.png "Daftar bernomor")

### Images

```
[img]ADDRESS[/img]
```

Tag `[img]` atau *gambar* digunakan untuk menyematkan tautan gambar berekstensi dari online ke dalam postingan forum osu!. Untuk menggunakan tag, pengguna harus menempelkan alamat gambar langsung (diwakili oleh argumen `ADDRESS` di atas) yang bersumber dari situs web. Jalur file lokal. Menggunakan tautan langsung dari komputer (*offline*), (misalnya, `C:\Users\Name\Pictures\image.jpg`), **tidak akan berfungsi**.

*Perhatikan: URL situs web **tidak** sama dengan alamat gambar.*

Untuk mendapatkan alamat suatu gambar, pengguna harus menavigasi ke sumber situs web, mengarahkan mouse ke gambar, klik kanan pada gambar, dan pilih `Salin alamat gambar`. Kemudian, alamat yang telah disalin, ditempel di antara tag.

Meskipun gambar dapat diambil dari mana saja, osu! menyarankan pengguna mengunggah gambar ke situs berbagi gambar ternama seperti [Imgur](https://imgur.com), karena beberapa situs web tidak mendukung tautan langsung ke gambar (atau dikenal sebagai "hotlink").

Tombol pada toolbar: ![Tombol Image](img/image.png "Image")

### YouTube

```
[youtube]VIDEO_ID[/youtube]
```

Tag `[youtube]` digunakan untuk menyematkan video di situs web [YouTube](https://youtube.com) ke dalam forum osu!. Pengguna diharuskan untuk memasukkan hanya ID video (**bukan** seluruh URL) di antara kedua tag (diwakili oleh argumen `VIDEO_ID` di atas).

ID video YouTube terletak di URL video YouTube dan merupakan string 11 karakter *tepat setelah* huruf `v=`.

### Audio

```
[audio]URL[/audio]
```

Tag `[audio]` digunakan untuk menyematkan pemutar audio [HTML5](https://en.wikipedia.org/wiki/HTML5) berekstensi dari berbagai sumber audio online. File audio dapat bersumber dari mana saja, selama file tersebut terdapat URL tertentu. Menggunakan jalur file lokal dari komputer (*offline*), (misalnya, `C:\Users\Name\Music\audio.mp3`) **tidak akan berfungsi**.

*Perhatian: Karena masalah pembajakan musik, tidak semua layanan berbagi file mendukung file audio ripping. osu! tidak bertanggung jawab atas masalah hak cipta yang mungkin ditemui pengguna dalam hal tersebut.*

Untuk menyematkan file audio melalui metode ini, pengguna harus menempelkan sumber URL berekstensi (misalnya `https://www.example.com/example.mp3`) di antara dua tag `[audio]`.

<!-- Contoh URL file audio online untuk editor wiki: https://actions.google.com/sounds/v1/alarms/digital_watch_alarm_long.ogg -->

### Heading (v1)

```
[heading]teks[/heading]
```

Tag `[heading]` atau *tajuk* digunakan untuk pemformatan teks menjadi header besar berwarna merah jambu. Tag ini tidak mendukung tajuk multi-level, dan tidak dapat ditautkan secara khusus.

Tombol pada toolbar: ![Tombol Heading](img/heading.png "Heading")

### Notice

```
[notice]
teks
[/notice]
```

Tag `[notice]` atau *pemberitahuan* digunakan untuk menempatkan paragraf ke dalam kotak besar dengan garis tepi berwarna body gelap. Tombol ini utamanya digunakan untuk menunjukkan pemberitahuan atau peringatan mengenai subjek tertentu di situs web.

## Tag lawas yang tidak lagi digunakan

Berikut merupakan daftar tag BBCode yang telah dipensiunkan dari situs web osu!. Walaupun tidak lagi digunakan, fungsi dan tata cara penulisan tag-tag berikut turut didokumentasikan di bawah ini untuk keperluan sejarah.

### Google

```
[google]kueri pencarian[/google]
```

Tag `[google]` merupakan tag lawas yang dahulu digunakan pada forum osu! untuk menautkan teks ke kueri pencarian Google.

Tag ini akan mengarahkan pengguna ke laman pencarian Google melalui akun mereka. Berhubung Google mempersonalisasi hasil pencarian masing-masing pengguna, hasil pencarian yang ditampilkan tidak akan sama untuk semua orang. Karena hal ini pula, beberapa hasil pencarian tidak akan muncul bagi pengguna tertentu karena batasan bahasa atau negara.

### Lucky

```
[lucky]kueri pencarian[/lucky]
```

Tag `[lucky]` merupakan tag lawas yang dahulu digunakan pada forum osu! untuk menautkan teks ke situs web tertentu berdasarkan hasil tombol `Saya Lagi Beruntung` (*I'm Feeling Lucky*) milik Google. Situs web yang ditautkan melalui tag ini tidak akan sama untuk semua orang karena sifat tombol itu sendiri.

### Heading (v2)

```
[teks]
```

Tag *Heading (v2)* adalah sebuah tag usang yang pernah digunakan di forum osu! untuk pemformatan teks menjadi judul berwarna ungu yang tampak lebih menarik dengan garis horizontal. Tag ini hanya berfungsi di forum Beatmaps, dan hanya muncul setelah posting (bukan di pratinjau). Tag ini tidak memiliki tombol saat dalam pelayanan, dan dilambangkan dengan tanda kurung buka dan tutup (tidak ada tag pembuka dan penutup).

## Trivia

- Artikel ini diadaptasi dari utas forum ["HOW TO: Forum BBCodes"](https://osu.ppy.sh/community/forums/topics/445599) yang ditulis oleh [Stefan](https://osu.ppy.sh/users/626907).
- Dahulu kala, terdapat sebuah *bug* yang memungkinkan pengguna untuk membuat teks transparan dengan mencantumkan warna "transparent" pada [tag colour](#colour) (`colour=transparent`).
  - Saat ini, teks yang ada akan kembali ke warna *default* (putih) pada saat warna ini dipilih.
- Sebelum tag `imagemap` diperkenalkan, tautan dapat dibubuhkan kepada gambar dengan menggabungkan tag `url` dan `img`. Meskipun demikian, cara ini hanya dapat digunakan untuk membubuhkan satu tautan per gambarnya. Untuk membubuhkan lebih dari satu tautan, gambar tersebut harus terlebih dahulu dipotong menjadi beberapa bagian, ditautkan secara terpisah, dan kemudian disusun kembali secara berdampingan.