# 다독임 문서 안내

## 현재 상태

- 프로젝트: `다독임`
- GitHub 저장소: `https://github.com/SujinHuh/dadogim`
- 로컬 작업 범위: `/Users/huhsujin/Documents/Playground/개인프로젝트/다독임`만 기본 대상으로 사용
- 제품 관계: `inside-me`와 별개
- 핵심 기능: A. 수면 유도 소리, B. 긍정 확언, C. 멍 때리기 소리
- 진행 순서: `C → B → A`
- 현재 단계: C 요구사항 구체화
- 요구사항 완료 상태: `미완성`. `open-questions.md`가 미확정 사항의 임시 단일 목록이다.
- 최근 확정: C에서 `원하는 느낌으로 빠르게 추천받기`와 `전체 소리에서 직접 고르기`를 모두 제공한다.
- 앱 내부 구조: `기능 중심 폴더 + MVVM식 역할 분리 + 단방향 상태 흐름` (사용자 확정)
- 현재 정리: C·B·A·공통·기술·비기능·시장 검증의 미확정 사항을 식별 가능한 체크리스트로 분리했다.
- 비관적 검수 결과: 요구사항은 아직 완성되지 않았으며, 미확정 항목을 확정 요구사항이나 구현 기준으로 사용할 수 없다.
- 시장 조사: 초기 경쟁 서비스 기능 조사 완료. 정량 시장·실사용 수요 검증은 미수행이다.
- 현재 결정 질문: C의 첫 버전에 넣을 소리 3~5개 — DEC-022에 따라 논의 재개

## 필요한 문서만 읽기

| 작업 | 우선으로 읽을 문서 |
| --- | --- |
| 제품 요구사항 논의 | `requirements.md`의 관련 기능 섹션 |
| 현재 미확정 항목 선택 | `open-questions.md`의 `현재 질문`만 |
| 경쟁 제품·차별화 확인 | `market-research.md`의 비관적 판단과 권장 방향 |
| 기존 결정 확인 | `decision-log.md`에서 관련 DEC 번호 검색 |
| 최근 실제 변경 확인 | `change-log.md`의 마지막 CHG 항목 |
| PR 작성·크기·검증 기준 | `pull-request-guide.md` |
| 개발·병렬화·리뷰·GitHub·CI/CD | `development-workflow.md`의 관련 섹션 |
| 전체 이력 감사 | 위 문서 전체 |

## 토큰 효율적인 문서 작성 규칙

- 불변 지침은 `AGENTS.md`, 현재 상태는 이 문서, 확정 요구사항은 `requirements.md`, 미확정 질문은 `open-questions.md`, 이력은 로그에 한 번씩만 쓴다.
- 제목과 DEC/CHG ID를 사용해 전체 문서 대신 필요한 부분만 검색할 수 있게 한다.
- 원문 대화, 전체 터미널 출력, 중복 배경 설명을 복사하지 않고 `결론 + 근거 + 영향 + 재검토 조건`만 남긴다.
- 출처는 주장 가까이 한 번 링크하고, 같은 링크를 여러 로그에 반복하지 않는다.
- 문서가 커지면 서술을 지우기보다 상태 요약과 본문을 분리하고, 기본 작업에서는 요약만 읽는다.

## 관련 공식 근거

- [Custom instructions with AGENTS.md](https://learn.chatgpt.com/docs/agent-configuration/agents-md)
- [OpenAI model guidance: leaner prompts](https://developers.openai.com/api/docs/guides/latest-model)
- [Codex subagents](https://learn.chatgpt.com/docs/agent-configuration/subagents)
- [Automating repetitive work at OpenAI with Codex](https://developers.openai.com/blog/automating-repetitive-work-at-openai-with-codex)
