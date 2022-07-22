# Grasscutter 3.0 (GC3.0)

Zanim rozpoczniesz musisz pobrać te 2 rzeczy<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Konfiguracja serwera

1: Wejdź na https://github.com/lassedds/3.0-GC/releases/tag/Release i pobierz najnowsze wydanie GC3.0.

2: Pobierz zasoby stąd: https://github.com/lassedds/3.0-Resources

3: Wypakuj zasoby do foldery z GC3.0 // Pamiętaj o zmianie nazwy folderu na "resources".

4: Naciśnij prawym na start_config.cmd, wybierz **Edytuj**. Następnie znajdź folder "*bin*" swojej zainstalowanej javy. Powinna znajdować się w **`C:\Program Files\Java\`**, znajdź i otwórz folder który nazywa się "*jdk-17.x.x.x*". Teraz skopiuj ścieżkę folderu "*bin*". Powinna wyglądać podobnie jak ta: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Umieść ją teraz w pliku *start_config.cmd* w jako wartość "*JAVA_PATH=*".

5: Gotowe, teraz możesz użyc pliku *start.bat* aby uruchomić serwer.

6: Teraz wejdź do swojego folderu z Genshinem 3.0 i umieść <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">ten plik</a> w tych dwóch lokacjach:<br>
	1. "*FOLDERzGENSHINEM/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*FOLDERzGENSHINEM/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler

1: Pobierz Fiddler classic <a href=https://www.telerik.com/download/fiddler>here</a>.

2: Kiedy otworzysz Fiddler Classic, przejdź do zakładki **Tools** w górnej części okna i naciśnij **Options**.

3: W menu **Options** znajdziesz kilka pod-menu. Wybierz **HTTPS**, a następnie zaznacz opcję "*Decrypt HTTPS traffic*".

4: Po 3 kroku, nie zamykaj menu opcji ale wybierz tym razem **Connections**. W pod-menu **Connections** znajdziesz pole tekstowe opisane "*Fiddler Classiclistens onport*". Domyślnie port będzie ustawiony na '8888'. Musisz to **zmienić** na dowolny inny, rekomenduje użycie 8080.

5: Możesz teraz naciśnąć **OK** w menu opcji i teraz przejść do **FiddlerScript** (prawy górny róg ekranu). Jak już wybierzesz tą opcję, pobierz skrypt <a href=https://github.lunatic.moe/fiddlerscript>z tego linku</a>. Teraz skopiuj ten skrypt spowrotem do Fiddlera. Podmień oryginalny skrypt na ten który skopiowałeś i naciśnij przycisk **Save Script**.

6: Uruchom teraz grę, ale to jeszcze nie koniec. Kiedy spróbujesz się zalogować dostaniesz kilka powiadomień w Fillderze, zaakceptuj je wszystkie.

7: Sukces! Twój Fiddler powinien być gotowy do gry. Dobra robota! Jeśli masz pytania, dołącz na nasz <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
