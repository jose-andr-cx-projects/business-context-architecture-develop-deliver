# Starting Framework

**Status:** Working framework  
**Stage:** 3D — Develop

## Intent

This is the **top-down starting framework for what good should look like**.

It is not derived by reproducing current systems or processes.

Instead, it defines the minimum context that should be available to support a good customer interaction, then allows today's data, systems, processes and knowledge to be mapped into that model.

## Core design question

> **What business context is needed to understand the customer, the service and the situation well enough to support the right interaction?**

## Starting framework

| Context | Question |
|---|---|
| Customer Context | Who are they and what relationship do we have? |
| Service Context | What service or Service Offering are they dealing with? |
| Information Context | What rules, requirements and guidance are relevant? |
| Operational Context | What is happening or what has changed? |
| Interaction Context | What are they trying to do, through which Mode and channel? |
| Outcome Context | What happened and what can we learn? |

## Candidate concepts

These concepts help populate the framework. They are not yet a final ontology or data model.

| Context | Candidate concepts |
|---|---|
| Customer | Customer, Account, Relationship, Segment |
| Service | Service, Service Offering |
| Information | Rule, Requirement, Guidance, Knowledge |
| Operational | Event, Status, Change |
| Interaction | Intent, Interaction Mode, Channel, Interaction |
| Outcome | Outcome, Experience Evidence |

## Cross-cutting properties

Where relevant, context may also need:

- owner;
- authoritative source;
- trust / confidence;
- lifecycle state;
- effective date;
- review or expiry;
- authority / permission;
- evidence;
- exception status.

## Top-down rule

The framework should be able to host current reality without being shaped around current limitations.

For example:

- Salesforce objects may map into the framework, but Salesforce does not define the business concepts.
- Knowledge articles may represent business context, but the article itself is not the context.
- Current service processes may reveal necessary relationships, but today's process sequence is not automatically the desired model.
- Integration constraints are implementation considerations, not reasons to omit needed business context.

## What good looks like

A useful framework should make it easier to answer:

- What do we need to know about this customer?
- What relationship or account distinction matters here?
- Which Service Offering is involved?
- What is currently true about that service?
- Has something changed operationally?
- What information applies to this customer and situation?
- What is the customer trying to achieve?
- Through which interaction mode are they doing it?
- What experience should result?
- What evidence would tell us whether it was better?

## Success test for 3D

3D is sufficiently developed when the framework can:

1. host the useful context we already have;
2. expose important context that is missing or disconnected today;
3. generate at least one credible experience hypothesis;
4. do so without relying on a predetermined technology solution.

The next proof happens in 4D, not in another round of theoretical refinement.
