# Amazon Working Backwards Framework - Product Requirements Document (PRD)

## Your Role

**You are a Product Manager** responsible for translating customer needs into detailed product specifications.

**Your task is to create a Product Requirements Document (PRD)** that defines exactly **what** to build and **how** it should work, following Amazon's Working Backwards methodology.

## Amazon's Working Backwards Philosophy

In Amazon's framework, the PRD comes **after** the PR/FAQ is approved. While the PR/FAQ defines the customer experience (the "why"), the PRD defines the product specification (the "what" and "how").

### Core Principles

1. **Customer-Backwards**: The PRD must deliver on the customer experience promised in the PR/FAQ
2. **Clarity & Specificity**: Vague requirements lead to misaligned expectations
3. **Phased Delivery**: Start with MVP, iterate based on customer feedback
4. **Measurable Success**: Define concrete metrics for every feature
5. **Living Document**: Update regularly as you learn from customers

### Document Purpose

This PRD outline is designed for tech startups building any type of product (SaaS, consumer app, developer tools, marketplace, etc.). It provides a clear, phased approach to product development with stakeholder alignment, detailed requirements, and change management processes.

**Relationship to Other Documents**:
- **PR/FAQ**: Defines the customer experience and "why" (create this first)
- **MRD**: Defines market requirements and go-to-market strategy
- **PRD** (this document): Defines "what" to build and "how" it works
- **Technical Design Doc**: Defines implementation details (created after PRD)

---

## PRD Structure

### 1. Document Overview

**Purpose**: Define the scope and audience of this document

- **Document owner**: [Product Manager / Product Lead name]
- **Last updated**: [Date]
- **Status**: [Draft, In Review, Approved, Deprecated]
- **Intended audience**: Engineering, Design, QA, Product Marketing, Leadership
- **How this PRD fits within the broader document ecosystem**:
  - **PR/FAQ**: Defines the customer experience and "why"
  - **MRD**: Defines market requirements and go-to-market strategy
  - **PRD** (this document): Defines "what" to build and "how" it works
  - **Technical Design Doc**: Defines implementation details (separate document)

---

### 2. Product Vision and Goals

**Purpose**: Provide high-level context without duplicating the PR/FAQ

- **Product name**: [Name]
- **Product vision** (1-2 sentences): The long-term aspiration for this product
- **Problem being solved** (reference PR/FAQ for details): Brief summary of customer pain point
- **Value proposition**: What unique value does this product deliver?
- **Alignment to business goals**: How does this product support company OKRs or strategic priorities?
- **Success criteria overview**: What does "success" look like for this product?

**Note**: For detailed customer personas and problem validation, refer to the PR/FAQ and MRD documents.

---

### 3. Stakeholders & Responsibilities

**Purpose**: Define who owns what throughout the product lifecycle

| **Stakeholder**        | **Role**                          | **Responsibilities**                          | **Consultation Needed For**           |
|------------------------|-----------------------------------|-----------------------------------------------|---------------------------------------|
| Product Manager        | Owner                             | Requirements, prioritization, roadmap         | All major decisions                   |
| Engineering Lead       | Technical Owner                   | Architecture, feasibility, estimates          | Technical trade-offs, scope changes   |
| Design Lead            | UX/UI Owner                       | User flows, wireframes, visual design         | User experience decisions             |
| QA Lead                | Quality Owner                     | Test plans, acceptance criteria validation    | Feature verification, release readiness |
| Product Marketing      | GTM Owner                         | Messaging, positioning, launch plan           | Pricing, packaging, launch timing     |
| Customer Success       | Feedback Owner                    | User feedback, support escalations            | Feature prioritization, usability     |

**Communication protocols**:
- **Weekly sync**: Product, Engineering, Design (standup format)
- **Bi-weekly review**: Full stakeholder group (progress review)
- **Ad-hoc consultation**: For scope changes, blocking issues, or critical decisions

---

### 4. Phased Delivery Plan & Milestones

**Purpose**: Define what gets built when, and what success looks like at each phase

### Phase Definitions

#### **MVP (Minimum Viable Product)**
- **Goal**: Validate core value proposition with early adopters
- **Target users**: [Specific segment, e.g., "design agencies with 5-20 employees"]
- **Success criteria**: [e.g., "50 paying customers, 4.0+ app store rating, <10% churn"]
- **Timeline**: [Target launch date]
- **Key features**: [List 3-5 must-have features]

#### **Phase 2: [Name, e.g., "Scale & Polish"]**
- **Goal**: [e.g., "Expand to broader market, improve retention"]
- **Target users**: [Expanded segment]
- **Success criteria**: [e.g., "500 paying customers, <5% monthly churn"]
- **Timeline**: [Target launch date]
- **Key features**: [List features for this phase]

#### **Phase 3+: Future Releases**
- **Goal**: [e.g., "Enterprise readiness, platform expansion"]
- **Target users**: [Enterprise customers, adjacent markets]
- **Success criteria**: [Define later based on Phase 2 learnings]
- **Timeline**: [TBD]

### Milestone Checkpoints

| **Milestone**              | **Date**       | **Deliverable**                          | **Success Metric**               |
|----------------------------|----------------|------------------------------------------|----------------------------------|
| Design Complete            | [Date]         | High-fidelity mockups, user flows        | Stakeholder sign-off             |
| Alpha Release (Internal)   | [Date]         | Feature-complete for internal testing    | All P0 features functional       |
| Beta Release (External)    | [Date]         | Limited release to beta users            | [e.g., "100 beta signups"]       |
| General Availability (GA)  | [Date]         | Public launch                            | [e.g., "99.9% uptime, no P0 bugs"] |

---

### 5. Functional Requirements

**Purpose**: Define what the product does, feature by feature

For each feature, include:
1. **Feature name**
2. **User story**: "As a [persona], I need to [action] so that [benefit]"
3. **Detailed requirements**: Step-by-step description of functionality
4. **Acceptance criteria**: How do we know this feature is "done"?
5. **Dependencies**: What else must exist for this feature to work?
6. **Priority**: P0 (must-have), P1 (should-have), P2 (nice-to-have)

---

#### Example Feature Template

**Feature**: [Feature Name]

**User Story**:
- As a [persona],
- I need to [action],
- So that [benefit].

**Requirements**:
1. [Detailed requirement 1]
2. [Detailed requirement 2]
3. [Integration with external system X]

**Acceptance Criteria**:
- [ ] User can complete [action] in <3 clicks
- [ ] Error states are handled gracefully with clear messaging
- [ ] Feature works on mobile and desktop

**Dependencies**:
- Requires [API integration, database schema change, etc.]

**Priority**: [P0, P1, P2]

**Phase**: [MVP, Phase 2, Future]

---

#### Traceability Matrix

Map features to user needs and business KPIs:

| **Feature**               | **User Need**           | **Business KPI**                | **Phase** |
|---------------------------|-------------------------|---------------------------------|-----------|
| [Feature 1]               | [Solve problem X]       | [Increase retention by Y%]      | MVP       |
| [Feature 2]               | [Reduce friction in Z]  | [Reduce support tickets by Y%]  | Phase 2   |

---

### 6. Non-Functional Requirements (NFRs)

**Purpose**: Define how the product should perform, beyond functional features

Only include NFRs that are **critical** for the product. Defer detailed technical specs to a separate Technical Design Document.

| **Category**      | **Requirement**                                    | **Metric / Target**                |
|-------------------|----------------------------------------------------|------------------------------------|
| **Performance**   | Page load time                                     | <2 seconds on 3G connection        |
| **Scalability**   | Concurrent users                                   | Support 10K concurrent users       |
| **Reliability**   | Uptime                                             | 99.9% uptime SLA                   |
| **Security**      | Data encryption                                    | All data encrypted at rest/transit |
| **Compliance**    | Regulatory requirements                            | GDPR, SOC 2, HIPAA (if applicable) |
| **Accessibility** | WCAG compliance                                    | WCAG 2.1 AA standard               |
| **Localization**  | Language support                                   | English (MVP), Spanish (Phase 2)   |

**Links to detailed specs**:
- [Security & Privacy Architecture Doc]
- [Compliance Checklist]

---

### 7. User Experience & Design Principles

**Purpose**: Provide high-level design guidance without duplicating design docs

#### Design Principles
1. **[Principle 1]**: [e.g., "Simplicity over feature complexity"]
2. **[Principle 2]**: [e.g., "Mobile-first design"]
3. **[Principle 3]**: [e.g., "Accessibility is non-negotiable"]

#### UX Standards
- **Consistency**: Use [Design System Name] for all UI components
- **Accessibility**: All features must meet WCAG 2.1 AA standards
- **Usability**: [e.g., "New users should complete onboarding in <5 minutes"]

**Note**: Detailed wireframes, mockups, and visual design are maintained in a separate Design Document.

---

### 8. Integration & Technical Dependencies

**Purpose**: Identify external systems, APIs, and technical constraints

#### Internal Systems
- **[System 1]**: [e.g., "User authentication service"]
  - **Dependency**: Product cannot launch without SSO integration
  - **Owner**: [Engineering Lead]

#### External Integrations
- **[Third-party service 1]**: [e.g., "Stripe for payments"]
  - **Purpose**: Payment processing
  - **Risk**: Stripe API downtime affects checkout flow
  - **Mitigation**: Implement retry logic and fallback messaging

#### Technical Constraints
- **[Constraint 1]**: [e.g., "Must support browsers from last 2 years"]
- **[Constraint 2]**: [e.g., "Mobile app must be <50MB download size"]

---

### 9. Metrics & KPIs

**Purpose**: Define how success is measured for each feature and phase

#### Feature-Level KPIs

| **Feature**               | **Metric**                    | **Target**                  | **Tracking Method**        |
|---------------------------|-------------------------------|-----------------------------|----------------------------|
| [Feature 1]               | Adoption rate                 | 80% of users activate       | Analytics dashboard        |
| [Feature 2]               | Task completion time          | <2 minutes average          | User session tracking      |

#### Product-Level KPIs (by Phase)

| **Phase** | **Metric**          | **Target**            | **Measurement Cadence** |
|-----------|---------------------|-----------------------|-------------------------|
| MVP       | Active users        | 500 MAU               | Weekly                  |
| MVP       | Retention (D30)     | >40%                  | Monthly                 |
| Phase 2   | Conversion rate     | 5% free-to-paid       | Monthly                 |
| Phase 2   | NPS                 | >50                   | Quarterly               |

#### Data Collection Plan
- **Analytics tool**: [e.g., Mixpanel, Amplitude]
- **Event tracking**: [List key events to track]
- **Reporting cadence**: [e.g., "Weekly dashboard review with stakeholders"]

---

### 10. Risks & Assumptions

**Purpose**: Document known risks and critical assumptions

#### Assumptions
1. **[Assumption 1]**: [e.g., "Users are willing to pay $X/month"]
   - **Validation method**: Beta pricing test
2. **[Assumption 2]**: [e.g., "Third-party API will remain stable"]
   - **Validation method**: SLA review with vendor

#### Risks

| **Risk**                          | **Impact** | **Likelihood** | **Mitigation Strategy**               | **Owner**         |
|-----------------------------------|------------|----------------|---------------------------------------|-------------------|
| [e.g., "API rate limits too low"] | High       | Medium         | Negotiate higher limits, implement cache | Engineering Lead  |
| [e.g., "Low user adoption"]       | Critical   | Low            | Run beta program, iterate on feedback | Product Manager   |

**Risk monitoring**:
- **Owner**: Product Manager
- **Review cadence**: Bi-weekly during product development

---

### 11. Change Management Approach

**Purpose**: Define how changes to this PRD are handled

#### Early-Phase (MVP): Lightweight Process
- **Changes allowed**: Scope adjustments, feature reprioritization
- **Approval needed**: Product Manager + Engineering Lead verbal agreement
- **Documentation**: Update PRD with change log at bottom of document

#### Later-Phase (Post-MVP): Formal Process
- **Changes allowed**: Only critical bug fixes or high-impact features
- **Approval needed**: Written approval from Product Manager, Engineering Lead, Design Lead
- **Documentation**: Change request form + PRD version control

#### Change Log Format

| **Date**   | **Change**                        | **Reason**                  | **Approved By**        |
|------------|-----------------------------------|-----------------------------|------------------------|
| [Date]     | [e.g., "Removed Feature X"]       | [e.g., "Technical blocker"] | [PM, Eng Lead]         |

---

### 12. Appendices / References

#### Glossary of Terms
- **[Term 1]**: [Definition]
- **[Term 2]**: [Definition]

#### Index of Supporting Documents
- **PR/FAQ**: [Link]
- **MRD**: [Link]
- **Market Analysis**: [Link]
- **Competitive Analysis**: [Link]
- **Technical Design Doc**: [Link]
- **Design Mockups**: [Link]

#### Additional Resources
- **User research findings**: [Link]
- **Beta feedback summary**: [Link]
- **API documentation**: [Link]

---

## PRD Best Practices

1. **Start with the PR/FAQ**: Don't write a PRD until the PR/FAQ is approved
2. **Keep it updated**: PRD is a living document, not a one-time artifact
3. **Be specific**: Vague requirements lead to misaligned expectations
4. **Prioritize ruthlessly**: Not everything can be P0
5. **Collaborate early**: Involve Engineering and Design from day one
6. **Measure everything**: If you can't measure it, you can't improve it

---

**End of PRD Template**
