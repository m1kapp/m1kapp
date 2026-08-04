# m1kapp

> 버려지는 사이드 말고, 가꿔지는 사이드로.

이 저장소는 코드가 아니라 **지도**입니다. m1kapp 아래에서 무엇을 만들었고, 지금 어디서 돌아가고 있는지를 한 장에 모아둡니다. 실제 코드는 각 저장소에 있습니다.

- 홈: **[m1k.app](https://m1k.app)**
- 조직: [github.com/m1kapp](https://github.com/m1kapp)

---

## 만드는 방식

한 줄로 요약하면 **"작게 만들고, 도메인 붙이고, 첫 방문자까지 본다"** 입니다.

| 축 | 내용 |
|---|---|
| 스택 | TypeScript · Next.js / Vite · Vercel |
| 공통 킷 | [`@m1kapp/kit`](https://github.com/m1kapp/kit) — UI · OG · PWA · Fetch · Utils |
| 배포 | 대부분 `*.m1k.app` 서브도메인 |
| 만드는 법 | Claude Code 중심의 바이브코딩 |

---

## 제품 — 지금 돌아가는 것

| 프로젝트 | 하는 일 | 링크 |
|---|---|---|
| **[web](https://github.com/m1kapp/web)** (m1k) | 사이드 프로젝트의 **첫 1,000명 방문자**를 함께 만들어가는 곳. 뱃지 한 줄로 시작. | [m1k.app](https://m1k.app) |
| **[claude-rank](https://github.com/m1kapp/claude-rank)** | Claude 구독 **가성비 랭킹**. 사용량 리포트를 올리면 본전 배율로 줄 세웁니다. | [clauderank.m1k.app](https://clauderank.m1k.app) |
| **[fixearly](https://github.com/m1kapp/fixearly)** | 일찍 고치면 싸다 — 코드가 아니라 *다음에 고칠 때 드는 비용*을 잽니다. JS/TS 정적 분석, 100% 로컬. | [소개](https://m1kapp.github.io/fixearly/) |
| **[logodown](https://github.com/m1kapp/logodown)** | 브랜드 로고를 바로 받아 쓰는 곳. | [logodown.m1k.app](https://logodown.m1k.app) |
| **[maging](https://github.com/m1kapp/maging)** | 엔터프라이즈 리포트 빌더. 대시보드·주간보고·카드뉴스 생성 + 105개 브랜드 테마. CDN 한 줄. | [maging.m1k.app](https://maging.m1k.app) |
| **[promptwing](https://github.com/m1kapp/promptwing)** | 프롬프트 도구. | [promptwing.m1k.app](https://promptwing.m1k.app) |
| **[median-income-calc](https://github.com/m1kapp/median-income-calc)** | 중위소득 계산기. | [바로가기](https://median-income-calc.vercel.app) |

## 도구 · 라이브러리

| 프로젝트 | 하는 일 | 링크 |
|---|---|---|
| **[kit](https://github.com/m1kapp/kit)** | 사이드 프로젝트용 올인원 킷 (UI · OG · PWA · Fetch · Utils). | [npm](https://www.npmjs.com/package/@m1kapp/kit) · [kit.m1k.app](https://kit.m1k.app) |
| **[m1kskills](https://github.com/m1kapp/m1kskills)** | AI 쓰다 유용했던 스킬 모음. 전부 마크다운 프롬프트라 어느 도구에나 붙여넣어 씁니다. | — |
| **[webpilot](https://github.com/m1kapp/webpilot)** (webwing) | API도 MCP도 없는 근태 SaaS를 브라우저 자동화로 감싼 자동 조종석. | — |
| **[stackoverlap](https://github.com/m1kapp/stackoverlap)** | AI 에이전트 시대의 macOS 창 관리. 정렬이 아니라 **의도적 겹침**으로 여러 에이전트를 한 화면에. | — |
| **[flow-mcp](https://github.com/m1kapp/flow-mcp)** | flow 연동 MCP 서버. | — |

## 비공개 — 굽고 있는 것

접근 권한이 있어야 보입니다.

| 프로젝트 | 하는 일 |
|---|---|
| **workspace** | `~/dev/m1kapp` 아래 저장소 목록과 복원 스크립트. 새 맥에서 한 방에 되살립니다. |
| **brandkit** | 공식 로고·색·폰트·대표제품 갤러리 — 복사해서 바로 쓰기. |
| **mcp-feder** | 도메인 페더레이션 MCP. 여러 캘린더를 하나의 정규화된 일정 표면으로 묶는 **머지 계층**. |
| **runner-mate** | 에어팟 끼고 달리면서 대화하는 AI 러닝 메이트. GPS 기반 지역 이야기. |
| **llmrace** (ModelKombat) | "다음 모델 언제 나오냐"를 출시 주기로 역산하는 D-day 카운트다운. |
| **mysheet** | 자연어로 툭 던지면 구글 시트 타임테이블에 반영해주는 CLI. |
| **formychildren** | 유원이의 놀이터 — 아이 생일 선물 키즈 게임. |
| **ytcc-next** | 유튜브 자막 관련 실험. |
| **portyard** | 포트가 아니라 작업을 본다 — 워크트리별 CPU·메모리·포트를 한눈에 보는 로컬 관제실. |

---

## 이 저장소의 규칙

- 여기엔 **제품 코드가 들어오지 않습니다.** 지도와 문서만 둡니다.
- 새 저장소를 만들면 위 표에 한 줄 추가합니다.
- 공개로 전환하거나 접으면, 그 사실도 여기에 반영합니다.

## 라이선스

각 저장소의 라이선스를 따릅니다. 이 저장소의 문서는 자유롭게 인용하셔도 됩니다.
