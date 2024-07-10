# 📌Commit Convention

---

| Tag | Description | Example |
| --- | --- | --- |
| feat | 새로운 기능 추가 | feat: 페이지 상세 api 구현 |
| fix | 버그 수정 | fix: 사용자 조회 불가 버그 수정 |
| docs | 문서 수정 | docs: readme 프로젝트 소개 수정 |
| style | 코드 포맷팅 | style: 코드 포맷팅 |
| refactor | 코드 리팩토링 | refactor: 페이지 상세 리팩토링 |
| test | 테스트 코드 | test: 판매자의 다른 자료 테스트 코드 작성 |
| chore | 빌드 업무 수정, 패키지 매니저 수정 | chore: 서버 포트 수정 |
| remove | 파일 삭제 | remove: DS_STORE 파일 수정 |
| rename | 파일명 또는 폴더 구조 수정 | rename: 헥사고널 아키텍처 패키지 구조 적용 |
| comment | 주석 추가 | comment: 페이지 상세 주석 추가 |

# 🔗Pull Request Convention

---

| Icon | Code | Description | Example |
| --- | --- | --- | --- |
| 🎨 | :art | 코드의 구조/형태 개선 | 🎨 페이지 상세 리팩토링 |
| ⚡️ | :zap | 성능 개선 | ⚡️ 페이지 상세 호출 속도 개선 |
| 🔥 | :fire | 코드/파일 삭제 | 🔥 AI 코드 삭제 |
| 🐛 | :bug | 버그 수정 | 🐛 젬 계산 버그 수정 |
| 🚑 | :ambulance | 긴급 수정 | 🚑 젬 계산 오류 긴급 수정 |
| ✨ | :sparkles | 새 기능 | ✨ 페이지 상세 조회 기능 추가 |
| 💄 | :lipstick | UI/스타일 파일 추가/수정 | 💄 마켓 페이지 CSS 추가 |
| ⏪ | :rewind | 변경 내용 되돌리기 | ⏪ 젬 차감 기능 롤백 |
| 🔀 | :twisted_rightwards_arrows | 브랜치 합병 | 🔀 feat/page와 feat/user 브랜치 합병 |
| 💡 | :bulb | 주석 추가/수정 | 💡 마켓 페이지 주석 추가 |
| 🗃 | :card_file_box | 데이버베이스 관련 수정 | 🗃 사용자 스키마 변경 |

# 🖋️Branch Rule

---

| Branch | Description | Example |
| --- | --- | --- |
| main | 제품으로 출시될 수 있는 브랜치 |  |
| develop | 다음 출시 버전을 개발하는 브랜치 |  |
| feature | 기능 개발 | feature/market-page |
| release | 제품 출시 전 작업 | release/1.0.1 |
| fix | 버그 수정 | fix/gem-error |
| hotfix | 배포 서버 버그 수정 | hotfix/gem-error |
