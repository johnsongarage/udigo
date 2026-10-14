# 기존 솔루션 지도와 소상공인이 안 쓰거나 그만두는 이유 (한국 중심, 해외 비교)

조사일: 2026-10-14. 웹 검색 15회 정도. inflowinventory.com과 sellermoim.com은 직접 열리지 않아(DNS 오류) 검색 결과 요약문으로 대신했다. 앱스토어 리뷰 원문은 거의 읽지 못했다. 그래서 "직원이 안 씀", "초기 품목 등록 부담" 같은 한국어 불만 인용은 대부분 확보하지 못했다(Gaps 참고).

## 1. 경쟁 지형: 어떤 도구가 있고 가격·대상·기능·AI 기능은 무엇인가

### Takeaway
한국 시장은 세 갈래로 나뉜다. (a) 범용 재고 앱(박스히어로), (b) POS에 붙은 간단한 재고 기능(토스플레이스, 페이히어), (c) 식자재 발주·유통 플랫폼(마켓봄, 식봄, 오더히어로, 오더플러스)이다. 2026년에는 POS 매출과 레시피를 이용해 재고를 자동으로 빼고 발주를 추천하는 AI 서비스(니즈 '미리', 프랜차이즈 자체 AI 발주)가 나오고 있다. **사진으로 매장 재고를 세는 한국 서비스는 찾지 못했다.**

### Cited Findings
**범용 재고 앱**
- 박스히어로(BoxHero): 기본 월 $20에 모든 기능이 들어 있다. 품목 1,000개마다 월 $10, 인원 1명마다 월 $5, 위치 10개마다 월 $10가 더 붙는다. 연간 결제는 10% 할인이다. **달러로 결제되므로 해외 결제가 되는 카드가 있어야 한다.** 소상공인 전용 요금제는 확인되지 않았다. — [BoxHero 요금 문서](https://docs-ko.boxhero.io/pricing)
- 박스히어로는 소규모 매장부터 창고 여러 곳, 대형 도매업까지를 대상으로 하고 바코드 스캔과 재고 부족 알림을 내세운다. — [BoxHero About](https://boxhero.io/company/about)
- 앱스토어에는 "재고관리부", "바코드 스캐너와 재고 관리", "재고 추적-재고 관리" 같은 개인 개발 앱이 많다. 구글 플레이의 한 "재고관리" 앱은 상품 마스터를 직접 입력하거나 엑셀로 올릴 수 있다고 소개한다. — [Google Play 재고관리](https://play.google.com/store/apps/details?id=com.syncinventory&hl=en_US), [App Store 재고관리부](https://apps.apple.com/kr/app/%EC%9E%AC%EA%B3%A0%EA%B4%80%EB%A6%AC%EB%B6%80-%EC%9E%90%EC%82%B0-%EB%AA%A9%EB%A1%9D-%EC%A0%80%EC%9E%A5-%EA%B4%80%EB%A6%AC/id1539373277)

**POS에 붙은 재고 기능**
- 토스플레이스(토스 포스): 상품관리 → 재고관리 화면에서 **상품별로 수량을 직접 입력**한다. 이후 판매 수량을 자동으로 빼고, 0개가 되면 키오스크에 "품절"이 뜬다. 입출고 히스토리는 "준비 중"이라고 적혀 있다(게시일은 나와 있지 않다). 판매 단위 상품(완제품) 재고만 다루며, 식자재 원재료나 레시피 단위 차감에 대한 언급은 없다. — [토스플레이스 스토리](https://tossplace.com/story/stock-management)
- 토스 포스는 2023년 정식 출시됐고, 이후 Windows, Android, iOS, Mac에서 모두 돌아간다. — [토스피드](https://toss.im/tossfeed/article/tossplace-launching), [토스피드 전 OS](https://toss.im/tossfeed/article/tossplace-all-OS)
- 페이히어: POS를 스마트스토어·카페24와 연동한다. 과거 판매와 출고 데이터로 3일·7일·14일 뒤 품절 가능성을 예측하는 AI 재고 예측 기능이 보도됐다. 요금은 확인하지 못했다. — [벤처스퀘어](https://www.venturesquare.net/1089597/)
- 배민포스와 OKPOS: 재고 기능이나 사용 후기를 검색으로 찾지 못했다. OKPOS 계열 앱 "오늘얼마"는 매출 장부와 정산 확인 위주이고, 재고 기능은 설명에 없다. — [App Store 오늘얼마](https://apps.apple.com/us/app/%EC%98%A4%EB%8A%98%EC%96%BC%EB%A7%88-%EC%82%AC%EC%9E%A5%EB%8B%98-%EB%A7%A4%EC%B6%9C-%EA%B4%80%EB%A6%AC-%ED%95%84%EC%88%98%EC%95%B1/id1605931675?l=ko)

**식자재 발주·유통 플랫폼 (존재 확인함)**
- 마켓봄(마켓보로): 유통사용 수발주 SaaS다. 유통사가 월 최대 12만 1,000원을 내고, 식당은 무료로 쓴다. 약 8만 개 식당이 주문하고 연 거래액이 3조 원이 넘는다는 기사가 있다(기사 날짜 불명). 식당은 마켓봄에 가입한 유통사가 발급한 아이디로만 들어올 수 있다. — [MK 히든챔피언(다음)](https://v.daum.net/v/4eIw3bXDvl?f=p), [App Store 마켓봄](https://apps.apple.com/us/app/id1099676457)
- 식봄(마켓보로, CJ프레시웨이 자회사): 외식 사업자용 식자재 오픈마켓이다. 2025년 거래액은 2,341억 원으로 전년보다 52% 늘었다(채용 공고에 실린 회사 측 수치). 마켓보로 누적 거래액은 약 13조 원이고, 누적 투자는 약 600억 원이다. 2025년 5월 비수도권 거래액은 2024년 1월의 3.8배다. — [원티드 채용공고](https://www.wanted.co.kr/wd/360360), [머니투데이 2025-06](https://www.mt.co.kr/future/2025/06/18/2025061814570533398), [시사경제](https://sateconomy.co.kr/news/view/1065587102104584)
- 오더히어로(딜리버리랩): 식당과 식자재 유통사를 이어 주는 주문 앱이다. "자주 사는 품목" 목록, 월별 지출과 가격 변동 분석, 배송 조회를 제공한다. **App Store 평점은 3.4점(61개 평가)**이고 "주문 확인 화면이 느리다"는 리뷰가 있다. 창업 배경은 "메신저나 문자로 주문을 받는 경우가 많다 보니 오배송이나 커뮤니케이션이 잘 안 되는 경우가 흔했다"는 것이다. — [App Store 오더히어로](https://apps.apple.com/kr/app/%EC%98%A4%EB%8D%94%ED%9E%88%EC%96%B4%EB%A1%9C-%EC%A3%BC%EB%AC%B8%EC%A0%91%EC%88%98/id1490533725), [CJ뉴스룸 인터뷰](https://cjnews.cj.net/?p=16540)
- 오더플러스: 이름은 비슷하지만 별개 회사다. 대기업, 농수산, 수입, 도매시장 식자재를 최저가로 비교해 주문하는 앱이다. — [App Store 오더플러스](https://apps.apple.com/kr/app/id1216541676)

**2025~2026 AI 발주·재고 (한국)**
- 니즈 "미리": POS와 배달앱 매출을 연동해 레시피 기준으로 식자재 소비량을 계산한다. 재고 자동 차감, 수요 예측, 자동 발주를 하고, 형식이 제각각인 입고 데이터를 자동으로 정리한다. 약 3,000개 식당이 쓴다고 한다. 자체 조사로는 발주·정리 시간이 하루 90분에서 30분 이내로 줄었다. — [머니투데이 2026-10-14](https://www.mt.co.kr/policy/2026/10/14/2026101409395923678)
- 육수당(이연에프엔씨): 판매, 날씨, 요일, 상권 데이터로 매장별 적정 발주량을 매일 제안한다. 88개 매장의 활용률은 2026년 8월 68.1%에서 9월 81.1%로 올랐다. — [한국경제 2026-10](https://www.hankyung.com/article/202610140251g)
- 블리츠다이나믹스: 재고 조사와 발주를 AI에 맡겨 직영점만으로 여러 브랜드를 운영한다. 한 주방에서 23개 브랜드를 돌린다. — [머니투데이 2026-10](https://www.mt.co.kr/future/2026/10/10/2026092014585370925)
- 셀리스트: 손질·반조리 식자재를 공급하면서 동네 식당 발주까지 지원한다. — [유니콘팩토리 2025-11](https://www.unicornfactory.co.kr/article/2025111314102738556)
- 플렉스튜디오 블로그 "식자재 재고, 아직도 눈으로 확인하고 계신가요?"(서울푸드 2026)는 관련 제품이 있을 수 있다는 신호지만, 내용은 열어 보지 못했다. — [플렉스튜디오](https://flextudio.com/blog/seoul-food-2026)

**해외 비교 (가격은 집계 사이트마다 다르다)**
- Sortly: 무료 요금제가 있고, 유료는 대략 $49 / $149 / $299(월)다. 2022년 자료에서는 Advanced가 $29였다. — [business.org](https://www.business.org/finance/inventory-management/sortly-review), [costbench](https://costbench.com/software/inventory-management/sortly/)
- inFlow: 무료 요금제가 없다. Entrepreneur 요금제는 월 $186(Capterra 기준)이고, 다른 출처는 $129~$149로 적고 있어 서로 다르다. — [Capterra inFlow 가격](https://capterra.com/p/78431/inFlow-Inventory/pricing/)
- Square for Retail: 기본 무료이고 Plus는 위치당 약 월 $49다. 실제 비용은 결제 수수료(약 2.6%+10¢)다. — [dupple](https://dupple.com/learn/best-small-business-inventory-management-software)
- MarketMan(식당용): 월 약 $199(연간 결제 시 $169), Growth는 $249다. **처음 설정비 $500**과 인보이스 스캔·EDI 추가 요금이 따로 붙는다. Capterra 평점은 4.7점(112개)이다. — [The Restaurant HQ](https://www.therestauranthq.com/technology/marketman-review/), [Capterra](https://www.capterra.com/p/136439/Marketman-Restaurant-Inventory/reviews/)
- 사진 한 장으로 물건을 세는 범용 앱이 해외에는 이미 있다. Count This, Pixoate AI Inventory Counter(선반 사진 → 개수 → CSV 내보내기, 예시 물건 1~3개를 지정), SnapCount, Scanlily, Inventory Inventory(Shelf Watch)다. 식당 전용 제품은 찾지 못했다. — [Pixoate](https://pixoate.com/inventory-counter), [Count This](https://apps.apple.com/us/app/count-this-ai-object-counter/id6754241712), [SnapCount](https://apps.apple.com/app/id6745726513), [Scanlily](https://www.scanlily.com/), [Inventory Inventory](https://inventoryinventory.com/photo-inventory-app)

### Inferences
- 한국의 발주 플랫폼(마켓봄, 식봄)은 **주문 채널**을 쥐고 있지만, "지금 매장에 뭐가 얼마나 남았나"는 다루지 않는다. POS 재고 기능은 **완제품 판매 수량 차감**에 그친다. 식자재 원재료의 실제 수량(냉장고와 창고)은 어느 도구에서도 빈칸으로 보인다.
- 2026년 AI 발주 흐름(니즈, 육수당)은 레시피와 POS 데이터를 이용한 **이론 재고**다. 이론 재고는 폐기, 직원 식사, 계량 오차 때문에 실제와 어긋난다. 그 차이를 사진으로 빠르게 맞춰 주는 도구가 들어갈 자리가 있다.
- 사진 개수 세기는 기술로는 흔하지만(해외 앱 여러 개), 발주까지 이어지고 한국 식당 업무에 맞춘 제품은 확인되지 않았다.

### Gaps
- 페이히어, 배민포스, OKPOS, 포스뱅크의 재고 기능 세부와 과금은 확인하지 못했다.
- 마켓봄의 8만 식당·3조 원 수치는 기사 날짜를 모른다.
- meez(레시피 관리, 미국) 가격은 확인하지 못했다.
- 이카운트 같은 ERP-lite와 엑셀·구글시트 템플릿 배포처는 따로 조사하지 못했다.

## 2. 사용자 리뷰는 무엇을 칭찬하고 무엇을 불평하나, 사장님은 왜 그만두나

### Takeaway
확보한 불만은 네 가지로 모인다. **입출고를 손으로 입력하는 부담 → 숫자가 안 맞음 → 결국 엑셀과 병행하거나 포기**, 그리고 **도입·세팅이 어렵다**는 것이다. 칭찬은 "세팅만 끝나면 원가가 보인다"에 몰린다. 즉 문제는 세팅과 입력 과정이고, 결과물에는 만족한다.

### Cited Findings
- 셀러모임(온라인 셀러 커뮤니티): "정산 데이터랑 실재고랑 계속 안 맞아서 매달 차이 날 때마다 그냥 숫자 맞춰버리는 짓을 하고 있다." 입고와 출고를 매번 손으로 입력한다는 내용이다. 유료 솔루션을 써 봤지만 "채널 연동이 맘대로 안 되고 마진 계산은 또 따로 해야 해서" 엑셀을 같이 쓰게 됐다고 한다. — [셀러모임 post/914](https://sellermoim.com/post/914) (원문은 열리지 않아 검색 요약문으로 확인), [셀러모임 post/1591](https://sellermoim.com/post/1591)
- 박스히어로 블로그는 재고 프로그램 도입이 실패하는 이유로 세 가지를 꼽는다. 실무자가 직접 써 봤는가, 모바일에서 쓰기 편한가, 입출고 입력 기준을 정했는가. 판매사가 스스로 "현장 직원이 입력하지 않는 문제"를 인정한 셈이다. — [BoxHero 블로그](https://www.boxhero.io/ko/blog/egsel-jaegogwanriyi-bulpyeonhan-jinri)
- 토스페이먼츠 블로그: "쇼핑몰 초기에는 엑셀을 활용해서 무료로 간편하게 재고 관리할 수 있어요." 초기 단계에서는 엑셀이 정답이라는 메시지다. — [토스페이먼츠](https://www.tosspayments.com/blog/articles/semo-54)
- MarketMan Capterra 2.0점 리뷰(2025): 굴러가게 하려면 지원이 많이 필요하고, 특히 시작하기가 정말 어렵다고 했다. 다른 2.0점 리뷰는 해지가 어렵다고 불평했다. 또 다른 리뷰는 "POS와 연동될 때만 쓸 만하다"고 했다. 5.0점 리뷰는 학습 곡선이 중간 정도이고, 세팅과 직원 교육이 끝나면 원가가 보이고 폐기가 줄어든다고 했다. — [Capterra MarketMan](https://www.capterra.com/p/136439/Marketman-Restaurant-Inventory/reviews/)
- 오더히어로: 평점 3.4점, "주문 확인 화면이 느리다." — [App Store](https://apps.apple.com/kr/app/%EC%98%A4%EB%8D%94%ED%9E%88%EC%96%B4%EB%A1%9C-%EC%A3%BC%EB%AC%B8%EC%A0%91%EC%88%98/id1490533725)
- 박스히어로는 달러로만 결제되고 해외 결제 카드가 있어야 한다. 한국 영세 사장님에게는 진입 장벽이다. — [BoxHero 요금](https://docs-ko.boxhero.io/pricing)

### Inferences
- 그만두는 경로는 대략 이렇다. 초기 품목 등록과 기준 설정 → 매일 입출고 입력 → 입력이 빠지면서 숫자가 어긋남 → 신뢰 상실 → 엑셀이나 눈대중으로 돌아감. 맞는 숫자를 얻는 대가가 매일의 수동 입력인데, 바쁜 사장님은 그 비용을 끝까지 치르지 않는다.
- POS 재고 기능은 품목별 수량을 직접 입력해야 시작된다(토스). 같은 "첫 등록 장벽"이 POS 안에도 있다.

### Gaps
- 박스히어로, 토스, 페이히어의 플레이스토어·앱스토어 리뷰 원문 인용은 확보하지 못했다. 네이버 카페(아프니까 사장이다 등)의 원문 댓글도 마찬가지다. "직원이 안 씀", "초기 등록이 귀찮다"는 한국어 직접 인용이 필요하면 추가 조사가 필요하다.

## 3. 도입률 데이터, 해결 안 된 빈칸, 사진·AI 개수 세기 사례

### Takeaway
도입률 수치는 드물다. 2026년 해외 조사에서는 **85%가 스프레드시트를 주 도구로 쓰고, 전용 소프트웨어는 22%**였다. 한국 소상공인은 디지털 활용이 "기초·입문 단계"라는 답이 83.3%였다. 카메라·AI 재고 인식은 대형 유통에서도 비용과 정확도 문제를 겪었다(Amazon Just Walk Out). 그래서 저입력 사진 방식은 **완전 자동이 아니라 사람이 확인하는 방식(human-in-the-loop)**으로 설계해야 한다는 교훈이 나온다.

### Cited Findings
- inFlow "State of Inventory Management 2026"(400명, 33개 업종, 판매사가 직접 한 조사): 85%가 스프레드시트를 주 도구로 쓰고, 74%는 스프레드시트가 유일하거나 주된 시스템이다. 전용 재고 소프트웨어는 22.0%(복수 응답), 종이 기록은 27.0%다. 직원 500명 이상 기업도 53%가 주로 스프레드시트를 쓴다. — [inFlow 보고서](https://inflowinventory.com/blog/state-of-inventory-management-2026) (직접 열람 실패, 검색 요약문). 같은 맥락의 보도: "81% of inventory operators want AI, only 11% are using it"(2026-07). — [Distribution Strategy](https://distributionstrategy.com/2026/07/inventory-survey-finds-strong-interest-in-ai-but-adoption-remains-limited/), [AAP/Cision](https://www.aap.com.au/aapreleases/cision20260728ae09500/)
- 한국 소상공인 500곳 조사(외식 200, 소매 150 등, 2026-06 보도): 디지털 활용 수준이 기초 30.5%, 입문 52.8%로 합계 83.3%다. 경영지원 분야의 POS 활용은 68.3%다. 하지만 재고 기능만 따로 본 활용률은 없다. — [헤럴드경제 2026-06](https://www.heraldk.com/article/2026060918404673332)
- 정부의 스마트상점 기술보급사업이 재고 관리 소프트웨어 구독료를 지원한다는 언급이 있다(블로그 글이라 공식 확인은 필요). — [tilnote](https://tilnote.io/pages/6a5f984ed14b3050aae3aaaa)
- Amazon Just Walk Out(2024-04 보도): The Information은 인도의 1,000명 이상이 영상을 검수했다고 보도했다. 사람이 개입한 비율은 목표 5%에 비해 실제 70%였다는 보도인데, **Amazon은 이 수치를 부인**했다. Amazon Fresh는 Dash Cart와 셀프 계산대로 옮겨 갔다. — [OSnews](https://www.osnews.com/story/139138/amazons-just-walk-out-checkout-system-consisted-of-1000-people-in-india-watching-you-shop/), [RetailWire](https://retailwire.com/amazon-is-phasing-out-its-just-walk-out-tech-in-checkout-less-stores/), [HR Grapevine](https://www.hrgrapevine.com/us/content/article/2024-04-03-amazons-ai-powered-cashier-less-stores-relied-on-1000-remote-contractors)
- Trax(선반 이미지 인식): 2021년 $640M 시리즈 E로 기업가치 $2.25B~$2.6B를 받았다(출처마다 다르다). 2022년에는 여러 차례 감원했다(약 8~12%, 100명 이상). — [Times of Israel](https://www.timesofisrael.com/retail-data-startup-trax-raises-640-million-in-funding-round/), [Globes](https://en.globes.co.il/en/article-retail-analytics-co-trax-laying-off-over-100-1001415644)
- Simbe Robotics(선반 스캔 로봇 Tally): 2024-10 $50M 시리즈 C로 누적 $100M 이상을 모았다. 대형 마트 대상이다. — [Grocery Dive](https://www.grocerydive.com/news/simbe-raises-50-million-series-c/731116/)

### Inferences (빈칸: 사진 기반 저입력 앱이 채울 수 있는 것)
1. **원재료의 실제 수량**: POS는 완제품을 빼고, 발주 플랫폼은 주문만 받는다. 냉장고와 창고에 실제로 남은 식자재를 빠르게 세는 수단이 없다.
2. **첫 등록 장벽**: 사진에서 품목을 바로 만들어 주면 품목 마스터를 손으로 입력하는 단계를 건너뛸 수 있다.
3. **매일 입출고 입력 대신 주기적 스냅샷**: 입출고를 하나하나 기록하는 대신 "찍어서 맞추기"로 바꾸면 입력이 빠져 숫자가 어긋나는 문제를 근본적으로 피한다.
4. **센 결과를 발주로 잇기**: 센 결과를 카톡이나 문자로 보내는 발주서로 바로 바꿔 준다. 한국 유통사 주문의 상당 부분이 아직 문자와 메신저로 오간다(오더히어로 창업 배경).
5. **결제와 가격 장벽**: 원화 결제, 무료 또는 저가, 바코드 장비가 필요 없을 것.
6. 대형 유통의 비전 AI는 고정 카메라, 로봇, 큰 투자가 필요했다. 그것도 정확도와 비용 문제로 축소됐다(Amazon). 소규모 매장에서는 **사장님이 직접 폰으로 찍고 AI가 추정한 숫자를 사람이 한 번 확인**하는 방식이 현실적이다. 정확도 100%보다 "추정 + 빠른 수정"이 더 맞는 기대치다.

### Gaps
- 한국에서 POS 재고 기능을 실제로 켜고 쓰는 비율(토스, 배민포스 등)은 공개된 자료가 없다.
- 해외 식당 재고 소프트웨어의 도입률이나 해지율을 다룬 독립 조사는 찾지 못했다(inFlow 조사는 판매사 자료이고 식당 전용도 아니다).
- 사진 개수 세기 앱(Pixoate, SnapCount 등)의 실제 정확도, 사용자 수, 리텐션은 확인하지 못했다.
- 2025~2026년 Amazon Just Walk Out의 후속 상황(제3자 매장 판매 현황)은 확인하지 못했다.
