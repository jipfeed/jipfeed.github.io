# 집피드 웹사이트

집피드 App Store 제출과 사용자 지원에 필요한 정적 웹사이트입니다.

운영 URL:

- `https://jipfeed.github.io/`

## 포함 페이지

- `/` 서비스 소개
- `/privacy.html` 개인정보처리방침
- `/terms.html` 이용약관
- `/support.html` 고객 지원
- `/share.html` 공유 링크용 기본 페이지

## GitHub Pages 배포

무료 배포를 위해 앱 본체 private repo와 분리한 public repo에서 GitHub Pages를 사용합니다.

현재 공개 repo:

- `https://github.com/jipfeed/jipfeed.github.io`

배포 설정:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/`

`main` 브랜치에 push하면 GitHub Pages가 정적 HTML/CSS 파일을 배포합니다. 별도 서버, DB,
Vercel, Node 런타임은 없습니다.

## App Store Connect 입력값

- Marketing URL: `https://jipfeed.github.io/`
- Privacy Policy URL: `https://jipfeed.github.io/privacy.html`
- Support URL: `https://jipfeed.github.io/support.html`
- Terms URL: `https://jipfeed.github.io/terms.html`

커스텀 도메인은 출시 후 검색 유입이나 브랜드 운영이 필요해질 때 연결해도 됩니다.

## 비용

현재 구조에서는 서버 비용이 없습니다.

- GitHub Pages 정적 호스팅 사용
- public repo 기반 무료 배포
- 서버 API, 데이터베이스, 인증 기능 없음
- 커스텀 도메인 미사용

## 참고 기준

- Apple App Store Connect는 모든 앱에 공개 접근 가능한 개인정보처리방침 URL을 요구합니다.
- 개인정보처리방침은 수집 항목, 이용 목적, 보유 기간, 제3자 제공, 처리 위탁, 정보주체 권리,
  파기, 안전성 확보 조치, 개인정보 보호책임자 등 핵심 항목을 포함하도록 구성했습니다.
