# Manual Build

홈페이지에 사용되는 메뉴얼을 빌드 하는 방법을 제공합니다.


메뉴얼의 필드는 

`https://github.com/mobigen/IRIS-Documentation`

을 사용합니다.


`manual_build` 명령어를 사용 하시기 전에 다음 작업을 진행하시기 전에 다음 작업을 진행햐여, 필요 패키지를 설치해야 합니다.

manual_build는 python 3.6버전 이상을 지원하고 있습니다.


```
pip install -r requirements.txt
```

이후 다음과 같이 명령어를 사용하시면 됩니다.

명령어는 다음과 같은 형식으로 동작을 합니다.


- `https://github.com/mobigen/IRIS-Documentation` 클론
- 매뉴얼 빌드
- 기존 매뉴얼 삭제
- 신규 매뉴얼 복사
- 클론 파일 삭제
