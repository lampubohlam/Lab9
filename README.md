# Lab9


   Nama : Abdul Aziz
   
   
   NIM : 312210022 
# penanganan pengecualian
~ Exception (eksepsi) merupakan suatu kesalahan (error) yang terjadi saat proses eksekusi program sedang berjalan


~ Kesalahan ini akan menyebabkan program berakhir dengan tidak normal.

# penanganan
~ menangani file penting untuk menyelesaikan masalah dalam pemrograman apapun

berikut adalah coontoh ZerriDevissionError
![Screenshot (211)](https://user-images.githubusercontent.com/116137169/208714990-ba8a26e9-2f85-48f3-b613-b7152f9c4c77.png)

 >ZeroDivisionError merupakan salah satu jenis exception.
 
>pada saat exception terjadi python akan menampilkan traceback, detail error terjadi, dan program akan langsung dihentikan. Tentunya kita tidak ingin program kita

>berhenti dikarenakan ada error yang terjadi, kita bisa mengatasi ini dengan menggunakan try except

>pada python exception bisa di atasi dengan try except statement.

>dimana kode yang berpotensi menimbulkan exception/error kita masukkan ke dalam blok try, dan pada blok except dimasukkan kode yang akan dieksekusi saat terjadi error
  
  berikut contoh penggunaannya
  ![Screenshot (212)](https://user-images.githubusercontent.com/116137169/208718790-dbe08102-39bc-4373-8d38-e062bb17e1d0.png)
  
^ bila anda memasukkan nilai b atau penyebutnya 0, hal ini  tidak akan menimbulkan error dikarenakan kita sudah mengantisipasinya dengan menggunakan try except


adapun jika memasukan angka maka yang terjadi adalah valueError
![Screenshot (213)](https://user-images.githubusercontent.com/116137169/208720670-c37bc469-ee25-41ac-88f2-cfafe92e72bf.png)
Dan cara mengatasinya adalah dengan   exceptValueError,seperti berikut
![Screenshot (214)](https://user-images.githubusercontent.com/116137169/208721933-e96e16d0-0b2b-447a-ac9f-9b1501b46e63.png)



>Berikut adalah fungsi fungsi yang mengubah suhu dari derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat Kelvin dingin, fungsi penyimpanan jika 
melihat suhu negatif.

>Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:
![Screenshot (215)](https://user-images.githubusercontent.com/116137169/208725778-f7ce43f1-db61-45d5-9767-96d94e6fe172.png)
# langkah pengecualian
Jika Anda memiliki beberapa kode mencurigakan yang mungkin menarik perhatian, Anda dapat mempertahankan program Anda meletakkan kode yang mencurigakan di *coba: blok. Setelah coba: blok, sertakan proxy sertakan * kecuali: pernyataan, diikuti oleh blok kode yang menangani masalah seanggun mungkin.

# contoh
>Contoh-contoh ini membuka file, menulis konten file, dan keluar dengan aman karena tidak ada masalah
Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:

![contoh (2)](https://user-images.githubusercontent.com/116137169/208729161-477c94bc-96ed-4f1d-b0f2-03d9afb000f4.png)
![contoh (3)](https://user-images.githubusercontent.com/116137169/208729471-a1093039-cab1-4b25-8d6e-97d082953c68.png)



