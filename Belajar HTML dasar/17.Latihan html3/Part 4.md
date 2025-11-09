Part ke 3 dan 4
Tambahan kode di Buku.html

Menggunakan:

&lt;tr&gt;&lt;/tr&gt; → ini adalah table row, fungsinya mendefinisikan satu baris dalam sebuah tabel.

&lt;td&gt;&lt;/td&gt; → ini adalah table data, fungsinya mendefinisikan sebuah sel data (data cell) standar dalam sebuah tabel.

&lt;th&gt;&lt;/th&gt; → ini adalah table header, fungsinya sama seperti tag heading (h1, h2, h3) yaitu membuat teks tebal di bagian kepala tabel.


Tambahan kode di kontak.html 
yaitu membuat sebuah teks masukan sederhana 

&lt;form&gt;
&lt;label for="Nama"&gt;Nama&lt;/label&gt;&lt;br&gt;
&lt;input type="text" id="Nama"&gt;&lt;br&gt;

&lt;label for="tanya"&gt;Pertanyaan:&lt;/label&gt;&lt;br&gt;
&lt;textarea name="tanya" id="tanya" rows="10" cols="40"&gt;&lt;/textarea&gt;&lt;br&gt;

&lt;input type="button" value="submit"&gt;
&lt;/form&gt;


Penjelasan

&lt;form&gt; digunakan untuk membuat formulir tempat pengguna mengisi data.

&lt;label for="Nama"&gt;Nama&lt;/label&gt; memberikan keterangan pada kolom input di bawahnya.
Atribut for="Nama" menghubungkan label ini dengan elemen input yang memiliki id="Nama".

&lt;input type="text" id="Nama"&gt; membuat kolom teks satu baris untuk mengetik nama.

&lt;label for="tanya"&gt;Pertanyaan:&lt;/label&gt; adalah label untuk kolom pertanyaan, dihubungkan dengan textarea yang memiliki id="tanya".

&lt;textarea name="tanya" id="tanya" rows="10" cols="40"&gt;&lt;/textarea&gt; membuat area teks besar agar pengguna bisa menulis pertanyaan atau pesan panjang.

rows menentukan tinggi area teks

cols menentukan lebarnya
Tag &lt;br&gt; berfungsi untuk membuat newline.

&lt;input type="button" value="submit"&gt; adalah tombol untuk mengirim data formulir ke server.

&lt;/form&gt; menandakan akhir dari formulir.

