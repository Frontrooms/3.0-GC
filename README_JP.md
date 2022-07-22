# 3.0-GC

事前に以下の2つのファイルをダウンロードしてください。<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## サーバーの設定

1: https://github.com/lassedds/3.0-GC/releases/tag/Releaseにアクセスし、GC3.0リリースをダウンロードする。

2: リソースのダウンロードはこちら - https://github.com/lassedds/3.0-Resources

3: リソースをGC 3.0フォルダ内する。 // フォルダ名を「Resources」に変更するのを忘れないように。

4: 「start_config.cmd」と書かれたファイルを右クリックし、**Edit**をクリックする。　次に、インストールしたバージョンのJavaの「*bin*」フォルダを見つけます。　**`C:\Program Files\Java\`**にあるファイルが見つかるはずです。　このフォルダで、「*jdk-17.x.x.x*」という名前のフォルダを開きます。　「*bin*」フォルダを開き、ファイルのパスをコピーする。　**`C:\Program Files\Java\jdk-17.x.x.x\bin\`**として表示されるはずです。ここで、そのディレクトリを 「*start_config.cmd*」ファイルに 「*JAVA_PATH=*」variableとして貼り付けます。

5: これで完成だ！これで、「*start.bat*」ファイルを使ってサーバーを起動できるようになりました。

6: 3.0 Genshin (原神)のフォルダを開き、 <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">これ</a>を以下のロケーションにペースト付けます。<br>
	1. 「*あなたの原神フォルダ/GenshinImpact_Data/Managed/Metadata*」<br>
	2. 「*あなたの原神フォルダ/GenshinImpact_Data/Native/Data/Metadata*」

## Fiddlerガイド

1: Fiddler Classicのダウンロードは<a href=https://www.telerik.com/download/fiddler>こちら</a>。

2: Fiddlerを開き、上部にある「**Tools/ツール**」というメニューを見つける。　「**Options/オプション**」をクリックする。

3: 「**Options/オプション**」メニューには、多くのサブメニューがあります。　「**HTTPS**」と書かれたサブメニューをクリックする。　次に、「*Decrypt HTTPS traffic/HTTPS通信量の復号*」と書かれたテキストの横にある小さな四角いをクリックする。

4: 4番目のステップの後、オプションメニューは閉じない。　「**Connections/接続**」のサブメニューを見つける。　サブメニューに、「*Fiddler Classic listens on port/Fiddler Classicはポートで聴く*」と書かれたテキストが表示されます。　ポートはデフォルトで「8888」になります。　「8888」を他の番号に変更する。　(個人的には「8080」を使用しています。)

5: オプションメニューの**OK**をクリックし、「**FiddlerScript/Fiddlerスクリプト**」ボタンを見つけます。　それをクリックしたら、 <a href=https://github.lunatic.moe/fiddlerscript>ここか</a>らスクリプトを入手します。　スクリプトをコピーして、Fiddlerを再度開きます。　すでに存在するスクリプトを、コピーしたスクリプトに置き換えます。　「**Save Script/スクリプトセーブする**」ボタンを忘れずにクリックします！

6: これでゲームを起動することができます。　それでも、まだ終わってはいません。　ログインしようとすると、Fiddlerに多くのメニューが表示されます。　すべてのメニューで「OK」をクリックします。

7: 成功！٩( 'ω' )و Fiddlerが設定されたはずです。　よくできました88！　質問がある場合は、 <a href=https://discord.gg/AYtB7Q2er8>Discordサーバー</a>に参加してください。
