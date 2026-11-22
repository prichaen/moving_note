# 움직이는 노트 (moving_note)

과학 수업용 단원별 인터랙티브 HTML 노트를 모아두는 정적 웹사이트입니다.

- `index.html`: 노트 형태의 첫 화면 / 단원 목차
- `units/integrated-science-2-electromagnetic-induction.html`: 통합과학 2 · 전자기 유도 (업로드 원본 기반)

## 새로운 단원 추가

1. `units/`에 새 HTML 파일을 넣습니다.
2. `index.html`의 `.note-grid` 안에 새 단원으로 이동하는 `<a class="note" ...>` 카드를 추가합니다.
3. GitHub Pages가 설정된 저장소의 기본 브랜치에 변경사항을 올립니다.

## GitHub Pages

저장소 `Settings > Pages > Build and deployment > Deploy from a branch`를 선택하고, 게시 브랜치의 `/ (root)` 폴더를 설정합니다. 기존 Pages 설정이 있다면 덮어쓰지 말고 현재 설정을 확인하세요.