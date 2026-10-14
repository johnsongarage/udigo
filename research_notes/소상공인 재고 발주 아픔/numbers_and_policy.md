# 소상공인 재고·발주 문제: 정량 근거와 정책 맥락 (초기창업패키지 "문제인식"용)

> Method note (read first): research done 2026-10-14. WebFetch failed on every Korean news/government domain tried (mafra.go.kr, newsis.com, heraldk.com, metroseoul.co.kr all returned DNS "ENOTFOUND"), so **Korean figures below come from search-engine snippets/summaries of the cited pages, not from full-text reads**. Before you put any number in the business plan, open the cited URL (or the original 보도자료 / 보고서) and confirm it. "Primary" = the agency that ran the survey. "Secondary" = a news article or aggregator reporting it. "VENDOR" = produced by a company that sells inventory/retail software.

## Q1. What official Korean statistics exist, and what are the relevant figures?

### Takeaway
The 2024 기준 소상공인실태조사 (중기부·소진공, 2026 release) counts **6.134 million 소상공인 businesses**: 도소매업 2.10M (34.2%) and 숙박·음식점업 0.796M (13.0%). Together these are about 47% of all 소상공인, which is the core target for an inventory/ordering app. KREI's 2025 외식업체 경영실태조사 (2024 data) shows **식재료비 at 40.7% of costs, a record high**, and **영업이익률 down to 8.7% from 12.1% in 2020**. With margins that thin, small purchasing and waste errors hit profit directly.

### Cited Findings
**2024년 기준 소상공인실태조사 (중소벤처기업부·소상공인시장진흥공단; secondary citations of the official release)**
- 소상공인 기업체 수: 596.1만 (2023) → 613.4만 (2024), +2.9% — [파이낸셜뉴스](https://www.fnnews.com/news/202603130840507888); [세계일보](https://www.segye.com/newsView/20260109505471)
- 업종별 기업체 수: 도소매업 210만 (34.2%), 부동산업 86.2만 (14.0%), 숙박·음식점업 79.6만 (13.0%), 건설업 56.8만 (9.3%), 제조업 53.7만 (8.8%) — [파이낸셜뉴스](https://www.fnnews.com/news/202603130840507888)
- 종사자 수: 955.1만 → 961만 (+0.6%). 기업체당 평균 종사자 1.60 → **1.57명**. This supports the argument that most shops are run by the owner alone or with one helper, so there is no dedicated purchasing or inventory staff. — [파이낸셜뉴스](https://www.fnnews.com/news/202603130840507888)
- 업종별 종사자: 도소매 303.9만 (31.6%), 숙박·음식점 142.3만 (14.8%), 제조 126.3만 (13.1%) — same source
- 평균 창업비용 8,300만원 (본인부담 5,900만원), down from 8,900만원 the year before — [파이낸셜뉴스](https://www.fnnews.com/news/202606291334444403) (search snippet)
- Average sales, operating profit and debt per business from the 2024 기준 survey were NOT found in snippets (see Gaps).

**2025년 외식업체 경영실태조사 (농림축산식품부·한국농촌경제연구원 KREI; 2024 data; released ~2026-03-28 / 03-29)**
- 외식업체 평균 매출 **2억 5,526만원** (2024), up 41.4% vs 5 years earlier, but only +1.4% vs 2023 — [농림축산식품부 보도자료](https://www.mafra.go.kr/bbs/home/792/577439/artclView.do) (primary; could not fetch, snippet only); [다음/뉴스](https://v.daum.net/v/20260329110924835)
- **영업이익률 8.7% (2024), vs 12.1% (2020)**: sales grew about 40% while the margin fell 3.4%p — [뉴시스](https://www.newsis.com/view/NISX20260328_0003567838); [다음](https://v.daum.net/v/FeTRxkfzmC)
- **식재료비 비중 36.3% → 40.7%**, a record high. It first passed 40% in 2023 (40.4%). — [뉴시스](https://www.newsis.com/view/NISX20260328_0003567838); [supple.kr](https://supple.kr/news/cmu0b92t80018bpm38vo0j6j7)
- 식재료비 + 인건비 비중 **71.6% (일반음식점, 2024)**, the first time above 70% since the survey began. ⚠ This figure comes from 연합뉴스's own time-series analysis of the report, not from the government's headline release. — [supple.kr citing 연합뉴스](https://supple.kr/news/cmu0b92t80018bpm38vo0j6j7)
- ⚠ Sources disagree on whether 8.7% covers all 외식업 or only 일반음식점. Check the original report.
- Earlier edition, for the time series: [아시아경제, 2023년 외식업체 경영실태조사](https://view.asiae.co.kr/article/2024042311260144428)

**Other official or semi-official surveys (context)**
- 2025 상가건물임대차 실태조사 (published 2026-05). Average 소상공인 임차인 sales in 2024 were 2억1,200만원, and operating profit fell from 8,200만원 to **4,800만원**. 27.3% have business-related debt, with an average balance of 1억4,400만원. ⚠ This is a different survey from the 소상공인실태조사, and the snippet's "−1억4,700만원 sales" comparison looks odd, so verify it. — [한경비즈니스](https://magazine.hankyung.com/business/article/202605171652b); [SBS Biz](https://biz.sbs.co.kr/amp/article/20000310846)

### Inferences
- 도소매업 plus 숙박·음식점업 is about 2.9 million businesses (47%) and roughly 4.46 million workers. That is the serviceable population for a 재고·발주 app. Narrow it further for SAM, for example to 음식점 and 동네 소매 with perishable stock.
- Rough illustration (an inference, not a source): with 식재료비 at 40.7% of costs and an 8.7% margin, a restaurant that wastes or over-orders 5% of its 식재료 loses about 2%p of revenue. That is close to a quarter of its profit. The calculation is approximate because 식재료비 is a share of costs, not of sales. Label it clearly as an estimate in the plan.

### Gaps
- Per-business average 매출/영업이익/부채 and 업종별 영업이익 from the 2024 기준 소상공인실태조사 were not found in snippets. Get them from the 중기부 보도자료 or the KOSIS table "소상공인실태조사".
- The KOSIS table IDs and exact release date of the 2024 기준 조사 were not verified.
- No official Korean statistic on **inventory loss (재고 손실·폐기율) at 소상공인** was found. The 외식업체 경영실태조사 snippets did not mention 폐기율. Check whether the full KREI report has a 식재료 관리/폐기 문항.

## Q2. What share of small businesses track inventory manually vs with software (Korea and international)?

### Takeaway
No Korean government survey found reports a "재고관리 디지털 도입률" figure. The best Korean proxy is the 중소기업중앙회 2026 DX·AX survey: 80% of 소상공인 "use" digital tools, but **83.3% are at basic or entry level**, mostly POS (68.3%) and 배달앱. Only **3.2% have used a government support program**. Internationally, credible neutral figures on the manual-vs-software split are scarce. The available numbers are mostly vendor-produced.

### Cited Findings
**Korea**
- 중소기업중앙회 소상공인 DX·AX 실태조사 (500 businesses, released June 2026; secondary): 80.0% use some digital/AI tool, but this includes 문서작성·키오스크·배달앱. 83.3% are at 기초+입문 level. Digital POS is the most used tool, at **68.3%** in 경영지원. 76.2% of non-users said they did not use tools "because they didn't know about them" (몰라서 못 썼다). 69.8% reported time savings, but only **11.0% felt a cost reduction**. **3.2% had joined a government support program.** — [헤럴드경제](https://www.heraldk.com/article/2026060817383372575); [헤럴드경제 (2)](https://www.heraldk.com/article/2026060918404673332). ⚠ Snippet only. The articles did not say whether 재고관리 was a separate item.
- 경기도시장상권진흥원 (1,991 소상공인, Dec 2024): digital/AI technology adoption rate **17.5%** — [메트로신문](https://www.metroseoul.co.kr/article/20241223500609) (snippet). The much lower rate reflects a stricter definition than the 중기중앙회 survey.
- 중기중앙회 키오스크 실태조사 (402 businesses, Dec 2024): 93.8% said kiosks help their business, saving about 138만원/month in labor. 29.6% had operating difficulties. **91.3% did not use government support** when they adopted. — [아주경제](https://www.ajunews.com/view/20241225143312192); [다음](https://v.daum.net/v/20241225162257933)
- GRI (경기연구원) study: each one-level rise in digital transformation is associated with **+7.2% sales**. Product-side digitization (재료 사입, online order and delivery) had an especially large effect. — [GRI Review PDF](https://grireview.gri.re.kr/xml/42854/42854.pdf) (snippet; academic/think-tank)

**International**
- ⚠VENDOR: inFlow Inventory (Aug 2026), construction and trades SMBs only. **86% track inventory in spreadsheets, 35% use pen and paper**, and about 1 in 5 use dedicated inventory software. — [inFlow blog](https://www.inflowinventory.com/blog/tag/survey)
- ⚠VENDOR, untraceable: "43% of SMBs track inventory manually" is often cited, for example by GeniusERP, with no original study or year given. **Do not use it.** — [GeniusERP](https://www.geniuserp.com/?p=2302)
- Adjacent, not about inventory, 2017: Wakefield Research for Concur (a ⚠VENDOR) found 84% of small businesses rely on manual processes daily and 69% use spreadsheets for budgeting. — [Small Business Trends](https://smallbiztrends.com/2017/04/manual-process.html)
- ⚠VENDOR content: Capterra has an Excel-vs-software guide for SMB inventory, but no survey figure was confirmed in the snippet. — [Capterra](https://www.capterra.com/resources/inventory-management-excel/)

### Inferences
- The Korean pattern is broad but shallow digital use. POS is common, but it records sales rather than managing stock or orders. The pitch can argue that POS data exists but is not linked to 발주 decisions. This is an inference. No Korean survey measured POS-to-inventory linkage.
- The 3.2% government-program participation and 76.2% "didn't know" figures point to an awareness and onboarding barrier, not just a cost barrier.

### Gaps
- **Wasp Barcode "State of Small Business"**: not found in search results (only Wasp product pages and case studies came up). The figure often attributed to it, "~46% of small businesses don't track inventory or do so manually", is from a 2016-era report and could not be verified this session. Don't cite it without the original PDF.
- **Intuit/QuickBooks** inventory-tracking survey: not found.
- **Unleashed** reports and the **Capterra** inventory survey: not retrieved.
- 소진공's own 소상공인 디지털 전환 실태조사 (if one is published under that name) was not located. The adoption-barrier percentages from it are unknown.

## Q3. How large are stockout, overstock, shrinkage and waste losses as a % of sales?

### Takeaway
The global retail headline is IHL Group's "inventory distortion": about **US$1.7–1.77 trillion a year**, of which out-of-stocks are about $1.2T and overstocks about $554–562B. This is ⚠VENDOR/analyst research covering all retail, not SMB-specific. In the US, NRF puts the average **shrink rate at 1.6% of sales** (FY2022). UNEP estimates **food service wastes 290 million tonnes of food a year** worldwide. No Korean restaurant-level waste or loss rate was found.

### Cited Findings
- IHL Group, *Fixing Inventory Distortion – Are We There Yet?* (2024 ed.): about **$1.7T** global inventory distortion, with out-of-stocks about $1.2T and overstocks about $554B (overstocks include markdowns and spoilage). That is 3.7% better than the prior year. Out-of-stocks are measured as lost customer sales. — [IHL Services product page](https://www.ihlservices.com/product/fixing-inventory-distortion-are-we-there-yet/) (⚠ paid analyst report; figures come from the public summary)
- IHL 2023 ed.: $1.77T ($1.2T OOS, $562B overstock) — [Chain Store Age](https://chainstoreage.com/ihl-group-inventory-issues-cause-17t-annual-losses) (secondary)
- IHL 2025 ed.: $1.77T, split into theft >$500B, retailer internal inefficiency ~$500B and supplier missteps >$300B. One later summary says empty shelves are $690.9B. A 2026 edition exists but was not retrieved. — [IHL](https://www.ihlservices.com/product/inventory-distortion/); [Board.com summary](https://www.board.com/resources/fixing-inventory-distortion) (⚠ Board is a planning-software vendor)
- NRF National Retail Security Survey 2023 (FY2022 data): average **shrink 1.6%** (1.4% in FY2021), equal to **$112.1B**. 65% of shrink comes from internal and external theft, so about 35% is process/admin error and other causes. Sample: 177 retail brands, $1.6T in sales, 97,000+ locations. These are **large retailers, not SMBs**. — [NRF](https://nrf.com/research-insights/national-retail-security-survey); [NRF 2023 report PDF via Appriss](https://info.apprissretail.com/hubfs/Resource-Center/2023.038-national-retail-security-survey-report-2023.pdf)
- UNEP Food Waste Index Report 2024 (2022 data): 1.05B tonnes of food wasted (132 kg/capita, about 1/5 of food available to consumers). Households 631Mt (60%), **food service 290Mt**, retail 131Mt. — [UNEP press release](https://www.unep.org/news-and-stories/press-release/world-squanders-over-1-billion-meals-day-un-report); [Key messages PDF](https://wedocs.unep.org/bitstream/handle/20.500.11822/45275/Food-Waste-Index-2024-key-messages.pdf?sequence=4)
- KREI frames food waste as 손실 (losses at production, processing and distribution) vs 폐기 (waste at sale and consumption) — [KREI repository](https://repository.krei.re.kr/bitstream/2018.oak/21930/1/%eb%af%b8%ea%b5%ad%ec%9d%98%20%ec%8b%9d%ed%92%88%20%ec%86%90%ec%8b%a4%20%ed%98%84%ed%99%a9%ea%b3%bc%20%ea%b3%bc%ec%a0%9c.pdf)
- Korean 집단급식소: an industry estimate says about 25% of food waste is food never served (미배식) — [비즈한국](https://bizhankook.com/articles/21570.html) (⚠ industry estimate, not official)

### Inferences
- NRF's 1.6% shrink (35% non-theft) plus IHL's overstock and spoilage gives a defensible international range: inventory-related losses of a few percent of sales. For SMBs without systems, the loss is plausibly higher, but **no source found quantifies this for SMBs**. Present it as a hypothesis to be confirmed by your own 현장 인터뷰/파일럿 data, for example 폐기액 tracked over 4 weeks.
- UNEP's 290Mt in food service is a strong global framing number. For Korea, the plan will need 환경부 음식물류 폐기물 statistics (not found here).

### Gaps
- No Korean statistic on restaurants' share of total 음식물류 폐기물, or on 식재료 폐기율 as % of purchases. 환경부「전국 폐기물 발생 및 처리현황」 and data.go.kr may have the former. The search did not surface it.
- NRF 2024/2025 editions changed format (the 2024 report stopped publishing an aggregate shrink rate, as far as I know; unverified). Only the 2023 report was confirmed.
- No SMB-specific stockout or overstock loss figure was found (Korea or international).

## Q4. Which government programs fund or promote digital inventory tools for small merchants, and what do they say about adoption barriers?

### Takeaway
The main vehicle is 소진공's **스마트상점 기술보급사업**. In 2026 it selected about 130 supplier companies in January and ran a second merchant round from 2026-09-01 to 09-30, offering 구입형, 렌탈형 and **S/W형 (SaaS)** support. The cap is about 500만원 per shop, with government funding of roughly 50–80% depending on item and merchant type. An inventory/ordering SaaS would fit the S/W형 track, ideally as a registered supplier. On barriers, the strongest data is from 중기중앙회: low awareness (76.2% "didn't know"), only 3.2% program participation, and 91.3% of kiosk adopters used no government support.

### Cited Findings
- 2026 스마트상점 기술보급사업: supplier recruitment (about 130 firms with commercialized smart tech such as kiosks, serving robots and AI solutions; applications due Jan 23; barrier-free tech gets a higher cap). Second merchant round 2026-09-01 to 09-30, in 구입형/렌탈형/S/W형 types. Businesses already supported by the program are excluded. — [TIPA 공고 파일](https://tipa.or.kr/s040104/file_down/id/21809); [넥스트유니콘](https://www.nextunicorn.kr/support-programs/1d8271538d52ea85); [THE VC](https://thevc.kr/grants/b88cb476c6ed4eb218428979)
- Support level: up to **500만원 per shop**. Government share is up to 70% generally, up to 80% for 간이과세자, 1인 자영업자 and 장애인 사업주, and 50% for generic tech such as 전자칠판 and 사이니지 (sources differ, so check the 공고). — [메트로신문](https://www.metroseoul.co.kr/article/20260826500026); [한경 머니 (옴니씨앤에스 2차 모집)](https://magazine.hankyung.com/money/article/202609016994c)
- Scale: "about 11,000 shops in 2026" comes from a ⚠blog source only. Unverified. — [studygov.kr](https://studygov.kr/blog/0444-small-business-smart-store-2026/)
- The program supports SaaS subscription costs, including 재고관리, per a blog-type source. ⚠ Confirm in the 공고 that 재고·발주 SW is an eligible category. — [tilnote](https://tilnote.io/pages/6a5f984ed14b3050aae3aaaa)
- Summary of 2026 소상공인 support programs (⚠VENDOR: Toss Place, a POS company) — [tossplace.com](https://tossplace.com/story/2026support)
- Barriers: see the Q2 figures (76.2% "didn't know", 3.2% participation, 83.3% basic level, 91.3% kiosk adopters without support, 29.6% with kiosk operating difficulties). An expert column argues 소상공인 DX policy should shift to a demand-side approach. — [아주경제 기고 2022](https://www.ajunews.com/view/20220527173009344)
- MTN (Dec 2022): a 중기중앙회 survey cited weak response to digital transformation as a factor in a worse business outlook — [MTN](https://news.mtn.co.kr/news-detail/2022122511085523501)

### Inferences
- In the plan, use "정책 수요": the government is already paying for 소상공인 SaaS through the S/W형 track, but participation and awareness are low. A product that is easy to onboard and eligible as a 스마트상점 supplier lowers the merchant's cost by 50–80%.
- Kiosk results (93.8% satisfied, about 138만원/month labor savings) are useful as an analogy: once adopted, tools show clear value. Adoption is the bottleneck.

### Gaps
- The official 2026 budget, number of shops, and full eligible-technology list for 스마트상점 were not confirmed from 소진공/중기부 primary pages (semas.or.kr, mss.go.kr were not reachable or not surfaced).
- 소진공 performance reports or evaluations of 스마트상점 (adoption and continued-use rates, barriers) were not found.
- Other relevant programs were not researched in depth: 소상공인 디지털 역량 교육, 스마트슈퍼, 희망리턴패키지, and 2026 AI 전환 지원 for 소상공인. Check 중기부's 2026 소상공인 지원사업 통합공고.
- KOSI (중소벤처기업연구원) reports on 소상공인 디지털 전환 were not retrieved.
