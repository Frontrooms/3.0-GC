```# 3.0-GC
დაგჭირდებათ გადმოიწეროთ ეს 2 სანამ დაიწყებთ.
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Server setup

1: გადადით შემდეგ ლინკზე: https://github.com/lassedds/3.0-GC/releases/tag/Release და გადმოიწერეთ GC3.0 Release.

2: გადმოიწერეთ რესურსები აქედან: https://github.com/lassedds/3.0-Resources

3: გადაიტანეთ რესურსები 3.0 GC Folder-შ // არ დაგავიწყდეთ რომ შეუცვალოთ სახელი, დააწერეთ "resources".

4: მარჯვენა ღილაკით დააჭირეთ start_config.cmd ფაილს და დააჭირეთ **Edit**-ს. შემდეგ უნდა იპოვოთ "*bin*" ფოლდერი თქვენს გადმოწერილ ჯავა ვერსიაში. ის უნდა მდებარეობდეს **`C:\Program Files\Java\`**, აქ გავხსნით ფოლდერს რომელსაც ქვია "*jdk-17.x.x.x*". გახსენით "*bin*" ფოლდერი და დააკოპირეთ ფაილის path. ის უნდა გამოიყურებოდეს დაახლოებით ასე: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. შემდეგ გადაიტანეთ *start.config.cmd* ფაილში როგორც "*JAVA_PATH=*".

5: ახლა შეგიძლიათ გამოიყენოთ *start.bat* ფაილი რომ გახსნათ სერვერი.

6: ახლე გადახვალთ თქვენს 3.0 Genshin ფოლდერში და ჩაწერთ <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">this</a> ფაილს ამ ორ ლოკაციაში:
	1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler Guide

1: გადმოიწერეთ Fiddler Classic <a href=https://www.telerik.com/download/fiddler>here</a>.

2: როდესაც გახსნით Fiddler Classic-ს, გადადით **Tools** სექციაში Fiddler-ის ზემოთა მხარეს და დააჭერთ **Options**

3: **Options** მენიუში დაინახავთ ბევრ სექციას. ამჟამად თქვენ უნდა გადახვიდეთ **HTTPS**-ში. როდესაც დააჭერთ **HTTPS**-ს, დააჭირეთ პატარა ყუთზე "*Decrypt HTTPS traffic*" - ის გვერდზე.

4: მეოთხე საფეხურის შემდეგ, არ გამორთოთ options მენიუ მაგრამ გადადით **Connections** სექციაში. როდესაც გადახვალთ ამ სექციაში, დაინახავთ ტექსტს "*Fiddler Classiclistens onport*". თქვენი პორტი იქნება "8888". პორტი უნდა შეცვალოთ რაიმე სხვაზე, მე ვიყენებ 8080-ს.

5: ახლა შეგიძლიათ დააჭიროთ **OK**-ს Options-ში და უნდა იპოვოთ **FiddlerScript** ღილაკი. როდესაც დააჭერთ ამ ღილაკს, გადმოიტანეთ ეს სკრიპტი აქ <a href=https://github.lunatic.moe/fiddlerscript>here</a>. ახლა დააკოპირეთ სკრიპტი და დაბრუნდით Fiddler-ში. გადაანაცვლეთ მყოფი სკრიპტი იმითი რომელიც ახლა დააკოპირეტ და დააჭირეთ **Save Script** ღილაკს.

6: ახლა შეგიძლიათ ჩართოთ თამაში მაგრამ ჯერ არ მორჩენილხართ. როდესაც ცდით Login-ს, ამოგიგდებთ მენიუს Fiddler-სი და ყველაზე დააჭირეთ confirm-ს

7. მორჩა! თქვენ ახლა Fiddler უნდა გქონდეთ დაყენებული. ყოჩაღ! თუ გაქვთ კიდევ კითხვები, შემოდით ჩვენს Discord Server-ზე https://discord.gg/AYtB7Q2er8