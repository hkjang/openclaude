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
| Provider 기능 비교 매트릭스 | [openclaude-provider-matrix-ko.md](D:/project/openclaude/docs/openclaude-provider-matrix-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, DevOps, QA | provider 선택 규칙, transport, 인증, first-party 전용 기능 차이를 표 중심으로 정리 |
| Request Lifecycle 시퀀스 가이드 | [openclaude-request-lifecycle-guide-ko.md](D:/project/openclaude/docs/openclaude-request-lifecycle-guide-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, QA | 사용자 입력 1회가 query, compact, tool loop, transcript 저장까지 어떻게 흐르는지 정리 |
| 세션 저장소 / Transcript 가이드 | [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md) | 개발, 플랫폼 엔지니어, QA, 운영 | JSONL transcript, sidechain, session memory, resume 복원 구조를 저장소 관점에서 정리 |
| 변경 영향도 맵 | [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md) | 개발, 플랫폼 엔지니어, QA, DevOps | 핵심 모듈 수정 시 같이 봐야 하는 코드, 문서, 회귀 범위를 영향도 관점에서 정리 |
| 서버 기동 가이드 | [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md) | 개발, 플랫폼 엔지니어, DevOps, QA | direct connect 서버 기동 방법, 연결 방식, remote-control과의 차이, 보안 주의사항 정리 |
| Feature Flag / 빌드 가이드 | [openclaude-feature-flag-build-guide-ko.md](D:/project/openclaude/docs/openclaude-feature-flag-build-guide-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, DevOps | 오픈 빌드에서 feature gate가 어떻게 제거되는지, 내부 기능과 공개 기능이 어떻게 갈리는지 정리 |
| 릴리즈 / 패키징 / 포크 유지보수 가이드 | [openclaude-release-packaging-fork-guide-ko.md](D:/project/openclaude/docs/openclaude-release-packaging-fork-guide-ko.md) | 개발, 플랫폼 엔지니어, DevOps, 유지보수자 | npm 패키징, build macro, 실행 파일, legacy `claude` naming 잔존 지점을 릴리즈 관점에서 정리 |
| Remote Control / Bridge 가이드 | [openclaude-remote-control-bridge-guide-ko.md](D:/project/openclaude/docs/openclaude-remote-control-bridge-guide-ko.md) | 개발, 플랫폼 엔지니어, DevOps, QA | remote-control 구조, standalone/REPL 경로, bridge 세션 API, server와의 차이 정리 |
| 인증 / 자격증명 가이드 | [openclaude-auth-credential-guide-ko.md](D:/project/openclaude/docs/openclaude-auth-credential-guide-ko.md) | 개발, AI 엔지니어, 플랫폼 엔지니어, 운영 | provider별 인증 소스, OAuth/API key 우선순위, auth.json/secure storage 동작 정리 |
| 환경변수 / 설정 키 레퍼런스 | [openclaude-env-settings-reference-ko.md](D:/project/openclaude/docs/openclaude-env-settings-reference-ko.md) | 개발, 플랫폼 엔지니어, DevOps, 운영 | settings 소스 우선순위, 주요 settings.json 키, 핵심 환경변수 사용 기준 정리 |
| 명령어 실전 가이드 | [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md) | 개발, QA, 운영 | REPL slash command, CLI flags, subcommand, feature-gated 명령 구조와 사용 시나리오 정리 |
| 권한 / 보안 매트릭스 | [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md) | 개발, 플랫폼 엔지니어, QA, 운영 | 권한 모드, 경로 보호, 관리형 정책, remote 제약을 표 중심으로 정리 |
| 오류 메시지 카탈로그 | [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md) | 개발, QA, 운영, DevOps | 실제 사용자 노출 오류와 내부 분류, 1차 대응 경로를 카탈로그 형식으로 정리 |
| 트러블슈팅 가이드 | [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md) | 개발, QA, 운영, DevOps | 빌드/인증/네트워크/remote-control/server 증상을 기준으로 빠른 대응 경로 정리 |
| MCP 운영 가이드 | [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md) | 개발, 플랫폼 엔지니어, QA, 운영, DevOps | MCP scope, 상태값, OAuth, doctor, 정책 필터, 재연결 흐름을 운영 기준으로 정리 |
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
7. [openclaude-provider-matrix-ko.md](D:/project/openclaude/docs/openclaude-provider-matrix-ko.md)
8. [openclaude-request-lifecycle-guide-ko.md](D:/project/openclaude/docs/openclaude-request-lifecycle-guide-ko.md)
9. [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md)
10. [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md)
11. [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)
12. [openclaude-feature-flag-build-guide-ko.md](D:/project/openclaude/docs/openclaude-feature-flag-build-guide-ko.md)
13. [openclaude-release-packaging-fork-guide-ko.md](D:/project/openclaude/docs/openclaude-release-packaging-fork-guide-ko.md)
14. [openclaude-auth-credential-guide-ko.md](D:/project/openclaude/docs/openclaude-auth-credential-guide-ko.md)
15. [openclaude-env-settings-reference-ko.md](D:/project/openclaude/docs/openclaude-env-settings-reference-ko.md)
16. [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md)
17. [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md)
18. [openclaude-remote-control-bridge-guide-ko.md](D:/project/openclaude/docs/openclaude-remote-control-bridge-guide-ko.md)
19. [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md)
20. [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)
21. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
22. [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md)
23. [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md)
24. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
25. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)

### 3.3 AI 엔지니어 / 플랫폼 엔지니어

1. [coding-agent-architecture-spec-ko.md](D:/project/openclaude/docs/coding-agent-architecture-spec-ko.md)
2. [coding-agent-flow-security-spec-ko.md](D:/project/openclaude/docs/coding-agent-flow-security-spec-ko.md)
3. [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)
4. [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md)
5. [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)
6. [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md)
7. [openclaude-provider-matrix-ko.md](D:/project/openclaude/docs/openclaude-provider-matrix-ko.md)
8. [openclaude-request-lifecycle-guide-ko.md](D:/project/openclaude/docs/openclaude-request-lifecycle-guide-ko.md)
9. [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md)
10. [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md)
11. [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)
12. [openclaude-feature-flag-build-guide-ko.md](D:/project/openclaude/docs/openclaude-feature-flag-build-guide-ko.md)
13. [openclaude-release-packaging-fork-guide-ko.md](D:/project/openclaude/docs/openclaude-release-packaging-fork-guide-ko.md)
14. [openclaude-auth-credential-guide-ko.md](D:/project/openclaude/docs/openclaude-auth-credential-guide-ko.md)
15. [openclaude-env-settings-reference-ko.md](D:/project/openclaude/docs/openclaude-env-settings-reference-ko.md)
16. [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md)
17. [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md)
18. [openclaude-remote-control-bridge-guide-ko.md](D:/project/openclaude/docs/openclaude-remote-control-bridge-guide-ko.md)
19. [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md)
20. [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)
21. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
22. [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md)
23. [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md)
24. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)

### 3.4 QA

1. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
2. [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)
3. [index-ko.md](D:/project/openclaude/docs/src-folders/index-ko.md)
4. [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)
5. [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md)
6. [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md)
7. [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)
8. [openclaude-request-lifecycle-guide-ko.md](D:/project/openclaude/docs/openclaude-request-lifecycle-guide-ko.md)
9. [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md)
10. [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md)
11. [openclaude-qa-test-cases-ko.md](D:/project/openclaude/docs/openclaude-qa-test-cases-ko.md)
12. [openclaude-qa-test-cases-import-ko.csv](D:/project/openclaude/docs/openclaude-qa-test-cases-import-ko.csv)
13. [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md)
14. [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md)
15. [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md)

### 3.5 운영 / 고객지원

1. [openclaude-overview-ko.md](D:/project/openclaude/docs/openclaude-overview-ko.md)
2. [openclaude-operations-manual-ko.md](D:/project/openclaude/docs/openclaude-operations-manual-ko.md)
3. [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)
4. [openclaude-api-integration-spec-ko.md](D:/project/openclaude/docs/openclaude-api-integration-spec-ko.md)
5. [openclaude-env-settings-reference-ko.md](D:/project/openclaude/docs/openclaude-env-settings-reference-ko.md)
6. [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md)
7. [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md)
8. [openclaude-provider-matrix-ko.md](D:/project/openclaude/docs/openclaude-provider-matrix-ko.md)
9. [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md)
10. [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md)
11. [openclaude-release-packaging-fork-guide-ko.md](D:/project/openclaude/docs/openclaude-release-packaging-fork-guide-ko.md)
12. [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md)
13. [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md)
14. [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md)

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
| 변경 영향도 맵 | 코드 레퍼런스, QA, 운영 문서 | 특정 파일 변경 시 같이 봐야 하는 모듈, 문서, 회귀 범위를 연결 |
| 릴리즈 / 패키징 / 포크 유지보수 가이드 | Feature Flag / 빌드 가이드, 트러블슈팅 가이드 | npm 패키징과 build macro, 실행 파일, legacy naming 잔존 지점을 운영 관점으로 연결 |

## 5. 유지보수 원칙

- 기능이 바뀌면 먼저 [openclaude-functional-spec-ko.md](D:/project/openclaude/docs/openclaude-functional-spec-ko.md)를 갱신합니다.
- 실제 폴더 구조나 대표 진입 파일, 모듈 책임이 바뀌면 [openclaude-src-folder-reference-ko.md](D:/project/openclaude/docs/openclaude-src-folder-reference-ko.md)를 갱신합니다.
- 특정 최상위 폴더 내부 구조가 달라지면 대응하는 `docs/src-folders/*.md`도 함께 갱신합니다.
- `commands`, `services`, `tools`, `utils` 하위 폴더 구조가 달라지면 [index-ko.md](D:/project/openclaude/docs/src-subfolders/index-ko.md)와 대응하는 `docs/src-subfolders/<group>/*.md`를 함께 갱신합니다.
- provider 선택 규칙, shim 구조, bootstrap/files/session ingress 같은 API 구현 규칙이 바뀌면 [openclaude-api-guide-ko.md](D:/project/openclaude/docs/openclaude-api-guide-ko.md)를 갱신합니다.
- provider 판정 우선순위, transport 분기, first-party 전용 기능 범위가 바뀌면 [openclaude-provider-matrix-ko.md](D:/project/openclaude/docs/openclaude-provider-matrix-ko.md)를 갱신합니다.
- query 루프의 단계 순서, compact 파이프라인, tool loop, transcript 저장 흐름이 바뀌면 [openclaude-request-lifecycle-guide-ko.md](D:/project/openclaude/docs/openclaude-request-lifecycle-guide-ko.md)를 갱신합니다.
- transcript 파일 경로, Entry 타입, sidechain 저장, resume 복원 규칙이 바뀌면 [openclaude-session-transcript-storage-guide-ko.md](D:/project/openclaude/docs/openclaude-session-transcript-storage-guide-ko.md)를 갱신합니다.
- 핵심 모듈의 결합 구조나 변경 시 회귀 범위 판단 기준이 바뀌면 [openclaude-change-impact-map-ko.md](D:/project/openclaude/docs/openclaude-change-impact-map-ko.md)를 갱신합니다.
- direct connect server, `cc://` 연결 흐름, `remote-control` 구분 기준이 바뀌면 [openclaude-server-mode-guide-ko.md](D:/project/openclaude/docs/openclaude-server-mode-guide-ko.md)를 갱신합니다.
- build-time feature gate와 open build stub 정책이 바뀌면 [openclaude-feature-flag-build-guide-ko.md](D:/project/openclaude/docs/openclaude-feature-flag-build-guide-ko.md)를 갱신합니다.
- 패키지명, bin, build macro, update/install/doctor 브랜딩 또는 legacy `claude` naming 잔존 지점이 바뀌면 [openclaude-release-packaging-fork-guide-ko.md](D:/project/openclaude/docs/openclaude-release-packaging-fork-guide-ko.md)를 갱신합니다.
- bridge 구조, `remote-control` standalone/REPL 흐름, env-based vs env-less 경로가 바뀌면 [openclaude-remote-control-bridge-guide-ko.md](D:/project/openclaude/docs/openclaude-remote-control-bridge-guide-ko.md)를 갱신합니다.
- provider별 인증 우선순위, OAuth/API key 선택 규칙, Codex/GitHub credential 해석이 바뀌면 [openclaude-auth-credential-guide-ko.md](D:/project/openclaude/docs/openclaude-auth-credential-guide-ko.md)를 갱신합니다.
- settings 소스 우선순위, `settings.json` 상위 키, 운영용 환경변수 기준이 바뀌면 [openclaude-env-settings-reference-ko.md](D:/project/openclaude/docs/openclaude-env-settings-reference-ko.md)를 갱신합니다.
- REPL slash command, CLI flag, subcommand, feature-gated 명령 노출 규칙이 바뀌면 [openclaude-command-cookbook-ko.md](D:/project/openclaude/docs/openclaude-command-cookbook-ko.md)를 갱신합니다.
- 권한 모드, safety check, 위험 경로 보호, 관리형 권한 정책이 바뀌면 [openclaude-permission-security-matrix-ko.md](D:/project/openclaude/docs/openclaude-permission-security-matrix-ko.md)를 갱신합니다.
- 플러그인 구조, manifest 스키마, 훅 실행 규칙이 바뀌면 [openclaude-plugin-hook-guide-ko.md](D:/project/openclaude/docs/openclaude-plugin-hook-guide-ko.md)를 갱신합니다.
- 메모리, 세션 유지, compact, resume 구조가 바뀌면 [openclaude-memory-context-compaction-ko.md](D:/project/openclaude/docs/openclaude-memory-context-compaction-ko.md)를 갱신합니다.
- 사용자 노출 오류 메시지, API 오류 분류, MCP/plugin/update 오류 카탈로그가 바뀌면 [openclaude-error-catalog-ko.md](D:/project/openclaude/docs/openclaude-error-catalog-ko.md)를 갱신합니다.
- MCP scope 우선순위, OAuth 흐름, doctor 결과, policy 필터, reconnect 규칙이 바뀌면 [openclaude-mcp-operations-guide-ko.md](D:/project/openclaude/docs/openclaude-mcp-operations-guide-ko.md)를 갱신합니다.
- 빌드/인증/네트워크/remote-control/server 장애 분류 기준이 바뀌면 [openclaude-troubleshooting-guide-ko.md](D:/project/openclaude/docs/openclaude-troubleshooting-guide-ko.md)를 갱신합니다.
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
| 설정/환경변수 우선순위 변경 | 환경변수 / 설정 키 레퍼런스, 인증 / 자격증명 가이드 |
| 명령 표면 변경 | 명령어 실전 가이드, 트러블슈팅 가이드 |
| 권한 모드 또는 민감 경로 정책 변경 | 권한 / 보안 매트릭스, 운영 매뉴얼 |
