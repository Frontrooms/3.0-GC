# 3.0-GC

Voce vai precisar fazer o download esses dois programas antes de começar<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Configuração do Servidor

1: Vá para https://github.com/lassedds/3.0-GC/releases/tag/Release e faça o download da GC3.0 Release.

2: Baixe os recursos do jogo aqui: https://github.com/lassedds/3.0-Resources

3: Coloque a pasta de recursos dentro da pasta 3.0 GC //  lembre de renomea-los para "resources" exatamente assim.

4: Clique com o botão direito em start_config.cmd file e escolha **Edit**. Agora, voce precisará encontrar a pasta "*bin*" onde sua versão do Java foi Instalada. Normalmente encontra-se em **`C:\Program Files\Java\`**, dentro voce encontrará uma pasta chamada"*jdk-17.x.x.x*". Dentro dela voce encontrará a pasta "*bin*" copie o caminho completo. Deverá ser algo como: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**.  Então coloque o caminho dentro do arquivo *start_config.cmd* na variavel "*JAVA_PATH=*".

5: Agora voce poderá usar o arquivo *start.bat* para iniciar o servidor.

6: Agora voce vai querer entrar na sua pasta onde esta o cliente do Genshin 3.0 e colocar o arquivo <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">baixar</a> nessas duas pastas:<br>
	1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Guia do Fiddler

1: Faça o download do Fiddler classic <a href=https://www.telerik.com/download/fiddler>aqui</a>.

2: Abra o Fiddler Cassic e entre na opção **Tools** dentro de Tools clique em **Options**.

3: Dentro do menu de **Options** voce verá varios sub-menus. O que voce precisa encontrar é o **HTTPS**. uma vez clicado em **HTTPS**, clique na pequena caixa de texto escrita "*Decrypt HTTPS traffic*".

4: Depois to 3º passo, não feche o menu de opções vá para o **Connections** sub-menu. uma dentro do **Connections** sub-menu, voce verá o texto "*Fiddler Classiclistens onport*". Por padrão a porta será '8888'. Voce vai precisar **mudar-lá ** para qualquer outra, Eu uso a 8080 por exemplo.

5: Agora voce pode clicar em **OK** após isso voce deve procurar o menu **FiddlerScript**. Uma vez que tenha clicado nele, voce precisará desse script <a href=https://github.lunatic.moe/fiddlerscript>aqui</a>. Copie o script para dentro do Fiddler. Subistitua o script existe pelo novo que acabou de copiar então clique no botão **Save Script**.

6: Agora voce será capaz de executar o jogo mas ainda não acabou. Quando tentar efetuar o login no jogo irá aparecer pequenas janelas do Fiddler, apenas clique confirm em todas elas.

7: Parabens! Agora voce tem o Fiddler configurado tambem. Bom Trabalho!, Divirta-se! Se tiver qualquer pergunta, junte-se ao nosso <a href=https://discord.gg/AYtB7Q2er8>Discord</a>
