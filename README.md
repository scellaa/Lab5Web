# Lab5Web

### Penjelasan kode <br>
Latihan 1 <br>
<img width="826" height="391" alt="image" src="https://github.com/user-attachments/assets/2e8ed7ea-3b26-42a4-8166-3fcd00681f5c" />
<br>
Program ini menerima dua nilai dari prompt() lalu menampilkan hasil penjumlahan, pengurangan, perkalian, pembagian, dan modulus di console. Karena prompt() selalu mengembalikan string, nilainya harus dikonversi dengan Number(); tanpa itu, "9" + "4" menghasilkan "94", bukan 13. Fungsi isNaN() memastikan input berupa angka, sedangkan operator ternary mencegah pembagian dan modulus dengan nol. Perlu diingat bahwa prompt() hanya tersedia di browser, tidak di Node.js.
<img width="826" height="180" alt="image" src="https://github.com/user-attachments/assets/870ad2ea-a3ce-4568-9e91-3be71e650ce9" />
<img width="826" height="159" alt="image" src="https://github.com/user-attachments/assets/6d645b73-6f47-4576-8ed2-f8e8150e1b89" />
<img width="826" height="324" alt="image" src="https://github.com/user-attachments/assets/ef747b75-c602-43ef-b7e8-71577f43db30" />

Latihan 7 <br>
<img width="756" height="214" alt="image" src="https://github.com/user-attachments/assets/62aef061-4eb7-4a34-9c81-3020f0e8139c" /> <br>
Perulangan for dimulai dari i = 1, berjalan selama i <= 10, dan menambah i satu per satu di setiap putaran. Pada tiap putaran, hasil perkalian dicetak memakai template literal (tanda ` dan ${}) agar teks dan nilai dapat digabung tanpa operator +. Dengan membungkusnya dalam fungsi tabelPerkalian(angka), tabel untuk angka apa pun dapat ditampilkan.
<img width="826" height="386" alt="image" src="https://github.com/user-attachments/assets/35332180-09de-44ba-b329-f92544a5917d" />

Latihan 8 dan 9 <br>
<img width="826" height="156" alt="image" src="https://github.com/user-attachments/assets/ee6af96d-561d-4663-a509-e93a4b4851a1" /><br>
Halaman ini memeriksa apakah bilangan bulat yang dimasukkan pengguna genap atau ganjil. Fungsi cekGenap(angka) mengembalikan true jika angka habis dibagi 2 dan false jika tidak, tanpa perlu if tambahan karena operator === sudah menghasilkan nilai boolean. Fungsi cekBilangan() mengambil input, memvalidasinya dengan Number.isInteger(), lalu menampilkan hasilnya di elemen <p>. Memisahkan cekGenap dari logika tampilan membuat fungsi tersebut mudah dipakai ulang, dan bilangan negatif tetap dihitung dengan benar.

Latihan 10 <br>
<img width="826" height="597" alt="image" src="https://github.com/user-attachments/assets/6d790bdc-092c-45f2-a0c4-e46fb7f2a32c" /><br>
Halaman ini menampilkan daftar menu berupa checkbox dan menghitung total harga secara otomatis setiap kali pilihan berubah. Harga disimpan pada atribut value tanpa titik pemisah (3000, bukan 3.000) karena Number("3.000") terbaca sebagai 3. Fungsi querySelectorAll(".menu") mengambil semua checkbox ber-class menu, lalu event change memanggil hitungTotal() yang menjumlahkan nilai checkbox yang dicentang. Hasilnya diformat dengan toLocaleString("id-ID") sehingga tampil dengan pemisah ribuan gaya Indonesia. Karena JavaScript membaca class, menu baru cukup ditambahkan satu baris HTML tanpa mengubah kode JavaScript.
<img width="705" height="353" alt="image" src="https://github.com/user-attachments/assets/97c4eb1a-2c57-48ef-b06c-d0bcd4a75e31" />

Latihan 11 <br>
<img width="842" height="353" alt="image" src="https://github.com/user-attachments/assets/4f3eee0a-1f02-4c3d-8add-1d5475a7597a" /><br>
Setiap kali tombol diklik, properti hidden pada elemen konten dibalik nilainya dengan operator !, sehingga elemen bergantian tersembunyi dan tampil. Teks tombol ikut diperbarui lewat operator ternary agar sesuai kondisi saat ini, dan atribut aria-expanded membantu pembaca layar menyampaikan status konten. Alternatifnya adalah mengubah style.display antara "none" dan "block", yang lebih aman jika elemen sudah memiliki aturan CSS display sendiri seperti flex. <br>

<img width="287" height="119" alt="image" src="https://github.com/user-attachments/assets/0646ac1a-35e6-4ea9-860d-5885355d7fd3" /> <br>
<img width="251" height="81" alt="image" src="https://github.com/user-attachments/assets/78cac066-88d4-4c3a-bb06-77ca054602d7" />

