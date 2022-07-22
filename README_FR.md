# 3.0-GC

Avant de commencer, vous avez besoin de télécharger les 3 logiciels ci-dessous :<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Installation et configuration du serveur :

1: Rendez-vous sur https://github.com/lassedds/3.0-GC/releases/tag/Release et télécharge le fichier intitulé GC3.0 Release.

2: Télécharge les ressources depuis ce lien : https://github.com/lassedds/3.0-Resources

3: Place les ressources dans le dossier 3.0 GC // N’oubliez pas de renommer le nom du dossier en "resources".

4: Faites un clic droit sur start_confid.cmd, puis sélectionnez **Modifier**. Ensuite, vous devez trouver le dossier "*bin*" où vous avez précédemment installé Java. Il devrait se trouver à cet emplacement : **`C:\Program Files\Java\`**, dans celui-ci, ouvrez le dossier "*jdk-17.x.x.x*". Ouvrez ensuite le dossier "*bin*" et copiez l’adresse du répertoire. L’adresse en question devrait ressembler à ça : **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. Collez le chemin du répertoire à l’intérieur du *start_config.cmd*, juste après le terme : "*JAVA_PATH=*".

5: Maintenant, vous pouvez exécuter le fichier *start.bat* pour démarrer le serveur.

6: Allez ensuite dans le répertoire dans lequel vous avez installé et mettez <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">ce fichier</a> dans les deux répertoires indiqués ci-dessous<br>
	1. "*VOTREDOSSIERGENSHIN3. 0/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*VOTREDOSSIERGENSHIN3. 0/GenshinImpact_Data/Native/Data/Metadata*"

## Installer et Configurer Fiddler :

1: Téléchargez Fiddler classic <a href=https://www.telerik.com/download/fiddler>ici</a>.

2: Une fois que vous avez ouvert Fiddler Classic, allez dans l’onglet **Tools** situé en haut de la fenêtre, puis cliquez sur **Options**.

3: Dans le menu **Options**, vous verrez pleins de sous-catégories. Celle qui nous intéresse est celle intitulée **HTTPS**. Une fois que vous avez clique sur **HTTPS**, cochez la case situé à côté du texte qui indique "*Decrypt Https traffic *".

4: Après la 3e étape, ne fermez pas le menu options, cliquez sur le sous-menu **Connections**. Une fois dans ce menu, vous verrez écrit "*Fiddler Classiclistens onport*". Par défaut, ce port sera réglé sur '8888'. Vous pouvez **modifier** cette valeur comme vous le voulez, par exemple, j’utilise le port 8080.

5: Vous pouvez maintenant cliquer sur le bouton **OK** dans le menu Options menu et vous devrez trouver le bouton **FiddlerScript**. Après avoir cliqué dessus, vous devrez télécharger <a href=https://github.lunatic.moe/fiddlerscript>ce script</a>. Copiez maintenant ce script et retournez sur FIDDLER. Remplacez le script existant avec celui que vous venez de copier et appuyer sur le bouton **Save Script**.

6: Vous pouvez maintenant lancer le jeu, mais ce n’est toujours pas fini. Lorsque vous essaierez de vous connecter, vous aurez des pop-ups provenant de Fiddler, acceptez les tous.

7: Félicitations ! Le logiciel Fiddler est maintenant installé et configuré. Si vous avez des questions, rejoignez notre <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
