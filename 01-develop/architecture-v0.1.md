# Business Context Architecture v0.1

**Status:** Working model  
**Stage:** 3D — Develop

## Design question

> What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?

## Context layers

| Layer | Core question | Candidate business objects |
|---|---|---|
| Customer Context | Who are they and what relationship do we have? | Customer, Account, Relationship, Segment |
| Service Context | What are they dealing with? | Service, Service Offering |
| Information Context | What is relevant and true? | Rule, Requirement, Guidance, Knowledge |
| Operational Context | What is happening or changing? | Event, Status, Change |
| Interaction Context | What are they trying to do? | Intent, Interaction Mode, Channel, Interaction |
| Outcome Context | What happened? | Outcome, Experience Evidence |

These are candidate objects, not a final data model.

## Working relationship model

```text
Customer
  ↕
Account / Relationship
  ↕
Service / Service Offering
  ↕
Rule / Requirement / Knowledge
  ↕
Operational Event / Status
  ↕
Interaction Mode / Channel / Intent
  ↕
Outcome / Experience Evidence
```

The architecture should make the relationships visible without requiring every concept to live in one system.

## Cross-cutting properties

The following are not separate layers. They apply where relevant:

- owner;
- source;
- trust / confidence;
- lifecycle state;
- effective date;
- review or expiry;
- permissions / authority;
- evidence;
- exception status.

## Design tests

A proposed object or relationship should earn its place by helping answer at least one real question such as:

- Which customer relationship matters for this service?
- Which Service Offering is affected?
- What rule or requirement is relevant?
- What changed operationally?
- Which interactions or channels are affected?
- Who owns the meaning?
- Can this context be trusted for this use?
- What outcome should be observed?

## Boundary

v0.1 is a **business model**, not:

- a Salesforce schema;
- a Databricks model;
- an integration design;
- a master-data model;
- an enterprise ontology;
- a procurement recommendation.

Technology follows the validated relationships.
