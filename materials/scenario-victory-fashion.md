# Scenario: Victory Fashion

**A fictional scenario built for the "Roadmapping for Success" workshop. Any resemblance to real fashion retailers, K-Pop bands, or doomed legacy commerce platforms is entirely intentional.**

Print one copy per participant. Hand out at the start of Block 2.

---

## The company

Victory is a global fashion retailer supplying clothing to **over 11,000 department stores** and **500 Victory retail stores** through a full-package production model. Manufacturing is outsourced to partners in Asia and Turkey.

Their success has depended on planning seasonal orders **9–12 months in advance**, managed through Salesforce Classic.

## What just happened

A recent viral TikTok moment featuring a K-Pop band has driven a surge in Gen Z demand for Victory's products. The surge has exposed serious limitations in Victory's outdated systems and long lead times: the supply chain cannot react, the legacy commerce shop cannot accept modern payment methods, and the marketing platform cannot segment the new audience.

To seize the moment, Victory has appointed a new **CDO** and **CTO** to drive digital transformation.

Goals:

1. Launch a modern direct-to-consumer **online store**.
2. **Modernise operations** end-to-end.
3. **Accelerate the product cycle** — halve the time from production to sale.

Analysts forecast elevated demand for up to **two years**. The technology strategy has been approved by leadership and board. The CTO is now responsible for the technology roadmap. That is what your team will draft today.

## Current systems (as-is)

| System | Purpose | State |
| --- | --- | --- |
| **Salesforce CRM** | Mainly B2B connections to the 11,000 department stores | Classic, in active use |
| **Multiple regional ERPs** | Order, inventory, finance per region | Doing their job, **not in scope for replacement** |
| **Old Fashioned Commerce Shop** | Direct sales site | Early 2000s, never touched, no modern payment providers |
| **Custom Portal** | Supplier design-draft uploads and complaint management | Bespoke, brittle, costly to extend |
| **Design Tool** | 3rd-party web app for designers, branded as Victory | Centrally managed, working well |

### Future-state signals from the CDO and CTO

- The current marketing platform "meets today's requirements but not tomorrow's" and is poorly integrated. **Not strategic.**
- The new online store must be built **from scratch**.
- The CTO publicly doubts the current Salesforce CRM implementation will improve supply chain management. **Open question for the architects.**

## Capabilities to consider — the raw material for your roadmap

The CDO has signed off the following capability ambitions. Your team's job is to **select, sequence, group, and prioritise** them across quarters, with dependencies, on a roadmap of your chosen type.

### Sourcing & Designing

- Integrated PLM with version control
- Real-time collaboration across global design teams
- AI-assisted design tool integration (seasonal colours, materials)
- Supplier-portal integration for rapid prototype feedback

### Supply chain & supplier management

- Unified SRM
- Self-service supplier onboarding and compliance validation
- Automated milestone tracking (sample approvals, shipping status)
- Embedded analytics for vendor performance and risk

### Inventory tracking

- Near real-time inventory visibility via ERP integrations
- Predictive inventory allocation from sales/demand signals
- Alert-based replenishment
- Cross-channel stock sync (B2B and future B2C)

### Sales & Customer Experience

- Modern headless commerce platform, mobile-first UX
- Modern payment gateways and fraud detection
- Personalisation engine
- Social commerce and influencer-driven flash sales

### Contracting

- Centralised CLM
- Pre-approved legal templates and digital signature
- Automated renewal and compliance tracking
- Contract-to-invoice integration

### Commercial & Marketing

- Unified CDP for B2B and future B2C segmentation
- AI-driven personal-shopper agent generating store "look-books"
- Floor-plan generation and placement scoring
- Performance marketing analytics dashboards

### Operations (automation & AI)

- Workflow automation (design approvals, supplier updates)
- AI for seasonal demand forecasting and production planning
- RPA for order reconciliation
- Exception management alerts in logistics and fulfilment

### Governance (fed by Insights & Intelligence)

- Enterprise data lake / warehouse with BI layer
- Role-based dashboards (merchandising, sourcing, finance)
- Audit trails and data-governance policy enforcement

## Your task

In **roughly 45 minutes** your team will:

1. Decide which **type** of roadmap you are building — capability, feature, or system — and why.
2. Choose a **horizon** (the default is four quarters; longer is fine if you justify it).
3. Place capabilities on swimlanes, with sequencing and at least one explicit **dependency**.
4. Be ready to say, for every item on the board, **which business goal it serves**. No orphans.

You will not finish. That is fine. A roadmap is never finished; it is always the best current view.

## The as-is landscape

See `examples/victory-fashion-landscape.svg` (also embedded on the workshop site).

Salesforce sits at the centre-right as the B2B management system, connected via an integration layer to the regional ERPs. The Commerce Shop, the Custom Portal and the Design Tool sit visibly **disconnected** on the left.

The visual disconnection is the point of the diagram.

---

*Victory Fashion is a fictional scenario built for this workshop. No real retailer, supplier or band was harmed in its making.*
