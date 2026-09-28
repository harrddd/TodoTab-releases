# TodoTab

화면 가장자리에 탭처럼 붙어 있다가 클릭하면 펼쳐지는 할 일 목록입니다.
웹 버전과 **같은 Google 계정으로 동기화**돼서, PC·웹·휴대폰 어디서든 같은 목록을 볼 수 있어요.

- 웹 버전: https://todo-tab.sjsn-leo.workers.dev
- 이 저장소는 **Windows 데스크탑 앱 설치 파일 배포용**입니다.

## 다운로드 (Windows 10/11, 64비트)

**[TodoTab-Setup.exe 받기](https://github.com/harrddd/TodoTab-releases/releases/latest/download/TodoTab-Setup.exe)** — 설치하면 시작 메뉴·바탕화면 바로가기가 생겨요.

한 번 설치하면 이후 새 버전은 **자동으로 업데이트**돼요 (2.0.2부터). 켤 때 새 버전을 받아두고, "지금 다시 시작"을 누르거나 앱을 종료할 때 설치됩니다.

위 링크는 항상 최신 버전을 받습니다. 이전 버전은 [Releases](https://github.com/harrddd/TodoTab-releases/releases)에 있어요.

## 처음 실행할 때 경고가 뜨면

코드 서명 인증서가 없는 앱이라 Windows가 **"Windows의 PC 보호"** 창을 띄울 수 있어요.
**추가 정보 → 실행**을 누르면 설치됩니다.

## 사용법

1. 화면 오른쪽 끝의 작은 탭을 클릭하거나 `Ctrl + Shift + Space`로 펼쳐요.
2. **Google로 계속하기**를 누르면 기본 브라우저에서 로그인하고, 끝나면 앱으로 자동으로 돌아와요.
3. ⚙ 설정에서 테마, 포인트 색, 화면 왼쪽에 붙이기, 모니터, 글자 크기, 단축키, 자동 실행을 바꿀 수 있어요.

## 개인정보

- 할 일은 본인 Google 계정에 연결된 클라우드 DB에 저장되고, 본인만 읽고 쓸 수 있어요.
- 앱은 로그인할 때만 브라우저를 열고, 이 PC 안의 임시 주소(127.0.0.1)로 결과를 받은 뒤 바로 닫아요.
