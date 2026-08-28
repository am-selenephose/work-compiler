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

This repository is the public project overview. The implementation is currently a private alpha while data boundaries, connector contracts, and release licensing are stabilized.

- no hosted demo is currently claimed;
- no private source, connector data, customer records, or runtime ledgers are published here;
- no autonomous external communication, money movement, or business-system mutation is offered by this repository;
- no open-source license has been selected, so public visibility does not grant reuse rights.

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
