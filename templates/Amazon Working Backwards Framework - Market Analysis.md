# Amazon Working Backwards Framework - Market Analysis

## Your Role

**You are a Market Strategist and Business Analyst** responsible for evaluating market opportunities and business viability.

**Your task is to create a Market Analysis** that validates whether a market opportunity is large enough, growing fast enough, and accessible enough to justify building a product.

## Amazon's Working Backwards Philosophy

In Amazon's framework, market analysis validates the PR/FAQ's customer vision by answering: "Is this market big enough to matter? Can we win here?"

### Core Principles

1. **Customer-First Validation**: Market size matters, but customer pain severity matters more
2. **Conservative Projections**: Under-promise and over-deliver on market potential
3. **Unit Economics Focus**: TAM is interesting, but unit economics determine success
4. **Honest Risk Assessment**: Identify risks early, with mitigation strategies
5. **Data-Driven Decisions**: Back all claims with credible sources and research

### Document Purpose

This market analysis helps you:
- Validate market size and growth potential (TAM/SAM/SOM)
- Understand market dynamics, trends, and timing ("why now?")
- Evaluate business model viability and unit economics
- Assess risks and identify strategic opportunities
- Make data-driven go/no-go decisions

**Relationship to Other Documents**:
- **PR/FAQ**: Defines the customer opportunity (validate this with market data)
- **Competitive Analysis**: Provides competitive context for market opportunity
- **MRD**: Market size and trends inform market requirements
- **PRD**: Business model constraints inform product scope

### Expected Outcome

A clear **GO / NO-GO / PIVOT** recommendation based on:
- Market opportunity size and growth
- Business model viability (unit economics)
- Competitive landscape and differentiation potential
- Risk assessment and mitigation strategies
- Capital requirements and path to profitability

---

> **Document Status:** [Draft, In Review, Approved]
>
> **Document Owner:** [Product Manager / Strategy Lead]
>
> **Last Updated:** [Date]

---

## Executive Summary

_1-2 page synthesis of findings with go/no-go recommendation_

* **Market Opportunity**: [Brief summary of market size, growth, and attractiveness]
* **Business Model Viability**: [Assessment of unit economics and scalability]
* **Strategic Recommendation**: [Go / No-Go / Pivot, with key rationale]
* **Key Risk Factors**: [Top 3 risks that could derail success]
* **Capital Requirements**: [Estimated funding needed to achieve profitability]

---

## 1. Market Definition & Sizing

### 1.1 Total Addressable Market (TAM)

_The total revenue opportunity if you captured 100% of the entire market._

**Definition**: [Describe the broadest definition of your market]

**Calculation Method**:
* **Top-down approach**: [e.g., "Global market for X = $Y billion (Source: Gartner, 2025)"]
* **Bottom-up approach**: [e.g., "Number of potential customers × Average spend per customer"]

**TAM Size**: $[Amount]

**Geographic Breakdown**:
* **North America**: $[Amount] ([X]% of TAM)
* **Europe**: $[Amount] ([X]% of TAM)
* **Asia-Pacific**: $[Amount] ([X]% of TAM)
* **Other regions**: $[Amount] ([X]% of TAM)

**Growth Rates**:
* **Historical (5-year CAGR)**: [X]%
* **Projected (5-year CAGR)**: [X]%

**Methodology Transparency**:
* **Data sources**: [List sources: industry reports, government data, analyst firms]
* **Assumptions**: [Key assumptions in your calculation]

---

### 1.2 Serviceable Addressable Market (SAM)

_The portion of TAM your product can realistically serve, given your business model, geography, and target customer._

**Definition**: [Describe the specific subset of TAM you can serve]

**SAM Size**: $[Amount]

**Filters Applied** (to get from TAM to SAM):
* **Geographic constraints**: [e.g., "English-speaking markets only"]
* **Customer segment**: [e.g., "Companies with 10-500 employees"]
* **Budget availability**: [e.g., "Customers who can afford $100+/month"]
* **Digital adoption**: [e.g., "Customers willing to use cloud-based tools"]
* **Regulatory constraints**: [e.g., "Markets where we can legally operate"]

**Justification**: [Explain why this is the realistic serviceable market]

---

### 1.3 Serviceable Obtainable Market (SOM)

_The realistic market share you can capture in the near term (3-5 years), accounting for competition and execution challenges._

**SOM Size (Year 3)**: $[Amount] ([X]% of SAM)

**Calculation Basis**:
* **Industry growth benchmarks**: [Reference similar companies' growth trajectories]
* **Competitive landscape**: [How crowded is the market?]
* **Distribution channels**: [How quickly can we acquire customers?]
* **Execution timeline**: [Multi-region rollout, product development phases]

**Realistic Capture Assumptions**:
* **Year 1**: [X]% of SAM = $[Amount]
* **Year 2**: [X]% of SAM = $[Amount]
* **Year 3**: [X]% of SAM = $[Amount]

---

## 2. Market Segmentation & Demographics

### 2.1 Segment Sizing & Growth

_Break down your market by key customer segments._

| **Segment**               | **Size (Users/Companies)** | **Growth Rate** | **Digital Adoption** | **Price Sensitivity** |
|---------------------------|----------------------------|-----------------|----------------------|-----------------------|
| [Segment 1: e.g., Enterprise] | X million                 | [X]% CAGR       | High                 | Low                   |
| [Segment 2: e.g., Mid-Market]  | X million                 | [X]% CAGR       | High                 | Medium                |
| [Segment 3: e.g., SMB]         | X million                 | [X]% CAGR       | Medium               | High                  |
| [Segment 4: e.g., Consumer]    | X million                 | [X]% CAGR       | Very High            | Very High             |

**Key Insights**:
* [Insight 1: e.g., "SMB segment is fastest-growing but most price-sensitive"]
* [Insight 2: e.g., "Enterprise segment has highest LTV but longer sales cycles"]

---

### 2.2 Geographic Market Prioritization

_Rank markets by attractiveness for entry and expansion._

| **Market**        | **Size** | **Growth** | **Ease of Entry** | **Competitive Intensity** | **Priority** |
|-------------------|----------|------------|-------------------|---------------------------|--------------|
| United States     | $X       | [X]%       | High              | High                      | Tier 1       |
| United Kingdom    | $X       | [X]%       | Medium            | Medium                    | Tier 1       |
| Canada            | $X       | [X]%       | High              | Medium                    | Tier 2       |
| Germany           | $X       | [X]%       | Medium (language) | High                      | Tier 2       |
| India             | $X       | [X]%       | Low (localization)| Very High                 | Tier 3       |

**Tier 1 Markets**: [Launch priority]
**Tier 2 Markets**: [Expansion in Year 2-3]
**Tier 3 Markets**: [Future consideration]

**Market Entry Barriers**:
* **Localization costs**: [e.g., "Translation, cultural adaptation"]
* **Regulatory requirements**: [e.g., "GDPR in EU, data residency in certain countries"]
* **Payment infrastructure**: [e.g., "Credit card penetration, mobile payments"]

---

### 2.3 Demographic Trends Impact

_How demographic and behavioral trends affect your market._

**Relevant Trends**:
1. **[Trend 1: e.g., "Gen Z/Alpha are mobile-first, AI-native"]**
   * **Impact**: [e.g., "Expect seamless mobile experience and AI features"]
   * **Opportunity/Threat**: [How this affects your product]

2. **[Trend 2: e.g., "Remote work shift"]**
   * **Impact**: [e.g., "Increased demand for collaboration tools"]
   * **Opportunity/Threat**: [How this affects your product]

3. **[Trend 3: e.g., "Privacy concerns rising"]**
   * **Impact**: [e.g., "Customers demand data control and transparency"]
   * **Opportunity/Threat**: [How this affects your product]

---

## 3. Business Model & Unit Economics

### 3.1 Revenue Model Validation

**Revenue Model**: [e.g., Subscription, freemium, usage-based, marketplace commission]

**Pricing Benchmarks** (from competitors and analogous markets):
* **Free tier**: [What do competitors offer for free?]
* **Entry tier**: $[X]/month (Competitor A: $Y, Competitor B: $Z)
* **Professional tier**: $[X]/month
* **Enterprise tier**: Custom (typically $[X]+)

**Conversion Funnel Metrics** (industry benchmarks vs. targets):

| **Stage**                | **Industry Benchmark** | **Our Target** | **Rationale**                     |
|--------------------------|------------------------|----------------|-----------------------------------|
| Freemium→Paid conversion | 2-5%                   | [X]%           | [e.g., "Better onboarding"]       |
| Trial→Paid conversion    | 20-30%                 | [X]%           | [e.g., "Faster time-to-value"]    |
| Monthly churn            | 3-7%                   | [X]%           | [e.g., "Stronger product-market fit"] |

**Pricing Elasticity**:
* **Sweet spot by segment**: [e.g., "$99/mo for mid-market, $500/mo for enterprise"]
* **Justification**: [Why customers will pay this amount]

**Revenue Mix Evolution** (Year 1 → Year 3):

| **Revenue Source**       | **Year 1** | **Year 2** | **Year 3** |
|--------------------------|------------|------------|------------|
| Subscription             | 80%        | 70%        | 60%        |
| Add-ons / Upsells        | 15%        | 20%        | 25%        |
| Partnerships / Affiliates| 5%         | 10%        | 15%        |

---

### 3.2 Customer Economics Model

**Customer Acquisition Cost (CAC)**: $[X]

**Breakdown by channel**:
* **Organic (SEO, content)**: $[X]
* **Paid ads**: $[X]
* **Partnerships**: $[X]
* **Sales (for enterprise)**: $[X]

**Lifetime Value (LTV)**: $[X]

**LTV Calculation**:
* **Average Revenue Per User (ARPU)**: $[X]/month
* **Average Customer Lifespan**: [X] months
* **Gross Margin**: [X]%
* **LTV = ARPU × Lifespan × Gross Margin**

**Key Metrics**:
* **LTV:CAC Ratio**: [X]:1 (Target: >3:1)
* **Payback Period**: [X] months (Target: <12 months)
* **Monthly Churn**: [X]% (Target: <5%)
* **Gross Margin**: [X]% (Target: >70% for SaaS)

**Unit Economics Health Check**:
* ✅ / ❌ LTV:CAC > 3:1
* ✅ / ❌ Payback period < 12 months
* ✅ / ❌ Monthly churn < 5%
* ✅ / ❌ Gross margin > 70%

---

### 3.3 Cohort Behavior Patterns

**Seasonality Impact**:
* **[e.g., Q4 holiday slowdown]**: [Impact on revenue]
* **[e.g., January surge in B2B budgets]**: [Opportunity to capitalize]

**Retention Curves** (by cohort):
* **Month 1 retention**: [X]%
* **Month 6 retention**: [X]%
* **Month 12 retention**: [X]%

**Expansion Revenue**:
* **[e.g., Multi-user expansion]**: [X]% of customers add seats over time
* **[e.g., Upsells to higher tiers]**: [X]% of customers upgrade
* **[e.g., Referrals]**: [X]% of customers refer others

---

## 4. Distribution Channel Economics

### 4.1 Channel Performance Matrix

_Evaluate the effectiveness of each customer acquisition channel._

| **Channel**              | **CAC** | **Scalability** | **Time to Scale** | **Expected Market Share** |
|--------------------------|---------|-----------------|-------------------|---------------------------|
| **Organic (SEO/Content)**| $[X]    | High            | 12-18 months      | 30-40%                    |
| **Paid Ads (Google/FB)** | $[X]    | High            | 1-3 months        | 20-25%                    |
| **Partnerships (B2B2C)** | $[X]    | Medium          | 6-12 months       | 20-30%                    |
| **Direct Sales (Enterprise)** | $[X] | Low           | 3-6 months        | 10-15%                    |
| **App Stores**           | $[X]    | Medium          | 3-6 months        | 5-10%                     |
| **Influencer/Creator**   | $[X]    | Medium          | 3-6 months        | 5-10%                     |

**Channel Strategy Recommendations**:
1. **Primary channel (Year 1)**: [e.g., "Paid ads to validate messaging, then scale SEO"]
2. **Secondary channel (Year 1-2)**: [e.g., "Partnerships for credibility and distribution"]
3. **Long-term (Year 2+)**: [e.g., "Organic dominance + product-led growth"]

---

### 4.2 Viral Growth Mechanics

**Network Effects Potential**:
* **Direct network effects**: [e.g., "More users = more value (social platforms)"]
* **Indirect network effects**: [e.g., "More users = better data = better product"]

**Viral Coefficient (K-Factor)**: [X]
* **Calculation**: (Invitations sent per user) × (Conversion rate of invitations)
* **Target**: >1.0 for self-sustaining viral growth

**Natural Sharing Moments**:
* [e.g., "User achieves milestone and shares on social media"]
* [e.g., "Collaborative features encourage team invites"]

**Referral Program Economics**:
* **Incentive structure**: [e.g., "$10 credit for referrer, $10 for referee"]
* **Cost per referred customer**: $[X]
* **Referral conversion rate**: [X]%

---

### 4.3 Partnership Ecosystem Economics

**Partnership Types**:
1. **Distribution partners**: [e.g., "Sell through partner channels"]
2. **Integration partners**: [e.g., "Embed in other platforms"]
3. **Co-marketing partners**: [e.g., "Joint webinars, content"]

**Revenue Share Models** (industry benchmarks):
* **Affiliate commissions**: [e.g., "10-20% of first-year revenue"]
* **Reseller margins**: [e.g., "20-30% recurring revenue share"]

**Channel Conflict Management**:
* **Direct vs. partner sales**: [How will you handle overlapping territories?]

**Integration Costs**:
* **API development**: $[X] per integration
* **Maintenance**: $[X]/year per integration

---

## 5. Market Dynamics & Timing

### 5.1 Market Maturity Indicators

**Where is this market on the adoption curve?**
* ❌ Innovators (2.5%)
* ❌ Early Adopters (13.5%)
* ✅ Early Majority (34%) ← [Indicate where you believe the market is]
* ❌ Late Majority (34%)
* ❌ Laggards (16%)

**Indicators**:
* **Digital adoption**: [e.g., "70% of target market uses cloud-based tools"]
* **Funding velocity**: $[X] invested in this category in last 24 months
* **M&A activity**: [List recent acquisitions and their multiples]
* **Consumer behavior shifts**: [e.g., "Post-COVID remote work permanence"]

**Implication for Strategy**:
* [e.g., "Market is ready for mainstream adoption—focus on ease of use and clear value prop"]

---

### 5.2 Disruption Timing Factors

**Why Now?**

1. **Technology enablers**: [e.g., "AI costs have dropped 90%, enabling new use cases"]
2. **Consumer/business readiness**: [e.g., "Customers now expect AI-powered solutions"]
3. **Economic shifts**: [e.g., "Recession drives demand for cost-saving tools"]
4. **Regulatory changes**: [e.g., "New privacy laws create compliance needs"]

**Window of Opportunity**:
* **How long do we have before the market consolidates?**: [e.g., "18-24 months"]
* **First-mover advantages**:
  * [e.g., "Data accumulation creates defensibility"]
  * [e.g., "Brand equity as category leader"]
  * [e.g., "Network effects lock in users"]

---

### 5.3 Market Inflection Points

**Catalysts that could accelerate growth**:
1. **[e.g., "Major platform (Salesforce, Microsoft) partners with category leaders"]**
   * **Impact**: [How this changes the market]
2. **[e.g., "Regulatory mandate (like GDPR for privacy)"]**
   * **Impact**: [Drives demand for compliant solutions]
3. **[e.g., "Technology breakthrough (e.g., GPT-5 launch)"]**
   * **Impact**: [Enables new capabilities, resets competitive landscape]

**Risks that could slow growth**:
1. **[e.g., "Economic downturn reduces enterprise spending"]**
2. **[e.g., "Major competitor (Google, Amazon) enters market"]**
3. **[e.g., "Commoditization—features become free or open source"]**

---

## 6. Risk Assessment & Mitigation

### 6.1 Market Risks (Ranked by Impact × Likelihood)

| **Rank** | **Risk**                                | **Impact** | **Likelihood** | **Mitigation Strategy**                    |
|----------|-----------------------------------------|------------|----------------|--------------------------------------------|
| 1        | Market size contraction                 | High       | Low            | [e.g., "Diversify into adjacent markets"]  |
| 2        | Commoditization (AI becomes free)       | High       | Medium         | [e.g., "Build proprietary data moat"]      |
| 3        | Channel saturation (CAC inflation)      | Medium     | High           | [e.g., "Invest in organic/viral channels"] |
| 4        | Regulatory intervention                 | Medium     | Low            | [e.g., "Build compliance from day 1"]      |
| 5        | Economic downturn                       | Medium     | Medium         | [e.g., "Focus on ROI-driven products"]     |

---

### 6.2 Regulatory Landscape

**Current Regulations**:
* **[Region/Country 1]**: [e.g., "GDPR in EU—data privacy requirements"]
* **[Region/Country 2]**: [e.g., "CCPA in California—consumer privacy rights"]
* **[Industry-specific]**: [e.g., "HIPAA for healthcare, SOC 2 for B2B SaaS"]

**Pending Legislation** (that could impact your business):
* **[e.g., "AI regulation in EU"]**: [Impact on product development]
* **[e.g., "Antitrust scrutiny of big tech"]**: [Impact on partnerships]

**International Compliance**:
* **GDPR (EU)**: [Compliance requirements and costs]
* **Data residency laws**: [e.g., "China, Russia require local data storage"]

**Regulatory Arbitrage Opportunities**:
* **Favorable jurisdictions**: [e.g., "Incorporate in Delaware, host data in US/EU"]

---

## 7. Financial Projections & Scenarios

### 7.1 Base Case Model (3-Year Projections)

| **Metric**               | **Year 1** | **Year 2** | **Year 3** |
|--------------------------|------------|------------|------------|
| **Free Users**           | 50K        | 250K       | 1M         |
| **Paid Users**           | 1K         | 12.5K      | 75K        |
| **ARR**                  | $120K      | $1.5M      | $9M        |
| **Gross Margin**         | 70%        | 75%        | 80%        |
| **Burn Rate**            | ($1M)      | ($2M)      | $500K profit |
| **Employees**            | 10         | 30         | 75         |

**Key Assumptions**:
* **Free→Paid conversion**: [X]%
* **Average ACV (Annual Contract Value)**: $[X]
* **Monthly churn**: [X]%
* **CAC**: $[X] (Year 1) → $[X/2] (Year 3 with efficiency gains)

---

### 7.2 Sensitivity Analysis

_How do changes in key variables affect outcomes?_

| **Variable**           | **-20%**   | **Base Case** | **+20%**   |
|------------------------|------------|---------------|------------|
| **CAC**                | $[X] ARR   | $[Y] ARR      | $[Z] ARR   |
| **Conversion Rate**    | $[X] ARR   | $[Y] ARR      | $[Z] ARR   |
| **Churn Rate**         | $[X] ARR   | $[Y] ARR      | $[Z] ARR   |
| **Pricing**            | $[X] ARR   | $[Y] ARR      | $[Z] ARR   |

**Break-Even Thresholds**:
* **Minimum conversion rate needed**: [X]%
* **Maximum tolerable CAC**: $[X]
* **Maximum tolerable churn**: [X]%

---

### 7.3 Funding Requirements

**Capital Needed to Reach Profitability**: $[X]M

**Use of Funds**:
* **Product development**: [X]% ($[X])
* **Sales & marketing**: [X]% ($[X])
* **Operations & infrastructure**: [X]% ($[X])
* **General & administrative**: [X]% ($[X])

**Fundraising Milestones**:
* **Seed round**: $[X]M to achieve [milestone: e.g., "product-market fit, $500K ARR"]
* **Series A**: $[X]M to achieve [milestone: e.g., "$3M ARR, proven unit economics"]
* **Series B**: $[X]M to achieve [milestone: e.g., "$15M ARR, multi-market expansion"]

**Path to Profitability**:
* **Timeline**: [e.g., "36 months from launch"]
* **Key drivers**: [e.g., "CAC efficiency, reduced churn, pricing optimization"]

---

## 8. Strategic Market Opportunities

### 8.1 Adjacent Market Expansion

_Where can you expand once you dominate your core market?_

1. **[Adjacent Market 1]**: [e.g., "Test prep" if you're in college advising]
   * **Market size**: $[X]
   * **Strategic fit**: [Why this makes sense]
   * **Entry timeline**: [When to pursue]

2. **[Adjacent Market 2]**: [e.g., "Career coaching"]
   * **Market size**: $[X]
   * **Strategic fit**: [Shared customer base, complementary product]

3. **[Adjacent Market 3]**: [e.g., "International expansion"]
   * **Market size**: $[X]
   * **Strategic fit**: [Leverage existing product with localization]

---

### 8.2 Geographic Expansion Sequence

**Phase 1** (Year 1): [e.g., "English-speaking markets: US, UK, Canada, Australia"]
**Phase 2** (Year 2): [e.g., "Western Europe: Germany, France, Netherlands"]
**Phase 3** (Year 3+): [e.g., "Asia: India, Southeast Asia"]

**Market Entry Strategies**:
* **Phase 1**: Direct (own sales, marketing)
* **Phase 2**: Partnership (local distributors)
* **Phase 3**: Acquisition (buy local player)

---

### 8.3 Exit Strategy Considerations

**Potential Acquirers**:
1. **Strategic buyers**: [e.g., "Education companies, publishers, test prep firms"]
2. **Tech platforms**: [e.g., "Google, Microsoft expanding into education"]
3. **Private equity**: [e.g., "EdTech roll-ups, Vista Equity Partners"]

**Valuation Benchmarks** (recent comparable exits):
* **[Company A]**: Acquired for [X]x ARR
* **[Company B]**: Acquired for [X]x ARR
* **Current market multiples**: [X]-[Y]x ARR for similar companies

**Exit Timeline**: [e.g., "3-5 years, targeting strategic acquisition"]

**Strategic Value Drivers** (what makes you attractive to acquirers):
* [e.g., "Proprietary data set"]
* [e.g., "Strategic customer base"]
* [e.g., "Technology platform with network effects"]

---

## 9. Key Success Metrics

### 9.1 Market Capture Indicators

| **Indicator**               | **Year 1** | **Year 2** | **Year 3** |
|-----------------------------|------------|------------|------------|
| **Market share (% of SAM)** | [X]%       | [X]%       | [X]%       |
| **Share of voice (SEO)**    | [Rank]     | [Rank]     | [Rank]     |
| **Brand awareness**         | [X]%       | [X]%       | [X]%       |

---

### 9.2 Business Health Metrics

* **Magic Number** (Sales Efficiency): [ARR added / Sales & Marketing spend]
  * **Target**: >0.75
  * **Our projection**: [X]

* **Quick Ratio** (Growth vs. Churn): [New + Expansion ARR / Churned ARR]
  * **Target**: >4
  * **Our projection**: [X]

* **Rule of 40** (Growth + Profitability): [Growth rate % + Profit margin %]
  * **Target**: >40%
  * **Our projection**: [X]%

---

### 9.3 Investor Milestones

**Seed → Series A**:
* **ARR**: $1M+
* **Product-market fit**: NPS >50, retention >80%
* **Proof of concept**: Proven unit economics (LTV:CAC >3)

**Series A → Series B**:
* **ARR**: $5M+
* **Growth rate**: 3x YoY
* **Efficiency**: CAC payback <12 months

**Series B → Series C**:
* **ARR**: $20M+
* **Multi-market success**: Proven international expansion
* **Category leadership**: Top 3 in market by share/brand

---

## 10. Conclusion & Recommendation

### Critical Market Insights Summary

✅ / ❌ **Market opportunity**: Size, growth, and timing aligned
✅ / ❌ **Business model viability**: Unit economics proven
✅ / ❌ **Distribution strategy**: Scalable channels identified
✅ / ❌ **Risk mitigation**: Major risks addressable
✅ / ❌ **Capital efficiency**: Path to profitability clear
✅ / ❌ **Exit potential**: Strategic value creation evident

### Final Recommendation

**[GO / NO-GO / PIVOT]**

**Rationale**:
[1-2 paragraphs explaining your recommendation based on the analysis above]

**Next Steps** (if GO):
1. [e.g., "Validate pricing with customer interviews"]
2. [e.g., "Build financial model with sensitivity analysis"]
3. [e.g., "Develop GTM plan and channel strategy"]

---

## Appendices

### A. Market Sizing Methodology and Sources

* **TAM calculation**: [Detailed methodology]
* **Data sources**: [List all sources used]
* **Assumptions**: [Key assumptions and confidence levels]

### B. Financial Model with Assumptions

* [Link to detailed spreadsheet]

### C. Regulatory Compliance Matrix by Market

| **Market** | **Regulations** | **Compliance Cost** | **Timeline** |
|------------|-----------------|---------------------|--------------|
| [Market 1] | [e.g., GDPR]    | $[X]                | [X months]   |

### D. Partnership Term Sheet Benchmarks

* **Revenue share**: [Industry standards]
* **Exclusivity**: [Typical terms]
* **SLAs**: [Service level agreements]

### E. Exit Comparable Analysis

| **Company** | **Exit Type** | **Valuation** | **Revenue Multiple** |
|-------------|---------------|---------------|----------------------|
| [Company A] | [Acquisition] | $[X]M         | [X]x ARR             |

---

## Market Analysis Best Practices

1. **Use multiple data sources**: Don't rely on a single report—triangulate data
2. **Be conservative with projections**: Better to under-promise and over-deliver
3. **Update regularly**: Markets change—revisit quarterly
4. **Focus on obtainable market (SOM)**: TAM is interesting, but SOM determines success
5. **Validate assumptions with real data**: Customer interviews, beta tests, pilot programs
6. **Connect to strategy**: Market analysis should drive product, GTM, and fundraising decisions

---

**End of Market Analysis Template**
