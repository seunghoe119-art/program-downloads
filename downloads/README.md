# ZIP 프로그램 업로드 폴더

이 폴더에 `v1.zip`, `v2.zip`, `v3.zip`처럼 ZIP 파일을 올리면 다운로드 사이트에 자동으로 표시됩니다.

## 올리는 방법

1. 이 폴더에서 **Add file → Upload files**를 클릭합니다.
2. ZIP 파일을 끌어다 놓거나 선택합니다.
3. **Commit changes**를 눌러 `main` 브랜치에 저장합니다.
4. 다운로드 사이트 https://seunghoe119-art.github.io/program-downloads/ 에 접속해 확인합니다.

- 새 ZIP 파일을 올릴 때마다 사이트 코드 수정은 필요하지 않습니다.
- 이 폴더의 `.zip` 파일만 자동으로 목록에 표시됩니다.
- 파일명이 버전으로 쓰입니다. 예: `myprogram-v2.zip` → `v2`.
- 등록된 ZIP 파일을 삭제하면 사이트 목록에서도 사라집니다.
- 브라우저에서 GitHub 파일 업로드는 **파일당 25 MiB**로 제한됩니다. 더 큰 설치 파일은 GitHub Releases를 이용하세요.
