# Amazon Working Backwards Framework - Complete Guide

This directory contains a complete set of strategic planning templates based on Amazon's Working Backwards methodology, adapted for tech startups and product development.

---

## Table of Contents

1. [What is Working Backwards?](#what-is-working-backwards)
2. [The 7 Templates Explained](#the-7-templates-explained)
3. [How to Use This Framework](#how-to-use-this-framework)
4. [Recommended Order](#recommended-order)
5. [Document Relationships](#document-relationships)
6. [Practical Tips](#practical-tips)
7. [Example Workflow](#example-workflow)
8. [Common Mistakes to Avoid](#common-mistakes-to-avoid)

---

## What is Working Backwards?

**Amazon's Working Backwards methodology** is a systematic way to vet ideas and create new products by starting with the desired customer experience and working backward to define what needs to be built.

### Core Philosophy

> "Start with the customer and work backwards. Work vigorously to earn and keep customer trust. Although leaders pay attention to competitors, they obsess over customers."

### Key Principles

1. **Customer-First**: Begin with customer problems, not company capabilities
2. **Clarity Before Building**: Achieve clarity of thought before development
3. **Iterative Refinement**: Expect 10+ drafts and multiple review rounds
4. **Simple & Concrete**: Avoid abstraction, use specific examples
5. **Honest Assessment**: Address costs and challenges candidly

### The Process

1. Write a **Press Release** as if the product already launched
2. Draft **FAQs** addressing customer and internal questions
3. Use feedback to refine the concept iteratively
4. Only after PR/FAQ approval, write the **PRD** (Product Requirements Document)
5. Support with strategic analysis (market, competitive, fundraising, M&A)

**Important**: Most PR/FAQs don't get greenlit to build. The process helps you kill bad ideas early before wasting resources.

---

## The 7 Templates Explained

All templates are located in: `/Resources/Prompts/` with the prefix **"Amazon Working Backwards Framework"**

### Core Product Development Framework

These form the foundation of Amazon's Working Backwards process:

#### 1. **PR-FAQ (Press Release with FAQ)**
- **File**: `Amazon Working Backwards Framework - PR-FAQ.md`
- **What it is**: A press release written as if your product already launched, plus FAQs addressing customer objections
- **When to use**: **FIRST** - Before any other documents, at the idea stage
- **Output**: 500-700 word press release + 5-10 FAQs
- **Key question**: "Would a customer be excited about this?"

**What you'll define**:
- Customer personas and pain points
- Your solution in customer-friendly language
- Key benefits and differentiation
- How customers get started
- Answers to "why is this better?" objections

---

#### 2. **PRD (Product Requirements Document)**
- **File**: `Amazon Working Backwards Framework - PRD.md`
- **What it is**: Detailed specification of WHAT to build and HOW it works
- **When to use**: After PR/FAQ is approved, before engineering starts
- **Output**: Comprehensive product spec with features, requirements, and success metrics
- **Key question**: "Exactly what are we building?"

**What you'll define**:
- Product vision and goals
- Phased delivery plan (MVP, Phase 2, Phase 3)
- Functional requirements (features, user stories, acceptance criteria)
- Non-functional requirements (performance, security, compliance)
- Success metrics and KPIs

---

#### 3. **MRD (Marketing Requirements Document)**
- **File**: `Amazon Working Backwards Framework - MRD.md`
- **What it is**: Market-driven requirements defining WHAT customers need (not HOW to build it)
- **When to use**: Parallel to PRD, or before PRD to validate market needs
- **Output**: Market requirements organized by theme, with GTM strategy
- **Key question**: "What does the market need?"

**What you'll define**:
- Target market and personas (detailed)
- Market problem and current solution gaps
- Market requirements by theme (not features)
- Competitive positioning and differentiation
- Business goals and go-to-market strategy
- Pricing and packaging strategy

---

### Supporting Strategic Analysis

These documents inform the core framework with market intelligence:

#### 4. **Competitive Analysis**
- **File**: `Amazon Working Backwards Framework - Competitive Analysis.md`
- **What it is**: Systematic evaluation of competitors, their strengths/weaknesses, and your differentiation strategy
- **When to use**: Before or parallel to PR/FAQ to inform positioning
- **Output**: Competitor profiles, SWOT analysis, strategic recommendations
- **Key question**: "How do we win against competition?"

**What you'll define**:
- Primary and secondary competitors
- SWOT analysis for each competitor
- Market segmentation (who serves which customer segment)
- Your strategic positioning and differentiation
- Competitive dynamics and trends

---

#### 5. **Market Analysis**
- **File**: `Amazon Working Backwards Framework - Market Analysis.md`
- **What it is**: Comprehensive assessment of market opportunity, unit economics, and business viability
- **When to use**: Before committing resources, to validate market size and opportunity
- **Output**: TAM/SAM/SOM analysis, unit economics, GO/NO-GO recommendation
- **Key question**: "Is this market big enough to justify building this?"

**What you'll define**:
- Market sizing (TAM/SAM/SOM)
- Market segmentation and demographics
- Business model and unit economics (CAC, LTV, payback)
- Distribution channel strategy
- Financial projections (3-year model)
- Risk assessment and mitigation strategies
- Final GO / NO-GO / PIVOT recommendation

---

#### 6. **M&A Analysis**
- **File**: `Amazon Working Backwards Framework - M&A Analysis.md`
- **What it is**: Assessment of acquisition landscape, potential acquirers, and exit strategy
- **When to use**: Before fundraising or when planning long-term strategy
- **Output**: Acquirer profiles, valuation benchmarks, exit roadmap
- **Key question**: "Who would acquire us and for how much?"

**What you'll define**:
- Transaction landscape (deal volume, valuations)
- Potential acquirer profiles (strategic, PE, etc.)
- Acquisition criteria and value drivers
- Valuation benchmarks (revenue/EBITDA multiples)
- Exit timing and signals
- Strategic positioning for acquisition appeal

---

#### 7. **Investor Landscape**
- **File**: `Amazon Working Backwards Framework - Investor Landscape.md`
- **What it is**: Map of investor ecosystem, fundraising strategy, and relationship building plan
- **When to use**: 6-24 months before raising capital
- **Output**: Investor targets by stage, valuation benchmarks, fundraising roadmap
- **Key question**: "Who will fund us and how much can we raise?"

**What you'll define**:
- Investors by stage (pre-seed, seed, Series A, B, etc.)
- Investment criteria and proof points required
- Valuation benchmarks by stage
- Fundraising timeline and process
- Relationship cultivation strategy
- Pitch strategy and positioning

---

## How to Use This Framework

### Step 1: Choose Your Starting Point

**For a New Product Idea:**
1. Start with **PR-FAQ** to validate the customer vision
2. Support with **Market Analysis** to validate opportunity size
3. Add **Competitive Analysis** to understand the landscape
4. Only if PR/FAQ is compelling, proceed to **PRD** and **MRD**

**For an Existing Product:**
1. Start with **Market Analysis** or **Competitive Analysis** to assess current position
2. Use **MRD** to identify market gaps and opportunities
3. Use **PRD** to plan next product phases

**For Fundraising:**
1. Start with **Investor Landscape** to map the ecosystem
2. Support with **Market Analysis** to validate TAM/SAM
3. Use **M&A Analysis** to demonstrate exit potential

**For Exit Planning:**
1. Start with **M&A Analysis** to identify potential acquirers
2. Support with **Market Analysis** to benchmark valuations
3. Use **PRD/MRD** to align product with acquirer needs

---

### Step 2: Use AI to Fill Out Templates

**All templates are designed to be used with AI (Claude, ChatGPT, Gemini, etc.)**

Each template includes:
- **Role definition** for the AI ("You are a Product Manager...")
- **Task description** (what to create)
- **Amazon Working Backwards context** (methodology)
- **Structure and sections** to complete

**How to use**:
1. Copy the entire template into your AI chat
2. Provide context about your product/company
3. Let AI generate a first draft following the template structure
4. Iterate and refine based on feedback
5. Expect 5-10+ iterations to reach quality

---

### Step 3: Iterate Based on Feedback

**Amazon's process is iterative:**
- First draft: 2-3 hours (not days)
- Expected iterations: 10+ drafts
- Review meetings: 5+ rounds with stakeholders
- Process duration: Weeks to months (for PR/FAQ)

**Review process**:
1. Share document with stakeholders
2. Allow 15-20 minutes for silent reading
3. Discuss feedback and objections
4. Revise and repeat
5. Continue until consensus or kill the idea

---

## Recommended Order

### For Startups: Full Strategic Planning

**Phase 1: Validate the Idea (Week 1-2)**
1. ✅ **PR-FAQ** - Define customer experience
2. ✅ **Market Analysis** - Validate market size and opportunity
3. ✅ **Competitive Analysis** - Understand competitive landscape

**Decision Point**: GO / NO-GO / PIVOT

**Phase 2: Plan the Product (Week 3-4)**
4. ✅ **MRD** - Define market requirements
5. ✅ **PRD** - Specify product to build

**Phase 3: Plan Fundraising & Exit (Week 5-6)**
6. ✅ **Investor Landscape** - Map investors and plan fundraising
7. ✅ **M&A Analysis** - Understand exit landscape

---

### For Established Products: Incremental Planning

**Option A: New Feature/Product Line**
1. **PR-FAQ** - Customer vision for new feature
2. **MRD** - Market requirements
3. **PRD** - Product specification

**Option B: Fundraising Round**
1. **Investor Landscape** - Identify target investors
2. **Market Analysis** - Update TAM/SAM/SOM
3. **M&A Analysis** - Demonstrate exit potential

**Option C: Strategic Review**
1. **Market Analysis** - Assess current opportunity
2. **Competitive Analysis** - Update competitive position
3. **M&A Analysis** - Evaluate exit timing

---

## Document Relationships

### How Documents Connect

```
Strategic Foundation Layer:
┌─────────────────────────────────────────────────────────┐
│  Market Analysis    Competitive Analysis    M&A Analysis │
│  (Market size)      (Differentiation)      (Exit strategy)│
│                                                           │
│  Investor Landscape                                       │
│  (Fundraising)                                            │
└─────────────────────────────────────────────────────────┘
                           ↓
                    These inform:
                           ↓
┌─────────────────────────────────────────────────────────┐
│              Core Amazon Framework                        │
├─────────────────────────────────────────────────────────┤
│  1. PR-FAQ (Customer experience - "Why?")                │
│     ↓                                                     │
│  2. MRD (Market requirements - "What does market need?") │
│     ↓                                                     │
│  3. PRD (Product specification - "What do we build?")    │
└─────────────────────────────────────────────────────────┘
```

### Document Dependencies

| **Document** | **Depends On** | **Informs** |
|--------------|----------------|-------------|
| **Market Analysis** | None (start here for validation) | PR-FAQ, MRD, Investor Landscape |
| **Competitive Analysis** | None (parallel to Market Analysis) | PR-FAQ, MRD |
| **PR-FAQ** | Market + Competitive Analysis (optional) | MRD, PRD |
| **MRD** | PR-FAQ, Market Analysis | PRD |
| **PRD** | PR-FAQ (required), MRD (recommended) | Engineering execution |
| **Investor Landscape** | Market Analysis, M&A Analysis | Fundraising strategy |
| **M&A Analysis** | Market Analysis, Competitive Analysis | Exit strategy, Investor Landscape |

---

## Practical Tips

### General Best Practices

1. **Start Small**: Don't try to complete all 7 documents at once. Start with PR-FAQ.

2. **Use AI Effectively**: These templates are designed for AI. Copy the entire template, provide context, iterate.

3. **Be Honest**: Working Backwards is about killing bad ideas early. Be brutally honest about challenges.

4. **Focus on Customers**: Every document should start with customer needs, not your capabilities.

5. **Iterate, Iterate, Iterate**: First drafts are terrible. Plan for 10+ rounds of refinement.

6. **Get Feedback**: Share with advisors, customers, team members. Fresh perspectives matter.

7. **Update Regularly**: Documents go stale. Review quarterly or after major changes.

### Specific Document Tips

**PR-FAQ**:
- Write for your customer, not investors or press
- If you're not excited reading it, customers won't be either
- Avoid buzzwords and jargon—write like you're explaining to a friend
- FAQs should address real objections, not softballs

**PRD**:
- Be specific: "Users can X" not "Users can do stuff"
- Include acceptance criteria for every feature
- Map features to customer needs (traceability matrix)
- Update as you learn from customers

**MRD**:
- Define market requirements (problems), not product features (solutions)
- Prioritize ruthlessly: Not everything is P0
- Back claims with data (customer interviews, market research)
- GTM strategy is critical—don't skip it

**Market Analysis**:
- Be conservative with projections (under-promise, over-deliver)
- Focus on SOM (Serviceable Obtainable Market), not TAM
- Unit economics matter more than TAM
- Always include GO/NO-GO recommendation

**Competitive Analysis**:
- Analyze competitors through customer's eyes
- Honest assessment: where are they better than you?
- Update quarterly—competitors evolve fast
- Track win/loss reasons

**M&A Analysis**:
- Start 2-3 years before target exit
- Build relationships with acquirers years in advance
- Focus on value creation, not just exit prep
- Be realistic about valuations

**Investor Landscape**:
- Start building relationships 12-24 months before raising
- Research investor portfolios and thesis
- Don't waste time on wrong-stage VCs
- Monthly updates to potential investors

---

## Example Workflow

### Scenario: New SaaS Startup Idea

**Week 1: Validate the Idea**

**Monday**: Draft PR-FAQ (2-3 hours for first draft)
- Define customer persona and problem
- Write press release as if product launched
- Draft 5-10 FAQs addressing objections

**Tuesday-Thursday**: Iterate on PR-FAQ
- Share with 5-10 potential customers
- Get feedback: "Would you buy this?"
- Revise based on feedback
- Repeat until customer reaction is "I need this now"

**Friday**: Decision point
- If PR-FAQ is compelling → Proceed to Week 2
- If lukewarm response → Pivot or kill idea

---

**Week 2: Validate Market & Competition**

**Monday-Tuesday**: Market Analysis
- Size the market (TAM/SAM/SOM)
- Model unit economics (CAC, LTV, payback)
- Project 3-year financials
- Make GO/NO-GO recommendation

**Wednesday-Thursday**: Competitive Analysis
- Identify 5-10 competitors
- SWOT analysis for top 3
- Define differentiation strategy
- Strategic positioning

**Friday**: Decision point
- If market is big enough + you can differentiate → Proceed
- If market too small or too crowded → Pivot or kill

---

**Week 3: Plan the Product**

**Monday-Wednesday**: MRD
- Define target personas (detailed)
- List market requirements by theme
- Prioritize requirements (P0, P1, P2)
- Define GTM strategy and pricing

**Thursday-Friday**: PRD
- Translate MRD requirements into product features
- Define MVP scope
- Create phased delivery plan
- Set success metrics

---

**Week 4: Plan Fundraising & Exit**

**Monday-Wednesday**: Investor Landscape
- Research 20-30 target investors by stage
- Understand investment criteria
- Benchmark valuations
- Plan fundraising timeline

**Thursday-Friday**: M&A Analysis
- Identify potential acquirers
- Benchmark exit valuations
- Plan relationship cultivation
- Set exit timeline (3-5 years)

---

**Week 5+: Execute**

- Build MVP based on PRD
- Track metrics from MRD/PRD
- Update documents quarterly
- Start investor relationship building

---

## Common Mistakes to Avoid

### PR-FAQ Mistakes

❌ **Writing for investors instead of customers**
- PR should excite customers, not pitch VCs

❌ **Using buzzwords and jargon**
- "AI-powered blockchain disruption" means nothing to customers

❌ **Avoiding hard questions in FAQ**
- FAQs should address real objections, not softballs

❌ **Being vague about benefits**
- "10x faster" is better than "much faster"

✅ **Good PR-FAQ**: Customer reads it and thinks "I need this NOW"

---

### PRD Mistakes

❌ **Starting PRD before PR-FAQ**
- You'll build the wrong thing

❌ **Vague requirements**
- "Users can manage tasks" → What does "manage" mean?

❌ **Feature list without user stories**
- Features without context = misaligned expectations

❌ **No acceptance criteria**
- How do you know when a feature is done?

✅ **Good PRD**: Engineers can build exactly what customers need

---

### MRD Mistakes

❌ **Listing features instead of market needs**
- MRD defines WHAT market needs, not HOW to solve it

❌ **Skipping GTM strategy**
- Great product, no distribution = failure

❌ **No prioritization**
- Everything can't be P0

❌ **Ignoring competitive gaps**
- "Build better" isn't a strategy

✅ **Good MRD**: Clear market requirements prioritized by customer impact

---

### Market Analysis Mistakes

❌ **Confusing TAM with reality**
- "We only need 1% of the market" is not a strategy

❌ **Optimistic projections**
- "We'll grow 10x every year" → Be realistic

❌ **Ignoring unit economics**
- TAM doesn't matter if LTV < CAC

❌ **No GO/NO-GO decision**
- Analysis without decision is useless

✅ **Good Market Analysis**: Clear GO/NO-GO with realistic projections

---

### Competitive Analysis Mistakes

❌ **Only highlighting competitor weaknesses**
- Ignoring their strengths is dangerous

❌ **Feature comparison tables without context**
- "We have 50 features, they have 30" → So what?

❌ **Not updating regularly**
- Competitive landscape changes fast

❌ **Forgetting to define YOUR differentiation**
- Knowing competitors ≠ having a strategy

✅ **Good Competitive Analysis**: Honest assessment → Clear differentiation strategy

---

### M&A Analysis Mistakes

❌ **Focusing on exit instead of value creation**
- Build a company acquirers want to buy, don't optimize for exit

❌ **Unrealistic valuations**
- "We'll exit for $1B" → Based on what?

❌ **Not building acquirer relationships**
- Exit prep starts years before, not months

❌ **Ignoring integration challenges**
- Technical debt kills acquisition value

✅ **Good M&A Analysis**: Realistic valuation + strategic positioning

---

### Investor Landscape Mistakes

❌ **Cold emailing random VCs**
- Warm intros matter—research shows 10x higher response

❌ **Targeting wrong-stage investors**
- Seed-stage company pitching growth VCs = waste of time

❌ **Waiting until desperate to fundraise**
- Raise proactively with 18+ months runway

❌ **Not doing investor research**
- "Will any VC invest?" → No. Research their thesis first.

✅ **Good Investor Landscape**: Targeted list + warm intros + relationship building

---

## Resources & Further Reading

### Books

* **"Working Backwards"** by Colin Bryar & Bill Carr (Amazon insiders)
  - Definitive guide to Amazon's process
  - Real examples from Amazon products

### Online Resources

* [Amazon's PR/FAQ Process (Official)](https://workingbackwards.com/concepts/working-backwards-pr-faq-process/)
* [ProductPlan: Working Backwards Method](https://www.productplan.com/glossary/working-backward-amazon-method/)
* [Product School: PR/FAQ Template](https://productschool.com/blog/product-fundamentals/prfaq)

### Communities

* **Y Combinator**: Startup School (free)
* **Reforge**: Product management courses
* **Lenny's Newsletter**: PM best practices

---

## Getting Help

### Questions?

If you're stuck or need help:
1. Re-read the specific template you're working on
2. Review the "Common Mistakes" section above
3. Share your draft with advisors or customers for feedback
4. Use AI to iterate (Claude, ChatGPT, Gemini)

### Feedback

This framework is designed to evolve. As you use these templates:
- Note what works and what doesn't
- Adapt templates to your specific needs
- Share learnings with your team

---

## Summary

**Amazon's Working Backwards Framework** is a powerful methodology for:
- ✅ Validating ideas before building
- ✅ Achieving clarity of thought
- ✅ Aligning teams around customer needs
- ✅ Making data-driven strategic decisions

**The 7 Templates** provide a complete strategic planning suite:
1. **PR-FAQ** - Customer vision
2. **PRD** - Product specification
3. **MRD** - Market requirements
4. **Competitive Analysis** - Differentiation strategy
5. **Market Analysis** - Opportunity validation
6. **M&A Analysis** - Exit strategy
7. **Investor Landscape** - Fundraising strategy

**Start with PR-FAQ**, validate with Market + Competitive Analysis, and proceed only if customer vision is compelling.

**Remember**: Most ideas fail the PR/FAQ test. That's the point. Better to kill bad ideas on paper than after wasting resources building them.

---

**Good luck building!** 🚀

---

*Last Updated: 2025-11-22*
*Framework Version: 1.0*
*Based on Amazon's Working Backwards methodology*
