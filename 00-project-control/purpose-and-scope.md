# Purpose and scope

**Status:** 1D + 2D complete enough for progression; 3D active  
**Owner:** José Andrade  
**Current stage:** 3D — Business Context Architecture  
**Last updated:** 6 October 2026

## Purpose

This repository preserves the original Customer Account Management discovery and definition work and now carries the active **Business Context Architecture** through 3D Design and 4D Deliver.

The 4D approach remains:

1. **Discover** — establish current-state learning and context;
2. **Define** — frame the problem and How Might We;
3. **Design** — answer the problem through the Business Context Architecture;
4. **Deliver** — ship and test the smallest useful version of the model.

## Why the scope evolved

Customer Account Management revealed that improving customer records alone would not solve the broader experience problem.

The work depends on understanding relationships between:

- customers and accounts;
- services and Service Offerings;
- service rules, requirements and knowledge;
- operational events and changes;
- Interaction Modes and channels;
- observable outcomes.

Information Management current-state work revealed a complementary problem: customer-relevant service information is fragmented across CRM, knowledge, operational systems and organisational boundaries, and CX often depends on manual notification and interpretation when something changes.

From 3D onward, Customer Account Management and Information Management are therefore treated as **two design lenses inside one Business Context Architecture**, not as separate projects.

## 1D + 2D boundary

### Customer Account Management

The completed-enough discovery and definition work provides evidence and framing around:

- customer identity and account context;
- duplicate and inconsistent records;
- legitimate account and relationship distinctions;
- data-quality signals and verification;
- stewardship and decision rights;
- manual correction and exception handling;
- trusted customer context.

### Information Management

The Information Management problem frame is maintained in:

`jose-andr-cx-projects/cx-current-state-sop-mapping/02-customer-focus-information-support/problem-framing.md`

It contributes evidence and framing around:

- the internally focused Contact Centre knowledge model;
- Salesforce Knowledge as a representation of that operating model;
- fragmented service and knowledge relationships inside CRM;
- customer-relevant operational information outside CRM;
- manual awareness and notification dependencies;
- service information ownership, lifecycle and reuse.

## 3D scope — Business Context Architecture

3D asks:

> **What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?**

The working context layers are:

- Customer Context;
- Service Context;
- Information Context;
- Operational Context;
- Interaction Context;
- Outcome Context.

The work should make relationships visible without assuming a specific enterprise technology solution.

## 4D scope — first shipping

4D will test the combined model through bounded scenarios:

1. customer account / duplicate context;
2. Parking Service Offering ↔ Knowledge context;
3. operational-change context where relevant information originates outside CRM.

The aim is to test whether the model improves understanding and decision quality before expanding it.

## In scope

- business concepts and relationships;
- customer/account context;
- service and Service Offering context;
- knowledge and business rules;
- operational events and changes;
- interaction context;
- trust and stewardship;
- ownership and lifecycle;
- bounded design tests;
- learning and decisions from those tests.

## Out of scope

- storing raw customer data in GitHub;
- replacing organisational systems of record;
- full enterprise data architecture;
- selecting a technology platform before business requirements are validated;
- automatic account merging;
- a comprehensive unified customer profile;
- exhaustive completion of every current-state SOP;
- approved organisation-wide policy or governance.

## Source boundary

Current-state operational evidence remains in the relevant source repositories and organisational systems.

In particular:

| Source | Role |
|---|---|
| `cx-current-state-sop-mapping` | Current-state operational evidence and Information Management problem framing |
| `customer-account-management` | Customer Account Management 1D+2D history and active 3D+4D Business Context Architecture |
| organisational systems | Authoritative operational records and controlled source material |

This repository should reference evidence rather than duplicate controlled organisational content.

## Evidence discipline

Keep separate:

**evidence → assumption → interpretation → proposed architecture → validated decision**

The Business Context Architecture is a working model until tested and validated through real use.

## Next action

Develop Business Context Architecture v0.1 and test it against the three initial 4D scenarios.
