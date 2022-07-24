# 3.0-GC 

Перед скачиванием нужно установить эти 3 программы<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Установка сервера

1: Перейдите в https://github.com/lassedds/3.0-GC/releases/tag/Release и скачайте последний релиз GC 3.0

2: Скачайте ресурсы отсюда: https://github.com/lassedds/3.0-Resources

3: Разместите ресурсы вместе с 3.0-GC // Не забудьте изменить название папки на "resources", чтобы всё работало.

4: Правой кнопкой мыши нажмите по start_config.cmd и нажмите **Изменить**. Дальше вам нужно найти "*bin*" папку, где установлена Java. Обычно он хранится в папке **`C:\Program Files\Java\`**, там вы открываете папку под названием "*jdk-17.x.x.x*". Откройте папку "*bin*" и скопируйте путь к этому файлу. Это должно выглядеть так: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. Затем поместите это в файл *start_config.cmd* как переменную "*JAVA_PATH=*".

5: Готово. Теперь вы можете просто использовать файл *start.bat*, чтобы открыть сервер.

6: Теперь вам нужно зайти в папку с Genshin 3.0 и положить <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">этот</a> файл в следующие папки:<br>
	1. "*ПАПКАСГЕНШИНОМ/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*ПАПКАСГЕНШИНОМ/GenshinImpact_Data/Native/Data/Metadata*"

## Гайд по настройке Fiddler.

1: Скачайте Fiddler classic <a href=https://www.telerik.com/download/fiddler>здесь</a>.

2: Открыв Fiddler Classic, перейдите в **Tools/Инструменты** в верхней части Fiddler'а и нажмите **Options/Параметры**.

3: В меню **Options/Параметры** вы увидите много подменю. Перейдите в подменю **HTTPS**. Когда вы нажали на **HTTPS**, поставьте галочку возле "*Decrypt HTTPS traffic/Расшрифровывать HTTPS трафик*".

4: После 3-го шага вы не закрываете меню опций, а переходите в подменю **Connections/Подключения**. В подменю **Connections/Подключения**, вы увидите текст "*Fiddler Classiclistens onport*". по умолчанию порт будет '8888'. Если вы захотите **изменить** на что нибудь другое, Я использую 8080.

5: Теперь вы можете нажать кнопку **OK** в параметрах и найти кнопку **FiddlerScript**. После того, как вы нажмёте на это, вы должны получить скрипт <a href=https://github.lunatic.moe/fiddlerscript>отсюда</a>. Скопируйте скрипт и вернитесь в Fiddler. Замените скрипт только что существующим, после чего нажмите кнопку **Save Script/Сохранить скрипт**.

6: Теперь вы можете запускать игру, но вы ещё не закончили. После того, как вы попытаетесь войти в систему, вы получите несколько всплывающих меню в Fiddler, просто подтвердите их.

7: Успех! Теперь у вас должен быть настроен Fiddler. Если у вас появились вопросы, присоединяйтесь в <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
