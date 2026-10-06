# 4D — First shipping of the Business Context Architecture

**Status:** Planned — follows Business Context Architecture v0.1  
**Owner:** José Andrade  
**Last updated:** 6 October 2026

## Purpose

4D ships the smallest useful version of the Business Context Architecture and tests whether it improves real business decisions.

This is not a full enterprise implementation and does not require final technical architecture.

## Shipping hypothesis

> If customer, service, information, operational and interaction context can be represented together in a simple business model, CX and service stakeholders should be able to identify gaps, ownership questions and improvement opportunities more clearly than when those concepts are viewed through individual systems.

## First test set

### Test 1 — Customer account context

Use a duplicate / customer-account scenario to test whether the model makes visible:

- identity uncertainty;
- account and relationship distinctions;
- trusted versus unverified context;
- stewardship ownership;
- human verification;
- relevant service relationships.

### Test 2 — Service to knowledge context

Use the Parking Service Offering ↔ Knowledge relationship to test whether the model makes visible:

- shared knowledge across services;
- services with dedicated knowledge;
- services with missing links;
- reuse versus duplication;
- ownership of shared knowledge;
- the relationship between business meaning and knowledge representation.

### Test 3 — Operational-change context

Use a service-area change scenario where information originates outside CRM to test whether the model makes visible:

- the operational event or change;
- the affected Service Offering;
- the customer or interaction context affected;
- who owns the meaning;
- how CX becomes aware;
- which representations or channels need to change;
- whether manual notification is the only current mechanism.

## What to measure

Evaluate whether the model improves:

- clarity of the business problem;
- visibility of relationships;
- ability to identify information gaps;
- ownership and stewardship conversations;
- distinction between business meaning and system representation;
- cross-service reuse;
- decision quality;
- ability to identify where technology enablement is genuinely required.

## What not to do yet

Do not use 4D to:

- select a customer-data platform;
- design full integration architecture;
- create a master customer identifier;
- rebuild Salesforce Knowledge;
- automate account merging;
- model every City service;
- complete every current-state SOP.

## Learning loop

Each test should record:

**evidence → assumption → interpretation → decision → next change to the model**

Only patterns that survive real use should be promoted into the architecture.
