# Oura OAuth Public Pages

이 폴더는 Oura 앱 등록에 필요한 최소 공개 페이지를 담고 있습니다.

포함 파일:

- `index.html`: website 용
- `privacy.html`: privacy policy 용
- `terms.html`: terms of service 용
- `callback.html`: OAuth redirect URL 용
- `styles.css`: 공통 스타일

## GitHub Pages로 올리는 가장 쉬운 방법

1. GitHub에서 새 **public repository** 생성  
   추천 이름: `linneshin-oura-bridge-site`
2. 이 폴더 안 파일을 전부 업로드
3. GitHub repository `Settings > Pages`
4. `Build and deployment`
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 저장 후 몇 분 기다리기

예상 URL:

- website: `https://YOUR_GITHUB_USERNAME.github.io/linneshin-oura-bridge-site/`
- privacy policy: `https://YOUR_GITHUB_USERNAME.github.io/linneshin-oura-bridge-site/privacy.html`
- terms: `https://YOUR_GITHUB_USERNAME.github.io/linneshin-oura-bridge-site/terms.html`
- redirect url: `https://YOUR_GITHUB_USERNAME.github.io/linneshin-oura-bridge-site/callback.html`

## Oura 앱 등록 시 입력 예시

- Display name: `LinnEshIn Oura Bridge`
- Description: `Personal local integration for my own Oura Ring data in LinnEshIn system.`
- Contact email: 본인 이메일
- Website: GitHub Pages 메인 URL
- Privacy policy: `privacy.html` URL
- Terms of service: `terms.html` URL
- Redirect URLs: `callback.html` URL
