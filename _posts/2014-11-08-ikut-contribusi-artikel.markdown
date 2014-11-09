---
layout: post
title:  "Ikut Kontribusi Artikel"
description: "Untuk ikut serta berkontribusi menulis artikel di UKM PPN caranya mudah sekali, cukup menulisnya di editor notepad, kemudian menyimpannya dan kirim ke email kemudian konfirmasi pengiriman artikel, ta-ta ... tunggu konfirmasi publikasi dari kami dan artikel sudah terpublikasi, cukup mudah."
date:   2014-11-08 08:07:00
categories: update
author: M. Saiful Mukharom
meta: Artikel ilmiah anda, kami tunggu.
---

Overview
========
Untuk ikut serta berkontribusi menulis artikel di UKM PPN caranya mudah sekali, cukup menulisnya di editor notepad, kemudian menyimpannya dan kirim ke email kemudian konfirmasi pengiriman artikel, ta-ta ... tunggu konfirmasi publikasi dari kami dan artikel sudah terpublikasi, cukup mudah. Yang perlu disiapkan untuk ikut kontribusi menulis artikel di website UKM PPN adalah sebagai berikut:

- **Editor**, Editor yang digunakan secara default boleh menggunakan notepad, akan tetapi lebih bagus bisa menggunkan notepad++, Sublime dan lainnya.
- **Nama File**, `tahun-bulan-tanggal-judul-artikel.markdown` contoh: `2014-11-08-ikut-contribusi-artikel.markdown`
- **Format**, Untuk menulis artikel format `.markdown` download panduan berikut: [Panduan Markdown][panduan], Ekstrak dengan rar atau zip, kemudian edit sesuai artikel yang akan di postkan dan simpan.
- Kirim ke email **ppn@unpkdiri.ac.id**, format pengiriman email: 

|---
| Item | keterangan
| :-| :-| :-
| kepada | ppn@unpkdiri.ac.id 
| subjek | Judul Artikel 
| content | Nama, Jurusan, Tingkat, HP (untuk mngkonfirmasi bahwa artikel sudah di publikasi)
---|  

- Jika artikel beserta gambar, kirim juga gambar-nya ke email
- Konfirmasi Pengiriman Artikel : nama_lengkap.judul_artikel kirim ke: 085730947129
- Ta-ta ... artikel sudah terpublikasi.

### Penjelasan Panduan Markdown
Perhatikan symlinks berikut :
{% highlight markdown %}
---
layout: post 
title:  "Judul Artikel"
description: "diskripsikan secara umum tentang artikel kamu disini, maksimal 35 kata"
date:   tahun-bulan-tanggal, contoh: 2014-12-12
categories: update
author: Tulis Nama Lengkap
meta: diisi diskripsi judul maksimal tujuh kata
---
{% endhighlight %}

Hasil dari script diatas seperti:

![Symlinks][symlinks]

Perhatikan Headling berikut:
{% highlight markdown %}
Overview
========
Gambaran secara universal dari artikel, maksimal 50 kata.
{% endhighlight %}

hasilnya :

![Overview][overview]

Perhatikan list berikut:
{% highlight markdown %}
### subbab1
 1. subsubab1
    Isi subsubbab disini, **Tulisan tebal**, **Tulisan Miring*, [links yang disertakan][link1]
    ![gambar1][gambar1]
    * subsubsubab1
      Isikan subsubsubbab disini, **Tulisan tebal**, **Tulisan Miring*, [links yang disertakan][link1]
      ![gambar2][gambar2]
    * subsubsubab2

[link1]: http://example.com
[gambar1]: http://ppn.unpkediri.ac.id/images/research.jpg
{% endhighlight %}

hasilnya :

![Subab][list]


[panduan]: /files/panduan_markdown.7z
[symlinks]: /images/2014/11/symlinks.jpg
[overview]: /images/2014/11/overview.jpg
[list]: /images/2014/11/list-bold-italic-link-images.jpg