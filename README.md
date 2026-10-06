# Business Context Architecture — Customer Account Management repository

**Status:** Active — 3D Design  
**Owner:** José Andrade  
**4D position:** 1D Discover complete enough for progression; 2D Define complete enough for progression; 3D active; 4D first shipping next.

## Purpose

This repository now carries the 4D progression from the original Customer Account Management work into the **Business Context Architecture**.

The 4D method remains the organising logic:

1. **1D — Discover:** understand current state, evidence and context;
2. **2D — Define:** frame the problem and define the How Might We;
3. **3D — Design:** answer the How Might We through the Business Context Architecture;
4. **4D — Deliver:** ship the smallest useful version of the model and test it through real use.

The repository preserves the Customer Account Management discovery and definition history. From 3D onward, the active design scope is broader: **Customer Account Management and Information Management become two problem streams inside one Business Context Architecture.**

## 1D + 2D — what got us here

### Customer Account Management

The work established a practical problem frame around:

- fragmented customer and account context;
- duplicate and inconsistent records;
- legitimate account and relationship distinctions;
- data-quality signals versus confirmed identity;
- unclear stewardship and decision rights;
- manual correction and verification;
- the need to define trusted customer context before selecting technology.

Customer Account Management asks:

> What context do we need to understand the customer and their relationship with the City?

### Information Management

Current-state SOP work and operational knowledge identified a related information problem:

- information management has historically been shaped around an internally focused Contact Centre model;
- Salesforce Knowledge largely reflects this model, with manually refined guidance focused on how phone agents handle enquiries;
- rich service and knowledge information exists inside CRM but is fragmented and weakly connected to customer, service and operational context;
- a large amount of customer-relevant information exists outside CRM;
- CX often relies on service areas recognising that something has changed and manually telling the Contact Centre or Customer Experience;
- service-to-knowledge relationships are uneven and not yet governed as a reusable business relationship.

Information Management asks:

> What context do we need to understand the service, what is currently true, and what has changed?

The detailed current-state evidence remains in:

`jose-andr-cx-projects/cx-current-state-sop-mapping`

## 3D — Business Context Architecture

### Design question

> **What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?**

### Working model

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

The model should connect business meaning without assuming one platform, one master profile or one enterprise technology solution.

### Two design lenses, one architecture

**Customer Account Management lens**

Test whether the model makes customer identity, relationships, account distinctions, trust and stewardship easier to understand and manage.

**Information Management lens**

Test whether the model makes service information, knowledge, operational change, ownership, lifecycle and reuse easier to understand and manage.

Neither lens is a separate project from 3D onward.

## Business ownership principle

The work begins with business meaning and customer/service outcomes.

CX and business owners should be able to define:

- the context needed;
- the relationships that matter;
- trust requirements;
- business rules;
- stewardship questions;
- lifecycle expectations;
- success measures.

Technology and data architecture enable that model through platforms, integration, authorised access and implementation.

The architecture should not depend on final enterprise technical architecture before useful business-context design can begin.

## 4D — first shipping

4D is not a full enterprise implementation.

It is the first bounded shipping of the model to test whether it improves real decisions.

Initial test set:

1. **Customer account / duplicate scenario** — tests customer context, identity uncertainty, relationship distinctions and stewardship.
2. **Parking Service Offering ↔ Knowledge relationship** — tests service and information context, reuse, coverage and ownership.
3. **Operational-change scenario** — tests whether a change outside CRM can be related to the relevant service, interaction and customer context without relying solely on manual awareness.

The aim is to learn whether the model is useful before expanding architecture or technology.

## Repository boundary

This repository contains:

- the original Customer Account Management 1D and 2D evidence and decisions;
- the active 3D Business Context Architecture design;
- the active 4D tests and learning.

It does not replace:

- organisational systems of record;
- current-state SOP evidence;
- Salesforce, Databricks or other operational platforms;
- enterprise architecture governance;
- approved policy or data governance.

## Navigation

- `01-discover/` — Customer Account Management discovery evidence.
- `02-define/` — Customer Account Management problem definition and rule refinement.
- `03-design/` — active Business Context Architecture design.
- `04-deliver/` — bounded 4D tests and first shipping.
- `05-evaluation-and-learning/` — learning from tests.
- `06-decisions/` — material project and architecture decisions.

## Current next step

Develop Business Context Architecture v0.1 around the six context layers and test it against the three initial use cases before adding further structure.
