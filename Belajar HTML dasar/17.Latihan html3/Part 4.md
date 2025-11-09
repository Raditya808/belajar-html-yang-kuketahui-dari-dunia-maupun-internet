Part ke 3 dan 4 

Tambahan kode di Buku.html 
yaitu menggunakan 
<tr></tr> → ini adalah table row, fungsinya mendefinisikan satu baris dalam sebuah tabel.

<td></td> → ini adalah table data, fungsinya mendefinisikan sebuah sel data (data cell) standar dalam sebuah tabel.

<th></th> → ini adalah table header, fungsinya sama seperti tag heading (h1, h2, h3) yaitu membuat teks tebal di bagian kepala tabel.

Tambahan kode di kontak.html 
yaitu membuat sebuah teks masukan sederhana 

<form>
<form> digunakan untuk membuat sebuah formulir tempat pengguna mengisi data 

<label for="Nama">Nama</label><br>
<label> memberikan keterangan pada kolom input di bawahnya.
Atribut for="Nama" menghubungkan label ini dengan elemen input yang memiliki id="Nama"

<input type="text" for="Nama"><br>
<input type="text"> membuat kolom teks satu baris untuk mengetik nama.

<label for="tanya">Pertanyaan:</label><br>
Label untuk kolom pertanyaan, dihubungkan dengan textarea yang memiliki id="tanya". 

<textarea name="tanya" id="tanya" rows="10" cols="40"></textarea><br>
<textarea> membuat area teks besar agar pengguna bisa menulis pertanyaan atau pesan panjang.
<br> yang berfungsi untuk membuat newline 
Atribut rows menentukan tinggi area teks, cols menentukan lebarnya. 

<input type="button" value="submit">
Tombol untuk mengirim data formulir ke server.

</form>
Penutup tag </form>, menandakan akhir dari formulir.

