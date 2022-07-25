// 3.0 KURULUM //

Başlamadan önce bu üç dosyayı indirmeniz lazım.
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

// SUNUCU KURULUMU //

1: https://github.com/lassedds/3.0-GC/releases/tag/Release gidin ve GC3.0 Sürümünü indirin

2: Kaynak dosyalarını burdan indirin : https://github.com/lassedds/3.0-Resources

3: GC3.0 Dosyasını herhangi bir yere çıkartın ardından kaynak dosyalarını da GC3.0 Dosyalarının içine atın

4: Ardından MongoDB'yi kurup açın sonra gelen ekrandan hiçbirşeye basmadan *Connect* butonuna basmanız yeterli.

5: start_config.cmd Dosyasına sağ tıklayın ve DÜZENLE'ye basın. Sonra, İndirdiğiniz java dosyasının içindeki "bin" dosyasını bulmanız lazım. C:\Program Files\Java\C:\Program Files\Java\ bu konumdan indirdiğiniz java versiyonunun dosyasını bulmanız lazım. Dosya adı *jdk-17.x.x.x* oluyor. Açtıktan sonra bin dosyasını bulun ve dosya yolunu kopyalayın. *C:\Program Files\Java\jdk-17.x.x.x\bin\* bunun gibi olması lazım. Sonra dosya konumunu *start_config.cmd* dosyasının içindeki *JAVA PATH=* Değerinin yanına girin. 

6: Herşey hazır! Yapman gereken sadece *Start.bat* dosyasını çalıştırmak.

7: Şimdi yapman gereken sunucuya girebilmek için güncel değiştirilmiş *METADATA* dosyasını indirmeniz gerek. Dosyayı discrod sunucusunda #Downloads veya #public-resources kısmından bulabilirsin. Ardından metadata dosyalarını burdaki metadata dosyalarıyla değiştirin.

      1: YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata
      2: YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata

// Fiddler Rehberi //

1: Fiddler Classic'i indirin https://www.telerik.com/download/fiddler

2: Kurup Fiddler classic'i açın ardından üst soldan *Tools* Kısmını açın ve ordan *options* kısmına girin

3: *Options* kısmını açınca karşınıza bissürü menü çıkacak ordan *HTTPS* Kısmına girin . HTTPS kısmında *Decrypt HTTPS traffic* Yazan yerin yanındaki minik butonu tikleyin.

4: Şimdi ise üst taraftan *Connections* kısmını açın. Ardından *Fiddler Classiclistens onport* görüceksiniz. Normalde o kısımdaki sayı *8888* olucaktır. Onu 8080 yapın.

5: şimdi *OK* Butonuna tıklayın sonra *FiddlerScript* yerine girin ardından çıkan menüde yazılar yazıyor olucak ordaki tüm yazıları silip *https://github.lunatic.moe/fiddlerscript* burdaki siteye girip ordaki yazıları kopyalayıp fiddlerscript yerine girin ardından *SaveScript* Butonuna tıklayın.

6: Herşey hazır! Şimdi oyunu açabilirsiniz.