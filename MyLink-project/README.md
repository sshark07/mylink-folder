# MyLink (마이링크)

바이브코딩 수업의 프로필 및 링크 목록, CRUD, 클릭 통계 개념을 적용한 정적 웹 프로젝트입니다.

- `mylink/index.html`: 실제 웹페이지 (HTML/CSS/JavaScript)
- `index.html`: 저장소 루트 URL에서 마이링크로 이동
- 기본 링크는 공개 웹사이트 예시입니다.
- 추가/수정/삭제/클릭 통계는 localStorage 기반으로 현재 브라우저에만 저장됩니다.
- Firebase, Google 로그인, 사용자별 서버 데이터 분리, 전체 방문자 통계는 구현하지 않았습니다.

## 배포
GitHub 공개 저장소에 프로젝트 폴더의 내부 항목을 올린 후 Settings > Pages > Deploy from a branch > main > /(root) > Save 를 선택합니다.

저장소 이름을 `mylink-folder`로 정했다면 사이트는 `https://USERNAME.github.io/mylink-folder/`, 실제 마이링크 폴더 페이지는 `https://USERNAME.github.io/mylink-folder/mylink/` 입니다. USERNAME을 본인 계정명으로 바꾸고 실제 공개 접속을 확인하세요.
