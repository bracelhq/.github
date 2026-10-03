# Bracel

### Ship with proof.

**Critical business rules need evidence that they hold.**

Bracel is building an execution-based verification platform for pull requests. We connect approved rules to executable scenarios, then connect each result to the tested commit, expected behavior and observed outcome.

[Explore Bracel](https://bracel.dev/) · [Acceptance evidence](https://bracel.dev/docs/acceptance/) · [LinkedIn](https://www.linkedin.com/company/bracelhq/)

## What we focus on

- **Tenant isolation:** one customer must not access another customer's data.
- **Authorization:** critical operations require the right permissions.
- **Financial invariants:** payment and refund limits must remain intact.
- **Idempotency:** retries must not create duplicate effects.
- **Concurrency:** competing operations must preserve the rule.
- **State consistency:** related changes must remain coherent.
- **Failure recovery:** failed operations must not leave partial results.

## Evidence before confidence

| Result | Meaning |
| --- | --- |
| PASS | The executed scenarios satisfied the approved rule. |
| FAIL | Execution produced evidence of a rule violation. |
| UNKNOWN | Verification was incomplete or inconclusive. |

A PASS applies to the tested scenarios and execution conditions. It is not proof that every possible behavior is correct.

## From detection to repair

Our planned Fix workflow connects a demonstrated failure to an AI-proposed patch, independent validation and human review. The patch author does not decide whether the repair is correct.

## Follow the work

We are developing the platform. Supported profiles, acceptance evidence and verification boundaries are published on [bracel.dev](https://bracel.dev/). This repository contains our public organization profile; it does not distribute the verification engine.

For product questions, contact [support@bracel.dev](mailto:support@bracel.dev). Report security concerns privately to [security@bracel.dev](mailto:security@bracel.dev); please do not include secrets or vulnerability details in public issues.

**Proof, not opinions.**
