# ProjectSpringboot_Kelompok4
Berikut merupakan dokumentasi project dengan menggunakan Framework java Spring-boot

#### Disusun oleh :
- Nama           : - Fannysia Arum Sari (09011282429057)
                   - Fira Rahmadani (09011282429052)
                   - Zulia Angraini (09011282429079)
                   - Muhammad Araffi Nabil (09011282429045)
                   - M Ojie Gusti Prakarsa (09011282429062)
                   - M Fajri Rahmadani (09011282429071)
- Kelas          : SK1B
- Dosen Pengampu : Abdurahman S.Kom., M.Han.

# Langkah-Langkah Membuat Project Spring-Boot
1.	Cek apakah lingkungan java sudah terinstall dengan periksa lewat cmd/command prompt
   `Perintah : Java -version`
2.	Jika belum kalian install jdk di sini https://www.oracle.com/id/java/technologies/downloads/  disarankan versi terbaru/ senyaman kalian
3.	Install java maven di sini https://maven.apache.org/download.cgi 

![image](https://github.com/user-attachments/assets/98689302-7278-49d7-9cdf-9a8b01de043b)

4.	Folder yg didownload berupa .zip, extract lalu masukkan folder apache-maven-3.9.9-bin ke folder C: Program Files kalian
5.	Cek Kembali dengan perintah `mvn -version` jika masih seperti ini

![image](https://github.com/user-attachments/assets/3af336d8-a241-47fa-b610-dccb147b5a7c)

6.	Setting env maven dengan buka folder tersebut lalu buka bin salin alamatnya. Contoh alamat ( C:\Program Files\apache-maven-3.9.9-bin\apache-maven-3.9.9\bin )
7.	Ketik env di pencarian sebelah logo windows open terus pilih environment variables

![image](https://github.com/user-attachments/assets/19185dc8-4637-4520-bef6-0aa983ba9f3e)

8.	Klik bagian path 2x, new trs paste. Jalanin kembali perintah mvn -version

![image](https://github.com/user-attachments/assets/2f76d2c1-8cf1-43a2-bbc8-6b9988b47e64)


9.	Buka Visual Studio Code install extension : Extension Pack for Java yg dari Microsoft
10.	Install extension : Spring Boot Extension Pack tunggu sampe tulisan disabled
11.	Buka command palette dgn shortcut Ctrl + Shift + P ketik spring kemudian pilih yang Spring initializer : create a maven project
12.	Pilih kembali versi yang akan kalian gunakan selanjutnya pilih bahasa Java, buat nama group.id, kemudian nama projectnya apa, pilih packaging Jar, lalu versi java yang sesuai dengan punya kalian jika tidak ada yang sesuai nanti bisa kalian ubah di file pom.xml.
13.	Pilih dependencies disini kita cukup menggunakan Spring Boot DevTools serta Spring web
14.	Langkah terkakhir hanya kalian perlu menempatkan project tersebut di dalam folder apapun yang kalian mau lalu klik generate into this folder.
    

