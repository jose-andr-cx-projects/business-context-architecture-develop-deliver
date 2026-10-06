# 3D — Business Context Architecture

**Status:** Active  
**Owner:** José Andrade  
**Last updated:** 6 October 2026

## Purpose

3D answers the problems framed through Customer Account Management and Information Management by developing one **Business Context Architecture**.

The architecture is business-led. It should make the relationships needed for better customer decisions visible before technology choices are made.

## Design question

> **What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?**

## Working architecture

```text
CUSTOMER CONTEXT
Who are they and what relationship do we have?
        ↕
SERVICE CONTEXT
What service or Service Offering are they dealing with?
        ↕
INFORMATION CONTEXT
What rules, requirements and guidance are relevant?
        ↕
OPERATIONAL CONTEXT
What is happening or has changed?
        ↕
INTERACTION CONTEXT
What are they trying to do, through which Mode and channel?
        ↕
OUTCOME CONTEXT
What happened and what can we learn?
```

## Input A — Customer Account Management

Use the existing discovery and definition work to test:

- customer identity and account context;
- relationships between people, organisations and accounts;
- legitimate account distinctions;
- trust and uncertainty;
- stewardship and human verification;
- business rules and decision rights;
- continuity across services.

## Input B — Information Management

Use current-state SOP evidence and working problem framing to test:

- Service and Service Offering context;
- service rules and requirements;
- knowledge and guidance;
- operational events and changes;
- service-to-knowledge relationships;
- ownership and lifecycle;
- source versus representation;
- reuse across staff, customer, digital and AI experiences.

## Design principles

1. **Business context before platforms.**
2. **Relationships before catalogues.**
3. **Meaning before integration.**
4. **Trust should be explicit, not assumed.**
5. **Operational change is context, not just communication.**
6. **Knowledge articles are representations of business context, not the context itself.**
7. **Account and information management remain distinct lenses inside one architecture.**
8. **Human review remains necessary where identity, meaning, ownership or applicability is uncertain.**
9. **Design the smallest useful model before adding enterprise-scale complexity.**

## 3D output

The minimum 3D output is Business Context Architecture v0.1 with:

- the six context layers;
- a small set of core business objects and relationships;
- explicit trust/stewardship questions;
- three test scenarios;
- assumptions and unresolved questions;
- no predetermined enterprise technology solution.

## Handoff to 4D

3D is complete enough to ship when the model can be tested against:

1. a customer account / duplicate scenario;
2. a Parking Service Offering ↔ Knowledge scenario;
3. an operational-change scenario where relevant information originates outside CRM.
