# 집피드 웹사이트

App Store 제출에 필요한 최소 웹 페이지입니다.

## 포함 페이지

- `/` 서비스 소개
- `/privacy` 개인정보처리방침
- `/terms` 이용약관
- `/support` 고객 지원
- `/share` 공유 링크용 기본 페이지

## GitHub Pages 배포

무료 배포를 위해 앱 본체 private repo와 분리한 public repo에서 GitHub Pages를 사용합니다.

현재 공개 repo:

- `https://github.com/seongmin-kye/jipfeed-site`

배포 설정:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/`

배포 후 아래 URL을 App Store Connect에 입력합니다.

권장 입력값:

- Privacy Policy URL: `https://seongmin-kye.github.io/realty_app/privacy.html`
- Support URL: `https://seongmin-kye.github.io/realty_app/support.html`
- Terms URL: `https://seongmin-kye.github.io/realty_app/terms.html`
- Marketing URL: `https://seongmin-kye.github.io/realty_app/`

커스텀 도메인은 출시 후 검색 유입이나 브랜드 운영이 필요해질 때 연결해도 됩니다.

## 참고 기준

- Apple App Store Connect는 모든 앱에 공개 접근 가능한 개인정보처리방침 URL을 요구합니다.
- 개인정보처리방침은 수집 항목, 이용 목적, 보유 기간, 제3자 제공, 처리 위탁, 정보주체 권리,
  파기, 안전성 확보 조치, 개인정보 보호책임자 등 핵심 항목을 포함하도록 구성했습니다.
