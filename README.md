# side-c
c# 기초

# vscode 환경 설정
[.NET 문서](https://learn.microsoft.com/ko-kr/dotnet/)

ms에서 제공하는 아주 상세한 문서를 통해 그대로 진행하면 됨.

# 🎯 .net 설치하기

[Download .NET 6.0 SDK (v6.0.404) - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-6.0.404-windows-x64-installer)

1. **먼저 구글에다 .net download 검색해서 6.0 버전으로 설치해줬다. 환경변수나 따로 설정할 거 없이 설치하면 자동으로 세팅되는 듯하다**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/62d79534-55c6-45cf-a980-26b1ef4f7448/Untitled.png)

1. **c# 프로젝트 경로에서 `dotnet new console` 명령어를 입력한다. 이 폴더를 c# 프로젝트로 사용할 거라는 뜻.**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ac32ec90-acc9-4a19-910c-0792739ede00/Untitled.png)

제대로 설치됐으면 다음과 같은 파일이 생성됨.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f1a1b350-05ce-4de4-b9d3-474e0820dbc0/Untitled.png)

1. **vs code에서 c# 익스텐션을 설치한다.**

익스텐션을 설치한 후 vscode 터미널에서 바로 명령어를 치면 실행되는데, 안 돼서 이렇게 함.

# ⚠️ omnisharp 설정 오류

1. c# 익스텐션 설정으로 들어감
2. omnisharp 검색 -> 관련 설정이 나옴

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b5f7310-fbbe-4649-92ae-0ad42f9a37e3/Untitled.png)

use modern net을 활성화 하니까 설치됨. 최신 버전으로 설정.

[https://stackoverflow.com/questions/35229072/omnisharp-server-is-not-running-windows-10](https://stackoverflow.com/questions/35229072/omnisharp-server-is-not-running-windows-10)

<aside>
⚠️ 추가적으로 f5 키 누르면 실행되도록 설정하는 방법

</aside>

[C# : Visual Studio Code C# 개발환경 설정 (VS Code C#)](https://cosmosproject.tistory.com/566)

# Hello word!

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a6534e80-8a10-49f5-b572-03d02382c646/Untitled.png)

기본으로 만들어지는 program.cs를 `dotnet run` 명령어로 실행하여 테스트 한다.

# 디버그 모드

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a8b6b29-77d5-4385-8576-8d22184fda44/Untitled.png)

omnisharp 디버그

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/34178e46-28cf-4d94-86af-31a645e26e33/Untitled.png)

이 설정을 하고 나면, .vscode에 json 파일 두개가 생기고, debug 모드에서 실행가능함.
