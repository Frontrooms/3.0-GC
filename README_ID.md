# 3.0-GC

Kamu perlu unduh 2 file berikut sebelum memulai<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Setup Server

1: Pergi ke https://github.com/lassedds/3.0-GC/releases/tag/Release dan unduh GC3.0 Release.

2: Unduh resources dari sini: https://github.com/lassedds/3.0-Resources

3: Letakkan resources di dalam folder GC 3.0 yang sudah diunduh tadi // Ingatlah untuk mengganti namanya menjadi "resources".

4: Klik kanan file start_config.cmd dan klik **Edit**. Selanjutnya, kamu harus mencari folder "*bin*" versi java yang sudah kamu install tadi. Seharusnya itu ada di **`C:\Program Files\Java\`**, di dalam sana kamu buka folder yang bernama "*jdk-17.x.x.x*". Buka folder "*bin*" lalu salin file path nya. Seharusnya akan terihat seperti ini: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. Kemudian letakkan itu ke dalam file *start_config.cmd* tadi sebagai variabel "*JAVA_PATH=*".

5: Selesai, kamu sekarang bisa menggunakan file *start.bat* saja untuk membuka server.

6: Kamu sekarang perlu pergi ke folder Genshin 3.0 dan letakkan file <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">ini</a> ke dalam kedua lokasi berikut:<br>
	1. "*FOLDERGENSHINMU/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*FOLDERGENSHINMU/GenshinImpact_Data/Native/Data/Metadata*"

## Panduan Fiddler

1: Unduh Fiddler classic <a href=https://www.telerik.com/download/fiddler>di sini</a>.

2: Setelah kamu membuka Fiddler Classic, pergi ke opsi **Tools** yang terletak di atas Fiddler dan klik **Options**.

3: Di dalam menu **Options** kamu akan melihat banyak submenu. Satu-satunya tempat yang kita ingin tuju adalah **HTTPS**. Setelah kamu mengklik **HTTPS**, klik pada kotak kecil di samping teks yang bertuliskan "*Decrypt HTTPS traffic*".

4: Setelah langkah ke-4, jangan tutup menu options tadi melainkan pergilah ke submenu **Connections**. Setelah berada di submenu **Connections**, kamu akan melihat teks yang tertulis "*Fiddler Classiclistens onport*". Secara default, port nya adalah '8888'. Kamu perlu **mengganti** port itu terserah mau apa saja, saya menggunakan 8080.

5: Kamu bisa klik **OK** sekarang di dalam menu Options dan kemudian kamu perlu mencari tombol **FiddlerScript**. Setelah kamu mengklik itu, Kamu butuh script ini <a href=https://github.lunatic.moe/fiddlerscript>di sini</a>. Sekarang salin script nya dan kembali ke Fiddler. Ganti script yang sudah ada sebelumnya dengan script yang baru saja disalin kemudian klik tombol **Save Script**.

6: Sekarang kamu bisa membuka game nya tetapi masih ada sesuatu yang perlu dilakukan. Ketika kamu mencoba login, kamu akan mendapatkan beberapa menu popup di Fiddler. Cukup tekan confirm atau yes ke semuanya.

7: Sukses! Seharusnya Fiddler mu sudah berhasil diatur. Kerja bagus! Apabila kamu punya pertanyaan, silakan bergabung ke <a href=https://discord.gg/AYtB7Q2er8>Discord</a> kami.
