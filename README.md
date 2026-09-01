# 2026 한서고 1학년 수련회 안내 사이트

강원도 용평리조트 블리스힐스테이에서 진행되는 2026학년도 1학년 수련회(09.07~09.09) 안내 페이지입니다.
`index.html` 하나로 동작하는 단일 파일 사이트라 별도 빌드 과정 없이 바로 배포할 수 있습니다.

## GitHub Pages로 배포하는 방법

1. GitHub에서 새 저장소를 만듭니다 (예: `grade1-training-camp`).
2. 이 폴더의 `index.html`을 저장소 루트에 업로드(또는 `git push`)합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Source**를 `Deploy from a branch`로 설정하고, 브랜치는 `main`(또는 `master`), 폴더는 `/ (root)`를 선택한 뒤 **Save**를 누릅니다.
5. 잠시 후 `https://사용자아이디.github.io/저장소이름/` 주소로 사이트가 열립니다.

## 내용을 수정하려면

`index.html` 안의 해당 영역을 직접 편집하면 됩니다.
- 일정: `<section id="schedule">` 안의 `.day-panel` 블록
- 준비물/금지품목: `<section id="prepare">`
- 응급상황 안내: `<section id="safety">`
- 비상연락망: `<section id="contact">`
- 팝업(자세히 보기) 내용: 파일 하단 `<!-- MODALS -->` 부분
