## Praktikum 1: HTML Dasar

### 1. Membuat Paragraf
Pada dokumen web, paragraf biasanya digunakan untuk menampilkan teks atau artikel. Paragraf dalam dokumen HTML dibuat dengan tag `<p>` .
Di bawah ini contoh paragraf sederhana yang dibuat pada HTML:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodepar1.PNG)

Dan berikut ini tampilan paragraf pada Browser:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/paragraf1.PNG)

Kemudian kita dapat mengubah tampilan paragraf tersebut dengan menggunakan atribut seperti contoh di bawah ini:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodepar2.PNG)

Atribut (align=> justify, center, right, left) digunakan untuk mengubah letak paragraf dalam dokumen.
dan ini perubahannya:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/paragraf2.PNG)

### 2. Menambahkan Judul
Judul memiliki 6 level yaitu mulai dari h1 sampai h6. Dengan cara  menambahkan judul h1 sebelum paragraf pertama dan menambahkan sub judul h2 sebelum paragraf kedua.

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodejudul.PNG)

 Dan seperti ini tampilan judul Heading 1 dan Heading 2:
 
 ![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/judul.PNG)
 
### 3. Memformat Teks

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodeformat.PNG)

 - tag `<mark>` (marker) digunakan untuk menandai teks yang penting atau kata kunci yang penting. Warna default marker adalah kuning. Warna ini bisa kita ubah dengan style CSS.
 - tag `<b>` (bold) dan tag `<strong>`digunakan untuk membuat teks tebal di HTML.
 - tag `<i>` (italic) digunakan untuk teks miring yang biasanya untuk menegaskan sebuah kata atau istilah baru.
 - tag `<ins>` (insert) atau tag `<u>` (underline) digunakan untuk menggaris bawahi teks yang disisipkan atau teks yang mimiliki arti penting dibandingkan teks normal lainnya.
 
 Hasilnya:
 
 ![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/format.PNG)

### 4. Menyisipkan Gambar

 - Tag yang digunakan untuk menampilkan gambar adalah `<img>` dengan atribut _src_ sebagai URL atau Path file gambar berada. Tag ini dapat memuat gambar dengan berbagai jenis ekstensi file gambar.
 - Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. 
 - Sebelum menambahkan tag `<img>` , tambahkan heading 3 setelah paragraf kedua.
 - Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
 
 ![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodesisip.PNG)
 
Hasilnya:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/sisipgambar.PNG)

### 5. Menambahkan Hyperlink
Untuk membuat Hyperlink menggunakan tag `<a>` dengan menambahkan atribut `<href>` sebagai penentu URL yang dimaksud.

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/kodelink.PNG)

Hasilnya:

![enter image description here](https://github.com/kameliacindy/Lab1Web/blob/main/img/link.PNG)



## Jawaban Pertanyaan-pertanyaan
1. Tidak ada error
2. **Tag `<p>`** digunakan untuk membuat paragraph baru dimana terdapat jarak antar paragraph, sedangkan **tag `<br>`** digunakan untuk pidah ke baris baru tanpa memberikan ruang/jarak.
3. Perbedaan alt dan tittle pada tag `<img`>:
**Alt text** atau text alternatif adalah atribut yang ditambahkan ke tag gambar dalam HTML. Teks ini muncul di dalam wadah gambar ketika gambar tidak dapat ditampilkan. Text alternatif juga sangat membantu dalam kasus gambar yang tidak ditemukan pada halaman atau gambar rusak.
**Title image** adalah atribut lain yang dapat ditambahkan ke tag gambar dalam HTML. Title image ini digunakan untuk memberikan judul untuk gambar Anda. Text yang Anda masukkan di dalam tag judul tidak akan ditampilkan kepada pengguna ketika gambar tidak dapat ditampilkan. Sebaliknya, tag judul gambar ini ditampilkan saat Anda menyorot gambar dengan mouse.
4. Boleh diisi semua, boleh salah satu.
 - Untuk mengatur gambar agar tampil proporsional gunakan width dan height sesuai ukuran aslinya, jika ingin mengecilkan gunakan ukuran yang proposional misal, kita akan ubah width 50px dan height 50px.
 - Cara mengecilkan gambar pada html yang baik hanya mengubah width atau heightnya saja, cara ini lebih disarankan karena height akan mengikuti width gambar tersebut jadi akan terlihat proporsional
5. **_blank, _self, _top, _parent**

**_blank** : untuk membuka link di tab baru

**_self** : untuk membuka link di frame link itu berada. ini merupakan setelan dasar link jika pada elemen link tidak diberi atribut target
**_top** : untuk membuka link di frame paling atas (paling luar).
**_parent** : untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada.



Nama	: Kamelia Cindy Astuti

NIM	: 311910104

Kelas	: TI. 19. A. 1

