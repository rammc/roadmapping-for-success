# Roadmap Types

The theory part of the session – short, opinionated, designed to be delivered in about 15 minutes from the front of the room.

## What is a roadmap?

### Roadmaps are…

- Plans from the "as-is" to the "to-be" state
- Capabilities assigned to incremental delivery
- Visibility into a foreseeable future
- Oriented toward business value
- Focused on target audience and purpose
- A single view

### Roadmaps are NOT…

- Statements of Work or requirements documents
- A backlog of user stories or epics
- Long-term, rigid plans
- Task-oriented like a project plan
- Too detail-focused
- The answer to everything

> A roadmap that cannot change is a poster. A roadmap that changes transparently is a power tool.

## Why this matters – the numbers

The Standish Group's Chaos Report puts roughly **24% of all IT projects in the "failed" bucket**, with a further "challenged" bucket sitting close to 50% across the long run. The trend has not improved meaningfully across the Waterfall, Agile, Scrum, SAFe waves of the last two decades. [Unverified – confirm exact current figure against the latest Standish CHAOS Report before quoting on stage.]

Roadmaps don't fix delivery on their own. But every failed programme we have personally seen had the same three symptoms: scope creep, mismanaged dependencies, and stakeholders who had forgotten *why* the work was being done. A good roadmap is the cheapest insurance against all three.

## The four roadmap types

We teach four. Three are useful tools. The fourth is the cautionary example everybody recognises.

### 1. Business Capability Roadmap

**Audience:** Executives, sponsors, business leadership.
**Question it answers:** "What must the organisation be able to do, and by when?"

Solution-agnostic. Swimlanes by business area (Sales, Marketing, Service, Platform). Capabilities like *Guided Selling*, *Journey Orchestration*, *Self-Service Portal*, *Single Customer View*. Dependencies between capabilities shown as dashed arcs.

This is the artefact that wins and retains executive buy-in. Keep it on one slide. Do not put technology names on it.

> See `examples/business-capability-roadmap.svg`.

### 2. Business Feature Roadmap

**Audience:** Product owners, delivery leads, business analysts.
**Question it answers:** "Within each capability, what features ship in which quarter, and what is at risk?"

Gantt-style feature bars across quarters. Status colour-coded: blue (on track) and amber (at risk). Dependency arrows make sequencing explicit.

Example sequence: *Identity & SSO* → *Case deflection bot* → *Entitlement checks*. Other features in flight: *Knowledge base revamp*, *Portal shell and navigation*, *Live order status*, *Appointment booking*, *CSAT surveys*, *Multilingual rollout*.

> See `examples/business-feature-roadmap.svg`.

### 3. Technology System Roadmap

**Audience:** Architects, delivery teams, infrastructure and security leads.
**Question it answers:** "What must the platform deliver, in what order, to make the business roadmap possible?"

Swimlanes by technical concern: Operations, Infrastructure, Compliance, Security. Sequencing of migrations, audits, integrations, and enablers. Long-lived architecture decisions live here.

This is the roadmap that carries dependencies the business does not want to see but cannot afford to ignore.

> See `examples/technology-system-roadmap.svg`.

### 4. The anti-pattern: `roadmap_final_v7_FINAL(2).pptx`

**Audience:** Nobody, although it gets shown to everybody.
**Question it answers:** None.

Overlapping bars with labels like *CRM thing phase 1?*, *Big Integration*, *Data clean-up again*, *AI something*, *Portal v2 v3*, *Quick wins*, *Everything else*, *Reporting??*. Sticky notes saying *ASAP!!*, *TBD*, *?*. Quarters out of order: Q1, Q3?, Q2, ??.

Every team in the room recognises a version of this from their own working life. It is the biggest laugh of the session and its sharpest teaching moment: *this is what you ship when you skip the work the other three roadmaps make you do.*

> See `examples/roadmap-anti-pattern.svg`.

## Business vs Technology – the traceability rule

Frame the Business Capability roadmap and the Technology System roadmap along the **Salesforce Well-Architected framework** (pillars: Trusted, Easy, Adaptable).

- The **Business Capability roadmap** keeps the "why" visible. It serves the *Intentional* and *Adaptable* qualities – stakeholders can see what the organisation is investing in and why, and can re-prioritise without losing the thread.
- The **Technology System roadmap** carries sequencing, dependencies, and the long-lived architecture decisions that make change cheap later. It serves the *Resilient* and *Adaptable* qualities.

The rule that disciplines scope creep: **every technical initiative must trace back to at least one business capability.** If a line on the system roadmap has no parent in the capability roadmap, it is either a hidden technical debt item (call it that and put it in its own lane) or it should not be there at all.

[Unverified] – confirm current Well-Architected pillar wording at https://architect.salesforce.com/well-architected before finalising the spoken framing. The pillars and quality groupings change over time; do not quote them from memory.

## What this means for facilitators

When you run Block 1 of the session, you are not just teaching the four types. You are setting up two questions the teams will have to answer themselves in Block 2:

1. *Which roadmap are you actually building?* (Most teams default to a mix – push them to pick one.)
2. *Where does each line on it come from in Victory's strategy?* (No orphans.)

Then in Block 3, the distractors test whether the answers hold up when the world moves.
