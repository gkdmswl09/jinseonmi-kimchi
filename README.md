# 진선미 김치 — 졸업전시 웹사이트

국내용 13종 / 수출용 8종으로 구성된 반응형 전시용 사이트입니다.
처음에는 국내용을 표시합니다. 상품 검색, 상세 보기, 장바구니, 모의 주문을 체험할 수 있습니다.
실제 결제 및 주문 전송은 이루어지지 않습니다.

## GitHub 웹사이트에서 업로드하기

1. GitHub에 로그인하고 새 저장소(New repository)를 만듭니다.
2. 이름은 jinseonmi-kimchi로 정하고 Public을 선택합니다. README 추가를 선택해 생성하면 업로드 메뉴를 찾기 쉽습니다.
3. 이 압축파일을 컴퓨터에서 풀어 둡니다.
4. 저장소에서 Add file → Upload files를 누릅니다.
5. 압축을 푼 폴더 안의 index.html, style.css, app.js, assets 폴더, README.md, .nojekyll을 올립니다.
   폴더 자체로 한 겹 감싸지 말고, 저장소 첫 화면에 index.html과 assets가 바로 보이게 올립니다.
   ZIP 파일 자체를 올리지 마세요.
6. Commit changes를 눌러 main 브랜치에 저장합니다.
7. Settings → Pages → Build and deployment로 이동합니다.
8. Source를 Deploy from a branch로 선택합니다.
9. Branch는 main, 폴더는 /(root)를 선택하고 Save를 누릅니다.
10. 배포가 끝나면 같은 Pages 화면의 Visit site 링크를 엽니다.

.nojekyll이 보이지 않을 경우:
파일 탐색기의 숨긴 항목 표시를 켜거나 GitHub의 Add file → Create new file에서
파일명을 .nojekyll로 지정하고 빈 파일로 저장하세요.
별도 Actions 설정이나 빌드 명령, 패키지 설치, API 키는 필요 없습니다.

## 아이패드에서 열기

Settings → Pages에 표시된 사이트 주소를 아이패드 사파리로 엽니다.
주소 형태 예시: https://YOUR-USERNAME.github.io/jinseonmi-kimchi/
위 예시는 실제 배포 주소가 아닙니다. YOUR-USERNAME은 본인의 GitHub 사용자 이름입니다.
GitHub 저장소 주소(github.com/...)가 아니라 Pages 주소(github.io/...)를 사용하세요.
인터넷 연결이 필요하며, 공개 사이트 열람에는 ChatGPT 로그인이 필요 없습니다.
장바구니 내용은 브라우저별로 저장되며 다른 기기와 동기화되지 않습니다.

## 업데이트

같은 저장소의 파일을 수정하거나 교체하고 Commit changes를 누르면
Pages가 자동으로 다시 배포됩니다. 기존 주소를 계속 사용할 수 있습니다.

## 파일 구성

- index.html: 화면 구성
- style.css: PC·태블릿·모바일 디자인
- app.js: 상품 분류 및 구매 체험 기능
- assets/: 이미지 및 폰트
- .nojekyll: 정적 파일 그대로 배포
- README.md: 업로드 안내

공식 안내:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
