<a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_zh.md">CN<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_pl.md">PL<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_VN.md">VN<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_JP.md">JP<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_IT.md">IT<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_FR.md">FR<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README.tr.md">TR<a> |  <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_PH.md">PH<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_PT.md">PT<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_ID.md">ID<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_KO.md">KO<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_ES.md">ES<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_RU.md">RU<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_RO.md">RO<a> | <a href="https://github.com/Frontrooms/3.0-GC/blob/main/README_GE.md">GE<a> |


# 3.0-GC 

You will need to download these 2 before you start<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Server setup

1: Go to https://github.com/lassedds/3.0-GC/releases/tag/Release and download the GC3.0 Release.

2: Download the resources from here: https://github.com/lassedds/3.0-Resources

3: Place the resources within the 3.0 GC Folder // Remember to change the name to "resources" just like that.

4: Right click the start_config.cmd file and click **Edit**. Next, you have to find the "*bin*" folder of your installed java version. It should be at **`C:\Program Files\Java\`**, in there you open the folder called "*jdk-17.x.x.x*". From there, open the "*bin*" folder and copy that file path. It should look like something like this: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Then put that into your *start_config.cmd* file as the variable "*JAVA_PATH=*".

5: Done you can now just use the *start.bat* file to open the server.

6: You will now want to go into your 3.0 Genshin folder and put <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">this</a> file in both of these locations:<br>
	1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler Guide

1: Download Fiddler classic <a href=https://www.telerik.com/download/fiddler>here</a>.

2: Once you have opened Fiddler Classic, go to the **Tools** option at the top of Fiddler and click **Options**.

3: In the **Options** menu you will see a lot of sub menus. The one we want to go to currently is **HTTPS**. Once you have clicked on **HTTPS**, click on the little box next to the text saying "*Decrypt HTTPS traffic*".

4: After the 3rd step, you do not close the options menu but go to the **Connections** submenu. Once you are in the **Connections** submenu, you will see a text saying "*Fiddler Classiclistens onport*". By default, the port will be '8888'. You will want to **change** that to anything else, I use 8080.

5: You can now click **OK** in the Options menu and will want to find the **FiddlerScript** button. Once you have clicked on that, you will want to get this script <a href=https://github.lunatic.moe/fiddlerscript>here</a>. Now copy the script and go back into Fiddler. Replace the existing script with the one you just copied and then press the **Save Script** button.

6: Now you can launch the game but you are still not done. Once you try and login, you will get some popup menus in Fiddler and just confirm to all of them.

7: Success! You should now have Fiddler set up. Good job! If you have any questions, join our <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
