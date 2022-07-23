# 3.0-GC

Prima di iniziare scarica i 2 file qui sotto<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Setup del server

1: Vai su https://github.com/lassedds/3.0-GC/releases/tag/Release e scarica la versione 3.0 di GC.

2: Scarica le risorse da qui: https://github.com/lassedds/3.0-Resources

3: Metti la cartella delle risorse scaricate sotto la cartella di GC 3.0 // ricorda di rinominare con il nome "resources" la cartella che stai mettendo sotto la cartella di GC.

4: Click destro su start_config.cmd e clicca **Modifica**. Poi, trova la cartella "*bin*" della tua versione di java installata. La cartella di java dovrebbe essere nel percorso **`C:\Programmi\Java\`**, apri la cartella "*jdk-17.x.x.x*". Apri anche la cartella "*bin*" e da qui copia il percorso. Dovrebbe somigliare a questo: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Modifica *start_config.cmd* mettendo il percorso precedente nella variabile "*JAVA_PATH=*".

5: Fatto, ora puoi avviare *start.bat* per aprire il server.

6: Adesso vai nella cartella di Genshin 3.0 e metti <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">questo</a> file in entrambi i percorsi:<br>
	1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Guida per Fiddler

1: Scarica Fiddler classic <a href=https://www.telerik.com/download/fiddler>qui</a>.

2: Dopo aver aperto Fiddler Classic clicca su **Tools** in alto al programma e clicca **Options**.

3: Nel menu **Options** vedrai molti sottomenu. Clicca sul sottomenu **HTTPS**. Una volta cliccato **HTTPS**, seleziona il riquadro a sinistra della scritta "*Decrypt HTTPS traffic*".

4: Dopo il quarto step, non chiudere il menu delle opzioni e vai sul sottomenu **Connections**. Quando sei nel sottomenu **Connections** vedrai un testo con scritto "*Fiddler Classiclistens onport*". Di default il port sara' '8888'. Dovrai **cambiarlo** a un qualsiasi altro port, io uso 8080.

5: Adesso puoi cliccare **OK** del menu delle opzioni. Cerca dopo aver chiuso le opzioni il bottone **FiddlerScript**. Una volta cliccatoci scarica <a href=https://github.lunatic.moe/fiddlerscript>questo</a> script. Copia il testo dello script scaricato, cancella quello vecchio su fiddler e incolla quello nuovo. Alla fine premi **Save Script** per salvare il cambiamento.

6: Adesso puoi lanciare il gioco ma ancora non hai finito. Quando provi a fare il login troverai dei popup di fiddler, confermali tutti.

7: Finito! Adesso Fiddler dovrebbe essere configurato. Se hai delle domande vieni nel nostro <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
