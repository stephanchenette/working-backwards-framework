# Working Backwards Framework

A practical startup strategy system built around Amazon's Working Backwards method.

This repo is not just a copy of Amazon's PR/FAQ process. It separates:

- the **core Working Backwards artifacts** I think are foundational
- the **strategic extensions** I added because a startup eventually needs more than a customer-facing narrative

The goal is not to produce a stack of pretty documents. The goal is to pressure-test startup ideas before they absorb too much time, money, and attention.

## What Is In This Repo

### Core Working Backwards

These are the documents closest to the original spirit of Working Backwards:

- `core/pr-faq.md`
- `core/mrd.md`
- `core/prd.md`

They answer three different questions:

- **PR/FAQ**: What is the customer promise?
- **MRD**: What does the market need?
- **PRD**: What are we actually building?

### Strategic Extensions

These are not canonical Amazon artifacts. They are extensions I use when the idea survives the first stage and needs deeper pressure-testing:

- `extensions/market-analysis.md`
- `extensions/competitive-analysis.md`
- `extensions/investor-landscape.md`
- `extensions/ma-analysis.md`

They answer questions like:

- Is the market large and attractive enough?
- Where do we actually win?
- Who would fund this?
- Who would buy this and why?

## How I Use It

### Stage 1. Validate the customer story

Start with:

1. `core/pr-faq.md`

Do not skip this step.

If the PR/FAQ is weak, vague, incremental, or internally framed, stop there. Most ideas do not deserve the full stack.

### Stage 2. Validate the market and product logic

If the PR/FAQ survives:

2. `extensions/market-analysis.md`
3. `extensions/competitive-analysis.md`
4. `core/mrd.md`
5. `core/prd.md`

This is where customer promise, market reality, positioning, and product requirements start checking each other.

### Stage 3. Pressure-test financing and exit logic

Only after the idea still looks coherent:

6. `extensions/investor-landscape.md`
7. `extensions/ma-analysis.md`

These are optional early and much more useful once the product and market story are sharper.

## Why This Structure Exists

PR/FAQ alone is excellent for customer clarity, but it is not enough for full company strategy.

A startup idea can survive the PR/FAQ and still fail because:

- the market is too small
- the buyer is wrong
- the positioning is weak
- the product requirements do not support the promise
- the investor case is unconvincing
- the likely exit logic is poor

That is why this repo is structured as a system instead of a single template.

## How To Use These Files With LLMs

These templates are designed to work well with LLMs, but the LLM is not the strategist.

Use an LLM for:

- first drafts
- critique
- alternative framings
- consistency checks across documents
- fast iteration after new evidence

Do not use an LLM to:

- invent customer truth
- replace user research
- skip judgment
- fill weak sections with generic confidence

## How To Avoid Doc Rot

Documents like these go stale quickly unless they stay coupled to reality.

At a minimum, each working doc should have:

- an owner
- a status
- a last updated date
- a reason it changed

Good update triggers include:

- new customer interview patterns
- a major competitor launch
- a product-direction shift
- pricing changes
- new evidence that invalidates a prior assumption
- fundraising timing changes

The point is not to update constantly. The point is to keep the documents alive enough that dead assumptions do not masquerade as current strategy.

## Suggested Reading Order

Start here:

1. `core/pr-faq.md`
2. `core/mrd.md`
3. `core/prd.md`
4. `docs/template-index.md`

Then use the extension docs as needed.

## Important Note

The extension documents are my adaptation, not a claim about what Amazon formally does.

That distinction matters.

The repo is best understood as:

- **Working Backwards as the spine**
- **additional strategy documents as the surrounding system**
