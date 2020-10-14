# Currency-App

1. Review kembali percobaan 1 sampai dengan 3 dengan menjawab pertanyaan-pertanyaan pada latihan tersebut.
Percobaan 1
1. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang angka dan tulisan lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Aplikasi masih belum biisa mengkonversi usd ke idr. Jika kita menginputkan angka 100 ke box usd maka di box rupiah akan muncul value yang sama


Percobaan 2
2. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang angka lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Aplikasi akan mengkonversi nilai usd ke rupiah, karena ada codingan resultLabel.Content = Convert.ToString(nominalDouble * 10000); maka setiap value yang diinputkan ke dalam box usd akan dikali 10000. Maka dari itu value yang ditampilkan dalam box rupiah adalah hasil perkalian tersebut

3. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang huruf lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Aplikasi belum bisa menghandle inputan huruf maka aplikasi akan menutup dengan sendirinya (force close)


Percobaan 3
4. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang angka lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Dikarenakan ada codingan resultLabel.Content = Convert.ToString(nominalDouble * 4); Jika box usd diinput angka maka hasilnya akan tampil dari perkalian dari value yang diinput dikali 4

5. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang huruf lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Aplikasi sudah bisa menghandle inputan huruf. Jika user menginput huruf maka value yang akan ditampilkan adalah "invalid"


Percobaan 4
6. Jalankan aplikasi dengan shortcut ctrl+f5, masukkan sembarang angka dan tulisan lalu klik tombol Hitung. Apa yang terjadi pada aplikasi?
Jawab : Jika user menginput angka pada box usd maka aplikasi akan mengkonversinya ke dalam bentuk rupiah ( value x 15000 ) dan hasil akan tampil didalam box rupiah. Jika user menginput huruf maka box rupiah akan menampilkan "invalid"


2. Mengapa perlu membuat class CurrencyController.cs pada percobaan 4 ?
Jawab : Controlller disimpan didalam file yang berbeda agar codingan didalam main window lebih pendek dan programmer lebih mudah mengamati code di main window dan memfix bug jikalau ada


3. Jelaskan kegunaan method isAllowed pada percobaan 4!
Jawab : untuk mempresentasikan regex


4. Jelaskan secara singkat mengenai Regex pada percobaan 4!
Jawab : Dalam aplikasi ini Regex dibungkus dalam method isAllowed. Ekspresi [^ 0-9] digunakan untuk menemukan karakter apa pun yang bukan digit. Digit di dalam tanda kurung dapat berupa angka atau rentang angka dari 0 hingga 9.


5.  
