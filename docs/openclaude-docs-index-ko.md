# OpenClaude 문서 인덱스

## 1. 문서 개요

이 문서는 OpenClaude 한국어 문서 세트의 진입점이다. 기능 정의, 운영 절차, QA 검증, API/연동, 화면 기획 문서를 역할별로 빠르게 찾을 수 있도록 정리한다.

## 2. 문서 목록

| 문서명 | 파일 | 대상 독자 | 활용 목적 |
|---|---|---|---|
| 종합 기능 명세서 | [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md) | 기획, 개발, QA, 운영 | 전체 기능 정의와 설계 기준 확인 |
| 운영 매뉴얼 | [openclaude-operations-manual-ko.md](D:/project/openclaude/docs/openclaude-operations-manual-ko.md) | 운영, 개발, 고객지원 | 실제 사용 절차와 장애 대응 |
| QA 테스트 케이스 | [openclaude-qa-test-cases-ko.md](D:/project/openclaude/docs/openclaude-qa-test-cases-ko.md) | QA, 개발 | 기능 검증 시나리오 수행 |
| QA Import CSV | [openclaude-qa-test-cases-import-ko.csv](D:/project/openclaude/docs/openclaude-qa-test-cases-import-ko.csv) | QA, 운영도구 관리자 | 엑셀/테스트관리도구 업로드 |
| API/연동 명세 | [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md) | 개발, 운영 | 외부 시스템 연동 설계와 장애 분석 |
| 화면별 상세 기획서 | [openclaude-screen-spec-ko.md](D:/project/openclaude/docs/openclaude-screen-spec-ko.md) | 기획, 디자인, 개발, QA | 화면 단위 UX/상태/검증 기준 확인 |

## 3. 역할별 추천 읽기 순서

### 3.1 기획자

1. 종합 기능 명세서
2. 화면별 상세 기획서
3. 운영 매뉴얼

### 3.2 개발자

1. 종합 기능 명세서
2. API/연동 명세
3. 화면별 상세 기획서
4. QA 테스트 케이스

### 3.3 QA

1. 종합 기능 명세서
2. QA 테스트 케이스
3. QA Import CSV
4. 운영 매뉴얼

### 3.4 운영/고객지원

1. 운영 매뉴얼
2. 종합 기능 명세서
3. API/연동 명세

## 4. 문서 간 관계

| 기준 문서 | 파생 문서 | 관계 설명 |
|---|---|---|
| 종합 기능 명세서 | 운영 매뉴얼 | 기능 정의를 실제 운영 절차로 변환 |
| 종합 기능 명세서 | QA 테스트 케이스 | 기능별 검증 포인트를 테스트 케이스로 구체화 |
| 종합 기능 명세서 | API/연동 명세 | 외부 시스템 통신만 분리 정리 |
| 종합 기능 명세서 | 화면별 상세 기획서 | 대화형/설정형 UI를 화면 기준으로 재구성 |
| QA 테스트 케이스 | QA Import CSV | 동일 케이스를 테스트관리도구 적재 형식으로 평탄화 |

## 5. 문서 유지보수 원칙

- 기능 변경 시 가장 먼저 종합 기능 명세서를 갱신한다.
- UI 변경 시 화면별 상세 기획서를 함께 수정한다.
- 외부 연동 정책, 인증, timeout, retry 변경 시 API/연동 명세를 갱신한다.
- 회귀 테스트 범위가 바뀌면 QA 테스트 케이스와 CSV를 동시에 갱신한다.
- 운영 절차가 바뀌면 운영 매뉴얼과 고객지원 템플릿을 함께 수정한다.

## 6. 변경 시 우선 점검 문서

| 변경 유형 | 우선 수정 문서 |
|---|---|
| 신규 슬래시 명령 추가 | 종합 기능 명세서, 화면별 상세 기획서, QA 테스트 케이스 |
| 인증 방식 변경 | 종합 기능 명세서, API/연동 명세, 운영 매뉴얼 |
| 설정 화면 변경 | 화면별 상세 기획서, 운영 매뉴얼, QA 테스트 케이스 |
| MCP/플러그인 구조 변경 | 종합 기능 명세서, API/연동 명세, 운영 매뉴얼 |
| 배경 작업/스케줄링 변경 | 종합 기능 명세서, 운영 매뉴얼, QA 테스트 케이스 |
