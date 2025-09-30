# 노무 계산기 GitHub Pages 스타터

이 저장소는 `index.html` 하나로 **퇴직금/연차수당/주52시간 계산기**를 제공하는 GitHub Pages용 기본 템플릿입니다.

## 만들기 (웹에서만, 깃 명령어 불필요)

1. GitHub에 로그인 → 오른쪽 위 **+** → **New repository** 선택
2. **Repository name**에 `YOURUSERNAME.github.io` 입력 (YOURUSERNAME은 깃허브 아이디)
3. **Public** 선택 → **Create repository**
4. **Add file → Upload files** 클릭 → 이 폴더의 파일들(`index.html`, `about.html`, `privacy.html`, `404.html`)을 업로드 → 맨 아래 **Commit changes**
5. 상단 **Settings → Pages**로 이동 → **Build and deployment**에서 **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
   - Save
6. 잠시 후 `https://YOURUSERNAME.github.io` 로 접속하면 사이트가 열립니다.

## 커스텀 도메인 연결(선택)

- `Settings → Pages → Custom domain`에 구매한 도메인을 입력하고 안내에 따라 DNS 레코드를 추가하세요.

## 애드센스 붙이기(승인 후)

- `index.html` 상단의 애드센스 스크립트 주석을 해제하고 발급받은 `client`/`slot` 값을 넣으세요.
- `about.html`, `privacy.html`은 승인을 돕는 기본 페이지입니다. 내용을 실제에 맞게 수정하세요.

## 수정/배포

- 웹에서 `index.html` 편집 후 **Commit changes**를 누르면 1~2분 내 자동 반영됩니다.
