# Business Context Architecture — Develop + Deliver

**Status:** Active  
**4D stage:** 3D Develop + 4D Deliver  
**Owner:** José Andrade

## Purpose

This repository is the active working space for the **Business Context Architecture**.

It starts where the completed Discover + Define work ends.

The upstream evidence and problem framing live in:

`jose-andr-cx-projects/customer-accounts-and-information-management-discover-define`

This repository does **not** repeat that discovery.

Its job is simple:

> **Develop the smallest useful business-context model, ship it through bounded tests, learn, and refine.**

## Design question

> **What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?**

## Working architecture

```text
Customer Context
      ↕
Service Context
      ↕
Information Context
      ↕
Operational Context
      ↕
Interaction Context
      ↕
Outcome Context
```

### Customer Context
Who are they and what relationship do we have?

### Service Context
What service or Service Offering are they dealing with?

### Information Context
What rules, requirements and guidance are relevant?

### Operational Context
What is happening or what has changed?

### Interaction Context
What are they trying to do, through which Mode and channel?

### Outcome Context
What happened and what can we learn?

## Two lenses, one architecture

**Customer Accounts** tests whether the model helps us understand identity, relationships, account distinctions, trust and stewardship.

**Information Management** tests whether the model helps us understand service meaning, knowledge, operational change, ownership, lifecycle and reuse.

These are not separate projects.

## 3D — Develop

The immediate output is **Business Context Architecture v0.1**:

- minimum business objects;
- minimum relationships between them;
- where trust or ownership matters;
- what remains uncertain;
- enough structure to test against real scenarios.

The model should stay business-led and technology-neutral.

## 4D — Deliver

We will ship the model through three bounded tests:

1. **Customer account / duplicate scenario**  
   Tests customer context, identity uncertainty, relationships and stewardship.

2. **Parking Service Offering ↔ Knowledge scenario**  
   Tests service context, knowledge relationships, reuse, gaps and ownership.

3. **Operational-change scenario**  
   Tests how a change outside CRM becomes relevant to a service, customer interaction and channel response.

## Principles

- Business meaning before technology.
- Relationships before catalogues.
- Context before integration.
- Trust and uncertainty must be visible.
- Operational change is context, not just communication.
- Knowledge articles are representations of business context, not the context itself.
- Human review remains where identity, ownership or meaning is uncertain.
- Add complexity only when a real test requires it.

## Repository structure

```text
README.md

01-develop/
  architecture-v0.1.md
  test-cases.md

02-deliver/
  experiment-register.md
  learning-log.md

03-decisions/
  decision-log.md

references/
  discover-define-handoff.md
```

That is intentionally the whole structure.

## Current next step

Define the minimum business objects and relationships for v0.1, then pressure-test them against the three scenarios.
