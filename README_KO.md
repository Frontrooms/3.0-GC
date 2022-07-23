# 3.0-GC

시작하기 전에, 다음 두 프로그램을 설치하여야 합니다.<br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## 서버 셋업

1: https://github.com/lassedds/3.0-GC/releases/tag/Release 로 접속하여 GC3.0 Release를 다운로드합니다.

2: 다음 레포지토리에서 resources를 다운로드합니다: https://github.com/lassedds/3.0-Resources

3: 3.0 GC 폴더에 resources를 이동시킵니다 // 위 레포지토리 폴더 이름을 "resources"로 바꾸는 걸 잊지 마세요.

4: start_config.cmd 파일을 우클릭하고 **편집**을 누릅니다. 다음으로, 설치된 Java의 "*bin*" 폴더를 찾아야 합니다. **`C:\Program Files\Java\`** 폴더로 들어가서, "*jdk-17.x.x.x*" 폴더를 찾으면 "*bin*" 폴더를 찾게 될 것입니다. 다음과 같이 생긴 파일 경로를 복사하세요: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. 그리고 다시 *start_config.cmd* 편집 화면으로 돌아가 변수 "*JAVA_PATH=*"에 복사한 파일 경로를 붙여넣습니다.

5: *start.bat* 파일을 실행하여 GC를 실행시킬 수 있습니다.

6: 3.0 원신이 설치되어 있는 경로로 가서 <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing">global-metadata.dat</a> 파일을 다음 두 경로에 덮어씌웁니다:<br>
	1. "*/GenshinImpact_Data/Managed/Metadata*"<br>
	2. "*/GenshinImpact_Data/Native/Data/Metadata*"

## Fiddler 가이드

1: <a href=https://www.telerik.com/download/fiddler>Fiddler classic</a>을 다운로드 및 설치를 합니다.

2: Fiddler를 실행하고, 상단에 **Tools**에서 **Options**로 들어갑니다.

3: **HTTPS** 메뉴로 들어가서, "*Decrypt HTTPS traffic*"에 체크합니다.

4: **Connections** 메뉴로 들어가서, '8888'로 되어있는 포트 번호를 변경해야 합니다. 이 가이드에선 8080을 쓰겠습니다.

5: **OK** 버튼을 눌러 나오고, **FiddlerScript** 탭을 찾아 선택하면 스크립트를 작성하는 칸이 나옵니다. <a href=https://github.lunatic.moe/fiddlerscript>스크립트</a>를 복사 붙여넣기 하고 **Save Script** 버튼을 누릅니다.

6: 이제 게임을 실행하면 됩니다. Fiddler에서 어떠한 창이 뜬다면 확인(confirm) 버튼을 누르면 됩니다.

7: 문제가 생기면 <a href=https://discord.gg/AYtB7Q2er8>Discord</a>로 문의하세요.
