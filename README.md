# 최준형
## [ 3월 30일 ]
### google firebase nwitter 프로젝트 생성 

### firebase 설치

    npm install firebase

### firebase config 설정

- 암호파일 생성 후 gitignore를 이용해서 보안처리

### routes관련 js 생성
 - Router.js
 - Auth.js
 - EditProfile.js
 - Home.js
 - Profile.js

## [ 3월 23일 ] 

리엑트 앱 생성

    npx create-react-app@latest nwitter

불필요 파일 삭제 및 수정
- app.js, index.js 만 놔두고 불필요 파일 삭제
- index.js 필요없는 import 삭제
- package.json 삭제 -
    "test": "react-scripts test",
    "eject": "react-scripts eject"

    
깃 명령어

    git init 
    git remote origin add 주소 - 원격 저장소 연결
    git add . - 작업 파일 추가
    git commit -m "커밋 내용" - 커밋하기
    git push origin master  - 푸쉬하기