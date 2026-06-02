# GitHub Pages 설정 안내

이 폴더는 Google Play에 제출할 개인정보처리방침 웹페이지를 GitHub Pages로 공개하기 위한 준비물입니다.

## 현재 준비된 파일

- `docs/index.html`: 실제 공개될 개인정보처리방침 웹페이지
- `docs/privacy-policy.md`: 같은 내용을 Markdown 문서로 정리한 초안
- `docs/play-store-data-safety-draft.md`: Google Play 데이터 보안 설문 작성용 내부 초안

## GitHub Pages 설정 절차

1. GitHub에 새 저장소를 만들거나 현재 프로젝트를 기존 저장소에 연결합니다.
2. 프로젝트를 GitHub에 push합니다.
3. GitHub 저장소 페이지에서 `Settings`로 이동합니다.
4. 왼쪽 메뉴에서 `Pages`를 선택합니다.
5. `Build and deployment` 항목에서 다음처럼 선택합니다.
   - Source: `Deploy from a branch`
   - Branch: GitHub에 올린 기본 브랜치. 현재 로컬 프로젝트는 `master`입니다.
   - Folder: `/docs`
6. 저장하면 몇 분 뒤 GitHub Pages URL이 생성됩니다.

예상 URL 형식:

```text
https://GITHUB_USERNAME.github.io/REPOSITORY_NAME/
```

이 URL을 Google Play Console의 개인정보처리방침 URL에 입력하면 됩니다.

## 앱 안에 연결할 URL

GitHub Pages URL이 확정되면 앱 설정 화면에 같은 URL을 연결해야 합니다.

예시:

```text
https://GITHUB_USERNAME.github.io/REPOSITORY_NAME/
```

아직 이 프로젝트에는 GitHub 원격 저장소가 연결되어 있지 않으므로, 실제 URL은 저장소를 만든 뒤 확정할 수 있습니다.
