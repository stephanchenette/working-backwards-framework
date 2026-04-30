# Amazon Working Backwards Framework - Market Requirements Document (MRD)

## Your Role

**You are a Product Marketing Manager or Product Manager** responsible for defining market-driven product requirements.

**Your task is to create a Market Requirements Document (MRD)** that translates market needs into prioritized product requirements, bridging the gap between customer problems (PR/FAQ) and product specifications (PRD).

## Amazon's Working Backwards Philosophy

In Amazon's framework, the MRD supports the Working Backwards process by grounding the PR/FAQ's customer vision in market reality. It answers: "What does the market need?" not "What features should we build?"

### Core Principles

1. **Market-Driven, Not Feature-Driven**: Define WHAT customers need, not HOW to build it
2. **Customer Problem Focus**: Requirements should describe problems to solve, not solutions
3. **Prioritization Discipline**: Not everything can be P0 (must-have)
4. **Data-Backed**: Use market research, customer interviews, and competitive analysis
5. **GTM Integration**: Connect market requirements to go-to-market strategy

### Document Purpose

The MRD defines **market requirements**—the problems customers need solved—organized by theme. It informs the PRD but does not dictate features, UI, or technical implementation.

**Relationship to Other Documents**:
- **PR/FAQ**: Defines the customer experience (create this first)
- **Market Analysis**: Validates market size and opportunity
- **Competitive Analysis**: Identifies gaps in existing solutions
- **MRD** (this document): Defines market-driven requirements
- **PRD**: Translates MRD requirements into product specifications

---

> **Document Status:** [Draft, In Review, Approved]
>
> **Document Owner:** [Product Manager / Product Marketing Manager]
>
> **Last Updated:** [Date]

---

## 1. Executive Summary

_A brief, high-level overview for leadership, investors, and stakeholders. This section should summarize the entire document in 1-2 pages._

* **The Problem:** Concisely state the market problem or unmet customer need.
* **The Opportunity:** Describe the business opportunity this problem represents (e.g., market size, revenue potential, strategic value).
* **Target Audience:** Briefly define the primary customer segment(s) we will target.
* **Proposed Solution (High-Level Concept):** What is our conceptual approach to solving this problem?
* **Key Business Goals:** What are the 1-3 primary business objectives for this initiative?
  * Example: "Capture 10% market share in [segment] within 18 months"
  * Example: "Achieve $5M ARR by end of Year 2"
  * Example: "Establish category leadership in [niche]"

---

## 2. The Market Problem & Opportunity

_This section details the "why." It validates the problem's existence and size, based on market analysis._

### 2.1. Problem Statement

* **What is the specific, acute pain point?**
  * Describe the problem from the customer's perspective.
  * What are they struggling with today?
  * What is the emotional or business impact of this problem?

* **Who experiences this problem?**
  * Define the target audience experiencing this pain (link to Section 3 for personas).

* **Why does this problem exist?**
  * What are the root causes?
  * Examples: Existing solutions are too expensive, too complex, don't exist, or are outdated

### 2.2. Current Solutions & Their Gaps

* **How are customers solving this problem today?**
  * List direct competitors (similar products/services)
  * List indirect competitors (alternative approaches)
  * List manual workarounds or "do-it-yourself" methods

* **Why are these solutions failing to fully meet customer needs?**
  * Feature gaps (missing critical capabilities)
  * Pricing barriers (too expensive for target market)
  * Poor user experience (difficult to use, learn, or maintain)
  * Accessibility issues (language, geography, technical requirements)
  * Trust/reliability concerns

### 2.3. Market Opportunity

* **Market Sizing (TAM/SAM/SOM):**
  * **Total Addressable Market (TAM)**: The total revenue opportunity if you captured 100% of the market
  * **Serviceable Addressable Market (SAM)**: The portion of TAM your product can realistically serve
  * **Serviceable Obtainable Market (SOM)**: The realistic market share you can capture in the near term (3-5 years)

* **Market Trends:**
  * What industry, technology, or social trends make this opportunity compelling *now*?
  * Examples: New regulations, technology enablers (AI, mobile), demographic shifts, economic changes

---

## 3. Target Market & Personas

_This section defines exactly "who" we are building for. It translates market segments into human terms._

### 3.1. Primary Target Market

Provide a detailed description of the ideal customer segment:
* **Demographics**: Age, location, income, company size, industry
* **Psychographics**: Values, attitudes, behaviors, motivations
* **Market characteristics**: Size, growth rate, accessibility

**Example**: "Mid-market SaaS companies (50-500 employees) in North America with $5M-$50M ARR, experiencing rapid growth and struggling with [specific problem]."

### 3.2. Key User Personas

_List the 2-4 primary personas who will use the product. Focus on their problems and motivations._

---

#### **Persona Template**

**Persona 1: [Persona Name]**

* **Role & Demographics:**
  * Job title, age, experience level
  * Company size, industry
  * Technical proficiency

* **Core Problem(s):**
  * Primary pain points this persona experiences
  * Emotional or business impact of these problems
  * Current workarounds or solutions they use

* **Goals & Motivations:**
  * What are they trying to achieve?
  * What drives their decision-making?
  * What would success look like for them?

* **User Story Format:**
  * "As a [role], I need to [action] so that [benefit/outcome]."

**Example**:
* **Persona**: "The Overwhelmed Product Manager"
  * **Role**: Mid-level PM at a high-growth startup
  * **Problem**: "I'm drowning in roadmap requests and can't prioritize effectively"
  * **Goal**: "Ship the right features faster with confidence"
  * **User Story**: "As a product manager, I need to quickly analyze feature requests against business goals so that I can build a data-driven roadmap."

---

#### **Persona 2: [Persona Name]**

[Repeat persona template]

---

#### **Persona 3: [Persona Name]**

[Repeat persona template]

---

### 3.3. Secondary or "Anti-" Personas

* **Secondary Market**: Who else might benefit from this product but is not the primary focus?
  * Example: "While we're building for PMs, engineering leads may also find value in roadmap visibility."

* **Anti-Persona (Who we are *not* building for)**:
  * Define who this product is explicitly NOT for, to maintain focus.
  * Example: "Enterprise companies (>1000 employees) requiring extensive customization and white-glove service."

---

## 4. Competitive Landscape & Strategic Positioning

_This section defines where we fit in the market and how we will win._

### 4.1. Competitive Summary

* **Direct Competitors**: List 2-4 main competitors who solve the same problem with similar approaches
  * For each, note: Strengths, weaknesses, pricing, target market

* **Indirect Competitors**: Products or services that solve the problem differently
  * Example: If you're building a project management tool, indirect competitors might be "email + spreadsheets"

### 4.2. Our Unique Value Proposition (UVP)

A single, clear statement that explains our unique benefit, who it's for, and why we're different.

**Template**:
"For [Target Persona], who [Problem Statement], our product provides [Key Benefit / Solution]. Unlike [Main Competitor], we [Key Differentiator]."

**Example**:
"For mid-market product teams who struggle with data-driven prioritization, our product provides AI-powered roadmap recommendations. Unlike traditional roadmap tools, we automatically analyze customer feedback, usage data, and business metrics to suggest the highest-impact features."

### 4.3. Strategic Positioning

* **Market Position**: Where do we sit in the competitive landscape?
  * Example: "Premium but accessible," "Low-cost disruptor," "Enterprise-grade for SMBs"

* **Brand Attributes**: What 3-5 words should customers associate with our brand?
  * Example: Trustworthy, Simple, Powerful, Transparent, Innovative

* **Positioning Statement**: How we want to be perceived in the market
  * Example: "The most intuitive, data-driven roadmap tool for modern product teams."

---

## 5. Market Requirements

_This is the core of the MRD. It lists the prioritized problems to be solved and the user-centric requirements, grouped by theme._

**Important**: This section defines **WHAT** customers need, not **HOW** we'll build it. Features, UI, and technical specs belong in the PRD.

### 5.1. Prioritization Key

* **P0 (Must-Have)**: Critical to solving the core problem. Non-negotiable for launch.
* **P1 (Should-Have)**: High-impact requirement that addresses a key user need.
* **P2 (Nice-to-Have)**: Provides value but is not essential for the core solution.

### 5.2. Requirements by Theme

Organize market requirements by thematic area (e.g., Onboarding, Core Workflow, Trust & Security, Scalability).

---

#### **Theme Template**

**Theme: [e.g., Trust & Credibility]**

* **[P0] Problem**: [Describe the customer problem in this theme]
  * Example: "Users are skeptical of new tools and fear making the wrong choice."

* **[P0] User Story**: As a [persona], I need [capability] so that [benefit].
  * Example: "As a new user, I need to see proof of credibility (testimonials, case studies) so that I can trust the product."

* **[P1] User Story**: [Secondary requirement in this theme]

* **Market Requirement**: [High-level summary of what the market needs]
  * Example: "The product must establish trust and credibility from the first interaction."

---

**Example Themes to Consider** (adjust based on your product):

1. **Onboarding & Trust**: How do we get new users to trust and adopt the product?
2. **Core Workflow**: What is the primary job-to-be-done?
3. **Collaboration**: Do multiple users need to work together?
4. **Integration**: Does the product need to connect with other tools?
5. **Reporting & Analytics**: Do users need insights or dashboards?
6. **Scalability**: Can the product grow with the customer's needs?
7. **Security & Compliance**: What are the regulatory or security requirements?

---

## 6. Business Goals & Go-to-Market (GTM)

_This section connects the product to the business, defining what success looks like._

### 6.1. Business Objectives

Define 3-5 measurable business goals for this product:

* Example: "Achieve 10,000 active users in Year 1"
* Example: "Reach $2M ARR by end of Year 2"
* Example: "Establish partnerships with 50 companies in target vertical"
* Example: "Achieve freemium-to-paid conversion rate of 5%"

### 6.2. Key Success Metrics (KPIs)

| **Category**        | **Metric**                          | **Target**            | **Measurement Cadence** |
|---------------------|-------------------------------------|-----------------------|-------------------------|
| **Adoption**        | Number of active users (MAU)        | [Target number]       | Weekly / Monthly        |
| **Engagement**      | DAU/MAU ratio                       | [e.g., >30%]          | Weekly                  |
| **Conversion**      | Free-to-paid conversion rate        | [e.g., 5%]            | Monthly                 |
| **Retention**       | Monthly churn rate                  | [e.g., <5%]           | Monthly                 |
| **Revenue**         | ARR / MRR                           | [Target amount]       | Monthly                 |
| **Satisfaction**    | Net Promoter Score (NPS)            | [e.g., >50]           | Quarterly               |

### 6.3. Pricing & Packaging Strategy

* **Pricing Model**: How will customers be charged?
  * Examples: Freemium, subscription, usage-based, one-time purchase, marketplace commission

* **Pricing Tiers**: What tiers will be offered?

| **Tier**       | **Price**     | **Target Customer**       | **Key Features**                  |
|----------------|---------------|---------------------------|-----------------------------------|
| Free           | $0            | Individual users, trials  | [Core features, limited usage]    |
| Professional   | $X/month      | Small teams               | [Full features, higher limits]    |
| Enterprise     | Custom        | Large organizations       | [Advanced features, white-glove support] |

* **Justification**: Why is this pricing competitive and profitable?

### 6.4. Distribution Channels

* **Primary Channels**: How will we acquire customers?
  * Examples: Direct sales, self-service website, app stores, partnerships, marketplaces

* **Secondary Channels**: Additional acquisition methods
  * Examples: Content marketing (SEO, blog), paid advertising, events/conferences, influencer partnerships

* **Channel Strategy**: What percentage of customers do we expect from each channel?

| **Channel**              | **Expected % of Customers** | **CAC (Customer Acquisition Cost)** |
|--------------------------|-----------------------------|-------------------------------------|
| Organic (SEO)            | 40%                         | $X                                  |
| Paid Ads                 | 30%                         | $Y                                  |
| Partnerships             | 20%                         | $Z                                  |
| Referrals                | 10%                         | $W                                  |

---

## 7. Assumptions, Constraints, & Dependencies

### Key Assumptions

List critical assumptions that must be true for this product to succeed:

1. **Assumption**: [e.g., "Customers are willing to pay $X/month for this solution"]
   * **Validation method**: Pricing survey, beta testing, competitive benchmarking
   * **Risk if wrong**: [Impact on business model]

2. **Assumption**: [e.g., "We can achieve a 5% free-to-paid conversion rate"]
   * **Validation method**: Industry benchmarks, early pilot data
   * **Risk if wrong**: [Impact on revenue projections]

### Constraints

* **Technical Constraints**: [e.g., "Must support web, iOS, and Android"]
* **Budget Constraints**: [e.g., "Launch budget is $X"]
* **Timeline Constraints**: [e.g., "Must launch before Q2 2026"]
* **Regulatory Constraints**: [e.g., "Must be GDPR, SOC 2, and HIPAA compliant"]

### Dependencies

* **Internal Dependencies**: What other teams or systems must we rely on?
  * Example: "Requires data science team to build recommendation algorithm"
  * Example: "Requires infrastructure team to provision cloud resources"

* **External Dependencies**: What third-party vendors or partners are required?
  * Example: "Depends on Stripe for payment processing"
  * Example: "Depends on OpenAI API for AI features"

---

## 8. Out of Scope (What We Are Not Building)

_Clearly defines boundaries to prevent scope creep and ensure focus._

This is NOT a "future features" list. This section defines what we are explicitly choosing NOT to do in this version.

* Example: "We will not build a mobile app in V1 (web only)"
* Example: "We will not support non-English languages in V1"
* Example: "We will not offer white-label or API access in V1"
* Example: "We will not build custom integrations beyond [X, Y, Z] in V1"

---

## 9. Go-to-Market (GTM) Plan

### 9.1. Launch Strategy

* **Launch Date**: [Target date]
* **Launch Type**: [Private beta, public beta, general availability]
* **Launch Goals**: [e.g., "Acquire 500 signups in first month"]

### 9.2. Marketing Messaging

* **Core Message**: What is the one thing we want customers to remember?
  * Example: "The fastest way to build data-driven product roadmaps"

* **Value Props by Persona**: Tailor messaging to each persona
  * **For PMs**: "Stop guessing, start shipping the right features"
  * **For Engineering Leads**: "Align roadmaps with technical feasibility"

### 9.3. Launch Tactics

| **Tactic**                  | **Owner**              | **Timeline**       | **Budget**   |
|-----------------------------|------------------------|--------------------|--------------|
| Product Hunt launch         | Product Marketing      | Launch day         | $X           |
| Blog post & SEO             | Content Marketing      | 2 weeks pre-launch | $X           |
| Email to waitlist           | Growth Marketing       | Launch day         | $X           |
| Paid ads (Google, LinkedIn) | Performance Marketing  | Post-launch        | $X/month     |

### 9.4. Sales Enablement (if applicable)

* **Sales collateral**: Pitch deck, one-pager, demo script
* **Training**: Sales team training on product, personas, and objections
* **Launch incentives**: Early customer discounts, pilot programs

---

## 10. Success Criteria & Measurement

### Launch Success Metrics (First 30/60/90 Days)

| **Timeframe** | **Metric**                  | **Target**        | **Status** |
|---------------|-----------------------------|-------------------|------------|
| 30 days       | Total signups               | [e.g., 500]       | [Track]    |
| 30 days       | Activation rate             | [e.g., 60%]       | [Track]    |
| 60 days       | Free-to-paid conversions    | [e.g., 25]        | [Track]    |
| 90 days       | NPS                         | [e.g., >40]       | [Track]    |

### Long-Term Success Metrics (6-12 Months)

* **Revenue**: [$X ARR]
* **User Growth**: [X MAU]
* **Retention**: [<X% monthly churn]
* **Market Position**: [Top 3 in category, measured by G2/Capterra reviews]

---

## 11. Risks & Mitigation Strategies

| **Risk**                              | **Impact** | **Likelihood** | **Mitigation Strategy**                  | **Owner**           |
|---------------------------------------|------------|----------------|------------------------------------------|---------------------|
| Low customer adoption                 | High       | Medium         | Run beta program, iterate on feedback    | Product Manager     |
| Competitive response (price war)      | Medium     | Medium         | Differentiate on value, not just price   | Product Marketing   |
| Technical delays                      | High       | Low            | Build MVP first, phased rollout          | Engineering Lead    |
| Regulatory changes                    | Medium     | Low            | Monitor regulations, build compliance in | Legal / Product     |

---

## 12. Appendices

### A. Glossary of Terms

* **[Term 1]**: [Definition]
* **[Term 2]**: [Definition]

### B. Market Research Sources

* [Link to competitive analysis]
* [Link to user research findings]
* [Link to market sizing report]

### C. Supporting Documents

* **PR/FAQ**: [Link]
* **PRD**: [Link]
* **Competitive Analysis**: [Link]
* **Market Analysis**: [Link]

---

## MRD Best Practices

1. **Start with the customer problem, not the solution**: Validate the "why" before the "what"
2. **Use data to support claims**: Market size, customer pain points, and competitive gaps should be backed by research
3. **Keep personas specific**: Vague personas lead to vague products
4. **Prioritize ruthlessly**: Not everything can be P0
5. **Collaborate cross-functionally**: MRD should be co-created with Product, Marketing, Sales, and Customer Success
6. **Update regularly**: MRD is a living document that evolves as you learn more about the market

---

**End of MRD Template**
