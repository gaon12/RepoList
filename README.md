# RepoList
본 계정이 깃허브에 Public/Private 저장소를 여러개 생성했는데, 각 저장소를 소개합니다. 작성 언어별로 목차를 나누었습니다. 여러 언어로 작성된 경우, 주 언어에 따라 분류했습니다.

## 범례
1. 공개 저장소: 🌐, 비공개 저장소: 🔒
2. 타 프로젝트 PR 승인됨: 🚩
3. 설치 매니저에 등록되어 있음: 📦
4. 다국어 지원: 🌍 - 다국어 지원 기준은 별다른 코드 수정 없이 콘솔창이나 화면에 여러 언어를 출력하는 경우에만 적용. 사용자가 커스텀 해야 하는 경우에는 미기입
5. 타 저장소를 Fork하여 개발: 🔄
6. 프레임워크 사용 시 해당 프레임워크 아이콘 및 옆에 프레임워크 이름 작성. 예: <img src="images/icons/framework/react.svg" width="16px" height="16px" style="margin-bottom:-3px;"> 리액트

# 파이썬
## pykma_grid 🌐📦
* 목적: `pykma_grid`는 위도와 경도를 Lambert Conformal Conic Projection을 사용하여 격자 좌표로 변환하는 파이썬 패키지입니다. 이 패키지는 [기상청 API](https://www.data.go.kr/data/15084084/openapi.do)에서 격자X, Y를 사용할 때 유용합니다.
* 깃허브 주소: [https://github.com/gaon12/pykma_grid](https://github.com/gaon12/pykma_grid)
* 간단 사용 방법: [https://github.com/gaon12/pykma_grid?tab=readme-ov-file#%EC%84%A4%EC%B9%98-%EB%B0%A9%EB%B2%95](설치 방법) 문단 및 하위 문단 참조
* 기타:
  1. [pypi](https://pypi.org/project/pykma-grid/)에 등록되어 있어, 아래와 같이 `pip`로 설치 가능합니다.
```shell
pip install pykma_grid
```
  2. 자바스크립트의 [kma-grid](https://github.com/gaon12/kma-grid)와 동작 방식은 동일합니다.
  3. 연산 결과가 기상청 문서의 C언어 코드 결과와 약간 다릅니다. 소숫점 정확도 및 반올림 등으로 인해 약간의 차이가 있을 수 있습니다.

## MusicQueue 🌐
* 목적: 브라우저 드라이버를 이용하여 유튜브 영상을 차례대로 출력합니다.
* 깃허브 주소: [https://github.com/gaon12/MusicQueue](https://github.com/gaon12/MusicQueue)
* 간단 사용 방법: [사용 방법](https://github.com/gaon12/MusicQueue#%EC%82%AC%EC%9A%A9-%EB%B0%A9%EB%B2%95) 문단 참조csv_discordbot
* 기타: `Node.js`의 `Puppeteer` 버전으로도 제작할 예정입니다.

## csv_discordbot 🌐
* 목적: 기존에는 자유도는 높았지만, 단순히 사용자가 질문하면 답변하는 봇을 만들려면 각 명령어들을 일일이 입력하고, 답변도 적어 놓아야 하기 때문에 어렵고 복잡했지만, 이젠 단순히 질문과 답변하는 봇을 만들려면 `csv` 파일에 질문과 답변을 적으면 동작합니다.
* 깃허브 주소: [https://github.com/gaon12/csv_discordbot](https://github.com/gaon12/csv_discordbot)
* 간단 사용 방법: [준비물](https://github.com/gaon12/csv_discordbot#%EC%A4%80%EB%B9%84%EB%AC%BC) 문단 참조
* 기타: ~~`tsv` 파일도 사용 가능하도록 개선할 예정입니다.~~ `tsv, `xls(x)`도 지원합니다. 자세한 내용은 [이슈 #2](https://github.com/gaon12/csv_discordbot/issues/2)를 참고하시기 바랍니다.

## sw_camp_git_test 🌐
* 목적: 학교에서 배운 내용과 과제를 올려놓은 저장소입니다.
* 깃허브 주소: [https://github.com/gaon12/sw_camp_git_test](https://github.com/gaon12/sw_camp_git_test)
* 간단 사용 방법: 각 파일 코드를 읽으시기 바랍니다.
* 기타: 여담으로 `README.md` 파일에 Git 명령어를 상세히 작성해 놓았으므로 도움이 될 수도 있습니다.

## Did_you_cheat 🔒
* 목적: [서든어택](https://sa.nexon.com/)에선 핵의심 시 디스코드 라이브와 원격 점검을 하는데, 원격러(원격으로 핵이 있는지 확인하는 사람)가 오판하거나 개인정보 문제가 있으므로 PC의 로그를 정리하여 제공하는 프로그램입니다.
* 깃허브 주소: [https://github.com/gaon12/Did_you_cheat](https://github.com/gaon12/Did_you_cheat)
* 간단 사용 방법: [`running_program.py`](https://github.com/gaon12/Did_you_cheat/blob/main/running_programs.py) 실행
* 기타:
  1. 윈도우 환경에서만 동작합니다.
  2. 아직 기본 틀만 짜 놓은 상태입니다.

## site_up_check 🌐
* 목적: 현재 PC를 기준으로 도메인에 접속할 수 있는지 확인하며, `사이트 주소`, `ip주소`, `사이트 상태`를 기록합니다.
* 깃허브 주소: [https://github.com/gaon12/site_up_check](https://github.com/gaon12/site_up_check)
* 간단 사용 방법: [준비물](https://github.com/gaon12/site_up_check#%EC%A4%80%EB%B9%84%EB%AC%BC) 문단 참조
* 기타:
  1. `WARNING` 코드 인식이 약간 불안정합니다.
  2. 추후 해당 사이트 캡쳐 이미지도 저장되도록 개선할 예정입니다.
  3. 현재는 클라우드플레어 캡챠 인증 페이지 동작 시 정상 동작을 보장하지 않습니다.

## discord_gaon 🔒
* 목적: 디스코드 봇을 제작하고 있는 저장소입니다.
* 깃허브 주소: [https://github.com/gaon12/discord_gaon](https://github.com/gaon12/discord_gaon)https://github.com/gaon12/discord_gaon
* 간단 사용 방법: [`gaon.py`](https://github.com/gaon12/discord_gaon/blob/main/gaon.py) 파일 실행
* 기타: 사실상 개발 중단되었습니다.

# 자바스크립트
## WTrip 🔒 <img src="images/icons/framework/react.svg" width="22px" height="22px" style="margin-bottom:-3px;"> 리액트
* 목적: 해외 여행 시 해당 국가의 정보와 환율 정보를 보기 쉽도록 만든 사이트입니다. 환율을 3일~365일치 그래프로 볼 수 있고, 환율 예측 그래프도 제공합니다. 리액트를 사용했습니다.
* 깃허브 주소: [https://github.com/gaon12/WTrip](https://github.com/gaon12/WTrip)
* 간단 사용 방법: [사용법](https://github.com/gaon12/WTrip#%EC%82%AC%EC%9A%A9%EB%B2%95) 문단 참조 및 아래의 명령어 입력(비공개 저장소이므로 웹사이트에서 확인)
```shell
npm install
npm run start
```
* 기타:
  1. 모바일 등 반응형이 아직 부족합니다.
  2. [https://wtrip.uiharu.dev](https://wtrip.uiharu.dev)에서 기능을 확인할 수 있습니다.
  3. 에러 페이지는 [CustomErrorPages](https://github.com/gaon12/CustomErrorPages) 저장소를 사용했습니다.

## CustomErrorPages 🌐🌍 <img src="images/icons/framework/react.svg" width="22px" height="22px" style="margin-bottom:-3px;"> 리액트
* 목적: 기존의 멋없는 에러 페이지를 대체하여 깔끔한 디자인의 에러 페이지를 만들었습니다.
* 깃허브 주소: [https://github.com/gaon12/CustomErrorPages](https://github.com/gaon12/CustomErrorPages)
* 간단 사용 방법: [바꾸는 방법](https://github.com/gaon12/CustomErrorPages#%EB%B0%94%EA%BE%B8%EB%8A%94-%EB%B0%A9%EB%B2%95) 문단 참조
* 기타:
  1. 타 리액트 프로젝트나 아이프레임 등에서 불러오는 방식으로 사용 시, `body` 태그에 스크롤은 없앴기 때문에 각자 상황에 따라 수정이 필요할 수 있습니다.
  2. [https://error.uiharu.dev/error](https://error.uiharu.dev/error)에서 데모를 확인할 수 있습니다. 예를 들어 `404 에러`는 [https://error.uiharu.dev/error/404](https://error.uiharu.dev/error/404)에서 확인할 수 있습니다.

## BridgeWay 🌐 <img src="images/icons/framework/react.svg" width="22px" height="22px" style="margin-bottom:-3px;"> 리액트
* 목적: [WTrip 저장소](https://github.com/gaon12/WTrip)의 기능을 바탕으로 해외 여행시 도움을 주는 서비스 개발을 위해 제작했습니다.
* 깃허브 주소: [https://github.com/gaon12/BridgeWay](https://github.com/gaon12/BridgeWay)
* 간단 사용 방법: [FrontEndWeb/bridgewayweb](https://github.com/gaon12/BridgeWay/tree/main/FrontEndWeb/bridgewayweb) 폴더에서 아래의 명령어 입력
```shell
npm install
npm run start
```
* 기타: 본 저장소에는 백엔드와 프론트엔드 코드 모두 다 있습니다.

## Twitch_Username_Search 🌐🌍<sup>*일부 지원</sup> <img src="images/icons/framework/react.svg" width="22px" height="22px" style="margin-bottom:-3px;"> 리액트
* 목적: 트위치 닉네임으로 유저네임을 검색할 수 있습니다. 또한 사이트 내에서 여러 채널들을 닉네임 검색으로 한눈에 볼 수 있습니다.
* 깃허브 주소: [https://github.com/gaon12/Twitch_Username_Search](https://github.com/gaon12/Twitch_Username_Search)
* 간단 사용 방법: [준비물](https://github.com/gaon12/Twitch_Username_Search#%EC%A4%80%EB%B9%84%EB%AC%BC) 문단 참조
* 기타:
  1. 트위치 API키가 필요합니다.
  2. 멀티 스트리밍 사이트는 현재 시범 운영중 입니다. [https://mt.uiharu.dev](https://mt.uiharu.dev) 에서 확인할 수 있습니다.

## kma-grid 🌐📦
* 목적: 위도와 경도를 Lambert Conformal Conic Projection을 사용하여 격자 좌표로 변환하는 자바스크립트 라이브러리입니다. 이 라이브러리는 기상청 API에서 격자X, Y를 사용할 때 유용합니다.
* 깃허브 주소: [https://github.com/gaon12/kma-grid](https://github.com/gaon12/kma-grid)
* 간단 사용 방법: [설치](https://github.com/gaon12/kma-grid#%EC%84%A4%EC%B9%98) 문단 및 하위 문단 참조
* 기타:
  1. [npm](https://www.npmjs.com/package/kma-grid)에 등록되어 있어, 아래와 같이 `npm`으로 설치 가능합니다.
```shell
npm install kma-grid
```
  2. 파이썬의 [pykma_grid](https://github.com/gaon12/pykma_grid)와 동작 방식은 동일합니다.
  3. 연산 결과가 기상청 문서의 C언어 코드 결과와 약간 다릅니다. 소숫점 정확도 및 반올림 등으로 인해 약간의 차이가 있을 수 있습니다.

## Base64_ENDE_Chrome_Extension 🌐
* 목적: 텍스트를 선택 후 해당하는 기능 메뉴를 선택하면 `Base64`로 인코딩 또는 디코딩하는 크롬 확장기능입니다.
* 깃허브 주소: [https://github.com/gaon12/Base64_ENDE_Chrome_Extension](https://github.com/gaon12/Base64_ENDE_Chrome_Extension)
* 간단 사용 방법: [사용법](https://github.com/gaon12/Base64_ENDE_Chrome_Extension#%EC%82%AC%EC%9A%A9%EB%B2%95) 문단 참조
* 기타:
  1. Chrome 웹 스토어에 등록하지 않은 확장기능입니다.
  2. 이미지 등 텍스트가 아닌 경우에는 동작하지 않습니다.
  3. 디코딩 결과가 URL이면 링크에 하이퍼링크 처리가 되며, URL이 아니면 클릭 시 클립보드에 복사가 됩니다. 인코딩시에도 마찬가지입니다.
  4. 사용하는 사이트에서 `!important` 등의 처리를 하면 UI가 틀어질 수 있습니다.

## Imagine 🔒 <img src="images/icons/framework/react.svg" width="22px" height="22px" style="margin-bottom:-3px;"> 리액트
* 목적: Alice in Imagine Land! 인공지능을 활용한 기술을 웹에서 체험할 수 있습니다. 현재는 **악성 댓글 탐지** 기능을 체험해 볼 수 있습니다.
* 깃허브 주소: [https://github.com/gaon12/Imagine](https://github.com/gaon12/Imagine)
* 간단 사용 방법: 아래의 명령어 입력(비공개 저장소이므로 웹사이트에서 확인)
```shell
npm install
npm run start
```
* 기타:
  1. [https://alice.uiharu.dev](https://alice.uiharu.dev)에서 기능을 확인할 수 있습니다.
  2. GPU가 아닌 CPU를 사용해 모델을 구동하기 때문에 딜레이가 있습니다.

## FindBin 🌐 <img src="images/icons/framework/expo.svg" width="22px" height="22px" style="margin-bottom:-3px;"> Expo(리액트 네이티브)
* 목적: 우리 주변에 있는 공공 쓰레기통을 찾아 보아요!
* 깃허브 주소: [https://github.com/gaon12/FindBin](https://github.com/gaon12/FindBin)
* 간단 사용 방법: 아래의 명령어 입력
```shell
npm install
npm run start
```
* 기타:
  1. Expo 환경에서 제작되었기 때문에 확인 시 `Expo Go` 앱이 필요합니다.
  2. API에서 불러올 때, 최소 50m ~ 최대 2000m(2km) 범위를 지정해야 합니다.

## DMIA 🌐🌍 <img src="images/icons/framework/expo.svg" width="22px" height="22px" style="margin-bottom:-3px;"> Expo(리액트 네이티브)
* 목적: 재난 응급 정보 시스템 DMIA 프로젝트는 기존의 [안전디딤돌](https://www.mois.go.kr/frt/sub/a06/b11/safetyStep/screen.do)의 여러 문제점들을 해결하기 위해 만든 프로젝트입니다.
* 깃허브 주소: [https://github.com/gaon12/DMIA](https://github.com/gaon12/DMIA)
* 간단 사용 방법: 아래의 명령어 입력
```shell
npm install
npm run start
```
* 기타: Expo 환경에서 제작되었기 때문에 확인 시 `Expo Go` 앱이 필요합니다.

## show_markdown 🌐
* 목적: 마크다운 파일을 특정 div에 출력하는 read_md 함수를 제공합니다.
* 깃허브 주소: [https://github.com/gaon12/show_markdown](https://github.com/gaon12/show_markdown)
* 간단 사용 방법: [사용 방법](https://github.com/gaon12/show_markdown#%EC%82%AC%EC%9A%A9-%EB%B0%A9%EB%B2%95) 문단 참조 및 아래의 예시 코드 확인
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- 마크다운 출력할 div -->
    <div id="repo_div"></div>
    <!-- 의존성 라이브러리(marked) 로드-->
    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
    <!-- show_markdown 자바스크립트 로드 -->
    <script src="read_md.js"></script>
    <!-- 마크다운 출력할 div 및 마크다운 파일 지정 -->
    <script>read_md("README.md", "repo_div");</script>
</body>
</html>
```
* 기타:
  1. 의존성 라이브러리(marked)가 존재합니다.
  2. 아래의 순서에 맞게 로드해야 합니다. 그렇지 않으면 오류가 발생합니다.<br>
    2-1. 마크다운 내용을 출력할 div(id가 설정되어 있어야 함.)<br>
    2-2. marked 자바스크립트<br>
    2-3. read_md 자바스크립트<br>
    2-4. read_md 함수 호출
  3. `file://` 프로토콜에서는 `CORS 오류`가 발생하여 정상적으로 작동되지 않습니다.

## Ranick2-ko 🌐🌍 <img src="images/icons/framework/electron.svg" width="22px" height="22px" style="margin-bottom:-3px;"> Electron
* 목적: 메이플 2글자 닉네임을 랜덤으로 만들어주는 프로그램입니다.
* 깃허브 주소: [https://github.com/gaon12/Ranick2-ko](https://github.com/gaon12/Ranick2-ko)
* 간단 사용 방법: [릴리즈 페이지](https://github.com/gaon12/Ranick2-ko/releases)에서 최신 버전 다운로드 후 압축 해제 후 실행
* 기타:
  1. 방화벽이 인터넷 연결 여부를 묻는 창이 뜨면 승인해주세요.
  2. 직접 index.html 파일을 실행하는 경우, 정상 작동을 보장하지 않습니다.
