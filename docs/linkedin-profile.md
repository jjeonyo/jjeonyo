# LinkedIn 프로필 초안 · 전효준 (Hyojun Jeon)

> 출처: 이 저장소의 `README.md`에 기재된 사실만 사용했습니다.
> 추측으로 채운 내용은 없으며, 확인이 필요한 항목은 문서 하단 **확인 필요 항목**에 모았습니다.
> 각 섹션을 LinkedIn 해당 칸에 그대로 붙여넣으면 됩니다.

---

## 1. Headline (헤드라인 · 220자 제한)

**한국어**

```
AI 기능을 제품 흐름으로 연결하는 백엔드 개발자 | Spring Boot · FastAPI · RAG | SSAFY 15기 Java 전공
```

**English**

```
Backend Developer building AI product flows | Spring Boot · FastAPI · RAG | SSAFY 15th Java Track
```

---

## 2. About (소개 · 2,600자 제한)

```
AI 기능을 데모에서 끝내지 않고, 실제 서비스 흐름 안에서 동작하게 만드는 데 관심이 있는 백엔드 개발자입니다.

검색·생성형 응답을 단독 기능으로 두지 않고 데이터 수집 → 저장 → 질의 → 응답 → 상태 저장까지 하나의 흐름으로 묶는 작업을 주로 했습니다. 공공데이터 실거래가를 수집해 통합 검색과 챗봇 질의로 연결한 NoHome, 제품 매뉴얼을 RAG 답변과 영상 생성으로 연결한 LGDX가 그 결과물입니다.

한 흐름을 끝까지 책임지기 위해 서버와 클라이언트를 함께 다룹니다. Spring Boot와 FastAPI로 백엔드 orchestration을 구성하고, Vue와 Flutter로 사용자가 그 흐름을 실제로 겪는 화면까지 구현했습니다.

현재 SSAFY 15기 Java 전공 트랙에서 Spring Boot와 Spring AI를 중심으로 백엔드 역량을 심화하고 있으며, 알고리즘 문제 풀이를 꾸준히 기록하고 있습니다.

■ 주요 기술
Backend: Java, Spring Boot, Spring AI, FastAPI, MySQL, MyBatis
AI: LangChain, OpenAI, Google AI, RAG 파이프라인
Client: Vue, Flutter, Firebase, Supabase
Infra: Docker, Docker Compose, GitHub Actions

■ 링크
GitHub: https://github.com/jjeonyo
```

---

## 3. Experience (경력 · 활동)

### 3-1. SSAFY (삼성 청년 SW 아카데미)

| 항목 | 내용 |
| --- | --- |
| Title | 교육생 · Java 전공 트랙 (15기) |
| Company | 삼성 청년 SW 아카데미 (SSAFY) |
| Employment type | Apprenticeship |
| Dates | [확인 필요] |
| Location | [확인 필요] |

```
Java 전공 트랙에서 Spring Boot 기반 백엔드 개발과 Spring AI 활용을 중심으로 학습하고 있습니다.

· Spring Boot 기반 REST API 설계 및 구현
· Spring AI를 활용한 LLM 질의 기능 연동
· MySQL, MyBatis 기반 데이터 접근 계층 구성
· 팀 프로젝트 NoHome에서 데이터 수집 파이프라인과 검색 API 담당
· 알고리즘 문제 풀이 기록: https://github.com/jjeonyo/Algorithm
```

### 3-2. NoHome — 아파트 실거래가 검색 서비스 (팀 프로젝트)

| 항목 | 내용 |
| --- | --- |
| Title | 백엔드 개발 |
| Dates | [확인 필요] |
| Team size | [확인 필요] |

```
국토교통부 공공데이터 실거래가를 수집·저장하고, 매매/전세/월세를 통합 검색하는 서비스입니다.

· coverage 기반 자동 데이터 수집 흐름을 설계해 지역·기간별 수집 상태를 추적하고 누락분을 재수집
· 매매/전세/월세 거래 유형을 통합한 검색 API 구현
· Spring AI 기반 챗봇을 붙여 자연어 질의로 실거래가를 조회하도록 연결
· Kakao Map 연동으로 검색 결과의 위치 확인 제공
· Docker Compose로 백엔드·DB 실행 환경 구성

기술 스택: Spring Boot, Spring AI, MyBatis, MySQL, Vue, Vite, Kakao Map, Docker Compose
Repository: https://github.com/repechage-team/no-home-backend
```

### 3-3. LGDX — 매뉴얼 기반 AI 사용자 지원 서비스

| 항목 | 내용 |
| --- | --- |
| Title | 백엔드 · 클라이언트 개발 |
| Dates | [확인 필요] |
| Team size | [확인 필요] |

```
제품 매뉴얼을 검색해 답변하고, 필요 시 설명 영상까지 생성하는 AI 사용자 지원 서비스입니다.

· 매뉴얼 검색 → RAG 답변 → 영상 생성 → 상태 저장을 하나의 백엔드 흐름으로 orchestration
· FastAPI 기반 API 서버 구현, Firestore·Supabase로 대화 상태와 데이터 관리
· Flutter로 채팅·라이브·재생 화면을 구현해 응답 흐름을 사용자 경험으로 연결

기술 스택: FastAPI, Firestore, Supabase, Flutter, RAG
Repository: https://github.com/jjeonyo/lgdx_backend
```

---

## 4. Projects (프로젝트 섹션 · Experience와 별도로 등록 시)

| Project | 설명 | Link |
| --- | --- | --- |
| NoHome | 공공데이터 실거래가 수집·통합 검색·Spring AI 챗봇 | https://github.com/repechage-team/no-home-backend |
| LGDX | 매뉴얼 RAG 답변·영상 생성 AI 지원 서비스 | https://github.com/jjeonyo/lgdx_backend |
| Algorithm | 알고리즘 문제 풀이 기록 | https://github.com/jjeonyo/Algorithm |

---

## 5. Education

| 항목 | 내용 |
| --- | --- |
| School | [확인 필요 — 대학 / 전공 / 재학 기간] |
| SSAFY | 삼성 청년 SW 아카데미 15기, Java 전공 트랙 · [확인 필요 — 기간] |

---

## 6. Skills (상위 3개 고정 권장)

**고정 3개**

1. Spring Boot
2. FastAPI
3. Retrieval-Augmented Generation (RAG)

**전체 목록**

```
Java · Spring Boot · Spring AI · FastAPI · Python · REST API · MySQL · MyBatis ·
Retrieval-Augmented Generation (RAG) · LangChain · OpenAI API · Google AI ·
Vue.js · Vite · Flutter · Dart · Firebase · Firestore · Supabase ·
Docker · Docker Compose · GitHub Actions · Git · 공공데이터 API 연동 · 알고리즘
```

---

## 7. Contact / Custom URL

- GitHub: https://github.com/jjeonyo
- Custom LinkedIn URL: `linkedin.com/in/hyojun-jeon` (설정 완료)

---

## 확인 필요 항목

아래는 저장소에 근거가 없어 비워 둔 항목입니다. 값을 알려주시면 채워 넣겠습니다.

1. SSAFY 15기 시작·종료 시점, 교육 지역(캠퍼스)
2. 대학교 / 전공 / 재학 기간 (Education 섹션)
3. NoHome, LGDX 각 프로젝트의 진행 기간과 팀 인원, 본인 담당 범위
4. 정량 지표 — 수집한 실거래 데이터 건수, API 응답 시간 개선폭, RAG 답변 정확도, 사용자 수 등
5. 인턴·아르바이트·수상·자격증 등 저장소에 없는 경력
6. 희망 직무 (백엔드 / AI 엔지니어 / 풀스택) — Headline 문구를 여기에 맞춰 조정합니다
