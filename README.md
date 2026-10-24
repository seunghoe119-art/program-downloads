# SOFTWARE HUB — 프로그램 다운로드 센터

하늘색 · 파란색 · 흰색 테마의 공개 프로그램 다운로드 사이트입니다.

**사이트 주소:** https://seunghoe119-art.github.io/program-downloads/

## 가장 쉬운 방법: ZIP 파일을 downloads 폴더에 업로드

1. **[ZIP 업로드 폴더 열기](https://github.com/seunghoe119-art/program-downloads/tree/main/downloads)** 를 누릅니다.
2. **Add file → Upload files** 를 클릭합니다.
3. ZIP 파일을 선택합니다. 예를 들어 `v1.zip`, `v2.zip`, `v3.zip` 또는 `프로그램이름-v1.zip` 등이 가능합니다.
4. 아래 **Commit changes** 버튼으로 `main` 브랜치에 저장합니다.
5. **[다운로드 사이트](https://seunghoe119-art.github.io/program-downloads/)** 에 들어가 새로고침하면 ZIP 파일이 자동으로 목록에 나타납니다.

이 폴더에 ZIP 파일을 추가/삭제할 때는 **사이트 코드 수정이 필요 없습니다**. ZIP 파일 목록은 사이트 방문 시 GitHub API에서 불러옵니다. 목록에서 파일명을 검색할 수 있습니다.

> **용량 주의:** GitHub 브라우저 파일 업로드는 파일 하나당 25 MiB로 제한됩니다. 더 큰 설치 파일은 아래 GitHub Releases 사용을 권장합니다.

## 큰 파일 또는 정식 배포: GitHub Releases

1. [Releases](https://github.com/seunghoe119-art/program-downloads/releases)로 이동합니다.
2. **Draft a new release** 또는 **Create a new release**를 클릭합니다.
3. 새 태그(예: `v1.0.0`)를 만들고 제목 및 설명을 작성합니다.
4. 첨부 영역에 설치 파일(`.zip`, `.exe`, `.msi`, `.dmg`, `.apk` 등)을 올립니다.
5. **Publish release**를 누릅니다.

홈페이지에는 `downloads/`의 ZIP 파일과 공개된 Releases 파일이 함께 자동 표시됩니다.

## GitHub Pages 사이트 공개 설정 (최초 1회)

1. [Pages 설정](https://github.com/seunghoe119-art/program-downloads/settings/pages)을 엽니다.
2. **Build and deployment → Source:** `Deploy from a branch`
3. **Branch:** `main`, **Folder:** `/(root)`
4. **Save** 버튼을 클릭합니다.

## 참고

- `downloads/` 폴더에서는 `.zip` 확장자의 **파일**만 표시하며, 안내용 README.md는 목록에 표시되지 않습니다.
- 브라우저의 비로그인 GitHub API 호출에는 요청 횟수 제한이 있습니다. API 장애 시 GitHub 링크로 이동해서 확인할 수 있습니다.
- 프로그램을 배포하기 전 설치 파일을 직접 검사하고 정상 실행 여부를 확인해 주세요.
- 사이트는 별도 서버 없이 HTML/CSS/JavaScript로 동작합니다.
