# 위페어 드라이브 업데이트 배포

위페어 드라이브 데스크톱 앱의 설치 파일과 자동 업데이트 정보(`latest.json`)를 올리는 레포입니다.

- 릴리스는 `wepaircorp/desktop-wepair-drive`의 GitHub Actions(`build-windows.yml`)가 만듭니다.
  - main 머지: 운영 릴리스(`v<버전>`)
  - develop 머지: 개발 채널 `dev-latest`(사전 릴리스)
- 설치된 앱이 이 레포의 `latest.json`을 읽어 업데이트하므로 **릴리스·태그를 손으로 고치거나 지우지 마세요.**
