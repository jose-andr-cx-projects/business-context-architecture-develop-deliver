# 3D Test Cases

The architecture is developed through real scenarios rather than abstract completeness.

## Test 1 — Customer account / duplicate context

### Question

Can the model distinguish a customer, their accounts and legitimate relationships without treating every matching record as the same thing?

### Pressure-test

The model should make visible:

- customer versus account;
- statutory versus non-statutory context where relevant;
- potential versus confirmed duplicate;
- relationship to Service Offerings;
- trusted versus uncertain attributes;
- who can verify or act;
- consequences of an incorrect merge or assumption.

### What this tests

Customer Context + Service Context + trust/stewardship.

---

## Test 2 — Parking Service Offering ↔ Knowledge

### Question

Can the model show which knowledge supports which Service Offerings and reveal reuse, gaps or unclear ownership?

### Pressure-test

The model should make visible:

- Service Offering;
- linked knowledge/guidance;
- knowledge shared across multiple services;
- missing knowledge relationships;
- owner of business meaning;
- source versus representation;
- lifecycle/review requirements.

### What this tests

Service Context + Information Context.

---

## Test 3 — Operational change outside CRM

### Question

Can the model represent a customer-relevant change that originates in another area and connect it to the right service and interaction context?

### Pressure-test

The model should make visible:

- operational event/change;
- affected Service Offering;
- relevant rule, status or guidance;
- customers/interactions potentially affected;
- how CX becomes aware;
- who owns the meaning;
- which channels or representations need updating;
- what happens when the change expires or is resolved.

### What this tests

Operational Context + Information Context + Interaction Context.

## Test rule

If the model cannot explain a scenario simply, refine the model.

Do not add a new object or layer unless a real scenario requires it.
