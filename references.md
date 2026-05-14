# pi.dev 워크샵 교재 — 참고자료 & 학습 로드맵

본 교재(`textbook.html`)의 부록 D를 별도 마크다운으로 보존. 링크는 작성 시점(2026-05-14) 확인 기준.

## 1. pi.dev 공식

- **pi.dev** — https://pi.dev/
  공식 사이트. 설치 가이드, 매뉴얼, 예제 인덱스.
- **github.com/earendil-works/pi** — https://github.com/earendil-works/pi
  소스 레포. `examples/`, `packages/coding-agent/`가 학습 핵심.
- **coding-agent 패키지** — https://github.com/earendil-works/pi/tree/main/packages/coding-agent
  가장 정리된 레퍼런스 패키지.

## 2. 한국 커뮤니티

- **GeekNews(Hada) — pi.dev 토픽** — https://news.hada.io/topic?id=26324
  도입 후기·논점·한국어 비교 리뷰.

## 3. 관련 표준 · 컨셉

- **Agent Skills 표준** — pi의 Skills 블록이 따르는 규격. `/skill:name` 호출 컨벤션. pi 공식 docs 내 Skill 섹션 참조.
- **MCP (Model Context Protocol)** — Anthropic 주도. Extension의 인접 표준. 외부 도구·데이터와 LLM 연결.
- **프로젝트 아라 (Project Ara)** — 구글이 시도한 모듈러 스마트폰. 본 워크샵 메타포의 원천. 위키피디아·관련 다큐.

## 4. 본 교재 내부 자료

```
~/Documents/taikhan-vault/dev-log/2026-05-14-pi-workshop-design.md   ← 디자인 마스터 노트
~/Documents/taikhan-vault/tasks/2026-05-14-pi-workshop-prep-guide.md ← 1주 학습 가이드 원본
~/.openclaw/workspace/projects/pi-workshop/                          ← 시각 자료·카탈로그 이미지
```

## 5. 학습 로드맵

| 단계 | 기간 | 목표 |
|---|---|---|
| 0. 사전 점검 | D-8 | API 키 · Node · GitHub 체크 |
| 1. 1주 미션 | D-7 ~ D-1 | 본인 하네스 한 채 + 5분 데모 |
| 2. 워크샵 리허설 | D-1 | 02·03·04단계 시연 흐름 체크 |
| 3. 워크샵 1회차 | D-Day | 6~8명 파일럿 · 후기 확보 |
| 4. 회고 + v0.2 | D+3 | 카탈로그·교재 갱신 |
| 5. 다음 시즌 | D+30 | C 패턴 (작가·기획자 타깃) 분리 워크샵 검토 |

## 6. 심화 자습 (워크샵 후)

- **Themes** — 터미널 UI 스타일링. pi 공식 docs > Themes 섹션.
- **Pi Package 번들링/배포** — `npm publish`, git release 흐름.
- **Multi-agent 조합** — Skill이 다른 Skill을 부르는 컴포지션 패턴.
- **『다산선생 지식경영법』 (정민)** — 학습 방법론 50법 전체. 본 교재 챕터별 원칙의 원천.

## 7. 검증 메모

- pi.dev 공식, github 레포, GeekNews 링크는 2026-05-14 시점 디자인 마스터 노트에 정리된 출처를 그대로 옮긴 것.
- 학습자가 직접 클릭 시 도메인이 살아있는지 확인 권장 (무징불신법).
- 죽은 링크 발견 시 본 문서에 ❌ 표시 후 v0.2 작성 시 갱신.
