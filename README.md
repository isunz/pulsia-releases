# PULSIA Releases

PULSIA 데스크톱 앱의 설치 파일과 자동 업데이트 metadata를 배포하는 저장소다.

- 제품 소스: [isunz/pulsia](https://github.com/isunz/pulsia)
- 설치 파일: 이 저장소의 [Releases](https://github.com/isunz/pulsia-releases/releases)
- Windows 초기 배포본은 Authenticode 서명이 없어 Microsoft Defender SmartScreen 경고가 표시될 수 있다.

플러그인은 각 플러그인이 manifest에 선언한 전용 GitHub 저장소에서 독립적으로 배포하고 업데이트한다. 이 저장소에는 플러그인 ZIP이나 플러그인 버전 태그를 게시하지 않는다.

설치 파일은 PULSIA 소스 저장소의 release 품질 검사와 packaged runtime 검증을 통과한 뒤 자동으로 게시한다.
