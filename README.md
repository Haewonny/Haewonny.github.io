# Haewonny.github.io
---

## 📄 GitHub 페이지 배포하는 방법 

1️⃣ (사용자 이름).github.io Repository 생성

2️⃣ 원하는 이름으로 Repository 생성

3️⃣ 생성한 Repository에 프로젝트 파일 올리기

4️⃣ 터미널 입력
```
npm i gh-pages 
```

5️⃣ package.json파일에서 script 부분에 추가하기
```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build" 
```
맨 아래에 추가하기
```json
"homepage": "https://사용자이름.github.io/저장소이름"
```

6️⃣ 터미널 입력(published 뜨면 성공)
```
npm run deploy
```

7️⃣ [settings] -> [pages]에서 source를 gh-pages로 바꾸기
