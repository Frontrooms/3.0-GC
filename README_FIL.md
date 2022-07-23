# 3.0-GC

Kailangan mo muna i-download ang tatlong files na ito<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Server setup

1: Pumunta ka sa: https://github.com/lassedds/3.0-GC/releases/tag/Release and download the GC3.0 Release.

2: I-download ang resources dito: https://github.com/lassedds/3.0-Resources

3: Ilagay ang resources sa 3.0 GC Folder // Tandaan na baguhin/palitan ang pangalan ng folder at gawin itong "resources"

4: I-right click ang start_config.cmd file at pindutin ang  **Edit**. Sunod ay kailangan mong hanapin ang "*bin*" folder ng Java Version sa iyong PC. Nasa **`C:\Program Files\Java\`** kung tama ang iyong installation, buksan mo ang folder na may pangalang "*jdk-17.x.x.x*". Buksan mo ang "*bin*" folder at kopyahin ang file path o address. Dapat mag-mukha ito katulad nito: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Then put that into your *start_config.cmd* file as the variable "*JAVA_PATH=*".

5: Pwede mo na gamitin ang *start.bat* file para buksan ang server.

6: Pumunta ka sa 3.0 Genshin folder mo at ilagay ang: <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">this</a> file sa dalawang folder na ito:<br>
	1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler Guide

1: I-download mo ang Fiddler sa: <a href=https://www.telerik.com/download/fiddler>here</a>.

2: Pagkatapos mo buksan, Pumunta ka sa **Tools** sa taas ng Fiddler at pindutin ang **Options**.

3: Sa loob ng **Options**, marami kang makikitang opsyon pero ang pupindutin natin ay ang **HTTPS**. Pag nasa **HTTPS** ka na, Pindutin mo ang maliit ng box na may "*Decrypt HTTPS traffic*".

4: Pagkatapos ng 4th step, wag mo i-close ang options menu at pumunta sa **Connections** seksyon. Pag nasa **Connections** ka na, may makikita kang text na nakalagay "*Fiddler Classiclistens onport*". Ang regular na port ay '8888'. Kailangan mo **palitan** yan ng kahit ano, ang gamit ko ay 8080.

5: Pwede mo na pindutin ang **OK** sa options at at hanapin ang **FiddlerScript**. Pagkatapos mo ito pindutin ay kailangan mo kunin ang script na ito: <a href=https://github.lunatic.moe/fiddlerscript>here</a>. I-copy ang script at bumalik sa Fiddler. Palitan ang script na nandoon gamit ang script na cinopy mo at pagkatapos ay pindutin ang **Save Script**.

6: Ngayon, pwede mo na buksan ang game pero hindi ka parin tapos. Pag-sinubukan mo mag login, makakakuha ka ng mga popup sa Fiddler upang i-confirm to lahat.

7: Tapos na! Okay na ang Fiddler mo. Good job! Kung may katanungan pa, sumali ka sa: <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
