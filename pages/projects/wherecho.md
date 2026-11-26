# 어디초

요약: 초1 하교 후 우리 집 일정을 한눈에 짜고 확인하는 서비스. 시간표 생성이 첫 화면이다.
갱신: 2026-11-27 · 서비스: https://wherecho.co.kr · 코드: https://github.com/Sean-Kang-jpg/elementary

## 기본 방향 (Brief)
- **브랜드 축:** [[concepts/after-school-schedule]] ('학교 찾기'에서 전환)
- **1차 타겟:** [[concepts/wherecho-target]]
- **풀려는 문제:** 하교, 방과후, 돌봄, 학원 정보가 흩어져 있어서, 우리 집이 무엇을 확인하고 결정해야 하는지 모르는 상태
- **주려는 감정:** 공감 → 다음에 할 일이 보이는 안도감 → 우리 가족도 준비할 수 있다는 자신감
- **연계 제품:** [[projects/smart-friends]]

## 주요 결정
- [[decisions/2026-11-27-timetable-ui-redesign]]
- [[decisions/2026-11-27-remotion-content]]
- [[decisions/2026-11-27-brand-axis]]
- [[decisions/2026-11-26-home-timetable-first]]
- [[decisions/2026-11-26-data-enrichment-by-demand]]

## 로드맵
**지금**
- 시간표 입력 UI/UX 전면 개선: 1차 시안 반려 후 2차 시안 진행 (#23, SW 개발)
- 수요가 확인된 학교의 일정 보강: GA4 학교별 수요 확인 후 최대 5개교 (#3)
- Remotion 시연 콘텐츠: 제작 방식 채택 여부 (콘텐츠 제작)

**다음**
- 인스타그램 시간표 유입 실험: 게시물별 링크로 유입 → 시간표 시작 → 첫 일정 추가 비교 (#4)
- 인근 학원 조사: 도보권부터 (#5)
- 스마트 프렌즈 PoC 요구사항 (HW 제품 + SW 개발)

**나중**
- 수요 기반 학교 데이터 일배치 (#12): GA4 읽기 인증 준비 후

## 관련
- [[entities/benchmark-apps]]
- [[concepts/content-principles]]
- [[entities/bots]]
