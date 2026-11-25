📊 ITC Limited – Financial Performance Analysis & AI Assistant Framework

📌 Project Overview

This repository contains a comprehensive Financial Performance Analysis & Strategic Recommendation Report for ITC Limited (CIN: L16005WB1910PLC001985) spanning three consecutive financial years (FY 2023–24, FY 2024–25, and FY 2025–26), alongside a structured Financial Analysis Assistant prompt framework designed for MBA students, financial analysts, accountants, and business managers.

The project evaluates top-line revenue diversification, operating cost drivers, core vs. reported profitability (normalizing for the ITC Hotels Limited demerger), segment-wise EBIT margins, cash flow conversion, and strategic recommendations powered by AI-driven financial workflows.

🗂️ Repository Folder Structure

itc-financial-analysis-assistant/
│
├── README.md                                      # Project overview, financial summary & usage guide
├── LICENSE                                        # MIT License for academic & analytical use
├── .gitignore                                     # Standard exclusions for data & local environments
│
├── data/
│   ├── ITC-Report-and-Accounts-2024.pdf           # Audited Annual Report FY 2023–24
│   ├── ITC-Report-and-Accounts-2025.pdf           # Audited Annual Report FY 2024–25
│   └── lodr-21may26c.pdf                          # SEBI LODR Audited Results (Year Ended Mar 31, 2026)
│
├── reports/
│   ├── ITC_Comprehensive_Financial_Report.docx    # Full MBA Financial Analysis & Strategy Report
│   └── ITC_SWOT_and_Recommendations.md            # SWOT matrix & 10 strategic AI proposals
│
└── prompts/
    └── financial_analysis_assistant_prompt.md     # System prompt & output templates for AI workflows


🎯 Business Problem & Objectives

Problem Statement

"Financial Decision-Making Bottleneck Caused by High Information Density and Reporting Complexity in Multi-Segment Corporate Disclosures."

Analyzing multi-business conglomerates like ITC Limited across lengthy 300+ page statutory reports presents key challenges:

Multi-Segment Complexity: Divergent margins and capital intensities across Cigarettes, FMCG-Others, Agri Business, Paperboards & Packaging, and IT Services.

Inter-Segment Eliminations: Reconciling over ₹10,256.48 Crores in annual internal supply chain transfers.

Corporate Restructuring Distortions: Normalizing exceptional gains from the NCLT-approved demerger of the Hotels business into ITC Hotels Limited (₹15,016.01 Crores net exceptional gain in FY 2024–25).

Core Objectives

Evaluate consolidated revenue, expenses, EBITDA, net profit, and cash flows across FY 2023–24 to FY 2025–26.

Compute key financial ratios (CAGR, Net Profit Margins, Expense-to-Revenue, Debt-to-Equity, and Cash Conversion) step-by-step.

Identify operational, commodity, and regulatory risks.

Propose actionable strategic and AI-enabled recommendations to enhance capital efficiency (ROCE) and protect operating margins.

📂 Primary Data Sources

All financial figures in this analysis are grounded in ITC Limited's official audited disclosures:

ITC-Report-and-Accounts-2024.pdf – Audited Annual Report for FY 2023–24 (Consolidated Financial Statements & Note 29 Segment Reporting).

ITC-Report-and-Accounts-2025.pdf – Audited Annual Report for FY 2024–25 (Hotels Demerger Scheme, Note 30/31 Discontinued Operations, and Acquisitions).

lodr-21may26c.pdf – SEBI (LODR) Regulation 33 Audited Financial Results for the Year Ended March 31, 2026.

ITC Investor Relations & Quarterly Results Archives – Official corporate earnings releases and governance filings.

📈 Executive Financial Summary (Consolidated)

1. Multi-Year Performance Snapshot (FY 2023–24 to FY 2025–26)

Financial Metric (Consolidated)

FY 2023–24 (₹ Cr)

FY 2024–25 (₹ Cr)

FY 2025–26 (₹ Cr)

2-Year Change / CAGR

Revenue from Operations

76,840.49

81,612.78

89,913.33

+17.01% (8.17% CAGR)

Total Consolidated Expenses

52,448.49

57,325.95

64,391.12

+22.77%

Enterprise EBITDA

—

24,025.00

25,208.00

+4.92% YoY

PAT – Continuing Operations

20,751.36

20,036.47

21,018.15

+1.29%

Exceptional Gain (Discontinued Ops)

—

15,016.01

—

Hotels Demerger Gain

Total Reported PAT

20,751.36

35,052.48

21,018.15

Normalized in FY26

Net Operating Cash Flow

17,178.86

17,627.04

24,837.92

+44.58%

2. Segment-Wise Performance Breakdown (FY 2025–26)

Business Segment

Segment Revenue (₹ Cr)

Segment EBIT (₹ Cr)

EBIT Margin (%)

Strategic Role

FMCG – Cigarettes

36,256.60

22,245.62

61.36%

Primary cash & profit engine (>100% of continuing PAT)

FMCG – Others (Foods, Personal Care)

24,321.55

1,811.82

7.45%

Core non-tobacco consumer growth driver

Agri Business

20,787.33

1,584.24

7.62%

Export powerhouse & internal supply chain backbone

Paperboards, Paper & Packaging

8,768.58

754.06

8.60%

Transitioning toward sustainable barrier packaging

IT Services & Others (ITC Infotech)

5,036.23

583.11

11.58%

Scaled via Blazeclan & 24 Mantra Organic acquisitions

Inter-Segment Eliminations

(10,256.48)

—

—

Reflects >10.2% internal supply chain integration

3. Balance Sheet & Cash Flow Highlights (As of March 31, 2026)

Total Consolidated Assets: ₹93,792.38 Crores

Total Equity: ₹72,873.02 Crores

Total Borrowings: ₹2,186.22 Crores (Debt-to-Equity: 0.03x)

Liquid Reserves (Cash & Investments): >₹23,000 Crores

FY 2025–26 Capital Allocation: Funded ₹18,271.44 Crores in cash dividends and ₹2,182.89 Crores in capex purely through internal operating cash flows (118.17% cash conversion ratio).

🔍 Key Insights & Risk Assessment

Key Findings

Top-Line Diversification ('ITC Next' Strategy): Over 60% of gross segment revenue now originates from non-cigarette divisions, compounding consolidated revenue at 8.17% annually over two years.

Input Cost & Statutory Inflation: Total expenses grew +22.77% over two years—outpacing revenue growth (+17.01%)—driven by agricultural input inflation (Cost of Materials Consumed hit ₹26,272.33 Crores in FY26) and a ₹379.78 Crore one-time New Labor Codes gratuity adjustment.

Asset-Light Value Unlocking: Demerging the Hotels business distributed ₹22,033.37 Crores in fair value to shareholders while retaining ITC Grand Central, Mumbai under the 'Others' segment, boosting enterprise ROCE.

Key Financial Risks

Tobacco Taxation Concentration: Heavy reliance on Cigarettes (₹22,245.62 Cr EBIT) exposes group earnings to excise duty/GST cess revisions and illicit trade.

Foreign Paperboard Dumping: Low-priced imports from China and Indonesia alongside elevated domestic wood costs compressed Paperboards EBIT from ₹2,293.95 Crores (FY23) to ₹754.06 Crores (FY26).

Inventory & Commodity Volatility: Holding ₹18,622.96 Crores in inventory resulted in ₹362.93 Crores in write-downs/write-offs in FY 2025–26.

💡 Strategic Recommendations

Focus Area

Strategic Proposal

Expected Financial Impact

Expense Management

Predictive Commodity Hedging via ITCMAARS

Integrates crop intelligence from 2,050+ FPOs to hedge wheat, edible oil, and tobacco costs on ITC's ₹26,272 Cr raw material spend.

Margin Defense

Specialty Eco-Packaging Pivot in Paperboards

Shifts capacity toward plastic-substitute barrier boards (Filo, Bioseal) to counter Asian import dumping and restore double-digit margins.

FMCG Profitability

Brand-Level Activity-Based Costing (ABC)

Separates mature mother brands (Aashirvaad, Sunfeast) from gestation categories to lift FMCG-Others EBIT margin above 7.45%.

Financial Automation

AI Inter-Segment Reconciliation & Co-Pilot

Automates ₹10,256+ Cr inter-segment eliminations and enables natural-language C-suite querying across Ind AS disclosures.

Capital Allocation

ROCE Hurdle-Rate Matrix & ITCMAARS P&L

Enforces strict ROCE benchmarks for bolt-on acquisitions (Blazeclan, 24 Mantra) and monetizes digital farmer advisories.

🤖 Using the Financial Analysis Assistant Prompt

This repository also defines a reusable System Prompt (Financial Analysis Assistant) tailored for finance students and professionals:

Structured Output Format: Enforces an 8-point analytical structure (Introduction → Data Summary → Financial Analysis → Year-Wise Comparison → Key Findings → Risks & Limitations → Recommendations → Conclusion).

Strict Data Governance: Separates audited facts from calculations and assumptions, prohibits fabricating missing numbers, and includes built-in clarifying questions when user data is incomplete.

Quick Start (Git Upload)

git init
git add .
git commit -m "Initial commit: ITC Limited Financial Analysis & AI Assistant"
git branch -M main
git remote add origin https://github.com/<your-username>/itc-financial-analysis-assistant.git
git push -u origin main


📄 License & Disclaimer

License: Distributed under the MIT License for academic and research use.

Disclaimer: This repository is created for educational, academic (MBA Financial Analysis), and analytical demonstration purposes based on publicly available corporate disclosures of ITC Limited. It does not constitute personalized investment advice or guaranteed return projections.
