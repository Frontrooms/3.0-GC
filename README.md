# 3.0-GC

Başlamadan önce bu ikisini indirmeniz gerekecek<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Sunucu Kurulumu

1: https://github.com/lassedds/3.0-GC/releases/tag/Release adresine gidin ve GC3.0 Sürümünü indirin.

2: Kaynakları buradan indirin: https://github.com/lassedds/3.0-Resources

3: Kaynakları 3.0 GC Klasörüne koyun // Adı "resources" olarak değiştirmeyi unutmayın, aynen böyle.

4: start_config.cmd dosyasına sağ tıklayın ve **Düzenle** seçeneğine tıklayın. Ardından, yüklü java sürümünüzün "*bin*" klasörünü bulmanız gerekir. Bu klasör **`C:\Program Files\Java\`** adresinde olmalı, orada "*jdk-17.x.x.x*" adlı klasörü açmalısınız. "*bin*" klasörünü açın ve bu dosya yolunu kopyalayın. Şöyle bir şey görünmelidir: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Ardından bunu *start_config.cmd* dosyanıza "*JAVA_PATH=*" değişkeni olarak yerleştirin.

5: Tamamlandı. Artık sunucuyu başlatmak için *start.bat* kullanabilirsiniz

6: Şimdi 3.0 Genshin Klasörünüze gidin ve <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">bu dosyayı </a> aşağıdaki konumlara koyun:<br>
	1. "*SIZINGENSHINKLASÖRÜNÜZ/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*SIZINGENSHINKLASÖRÜNÜZ/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler Kılavuzu

1: Fiddler classic <a href=https://www.telerik.com/download/fiddler>buradan</a> indirin.

2: Fiddler Classic'i açtıktan sonra, Fiddler'ın üst kısmındaki **Araçlar**'a gidin ve **Seçenekler**'e tıklayın.

3: **Seçenekler** menüsünde birçok alt menü göreceksiniz. Şu anda **HTTPS** seçeneğine gitmek istiyoruz. **HTTPS** seçeneğine tıkladıktan sonra, "*HTTPS trafiğinin şifresini çöz*" yazan metnin yanındaki küçük kutuya tıklayın.

4: 3. adımdan sonra seçenekler menüsünü kapatmıyorsunuz, **Bağlantılar** alt menüsüne gidiyorsunuz. **Bağlantılar** alt menüsüne girdiğinizde, "*Fiddler Classiclistens onport*" yazan bir metin göreceksiniz. Varsayılan olarak, bağlantı noktası '8888' olacaktır. Bunu başka bir şeyle **değiştirmek** isteyeceksiniz, ben 8080 kullanıyorum.

Artık Seçenekler menüsünde **Tamam**'a tıklayabilirsiniz ve **FiddlerScript** düğmesini bulmak isteyeceksiniz. Bunu tıkladıktan sonra, bu komut dosyasını <a href=https://github.lunatic.moe/fiddlerscript>buradan</a> almak isteyeceksiniz. Şimdi betiği kopyalayın ve Fiddler'a geri dönün. Mevcut komut dosyasını az önce kopyaladığınızla değiştirin ve ardından **Komut Dosyasını Kaydet** düğmesine basın.

6: Artık oyuna başlayabilirsiniz, ancak henüz işiniz bitmedi. Giriş yapmayı denediğinizde, Fiddler'da bazı açılır menüler alacaksınız ve hepsini onaylamanız gerekecek.

7: Başarı! Şimdi Fiddler'ı kurmuş olmalısınız. Aferin! Herhangi bir sorunuz varsa <a href=https://discord.gg/AYtB7Q2er8>Discord</a>'umuza katılın.
