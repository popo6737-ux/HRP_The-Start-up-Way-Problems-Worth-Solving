# Reading 6 — Do Things that Don't Scale

**출처 (Source):** Graham, Paul (2013). *Do Things that Don't Scale.* paulgraham.com/ds.html — Y Combinator 공동창업자의 에세이.

## 핵심 메시지 (Core Message)

스타트업은 저절로 성장하지 않는다(don't just take off by themselves). 창업자가 처음에 **확장 불가능한(unscalable) 방식**으로 직접 밀어붙여야 성장이 시작된다. 자동차 시동을 걸던 옛날의 수동 크랭크(crank)처럼, 초기엔 힘겨운 수작업이 필요하다.

## 주요 개념 정리 (Key Concepts)

### 1. Recruit — 사용자를 직접 모집하라
사용자가 찾아오길 기다리지 말고(You can't wait for users to come to you) 직접 나가서 모집해야 한다.
- **Collison installation**: Stripe 창업자들이 베타 사용 동의를 받으면 "노트북 주세요(give me your laptop)"라며 그 자리에서 바로 설치해준 방식. 소극적으로 "링크 보내드릴게요" 하는 대신 즉시 행동.
- **복리 성장(compound growth)의 힘**: 주간 성장률(weekly growth rate) 10%를 유지하면 1년 후 14,000명, 2년 후 200만 명. 처음엔 작아 보여도 꾸준한 비율이 핵심.
- 창업자(보통 CEO)는 반드시 영업·마케팅에 많은 시간을 써야 한다 — 이를 회피하는 건 수줍음과 게으름의 조합.

### 2. Fragile — 초기 스타트업은 깨지기 쉽다
Airbnb도 초기엔 "약 30일간의 직접 사용자 응대(30 days of going out and engaging in person with users)"가 성패를 갈랐을 만큼 취약했다(fragile).
- 질문을 바꿔라: "이 회사가 세상을 정복할까?"가 아니라 **"창업자가 옳은 일을 한다면 이 회사가 얼마나 커질 수 있을까?"**
- 가장 큰 위험은 기자나 투자자의 무시가 아니라 **창업자 스스로 자기 회사를 과소평가하는 것**.

### 3. Delight — 고객을 기쁘게 하라
초기 사용자에게 "말도 안 되게(insanely)" 좋은 경험을 제공하라.
- 사례: Wufoo는 신규 가입자마다 손편지(hand-written thank you note)를 보냄.
- 엔지니어 출신 창업자들이 고객 응대(customer service)를 꺼리는 이유: (1) 공학 훈련은 개인 응대를 훈련하지 않음, (2) "확장이 안 될까봐" 걱정, (3) 정작 본인이 그런 수준의 응대를 받아본 적이 없음.
- **"Insanely great"** (Steve Jobs의 표현): 초기 스타트업에선 제품이 아니라 **"사용자가 되는 경험(the experience of being your user)"** 자체가 insanely great 해야 한다. 제품이 부족해도(incomplete, buggy) 정성으로 메울 수 있다.

### 4. Fire — 좁은 시장에 불을 지펴라 (contained fire strategy)
처음부터 넓은 시장을 노리지 말고, 의도적으로 좁은 시장(deliberately narrow market)에서 critical mass를 만들어라.
- 사례: Facebook은 처음엔 하버드생 전용이었고, 이후 특정 대학들로만 확장 — "여기가 내 자리(natural home)"라는 소속감을 만듦.
- B2B 스타트업에게 최고의 초기 고객(early adopter)은 대개 **다른 스타트업**이다 — 더 개방적이고 빠르게 성장하기 때문.

### 5. Meraki — 하드웨어는 직접 조립하라 ("pulling a Meraki")
하드웨어 스타트업은 공장 최소 발주량(수십만 달러)이라는 catch-22에 걸리기 쉽다. 초기엔 직접 손으로 조립(assembling their products themselves)해서 이 딜레마를 돌파하라.
- 사례: Pebble은 첫 수백 개의 시계를 직접 조립한 뒤에야 Kickstarter에서 1,000만 달러어치를 팔 수 있었다.

### 6. Consult — 단 한 명을 위해 컨설턴트처럼 일하라
B2B 스타트업은 단 한 명의 사용자를 위해 맞춤 제작하듯 과도하게 관여(over-engage)하는 것도 방법. 그 한 명의 니즈에 완벽히 맞추다 보면 다른 고객도 원하는 것을 만들게 된다.
- 단, **돈을 받으면 안 된다** — 무료로 도와줄 때는 감사해하지만, 시간당 요금을 받기 시작하면 고객은 "모든 걸 다 해달라"고 기대하게 된다.

### 7. Manual — 자동화 전에는 직접 수작업으로 서비스하라
초기엔 나중에 자동화할 일을 **직접 손으로(by hand)** 처리해도 괜찮다. 그래야 나중에 무엇을 자동화해야 할지 정확히 알게 된다.
- 사례: Stripe는 초기 "즉시 가맹점 계좌(instant merchant accounts)"를 창업자들이 뒤에서 수작업으로 전통적 가맹점 계좌를 만들어 제공했다.

### 8. Big — "대대적 런칭(Big Launch)"은 대개 효과가 없다
많은 창업자가 스타트업을 "충분한 초기 속도로 발사되는 발사체"로 착각한다. 실제로 성공한 스타트업 중 런칭 자체를 기억하는 사람은 거의 없다.
- **파트너십도 대개 효과가 없다** — "그 파트너십이 우리의 빅 브레이크가 될 것"이라 기대했다가 6개월 후 "생각보다 훨씬 일만 많고 얻은 건 거의 없었다"는 게 흔한 패턴.

### 9. Vector — 스타트업 아이디어는 벡터(vector)다
스타트업 아이디어를 하나의 숫자(scalar, "무엇을 만들 것인가")로만 생각하지 말고, **"무엇을 만들 것인가" + "초기에 할 확장 불가능한 일"**의 두 성분을 가진 벡터로 생각하라.
- 이상적으로는 이 확장 불가능한 초기 행동이 회사의 DNA에 영구히 남는다 — 예: 작을 때 공격적으로 사용자를 모았다면, 커져도 그 공격성이 남는다.

## FoamFit에 적용해보기

- **Recruit**: 첫 PoC 파트너(휴게소 등)를 어떻게 "Collison installation"처럼 즉시·직접 설득하고 설치할 것인가?
- **Fire**: 처음부터 모든 공중화장실을 노리지 말고, 좁은 세그먼트(예: 특정 휴게소 체인 1곳)에서 critical mass를 먼저 만드는 전략은?
- **Meraki**: 기계식 펌프 프로토타입을 자체 조립해보며 무엇을 배울 수 있을까?
- **Manual**: 카트리지 교체·재고 관리를 자동화하기 전, 초기엔 수작업으로 운영하며 배울 점은?
