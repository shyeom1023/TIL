---
title: 개발 환경 셋팅
author: 염석현
date: 2022-03-07
category: Jekyll
layout: post
---



## VSCODE 환경 설정



1. #### Node.js 설치 - node.js 런타임 & npm 설치

  https://nodejs.org/en/ 접속 -> 파일 설치
  $ node -v
  $ npm -v
  $ npm help
  $ npm version

  

2. #### Yarn 설치 - Facebook에서 만든 자바스크립트 패키지 매니저

  $ npm install --global yarn 	: npm 패키지 매니저를 통해 설치하는 방식(권장되는 방식)
  $ yarn --version
  $ yarn install	: package.json 파일의 의존성 모듈(dependencies) 설치

  

3. #### VS Code 설치

   1) default 설치 경로 :  C:\users\{username}\AppData\Local\Programs\Microsoft VS Code.
   2) extensions(플러그인) 폴더 경로 : %USERPROFILE%\.vscode\extensions		
   (해당 extensions 폴더를 그대로 복사해서 다른 폴더에 적용해도 완벽히 적용된다 함.)

- ##### ESLint : Javascript, JSX의 정적 분석 도구. 코드를 분석해서 문법 오류나 안티 패턴 등을 찾아내어 일관된 코드 스타일로 작성하도록 도와줌.

- ##### Reactjs Code Snippets

- ES7 React/Redux/GraphQL/React-Native snippets

- Prettier - Code forfmatter

- Code Runner : C, C++, Java, JavaScript, PHP, Python 등등 코드를 실행해줌. Ctrl+Alt+N

- open in browser : html 파일을 브라우저로 열어줌.

- ##### Live Server : html 같은 프론트 작업을 간단하게 로컬 서버 구축하여 실행.

- ##### Auto Rename Tag : 마크업 앞 혹은 뒤를 수정하면 그에 대응하는 마크업 뒤 혹은 앞을 자동으로 수정해줌.

- Auto-Open Markdown Preview : README.md 같은 파일에 대한 미리보기 창이 실시간 표출.

- TODO Highlight : todo 리스트 확인가능. 예) TODO: 내용, FIXME: 내용

- vscode-icons : 각종 폴더 및 파일에 아이콘 표시.

- Bracket Pair Colorizer : 괄호 (), {}, [] 의 짝을 맞추어 색을 다르게 해줌.

- ##### Git History : 오른쪽 마우스 클릭해서 각종 Git: view history 확인 가능.

- GitLens : 코드에 커서만 올려도 해당 커밋에 대한 내역 확인 가능.

- Settings Sync : github에 현재 vscode setting 정보를 저장해두어 여러 개의 컴퓨터를 같은 환경으로 동기화 가능.

- ##### Html CSS Support : html코드에서 css 자동완성 기능.

- ##### CSS Peek : html코드에 적용된 CSS 파일을 찾아감.

- ##### Color Highlight : 색깔코드 입력 시, 해당 색깔로 하이라이팅을 해줌.

- ##### Path Intellisense : 상대경로, 절대경로 등을 자동완성.

- indent-rainbow : tab 영역을 컬러로 구분하여 표시.

- ##### Active File In StatusBar : 화면 하단에 내가 작성하는 파일 경로 표출.

- npm : package.json 파일 검증.

- Eclipse Keymap : 이클립스 단축키 연동.



4. #### Chrome Extensions 설치

  크롬 검색창에 'chrome://version/' 입력 -> 프로필 경로 확인.  예) C:\Users\USER\AppData\Local\Google\Chrome\User Data\Profile 1\Extensions
  'chrome://extensions/' 입력 -> 개발자 모드 On -> 확장팩 ID값 확인(실제 폴더 이름)