# 최준형
## [ 4월 13일 ]
- firebase 오류
    - 경로 오류 - fbase.js import 수정

            import firebase from "firebase/compat/app";

    - 버전 오류

            npm install firebase @8.8.0

- UserState 값 False -> authService.currentUser 설정

        const [isLoggedIn, setIsLoggedIn] = useState(authService.currentUser);
- 구글, Git 로그인 설정 해보기
## [ 4월 06일 ]
### Router 적용
- useState function 사용
    
        import { useState } from "react";

        const [isLoggedIn, setIsLoggedIn] = useState(authService.currentUser);

- 라우터 버전 낮추기

        npm install react-router-dom@5.2.0

- 기본 경로 설정을 위한 json 파일 생성
 
        {
            "compilerOptions": {
                "baseUrl": "src"
            },
            "include": ["src"]
        }


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