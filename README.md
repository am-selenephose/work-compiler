# Work Compiler

An evidence-first approach to turning authorized operational traces into reviewable software proposals.

Work Compiler models a governed loop:

```text
authorized events
      ↓
identity + workflow reconstruction
      ↓
friction or state-gap evidence
      ↓
versioned work specification
      ↓
replay + approval policy
      ↓
bounded execution receipt
      ↓
after-state verification + outcome window
```

The core idea is that an AI-generated proposal is not operational truth. A meaningful change needs source evidence, explicit permissions, acceptance checks, observability, rollback conditions, human approval where required, and a verifiable after-state.

## Current status

This repository is the public project overview. The implementation remains a
private alpha while data boundaries, connector contracts, and release licensing
are stabilized.

As of 29 August 2026, private Work Compiler v0.6 has a 47-test deterministic
suite, a clean source-package/wheel gate, and private exact-head CI. That is a
status report, not publicly reproducible proof: the implementation and its CI
logs are not exposed by this repository.

- no hosted demo is currently claimed;
- no private source, connector data, customer records, or runtime ledgers are published here;
- no autonomous external communication, money movement, or business-system mutation is offered by this repository;
- no open-source license has been selected, so public visibility does not grant reuse rights.

## Revenue Rescue v1

The first bounded service surface is a **USD 350 fixed-scope repair engagement
for one customer-authorized site and up to three listed, twice-verified
revenue-path defects**.

Work Compiler prepares an internal evidence packet first. The packet remains
`HOLD`, with `external_action = NONE` and
`commercial_status = OFFER_PREPARED_NOT_SOLD`, until customer authority,
written scope approval, cleared payment, least-privilege access, and rollback
readiness are independently recorded.

The complete public offer, acceptance boundary, exclusions, and contact path
are in [`REVENUE_RESCUE.md`](REVENUE_RESCUE.md). Publishing an offer does not
mean outreach occurred, a buyer accepted, work was delivered, or revenue was
received.

## Safety contract

Work Compiler is designed around fail-closed boundaries:

- ambiguous identity remains a review item;
- connector conflicts are quarantined instead of silently overwritten;
- business-system writes require explicit approval;
- external communication, money, legal/security-sensitive work, and destructive actions remain human-gated;
- duplicate mutation intent must be idempotent;
- execution success requires provider after-state evidence;
- operational improvement is not treated as proof of revenue causation;
- rollback is staged from predeclared conditions rather than improvised after harm.

## Public-release gate

A source release should include all of the following before this page links to it as a usable package:

1. synthetic/redacted fixtures only;
2. install-from-clean-environment instructions;
3. deterministic tests and a passing public CI run;
4. a documented permission and approval matrix;
5. idempotency, conflict, replay, and rollback tests;
6. proof that example reports contain no client or credential material;
7. an explicit license;
8. a versioned threat model and security-reporting path.

Until those gates are public and reproducible, treat Work Compiler as a product and architecture direction—not a downloadable production system.
