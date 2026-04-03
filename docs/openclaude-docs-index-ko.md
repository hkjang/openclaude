# OpenClaude 문서 인덱스

## 1. 문서 개요

이 문서는 OpenClaude 한국어 문서 묶음의 진입점입니다.  
기능 정의, 아키텍처, 메모리와 컨텍스트 압축, 운영 절차, QA 검증, API 연동, 화면 기획 문서를 역할별로 빠르게 찾을 수 있도록 정리합니다.

## 2. 문서 목록

| 문서명 | 파일 | 주요 독자 | 사용 목적 |
|---|---|---|---|
| 제품 개요 | [openclaude-overview-ko.md](D:/project/openclaude/docs/openclaude-overview-ko.md) | 전체 독자 | 제품 구조와 문서 체계를 빠르게 파악 |
| 종합 기능 명세서 | [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md) | 기획, 개발, QA, 운영 | 전체 기능 정의와 동작 기준 확인 |
| `src` 폴더 코드 레퍼런스 | [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | `src` 전체 폴더 구조와 대표 엔트리 파일, 책임 범위 파악 |
| `src` 폴더별 문서 인덱스 | [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | `src` 최상위 폴더별 개별 문서 진입점 |
| `commands/services/tools/utils` 하위 폴더 문서 인덱스 | [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | `commands`, `services`, `tools`, `utils` 하위 폴더별 상세 문서 진입점 |
| API 가이드 | [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | provider 선택, 요청 변환, 스트리밍, 재시도, files/session API를 소스 기준으로 정리 |
| 서버 기동 가이드 | [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md) | 개발, 플랫폼 엔지니어, DevOps, QA | direct connect 서버 기동 방법, 연결 방식, remote-control과의 차이, 보안 주의사항 정리 |
| 플러그인 및 훅 추가 가이드 | [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | 플러그인 구조, 훅 실행 방식, 추가 절차, 디버깅 포인트를 소스 기준으로 정리 |
| 메모리/컨텍스트 압축 상세 설계 | [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | 메모리 계층, session memory, compact, resume 복원 구조 파악 |
| 코딩 에이전트 아키텍처 명세 | [coding-agent-architecture-spec-ko.md](D:/project/openclaude/docs/coding-agent-architecture-spec-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어 | 코딩 에이전트 공통 구조와 내부 모듈 설계 기준 |
| 코딩 에이전트 흐름/보안 명세 | [coding-agent-flow-security-spec-ko.md](D:/project/openclaude/docs/coding-agent-flow-security-spec-ko.md) | 개발, 플랫폼 엔지니어, DevOps, QA | 데이터 흐름, 보안, 오류 처리, 로그 기준 |
| API/연동 명세 | [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md) | 개발, 운영 | 외부 연동 구조, 요청/응답, 실패 처리 기준 |
| 화면별 상세 기획서 | [openclaude-screen-spec-ko.md](D:/project/openclaude/docs/openclaude-screen-spec-ko.md) | 기획, 디자이너, 개발, QA | 화면 단위 UX, 상태, 검증 기준 확인 |
| 운영 매뉴얼 | [openclaude-operations-manual-ko.md](D:/project/openclaude/docs/openclaude-operations-manual-ko.md) | 운영, 개발, 고객지원 | 실제 운영 절차와 대응 기준 |
| QA 테스트 케이스 | [openclaude-qa-test-cases-ko.md](D:/project/openclaude/docs/openclaude-qa-test-cases-ko.md) | QA, 개발 | 기능별 검증 시나리오 수행 |
| QA Import CSV | [openclaude-qa-test-cases-import-ko.csv](D:/project/openclaude/docs/openclaude-qa-test-cases-import-ko.csv) | QA 도구 관리자 | 테스트 관리 도구 적재용 데이터 |

## 3. 역할별 추천 읽기 순서

### 3.1 기획자

1. [openclaude-overview-ko.md](D:/project/openclaude/docs/openclaude-overview-ko.md)
2. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
3. [openclaude-screen-spec-ko.md](D:/project/openclaude/docs/openclaude-screen-spec-ko.md)
4. [openclaude-operations-manual-ko.md](D:/project/openclaude/docs/openclaude-operations-manual-ko.md)

### 3.2 개발자

1. [coding-agent-architecture-spec-ko.md](D:/project/openclaude/docs/coding-agent-architecture-spec-ko.md)
2. [coding-agent-flow-security-spec-ko.md](D:/project/openclaude/docs/coding-agent-flow-security-spec-ko.md)
3. [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)
4. [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md)
5. [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)
6. [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md)
7. [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)
8. [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)
9. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
10. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
11. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)

### 3.3 AI 엔지니어 / 플랫폼 엔지니어

1. [coding-agent-architecture-spec-ko.md](D:/project/openclaude/docs/coding-agent-architecture-spec-ko.md)
2. [coding-agent-flow-security-spec-ko.md](D:/project/openclaude/docs/coding-agent-flow-security-spec-ko.md)
3. [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)
4. [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md)
5. [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)
6. [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md)
7. [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)
8. [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)
9. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
10. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)

### 3.4 QA

1. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
2. [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)
3. [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md)
4. [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)
5. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
6. [openclaude-qa-test-cases-ko.md](D:/project/openclaude/docs/openclaude-qa-test-cases-ko.md)
7. [openclaude-qa-test-cases-import-ko.csv](D:/project/openclaude/docs/openclaude-qa-test-cases-import-ko.csv)

### 3.5 운영 / 고객지원

1. [openclaude-overview-ko.md](D:/project/openclaude/docs/openclaude-overview-ko.md)
2. [openclaude-operations-manual-ko.md](D:/project/openclaude/docs/openclaude-operations-manual-ko.md)
3. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
4. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)

## 4. 문서 간 관계

| 기준 문서 | 파생 문서 | 관계 설명 |
|---|---|---|
| 제품 개요 | 전체 문서 세트 | 전체 문서의 역할과 읽기 순서 안내 |
| 종합 기능 명세서 | 운영 매뉴얼 | 기능 정의를 실제 운영 절차로 변환 |
| 종합 기능 명세서 | QA 테스트 케이스 | 기능 정의를 검증 시나리오로 분해 |
| 종합 기능 명세서 | API/연동 명세 | 외부 통신 관점으로 상세화 |
| 종합 기능 명세서 | 화면별 상세 기획서 | 화면 UX와 상태 설계로 세분화 |
| `src` 폴더 코드 레퍼런스 | 기능 명세서, 메모리/컨텍스트 압축 상세 설계 | 실제 구현 폴더와 진입 파일 관점에서 코드 탐색을 보조 |
| `src` 폴더별 문서 인덱스 | 각 최상위 폴더 문서 | 특정 폴더의 코드 구조를 개별 문서로 탐색 |
| 코딩 에이전트 아키텍처 명세 | 흐름/보안 명세 | 아키텍처를 데이터 흐름, 보안, 예외 처리 관점으로 분리 |
| 메모리/컨텍스트 압축 상세 설계 | 기능 명세, 운영 매뉴얼, QA | 메모리와 compact 관련 구현 및 검증 기준 보강 |

## 5. 유지보수 원칙

- 기능이 바뀌면 먼저 [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)를 갱신합니다.
- 실제 폴더 구조나 대표 진입 파일, 모듈 책임이 바뀌면 [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)를 갱신합니다.
- 특정 최상위 폴더 내부 구조가 달라지면 대응하는 `docs/src-folders/*.md`도 함께 갱신합니다.
- `commands`, `services`, `tools`, `utils` 하위 폴더 구조가 달라지면 [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)와 대응하는 `docs/src-subfolders/<group>/*.md`를 함께 갱신합니다.
- provider 선택 규칙, shim 구조, bootstrap/files/session ingress 같은 API 구현 규칙이 바뀌면 [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md)를 갱신합니다.
- direct connect server, `cc://` 연결 흐름, `remote-control` 구분 기준이 바뀌면 [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)를 갱신합니다.
- 플러그인 구조, manifest 스키마, 훅 실행 규칙이 바뀌면 [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)를 갱신합니다.
- 메모리, 세션 유지, compact, resume 구조가 바뀌면 [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)를 갱신합니다.
- 아키텍처나 실행 흐름이 바뀌면 코딩 에이전트 아키텍처/흐름 문서를 함께 갱신합니다.
- UI 변경이 있으면 화면별 상세 기획서를 갱신합니다.
- 운영 절차나 장애 대응 기준이 바뀌면 운영 매뉴얼을 갱신합니다.
- 테스트 범위가 바뀌면 QA 문서와 CSV를 함께 갱신합니다.

## 6. 변경 유형별 우선 갱신 문서

| 변경 유형 | 우선 수정 문서 |
|---|---|
| 새 기능 추가 | 종합 기능 명세서, 화면별 상세 기획서, QA 테스트 케이스 |
| 폴더 구조/모듈 책임 변경 | `src` 폴더 코드 레퍼런스, 코딩 에이전트 아키텍처 명세 |
| 메모리/세션/compact 변경 | 메모리/컨텍스트 압축 상세 설계, 기능 명세서, QA 테스트 케이스 |
| 권한/보안 정책 변경 | 흐름/보안 명세, 운영 매뉴얼 |
| API 계약 변경 | API/연동 명세, 기능 명세서 |
| 운영 절차 변경 | 운영 매뉴얼, 기능 명세서 |
| 내부 아키텍처 리팩토링 | 코딩 에이전트 아키텍처 명세, 흐름/보안 명세 |
