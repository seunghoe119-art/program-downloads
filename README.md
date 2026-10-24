# SOFTWARE HUB — 프로그램 다운로드 센터

하늘색 · 파란색 · 흰색 테마의 공개 프로그램 다운로드 사이트입니다.

## 사이트 공개하기 (최초 1회)

1. [저장소 Pages 설정](https://github.com/seunghoe119-art/program-downloads/settings/pages)을 엽니다.
2. **Build and deployment → Source**를 **Deploy from a branch**로 설정합니다.
3. **Branch**를 **main**, 폴더를 **/(root)**로 선택한 뒤 **Save**를 클릭합니다.
4. 사이트 주소: https://seunghoe119-art.github.io/program-downloads/

> 이 저장소에 `index.html`이 이미 있으므로 별도의 서버나 설치가 필요 없습니다.

## 프로그램 업로드하기

1. [Releases](https://github.com/seunghoe119-art/program-downloads/releases)로 이동합니다.
2. **Draft a new release** 또는 **Create a new release**를 클릭합니다.
3. 새 태그(예: `v1.0.0`)를 만들고 제목 및 설명을 작성합니다.
4. 아래 첨부 영역에 프로그램 설치 파일(`.exe`, `.zip`, `.msi`, `.dmg`, `.apk` 등)을 올립니다.
5. **Publish release**를 누릅니다.

홈페이지의 다운로드 카드와 버튼에 공개된 릴리스 및 첨부 파일이 **자동 표시**됩니다. 프로그램마다 버전을 배포하면 해당 내역이 카드로 표시됩니다.

## 참고

- 프로그램 파일은 GitHub Releases에 첨부해야 합니다. 일반 소스 저장소에 파일만 올리는 것으로는 다운로드 카드가 만들어지지 않습니다.
- 등록한 릴리스가 없으면 준비 중 화면이 나타납니다.
- 설치 파일은 공개 전 본인이 직접 바이러스 검사하고 동작을 확인하세요.
- GitHub API의 일시적인 요청 제한 또는 오류가 있으면 다운로드 목록 대신 GitHub 링크가 표시됩니다.
- 사이트는 별도 백엔드 없이 HTML/CSS/JavaScript로 동작합니다.
