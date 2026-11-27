# CiC 4.0 소개 · 모바일

CiC 4.0 소개 페이지의 모바일 전용 버전입니다. 빌드 도구 없이 바로 열리는 정적 페이지입니다.

## 구성
- `index.html` — 페이지 전체 (스타일·스크립트 포함)
- `media/` — 이미지·영상
- `fonts/PretendardVariable.woff2` — 본문 폰트
- `.nojekyll` — GitHub Pages가 파일을 그대로 서비스하도록 하는 빈 파일

## 추가해야 할 파일 1개
`media/cic40-aisearch.mp4` (AI Overview 소개 영상)는 용량 문제로 포함되지 않았습니다.
PC 버전에서 쓰던 같은 파일을 `media/` 폴더에 그대로 넣어 주세요. 없으면 "AI Overview 소개 영상 보기"를 눌렀을 때 영상이 재생되지 않습니다.

## GitHub Pages 게시
1. GitHub에서 새 저장소를 만듭니다 (Public).
2. 이 폴더의 파일을 모두 업로드합니다 (`index.html`이 저장소 최상위에 오도록).
3. 저장소 **Settings → Pages**에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 저장합니다.
4. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 주소로 열립니다.

웹 업로드는 파일당 25MB까지 가능합니다. 가장 큰 파일(For Me 영상)은 약 11MB라 그대로 올릴 수 있습니다.
