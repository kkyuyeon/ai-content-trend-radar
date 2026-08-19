# Workflow

> AI Content Trend Radar의 Daily → Weekly → Monthly 분석 흐름과 AI·사람의 역할을 정리합니다.

---

## 1. Daily Workflow

```text
Gmail Newsletters
+ Web / Official Sources
+ Public Social Channels
        ↓
Collect
        ↓
Verify
        ↓
Filter & Deduplicate
        ↓
Prioritize
        ↓
Interpret
        ↓
Apply
        ↓
Daily Briefing
        ↓
GitHub Archive
```

### Collect

뉴스레터, 공식 웹, 신뢰할 수 있는 보조 매체, 지정 소셜 채널에서 새로운 신호를 수집합니다.

### Verify

정책·기능·광고·법률 등 정확성이 중요한 내용은 가능한 경우 공식 1차 출처를 확인합니다.

### Filter & Deduplicate

광고성 정보, 중복 이슈, 출처가 불명확한 내용, 실무 영향이 낮은 정보를 제외합니다.

### Prioritize

최신성·영향도·콘텐츠 마케팅 관련성·실행 가능성·근거 수준을 바탕으로 `필독 / 주목 / 참고`로 구분합니다.

### Interpret

단순 요약에서 멈추지 않고 다음 질문에 답합니다.

- 콘텐츠 마케터에게 왜 중요한가?
- 소비자의 행동이나 선택 기준은 어떻게 바뀌는가?
- 콘텐츠 기획·제작·배포·광고·검색 중 어디에 영향을 주는가?

### Apply

실무 적용 포인트와 콘텐츠 아이디어로 변환합니다.

### Archive

의미 있는 새 정보가 있는 날만 `01_Daily-Briefing/YYYY-MM/YYYY-MM-DD.md`에 기록합니다.

---

## 2. Weekly Workflow

Weekly Insight는 Daily Briefing의 단순 요약이 아닙니다.

```text
Daily Signals
      ↓
Repeated Themes
      ↓
Connections
      ↓
Trend Shift
      ↓
Marketer Action
      ↓
Next Watch Point
```

한 주 동안 서로 다른 출처에서 반복된 현상과 연결 관계를 찾습니다.

예:

`AI 콘텐츠 증가 → 획일화·신뢰 피로 → 실제 경험·사람의 판단 중요성 상승`

Weekly Insight에서는 다음을 중심으로 정리합니다.

- 이번 주 핵심 Trend Shift 3~6개
- 서로 다른 Daily 이슈의 연결 관계
- 콘텐츠 마케터에게 필요한 행동 변화
- 다음 주 계속 관찰할 신호
- 실제 콘텐츠로 발전시킬 후보

---

## 3. Monthly Workflow

Monthly Report는 한 달의 뉴스 목록이 아니라 **구조적인 변화와 다음 행동을 압축하는 문서**입니다.

```text
Daily Briefings
+ Weekly Insights
       ↓
Monthly Pattern
       ↓
Platform Change
+ Consumer Change
+ Content Change
       ↓
Marketing Implication
       ↓
Next-Month Action
```

월간 리포트에서는 다음을 정리합니다.

- Executive Summary
- Top Trend Shifts
- Platform / AI Changes
- Consumer / Content Trends
- What It Means for Content Marketers
- Trend → Content Ideas
- 다음 달 Watch List
- 개인적인 학습과 판단

---

## 4. Trend → Content Workflow

아카이브에서 실행 가치가 높은 트렌드를 선택하면 `04_Trend-to-Content`에서 실제 콘텐츠 기획으로 전환합니다.

```text
Trend
  ↓
Consumer Insight
  ↓
Marketing Opportunity
  ↓
Content Hypothesis
  ↓
Format / Hook / Message
  ↓
Test
  ↓
Result & Learning
```

이 단계에서 트렌드 분석이 실제 콘텐츠 제작 역량으로 연결됩니다.

---

## 5. AI Role vs Human Role

### AI-Assisted

AI는 반복적이고 탐색 비용이 높은 업무를 보조합니다.

- 다수 정보원 검색
- 뉴스레터·웹 정보 정리
- 유사 이슈 묶기
- 초안 구조화
- 여러 포맷 아이디어 확장
- 과거 기록에서 반복 패턴 찾기

### Human / Marketer Judgment

최종 판단은 다음 영역에서 사람이 담당합니다.

- 어떤 정보원을 볼지 결정
- 무엇을 제외할지 판단
- 타깃과 소비자 맥락 해석
- 핵심 메시지 우선순위 결정
- 브랜드 적합성 검토
- 사실과 출처 최종 확인
- 실제 적용 가치 판단

> **AI는 탐색과 구조화를 빠르게 하고, 마케터는 무엇이 중요한지 판단하고 실행 방향을 결정합니다.**

---

## 6. Automation Rule

Daily Briefing 자동화는 의미 있는 새로운 정보가 확인된 경우에만 사용자에게 브리핑을 전달하고, 같은 실행에서 GitHub Daily Archive를 생성·업데이트하도록 설계합니다.

새로운 정보가 없거나 기존 이슈의 반복뿐이라면 빈 리포트를 만들지 않습니다.

이를 통해 저장소의 파일 수보다 **각 기록의 정보 밀도와 판단 근거**를 우선합니다.

---

## 7. Quality Control Checklist

브리핑 또는 리포트 작성 전 다음을 확인합니다.

- [ ] 이전 Daily와 중복되는가?
- [ ] 출처를 확인할 수 있는가?
- [ ] 실제 콘텐츠 마케팅 업무에 영향을 주는가?
- [ ] 단순한 화제와 구조적 변화를 구분했는가?
- [ ] ‘왜 중요한가’가 설명되어 있는가?
- [ ] 실행 아이디어가 억지로 붙어 있지 않은가?
- [ ] 공개 GitHub에 개인정보·원문 복제가 포함되지 않았는가?

---

## Core Principle

> **Collect fast. Verify carefully. Interpret as a marketer. Turn signals into action.**
