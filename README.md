# LLM_SFG

Systemic Functional Grammar(SFG)를 기반으로, LLM의 응답에서 예측 가능한 AI 패턴(과도한 명사화·공허한 hedging·median modality·단조로운 Theme 등)을 제거하기 위한 스킬 패키지.

## 배경

응용언어학(Applied Linguistics)을 전공하며 접한 Systemic Functional Grammar의 *체계화된 언어 선택 시스템*이, LLM 응답 품질 개선에도 유효한 진단·교정 프레임이 될 수 있다는 아이디어에서 출발했다. 문법을 규칙이 아닌 "의미를 위한 선택"으로 보는 SFG의 관점은, LLM이 디폴트 패턴에서 벗어나 의식적인 언어 선택을 하도록 가르치는 데 적합하다.

## 구성

```
LLM_SFG/
├── references/
│   └── sfg.md                          # SFG 이론 정리 (원본)
└── skills/
    └── systemic-functional-llm/
        ├── SKILL.md                    # 코어 척추 — Choice principle, 3 metafunctions, Pre-writing routine, 7대 AI 패턴
        └── references/
            ├── ai-pattern-catalog.md   # 12종 AI 패턴 진단·교정
            ├── transitivity.md         # Process type 선택
            ├── mood-modality.md        # 스탠스·확신도 조정
            ├── theme-rheme.md          # 정보 구조와 리듬
            ├── cohesion.md             # 결속 5종 + clause complex
            ├── appraisal.md            # Attitude / Engagement / Graduation
            └── grammatical-metaphor.md # Nominalization 회복
```

## 사용

스킬 폴더(`skills/systemic-functional-llm/`)를 Claude의 skills 디렉터리로 복사하면 글쓰기·문서·이메일·콘텐츠·답변 작성 시 자동 트리거된다.

## 핵심 원리

언어는 **의미를 만드는 선택 시스템**이다. AI의 "글쓰기 특유의 톤"은 곧 *각 선택 시스템에서 가장 빈도 높은 디폴트로만 가는 경향*이다. 이 스킬은 그 디폴트를 의식화하고, 의미에 맞는 선택으로 대체하도록 LLM을 훈련시킨다.
