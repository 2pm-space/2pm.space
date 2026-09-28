<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/ko/agent-builder; edits here are overwritten by the next export. -->

# 비주얼 워크플로 캔버스를 갖춘 AI 에이전트 빌더

> AI 에이전트를 프롬프트 하나로, 또는 워크플로로 만드세요: 검색, 도구, 평가 루프, 사람의 검토, 분기를 위한 16가지 노드 유형. 단계별 로그가 담긴 테스트 실행, 캔버스 버전 관리, 받은편지함·일정·MCP 클라이언트로의 배포까지.

[2pm.space/ko/agent-builder](https://2pm.space/ko/agent-builder) · [English](../agent-builder.md) · [Tiếng Việt](../vi/agent-builder.md) · [中文](../zh/agent-builder.md) · [日本語](../ja/agent-builder.md) · **한국어** · [ไทย](../th/agent-builder.md) · [Français](../fr/agent-builder.md) · [ລາວ](../lo/agent-builder.md)

*에이전트 빌더 · 워크플로 캔버스 · 테스트 실행*

## 일을 실제로 해내는 에이전트, 프롬프트에 답만 하는 게 아니라

프롬프트 하나로 시작하거나, 작업을 워크플로로 그려 보세요: 알맞은 문서를 찾고, 추론하며 도구를 호출하고, 답을 확인하고, 중요한 순간에는 사람에게 묻고, 답합니다. 모든 실행은 각 단계가 무엇을 했는지, 무엇을 썼는지, 왜 그랬는지를 보여줍니다.

[무료로 시작하기](https://2pm.space/signup)

## 아이디어에서 작동하는 에이전트까지, 세 단계

그리고, 장비를 갖추고, 일이 있는 곳에 배치하세요.

1. **작업을 그리세요** — 프롬프트 하나면 Simple을, 검색·추론·확인·분기를 캔버스 위 노드로 좌에서 우로 배치하려면 Agentic을 고르세요.
2. **필요한 것을 갖춰 주세요** — 에이전트나 개별 노드에 도구, 스킬, 지식, 메모리를 연결하고, 모든 메시지가 거쳐 가는 가드레일을 설정하세요.
3. **실전에 투입하세요** — 캔버스에서 테스트한 뒤, 받은편지함 채널, 일정, 도구로 쓰는 다른 에이전트, 또는 MCP 클라이언트에 연결하세요.

## 도구를 곁들인 프롬프트, 그 이상

프롬프트 하나로는 해낼 수 없는 일을 위한 캔버스.

### 심플 또는 에이전틱

심플 에이전트는 시스템 프롬프트로 이루어지는 모델 호출 한 번입니다 — 질문 답변, 번역, 요약에 알맞습니다. 에이전틱 에이전트는 여러 단계와 그 사이의 판단이 필요한 작업을 위한 노드 그래프입니다.

### 열여섯 가지 단계

Agent, Crew, Run Agent, Code, Knowledge Retrieval, Skill Retrieval, Drive Action, Condition, Parallel, Loop, Evaluation, Human Review, Message, Send — 캔버스에 끌어다 놓고 다음 단계로 연결하는 카드입니다.

### 스스로 결과를 확인합니다

Evaluation 노드는 규칙 또는 LLM 판정으로 답변을 채점해 경로를 정합니다: Pass는 다음으로 넘어가고, Retry는 허용한 재시도 횟수까지 에이전트에게 다시 돌려보냅니다.

### 중요한 곳에는 사람이

Human Review 노드는 누군가 승인하거나 거부할 때까지 실행을 멈추고, Message 노드는 흐름이 이어지기 전에 폼이나 버튼으로 고객에게 세부 정보를 물을 수 있습니다.

### 도구, 스킬, 지식

기본 제공 도구 60개, 직접 만든 HTTP API와 Python, MCP 서버, 도구로 쓰는 다른 에이전트까지. 스킬은 모든 프롬프트에 로드되거나 질문이 일치할 때만 로드되므로, 방대한 라이브러리라도 매번 토큰을 소모하지 않습니다.

### 테스트하고, 추적하고, 되돌리세요

캔버스에서 흐름을 실행하고 각 노드의 출력, 토큰, 비용을 확인하세요. 캔버스 버전을 저장해 두면, 변경 사항이 기대에 못 미칠 때 언제든 복원할 수 있습니다.

## 캔버스 위의 모든 것

모든 노드, 모델 카탈로그, 그리고 에이전트가 실행될 수 있는 모든 곳.

### 추론과 실행

- Agent — 추론하고 행동하는 루프 안에서 자체 모델, 프롬프트, 도구를 사용
- Crew — 에이전트와 작업으로 이루어진 CrewAI 크루
- Run Agent — 이미 만든 에이전트를 호출
- Code — 샌드박스에서 실행하는 Python 또는 Bash, LLM 비용 없음

### 흐름 제어

- Start — 메시지가 들어오는 지점
- Condition — 규칙에 따른 분기, LLM 비용 없음
- Parallel — 나가는 모든 분기를 동시에 실행
- Loop와 Exit Loop — 목록을 순회하거나 N번 반복

### 확인과 사람

- Evaluation — 규칙 또는 LLM 판정 후 Pass 또는 Retry
- Human Review — 승인 또는 거부를 위해 일시 정지
- Message — 채팅 메시지, 폼 또는 버튼
- Send — 고객에게 메시지를 보내고 계속 진행

### 지식과 데이터

- Knowledge Retrieval — 시맨틱, 키워드 또는 하이브리드 검색
- Skill Retrieval — LLM 단계 없이 스킬을 매칭
- Drive Action — 문서, 표, 마인드맵, 스토리보드를 생성·읽기·수정
- 대화 사이에도 유지되는 메모리, 그리고 모든 에이전트가 공유하는 워크스페이스 메모리

### 모델

- Anthropic, OpenAI, Google, DeepSeek
- Alibaba Qwen, Z.AI GLM, xAI, MiniMax
- 워크플로당 하나가 아니라, Agent 노드마다 모델 선택
- 워크스페이스 크레딧에서 청구 — 관리할 제공사 키 없음

### 실행되는 곳

- 받은편지함 채널: Messenger, Telegram, 개인 Zalo, 웹사이트 채팅
- 반복 일정에 따른 스케줄러
- 도구로 노출된 다른 에이전트
- Claude Code, Cursor 같은 MCP 클라이언트
- 고객이 보기 전, Playground에서

## 프롬프트 입력창 대 에이전트 빌더

같은 작업을 두 가지 방식으로 만든 결과.

| 2pm.space 없이 | 2pm.space와 함께 |
| --- | --- |
| 프롬프트 하나가 검색, 추론, 확인, 답변을 한꺼번에 처리하려 하고 — 어느 부분이 실패했는지 알 수 없습니다. | 각 작업은 자신만의 노드를 가지며, 실행 로그는 모든 노드가 무엇을 받고, 반환하고, 소모했는지 보여줍니다. |
| 잘못된 답변이 그대로 고객에게 전달됩니다. | Evaluation 노드가 이를 걸러내 아무도 보기 전에 다시 시도하도록 돌려보냅니다. |
| 위험한 작업에는 개발자가 승인 단계를 직접 만들어야 합니다. | 그 앞에 Human Review 노드를 두면, 실행은 승인을 기다립니다. |
| 에이전트를 망가뜨린 변경 사항은 기억에 의존해 처음부터 다시 만들어야 함을 뜻합니다. | 변경 전 캔버스 버전으로 복원하면 됩니다. |

## 에이전트 빌더 관련 질문

첫 워크플로를 만들기 전에 사람들이 묻는 것들.

### 에이전트를 만들려면 코딩이 필요한가요?

아니요. 심플 에이전트는 모델, 프롬프트, 도구를 채우는 폼입니다. 에이전틱 에이전트는 노드를 끌어다 놓고 연결해 캔버스에 그립니다. 코드는 선택 사항입니다 — 모델 없이 처리하고 싶은 단계가 있을 때 Code 노드가 Python이나 Bash를 실행합니다.

### 심플 에이전트와 에이전틱 에이전트는 어떻게 다른가요?

심플 에이전트는 시스템 프롬프트와 연결한 도구, 지식으로 모델을 한 번 호출합니다. 에이전틱 에이전트는 그래프를 실행합니다: 각 노드가 검색, 추론, 확인, 분기, 반복, 사람에게 묻기 중 한 가지 일을 하고, 엣지가 다음에 무엇이 일어날지 정합니다.

### 에이전트는 어떤 모델을 쓸 수 있나요?

카탈로그는 Anthropic, OpenAI, Google, DeepSeek, Alibaba(Qwen), Z.AI(GLM), xAI, MiniMax를 아우르며, 에이전틱 캔버스에서는 Agent 노드마다 각자 모델을 고릅니다. 사용량은 워크스페이스 크레딧에서 결제되므로 관리할 제공사 키가 없습니다.

### 고객이 보기 전에 에이전트를 어떻게 테스트하나요?

캔버스나 Playground에서 실행해 보세요. 모든 실행은 각 단계의 입력, 출력, 토큰, 비용, 도구 호출과 함께 기록되므로, 답변이 어디서 잘못되었는지 확인하고 프롬프트 전체가 아니라 해당 노드만 고칠 수 있습니다.

### 여러 사람이 같은 에이전트를 함께 편집할 수 있나요?

네. 캔버스는 실시간으로 동기화되어 누가 함께 편집 중인지 보여주고, 캔버스 버전을 통해 잘 작동하던 상태를 저장해 두었다가 나중에 복원할 수 있습니다.

### 에이전트를 만들고 나면 어디서 실행할 수 있나요?

받은편지함 채널(Messenger, Telegram, 개인 Zalo, 웹사이트 채팅)에서, 일정에 따라, 다른 에이전트가 호출하는 도구로, 또는 Claude Code나 Cursor 같은 MCP 클라이언트에서 실행할 수 있습니다.

## 에이전트를 만드세요 실제 업무에 필요한

프롬프트 하나로 시작하세요. 작업이 요구하면 워크플로로 키워 가세요.

[무료로 시작하기](https://2pm.space/signup) · [문의하기](contact.md)

---

**제품**

- [AI Inbox](ai-inbox.md) — Messenger, Telegram, 웹사이트 채팅, 개인 Zalo를 하나의 대기열에서
- [Live Chat](live-chat.md) — 내 웹사이트에 설치하는 AI 채팅 위젯
- [Customer 360](customer-360.md) — 모든 채널을 아우르는 하나의 고객 기록
- [Ask Data](ask-data.md) — 일상 언어로 데이터베이스에 질문하기
- [BI 대시보드](bi-dashboards.md) — 일상 언어 질문에서 고정한 보드
- [Content Calendar](content-calendar.md) — 기획, 작성, 이미지 제작, 게시까지
- [Brand Kit](brand-kit.md) — 모든 작성자를 위한 보이스, 디자인, 지식
- [Magic Studio](magic-studio.md) — 단계별 캔버스에서 만드는 브랜드 맞춤 AI 이미지
- [Storyboard](storyboard.md) — 대본에서 샷, 렌더링된 클립까지
- [Mind Map](mind-map.md) — 무료 실시간 마인드맵, 무제한
- [모바일 앱](mobile-app.md)

**플랫폼**

- [에이전트 빌더](agent-builder.md) — 검색하고, 실행하고, 확인하는 워크플로 에이전트
- [도구 카탈로그](tools.md) — 기본 제공 도구 60개, 직접 만든 API, MCP
- [스케줄러](scheduler.md) — 일정에 따라 실행되는 에이전트
- [연동](integrations.md) — 채널, API, 데이터베이스, MCP
- [MCP 서버](mcp-server.md) — Claude Code나 Cursor에서 워크스페이스 작업하기
- [Fine-Tuning](fine-tuning.md) — 내 대화 데이터로 모델 학습
- [보안](security.md) — 역할, 공유, 감사 로그, 백업
- [요금제](pricing.md)

**회사**

- [문의](contact.md)
- [개인정보처리방침](https://2pm.space/privacy-policy)
- [계정 삭제](https://2pm.space/delete-account)
