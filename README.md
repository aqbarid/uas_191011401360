# uas_191011401360

UAS Mobile Programing

## Jawaban Pertanyaan

**1. Apa yang dimaksud dengan state management pada flutter?**
State Management adalah sebuah cara untuk mengatur data / state kita bekerja, bisa juga untuk memisahkan antara logic dan view dimana logic tersebut juga bisa re-usable.
Cara kerja State Management seperti Provide and Listen, maksudnya adalah kita bisa memasukan state yang kemungkinan bisa berubah sewaktu waktu, lalu Widget yang Subscribe (Listen) dengan Provider yang kita buat akan berubah sesuai dengan state yang berubah.

**2. Sebutkan apa saja state management pada flutter !**
Manajemen keadaan dapat dibagi menjadi dua kategori berdasarkan durasi keadaan tertentu berlangsung dalam suatu aplikasi.

> *Ephemeral* Berlangsung selama beberapa detik seperti status animasi saat ini atau satu halaman seperti peringkat produk saat ini. Flutter mendukungnya melalui StatefulWidget.

> *app* state aplikasi Terakhir untuk seluruh aplikasi seperti detail pengguna yang masuk, informasi keranjang, dll., Flutter mendukungnya melalui scoped_model.
