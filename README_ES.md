# 3.0-GC

Vas a necesitar desacargar estas 3 cosas antes de empezar<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Para iniciar el Servidor

1: Ve a https://github.com/lassedds/3.0-GC/releases/tag/Release y descarga GC3.0 Release.

2: Descarga los recursos de aqui: https://github.com/lassedds/3.0-Resources

3: Coloca los recursos dentro de la carpeta de GC 3.0 // Recuerda cambiarle el nombre a "resources"

4: Click derecho al archivo start_config.cdm y dale click a **Editar**. Siguiente, necesitas encontrar la carpeta "*bin*" en tu version de java instalada. Deberia estar en **`C:\Archivos de Programa\Java\**, dentro abre una carpeta llamada "*jdk-17.x.x.x*". Abre la carpeta "*bin*" y copia tu direccion del archivo. Deberia parecerse a algo como esto: **`C:\Archivos de Programas\Java\jdk-17.x.x.x\bin\`**.  Despues pon eso dentro del archivo *start_config.cmd* como la variable "*JAVA_PATH=*".

5: Hecho, ahora ya puedes iniciar el archivo *start.bat* para abrir el server.

6: Ahora hay que ir a la carpeta 3.0 Genshin y poner este archivo <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">this</a> en estas dos localizaciones:<br>
	1. "*TUCARPETADEGENSHIN/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*TUCAARPETADEGENSHIN/GenshinImpact_Data/Native/Data/Metadata*"

## Guia de Fiddler

1: Descarga Fiddler classic en <a href=https://www.telerik.com/download/fiddler>here</a>.

2: Una vez que habras Fiddler Classic, ve a **Tools/Herramientas** opcion que esta en la parte superior de fiddler y haz click en **Options/Opciones**.

3: En el menu **Options/Opciones** vas a ver un monton de sub-menus. El unico que nos interesa ir actualmente es a **HTTPS**. Una vez que des click en **HTTPS**, haz click en el pequeño recuadro que dice "*Decrypt HTTPS traffic*".

4: Despues del 4. paso, no necesitas cerrar el menu opciones si no ir al submenu **Connections/Conexiones** . Una vez que estas en el submenu **Connections/Conexiones**, vas a ver un texto diciendo "*Fiddler Classiclistens onport*". Por defecto, el puerto sera '8888'. Vas a necesitar **change/cambiarlo** antes que nada, Yo uso 8080.

5: Ahora puedes dar click en **OK** en el menu Opciones y vas a necesitar encontrar el boton **FiddlerScript**. Una evz que des click en eso, Vas a necesitar este Script <a href=https://github.lunatic.moe/fiddlerscript>here</a>. Ahora copia el script y vuelve a Fiddler. Reemplaza el script existente con el que acabas de copiar y presiona el boton **Save Script**.

6: Ahora ya puedes iniciar el juego pero todavia no hemos terminado. Una vez que intententes logearte, vas a recibir varias alertas en  Fiddler y simplemente dale a confirmar en todas ellas.
7: Felicidades! Deberias tener el FIddler Classic activo. Buen Trabajo! Si tienes alguna otra pregunta, unete a nuestro discord <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
