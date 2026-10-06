# DEC-026 — Carry Account Management and Information Management into one Business Context Architecture

**Status:** Agreed  
**Date:** 6 October 2026  
**Owner:** José Andrade

## Decision

Preserve the 4D approach, with the following progression:

1. **1D Discover** — current-state learning and context;
2. **2D Define** — problem framing and How Might We;
3. **3D Design** — answer the related Account Management and Information Management problems through one Business Context Architecture;
4. **4D Deliver** — ship and test the first bounded version of that model.

Customer Account Management and Information Management will **not** become separate 3D/4D projects.

They become two problem streams and test lenses inside the same Business Context Architecture.

## Rationale

The two streams address different but complementary context:

- Customer Account Management focuses on customer identity, relationships, account context, trust and stewardship.
- Information Management focuses on service meaning, knowledge, operational change, lifecycle and reuse.

Treating them separately in design would recreate the fragmentation the architecture is intended to address.

## Implication

The active design model should connect:

- Customer Context;
- Service Context;
- Information Context;
- Operational Context;
- Interaction Context;
- Outcome Context.

The first 4D shipping should test the combined model through bounded scenarios rather than attempting an enterprise-wide implementation.

## Boundary

This decision does not:

- merge the operational functions;
- prescribe a technology platform;
- establish an approved enterprise architecture;
- replace organisational systems of record;
- require exhaustive completion of Information Management discovery before design begins.
