# Connect Earth — Product Imagery Index

144 images across 6 categories, in `connect-earth-product-imagery/`. This index was regenerated from a full manual visual re-audit (every file opened and inspected, not inferred from filenames) — the previous version had drifted out of sync with the actual file contents in a number of places (e.g. a file called `risk-management.png` actually showed an SDG chart). See the PR that introduced this version for the full audit trail.

Two other asset sets live elsewhere in this repo and are out of scope for this index: `product-screenshots/` (24 files, already accurately named — a dedicated set of ESG risk/controversy/exclusion-screening screenshots) and `brand/` (logos/logomarks) plus `collateral-generator/` (template backgrounds, referenced by hardcoded path from the `/gtm:collateral-generator` skill — do not rename anything in that folder).

**Known duplication:** roughly 20 files across `use-cases/asset-owners/`, `use-cases/wealth-advisors/`, and `use-cases/tech-platforms/` are exact-pixel duplicates of five underlying screenshots that also live in `use-cases/asset-managers/` (the ESG risk/score card, the SDG breakdown, the EET/SFDR export form, the "Complete Regulatory Reports" screen, and the Sustainable Investments methodology screen). They're left in place since consumers reference them per-persona, but a future cleanup could consolidate them into one shared location per screenshot.

---

## 1. Product Overview (`product-overview/`)

| File | Title | Description |
|------|-------|-------------|
| `Act product detail image.png` | Act — Carbon Actions Product | Phone mockup, Act tab: "Install solar panels" action card + electricity-spend savings widget overlay. |
| `Data product detail image.png` | Data — Carbon Intelligence Product | Phone mockup, "Your data" screen: "Complete your profile" / "Sync utilities data" cards. |
| `Insight product detail image.png` | Insight — Carbon Measurement Product | Phone mockup, Insight tab: "Suggested actions" and "Offers for you". |

---

## 2. Product Modules (`product-modules/`)

### ESG (`product-modules/esg/`)

| File | Title | Description |
|------|-------|-------------|
| `hero.webp` | ESG Pillar Scores + Search | E/S/G score cards (Environment/Social/Governance) with mini bar charts, plus a company/fund search bar. |
| `company.webp` | Company-level ESG Data | "Acme Corp ESG" detail page — E/S/G tabs and an Air Emissions data table (Scope 1/2/3, carbon footprint). |
| `pillar-breakdown-best-worst.svg` | Portfolio ESG Pillar Breakdown | Vector: three E/S/G pillar cards each with a metric dropdown, bar chart, portfolio line, and best/worst-in-fund rows. |
| `business-involvements.webp` | Business Involvements Screening | Grid of exclusion categories (Alcohol, Defense, Tobacco, Fossil Fuels, Firearms, etc.) with company counts. |
| `benchmark-comparison-cards.webp` | ESG Benchmark Comparison | Floating scorecards comparing a portfolio's ESG/E/S/G scores against the OMX 30 benchmark. |
| `search.webp` | ESG Company Search | Search bar with Recent Searches and a "By Framework" (ESG/SDG/SFDR) filter. |
| `pillar-scores-fund-comparison.webp` | ESG Pillar Scores, Fund Comparison | Full E/S/G pillar cards view with both best-in-fund and worst-in-fund company rows. |

### SDGs (`product-modules/sdgs/`)

| File | Title | Description |
|------|-------|-------------|
| `hero.avif` | SDG Overview — Most Aligned/Misaligned | "Most Misaligned"/"Most Aligned" SDG cards, top-3 SDGs by AUM%, Goals/Portfolio company table. |
| `alignment.avif` | SDG Revenue Alignment | Misaligned/Aligned SDG cards plus a Revenue Misalignment/Alignment/Self-Declared % detail table. |
| `top-sdgs-by-aum.webp` | Top SDGs by AUM | Grid of 8 SDG cards, each with an AUM % (Reduced Inequalities, Life on Land, Zero Hunger, etc.). |
| `portfolio.webp` | Portfolio-level SDG Tagging | Portfolio tab: companies table with AUM% and SDG icon tags per company. |
| `sdg-summary-top-goals.webp` | SDG Summary + Top Goals | Summary card ("9 of 18 companies…") next to an AUM-invested-in-SDG card with a ranked top-goals list. |
| `search.webp` | SDG Company Search | Same shared search UI as ESG — search bar, Recent Searches, By Framework filter. |

### Stewardship (`product-modules/stewardship/`)

| File | Title | Description |
|------|-------|-------------|
| `hero.webp` | Stewardship Overview | General Meetings / Nomination Committees / Impact Discussions summary cards with "+Add" actions. |
| `discussions.webp` | Impact Discussion Creation | "Create an Impact Discussion" form plus a status filter (Pending/On going/Successful/Unsuccessful). |
| `overview-summary-cards.webp` | Stewardship Summary (no actions) | Same three summary cards as the hero, without the "+Add" call-to-action buttons. |
| `meetings.webp` | General Meeting Creation | "Create a General Meeting" form (AGM/EGM, company, date, fund representative, role). |
| `nominations.webp` | Nomination Committee Creation | "Create a Nomination Committee" form (date of invitation, company, representative, shares %). |

### Temperature Score (`product-modules/temperature-score/`)

| File | Title | Description |
|------|-------|-------------|
| `hero.webp` | Temperature Score Overview | Portfolio-vs-benchmark temperature trend chart, temperature gauge, and a company ratings table. |
| `sbti-coverage-and-ratings-table.webp` | SBTi Coverage + Ratings Table | Filterable "Portfolio Temperature Score by Asset" table plus an SBTi-participation progress bar. |
| `portfolio-temperature-trend.webp` | Portfolio Temperature Trend | Quarterly portfolio-vs-benchmark temperature line chart and gauge. |
| `company-temperature-rating.webp` | Company Temperature Rating | Single-company Long Term Temperature Rating chart across Base/Short/Mid/Long term. |
| `top-positive-contributors.webp` | Top Positive Contributors | Table of top-contributing companies by temperature rating, with a quarters filter. |
| `top-off-track-holdings.webp` | Top Off-Track Holdings | Table of holdings furthest off their climate target, vs.-target in °C. |

---

## 3. Use Cases (`use-cases/`)

### Retail Banking (`use-cases/retail-banking/`)

| File | Title | Description |
|------|-------|-------------|
| `retail-banking-benefits-1.png` | Accounts + Carbon Footprint | Banking app home screen with transaction list, each annotated with kg CO2e, plus a footprint summary card. |
| `retail-banking-benefits-2.png` | Suggested Actions | "Suggested actions" cards (insulate water tanks, upgrade appliances) with an achievement badge. |
| `retail-banking-benefits-3.png` | Emissions Breakdown | Donut chart of monthly emissions by category (Bills & Utilities, Travel, Food & Groceries). |
| `retail-banking-benefits-4.png` | Electricity Spend + Savings | Electricity spend bar chart with estimated cost/CO2 savings, upfront cost, and payback time. |
| `retail-banking-benefits-5.png` | Bills & Utilities Breakdown | "Save up to £450" notification banner and a Bills & Utilities emissions gauge by sub-category. |

### Business Banking (`use-cases/business-banking/`)

| File | Title | Description |
|------|-------|-------------|
| `carbon-insight-dashboard-transactions.png` | SME Carbon Insight Dashboard | "Earth Bank" dashboard: total emissions/intensity KPIs, transaction feed with per-transaction CO2, category donut. |
| `Business banking insights 2.png` | ⚠️ Needs re-capture | Corrupted/composited screenshot — an "Internal portal" eligibility-report screen with an unrelated CRM activity-feed overlaid on top. Do not use until re-exported. |
| `building-data-onboarding-wizard.png` | Building Data Onboarding | "Building details" wizard step (construction year, floor area, wall material) with an asset/EPC panel. |
| `scope-1-2-3-emissions-report.png` | Scope 1/2/3 Emissions Report | Full Scope 1/2/3 emissions table (GHG Protocol categories) with a scope-breakdown donut chart. |
| `portfolio-financed-emissions-pcaf.png` | Financed Emissions (PCAF) | Lender-side portfolio financed-emissions dashboard with PCAF data-quality metrics and a 2030 reduction goal tracker. |

### Asset Managers (`use-cases/asset-managers/`)

| File | Title | Description |
|------|-------|-------------|
| `sfdr.png` | Regulatory Reports / PAI Statement | "Complete Regulatory Reports" panel — EET/PAI downloads, language selector, Hazardous Waste & Carbon Footprint charts. |
| `risk.png` | ESG Score Breakdown | E/S/G score cards with metric dropdowns, bar charts vs. portfolio average, best/worst-in-fund rows. |
| `sdg.png` | SDG Alignment | SDG tile breakdown (%AUM per goal) plus a Goals/Portfolio company table. |
| `sustainable.png` | Sustainable Investments Methodology | SI quarterly trend chart, "Set Sustainability Methodology" 3-step panel, Controversial exposure tags. |
| `eet.png` | EET / SFDR Export | EET export form: PAIs checklist, Pre-contractual/Periodic report fields, SFDR Article 6/8/9 radio, Export button. |
| `stewardship.png` | Stewardship Activity | General Meetings / Nomination Committees / Impact Discussions KPI cards plus a meeting-creation form. |

### Asset Owners (`use-cases/asset-owners/`)

| File | Title | Description |
|------|-------|-------------|
| `fund-lookthrough.png` | Fund Lookthrough | Fund search + drill-down into a fund's underlying Companies/Funds/Other holdings. |
| `regulatory-reports-pai-statement.png` | Regulatory Reports / PAI Statement | Same regulatory-reports screen as asset-managers/sfdr.png. |
| `sustainable-investments-methodology.png` | Sustainable Investments Methodology | Same SI methodology screen as asset-managers/sustainable.png. |
| `sdg-breakdown-portfolio.png` | SDG Breakdown | Same SDG tile + portfolio table as asset-managers/sdg.png (previously mislabeled "risk-management"). |
| `risk.png` | ESG Score Breakdown | Same E/S/G score card as asset-managers/risk.png. |
| `sdg.png` | SDG Alignment | Same SDG tile breakdown as asset-managers/sdg.png. |
| `eet-export-sfdr-form.png` | EET / SFDR Export | Same EET export form as asset-managers/eet.png (previously mislabeled "sdgs"). |
| `sfdr.png` | Regulatory Reports / PAI Statement | Same regulatory-reports screen as asset-managers/sfdr.png. |
| `esg-score-breakdown-card.png` | ESG Score Breakdown | Same E/S/G score card as asset-managers/risk.png (previously mislabeled "sustainable-investments"). |
| `sustainable.png` | Sustainable Investments Methodology | Same SI methodology screen as asset-managers/sustainable.png. |

### Wealth Advisors (`use-cases/wealth-advisors/`)

| File | Title | Description |
|------|-------|-------------|
| `end-client-report.png` | End Client Sustainability Card | Client-facing "Sustainability distribution of investments" donut chart. |
| `sustainable-investments-methodology.png` | Sustainable Investments Methodology | Same SI methodology screen as asset-managers/sustainable.png (previously mislabeled "mutual-funds"). |
| `sdg-breakdown-portfolio.png` | SDG Breakdown | Same SDG tile + portfolio table as asset-managers/sdg.png (previously mislabeled "risk-management"). |
| `eet-export-sfdr-form.png` | EET / SFDR Export | Same EET export form as asset-managers/eet.png (previously mislabeled "sdgs"). |
| `esg-score-breakdown-card.png` | ESG Score Breakdown | Same E/S/G score card as asset-managers/risk.png (previously mislabeled "sfdr-metrics"). |

### Management Companies (`use-cases/management-companies/`)

| File | Title | Description |
|------|-------|-------------|
| `esg-benchmarking.png` / `use-cases_esg-benchmarking.png` | ESG Peer Benchmarking | Three-column E/S/G peer-benchmark cards (bar charts vs. portfolio average). Previously mislabeled "risk" — no risk-specific metric is shown. |
| `eet.png` / `use-cases_eet.png` | EET / SFDR Export | Same EET export form as asset-managers/eet.png. |
| `sfdr.png` / `use-cases_sfdr.png` | Regulatory Reports / PAI Statement | Same regulatory-reports screen as asset-managers/sfdr.png. |
| `sustainable.png` / `use-cases_sustainable.png` | Sustainable Investments Methodology | Same SI methodology screen as asset-managers/sustainable.png. |
| `sdg.png` / `use-cases_sdg.png` | SDG Alignment | Same SDG tile breakdown as asset-managers/sdg.png. |

*(Each `use-cases_*`-prefixed file is a confirmed byte-identical duplicate of its non-prefixed sibling.)*

### EU Regulations (`use-cases/eu-regulations/`)

| File | Title | Description |
|------|-------|-------------|
| `eet-1.webp` | EET Builder — New Template | "Create a new EET" modal — reuse old responses vs. start from scratch. |
| `eet-pai-indicator-selection.webp` | EET — PAI Indicator Selection | Mandatory PAIs checklist (GHG Scope 1/2/3, Carbon Footprint) inside the EET flow. |
| `eet-3.webp` | EET — Completion Progress | Left-nav completion tracker with warning icons for missing PAI/PCDFP sections. |
| `eet-general-info-export.webp` | EET — General Info + Export | "Complete the EET" general-info form (manufacturer, LEI, year) with an Export EET button. |
| `mifid-sustainability-distribution-donut.png` | MiFID — Sustainability Distribution | Donut chart: Sustainability objective / E&S characteristics / Other. Previously mislabeled "end-client-report" (belongs here, not wealth-advisors). |
| `eet-sfdr-article-classification.png` | EET — SFDR Article Classification | PAIs card + Pre-contractual/Periodic report cards + Article 6/8/9 classification radios. Previously mislabeled "eu-taxonomy" — contains zero Taxonomy content. |
| `mifid-1.webp` | MiFID — Sustainability Distribution | Donut chart: Sustainability objective 13.95% / E&S characteristics 23.26% / Other 62.79%. |
| `mifid-esg-performance-ratings-table.png` | MiFID — ESG Performance Ratings | Company table with ESG Performance/Environment/Social qualitative ratings. |
| `mifid-3.webp` | MiFID — Leaders & Laggards | ESG leaders vs. laggards table with performance rating and portfolio weight. |
| `mifid-4.webp` | MiFID — Benchmark | Portfolio vs. benchmark bar comparison for ESG Score and Environment sub-score. |
| `pai-calculations.webp` | PAI Calculations | Read-only Mandatory PAIs / GHG Emissions tab. |
| `eet-general-info-form.webp` | EET — General Info Form | Same "Complete the EET" general-info form as eet-general-info-export.webp. Previously mislabeled "pai-eet-builder" (no PAI→EET import action shown). |
| `entity-pai-statement.webp` | Entity PAI Statement | "Entity PAI Statement, Year: 2022" — Mandatory PAI table (GHG Scope 1/2/3, Carbon Footprint). |
| `si-methodology-negative-screening-panel.png` | SI Methodology — Negative Screening | "Set Sustainability Methodology" 3-step panel + Controversial exposure tags. Previously mislabeled "pai-statement" — contains no PAI statement content. |
| `pai-time-series.webp` | PAI Time Series | GHG Emissions / Carbon Footprint / Solid Fossil Fuel Exposure mini trend charts vs. benchmark. |
| `regulatory-reports-language-export-menu.png` | Regulatory Reports Export Menu | "Complete Regulatory Reports" + "Download PAI Statement" dropdowns with a language selector. Previously mislabeled "periodic-report" (undocumented orphan, no periodic-report-specific content). |
| `pr-1.avif` | Periodic Report — Export | "Export Periodic Report Template" modal — language + file-structure options. |
| `si-methodology-questionnaire-with-compliance-checklist.avif` | SI Methodology Questionnaire | SI methodology questionnaire plus an SFDR Annex IV/V compliance checklist card. Previously mislabeled "pr-2" (periodic-report compliance) — dominant content is SI methodology. |
| `portfolio-report-status-list.avif` | Portfolio Report Status List | Multi-fund list with report status (Completed/In progress/Pending) per fund. |
| `pr-4.avif` | Periodic Report — PAI + Export | Mandatory PAIs table + GHG intensity chart + Export Periodic Report button. |
| `si-fund-lookthrough-methodology-selector.png` | SI Fund-of-Funds Methodology | Methodology-source selector for fund-of-funds (EET-declared vs. look-through vs. hybrid). Previously mislabeled "si-fof" implying a look-through results view, not a selector. |
| `si-environmental-criteria-and-sdg-selection.webp` | SI Environmental + SDG Criteria | Environmental-criteria multi-select plus an SDG checklist and controversial-exposure tags. Previously mislabeled "si-holdings" — no per-holding table shown. |
| `si-single-holding-classification-result.png` | SI Single-Holding Classification | "Acme has been classified as Sustainable" result modal with PAI exclusion/controversy criteria. Previously mislabeled "si-kpis" — this is a classification result, not KPI/threshold setup. |
| `si-methodology.png` | SI Methodology Definition | "Set your own Sustainable Investments Methodology" — PAI exclusion/inclusion thresholds, benchmark, 3-step nav. |
| `si-portfolio-sustainable-investment-percentage-trend.png` | SI % Trend | Sustainable-investment % quarterly trend vs. minimum-planned threshold band. |
| `esg-scorecard-environment-social-governance.png` | ESG Scorecard (E/S/G) | Three-column E/S/G scorecard with company-level benchmarking. Previously mislabeled "sustainable-investments" — no SI classification content. |
| `tax-company.png` | EU Taxonomy — Company Data | Company-level Taxonomy donut (Eligible-Aligned/Non-Aligned/Non-Eligible) + activities table. |
| `tax-navigate.png` | EU Taxonomy — Navigate Classification | Filter bar (Category, Env. objective, asset type) over the taxonomy trend chart. |
| `tax-portfolio.png` | EU Taxonomy — Portfolio Reports | Portfolio-level Taxonomy eligibility/alignment breakdown with an economic-activities table. |
| `tax-time.png` | EU Taxonomy — Progress Over Time | Same taxonomy view with Year/Quarter filter dropdowns open, illustrating time filtering. |

### Tech Platforms (`use-cases/tech-platforms/`)

| File | Title | Description |
|------|-------|-------------|
| `pai-ghg-emissions-detail.webp` | PAI — GHG Emissions Detail | Mandatory PAIs GHG Emissions detail table (Scope 1/2/3, Carbon Footprint, Intensity). Previously mislabeled "mutual-funds". |
| `pai-indicators.png` | Regulatory Reports / PAI Statement | Same regulatory-reports screen as asset-managers/sfdr.png. |
| `risk-esg.png` | ESG Score Breakdown | Same E/S/G score card as asset-managers/risk.png. |
| `sdgs.png` | SDG Alignment | Same SDG tile breakdown as asset-managers/sdg.png. |

---

## 4. Product Demos (`product-demos/`)

Consumer carbon-tracking app screens, plus two institutional platform screens and one developer/API screen (mixed audiences — see notes).

| File | Title | Description |
|------|-------|-------------|
| `standalone-platform-preview.png` | Institutional Platform — ESG Overview | Full desktop platform: sidebar nav (Portfolio/ESG/SDGs/SFDR) + ESG score comparison. *Institutional audience.* |
| `api-preview.png` | API Preview | Code editor showing a `connectEarth.postTransaction()` call. *Developer audience.* |
| `pai-statement.png` | PAI / SFDR Dashboard | 2×2 grid: GHG intensity chart, Mandatory PAIs accordion, tobacco exposure, SDG 14 alignment. *Institutional audience.* |
| `carbon-intelligence.png`, `carbon-intelligence-hr.png` | Carbon Intelligence — Suggested Actions | Consumer app, Insight tab, suggested-actions list. *Byte-identical pair.* |
| `data-profile.png`, `data-profile-hr.png` | Your Data / Profile Completion | Consumer app, "Your data" — complete profile / sync utilities. *Byte-identical pair.* |
| `action-group.png`, `action-group-hr.png` | Suggested Action Detail | Consumer app, "Install solar panels" action + electricity-spend overlay. *Byte-identical pair.* |
| `electricity-spend-chart.png` | Electricity Spend Chart | Standalone electricity-spend bar chart with savings estimate. |
| `emissions-category-breakdown-app.png` | Emissions Category Breakdown | Full-phone-frame donut chart by spend category. |
| `insight-congratulatory-messaging.png` | Achievement Messaging | "You've reduced your emissions in Car and Transport by 13%" card. |
| `insight-flight-emissions.png` | Flight Emissions | Single flight transaction with CO2/route detail. |
| `insight-lifestyle-questionnaire.png` | Lifestyle Questionnaire | Onboarding "How do you heat your home?" screen. |
| `business-emissions-transactions-monthly.png` | Business Emissions Transactions | SME-style monthly emissions total + vendor transactions tagged to cost centers ("Van #3", "Warehouse heating"). Previously mislabeled "insight-monthly-totals" — business audience, not the consumer app. |
| `insight-offset-integration.png` | Carbon Offset Marketplace | Gold Standard offset project purchase card. |
| `insight-pie-chart.png` | Emissions Categories Donut | Small monthly emissions-by-category donut widget. |
| `insight-recommendations.png` | Suggested Actions | "Avoid air-freighted produce" recommendations list. |
| `insight-time-series.png`, `time-series-chart.png` | Carbon Emissions Time Series | Monthly emissions bar chart (near-duplicate concept, different framing). |
| `transaction-list.png` | Transaction List | Consumer transaction list with per-item CO2e. |
| `transactions-actions.png` | Transactions + Suggested Actions | Transaction list overlapping a suggested-actions card. |

---

## 5. Logos (`logos/`)

| File | Brand | Type |
|------|-------|------|
| `emirates-nbd.png` | Emirates NBD | Banking client |
| `liv.png` | Liv (Emirates NBD) | Digital banking client |
| `emirates-islamic.png` | Emirates Islamic | Banking client |
| `fis-color.png` | FIS | Technology partner |
| `ubb-gray.png` | UBB | Banking client (grayscale render — previously mislabeled "-color") |
| `kbc-gray.png` | KBC | Banking client (grayscale render — previously mislabeled "-color") |
| `tide-color.png` | Tide | Business banking client |
| `yuh-black.png` | Yuh | Digital banking client |
| `thought-machine-black.png` | Thought Machine | Technology partner |
| `q2-black.png` | Q2 | Technology partner |
| `hsbc-life-logo.png` | HSBC Life | Banking client (HSBC's insurance sub-brand specifically, not the parent HSBC mark) |
| `barrow-hanley-logo.png` | Barrow Hanley Global Investors | Compliance / asset management client |
| `fineco-logo.png` | Fineco Asset Management | Compliance / asset management client |
| `finserve.avif` | Finserve | Compliance / asset management client |
| `iSEC.avif` | iSEC | Compliance / asset management client |
| `atlant-fonder.avif` | Atlant Fonder | Compliance / asset management client |
| `carlsson-noren-asset-management.avif` | Carlsson | Norén Asset Management | Compliance / asset management client |
| `consensus-asset-management.avif` | Consensus Asset Management | Compliance / asset management client |
| `landkreditt.avif` | Landkreditt | Compliance / asset management client |

---

*Regenerated from a full visual re-audit — July 2026.*
