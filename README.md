# WraithVector — Runtime Governance & Evidence for Regulated AI

WraithVector is a **fail-closed runtime governance and cryptographic evidence layer** for AI systems operating inside regulated environments (EU AI Act, DORA, financial services, critical infrastructure).

It allows organizations to deploy AI and agentic systems **with technical control, not just monitoring**, and to produce **verifiable audit-grade evidence** of every AI decision.

This is not an AI model.  
This is the **control plane that makes AI legally operable**.

---

## The problem

Banks, insurers, utilities and governments are already deploying AI agents that:
- Read real customer and transaction data
- Support or influence human decisions
- Trigger internal APIs and operational tools

These systems are now inside **regulated workflows**.

Under EU regulation, it is no longer sufficient to:
- Log what happened
- Explain failures after the fact

Regulators require proof that:

> AI systems were technically prevented from acting outside their legal and operational scope.

Most enterprises **cannot prove this today**.

---

## What WraithVector does

WraithVector sits **between AI systems and execution**:

**AI Agent → WraithVector → Internal APIs / Tools / Data**

Every AI action is intercepted **before it executes** and evaluated against **deterministic policies**.

The system then:
- Allows
- Anonymizes
- Observes
- Or blocks (fail-closed)

Every decision produces **cryptographic evidence**.

No action exists without:
- A governing policy
- A recorded decision
- A verifiable proof

---

## Why this is different

Most AI security tools:
- Detect problems
- Alert after execution
- Provide dashboards

WraithVector:
- Enforces control before execution
- Operates in fail-closed mode
- Produces legally defensible evidence

This is **governance infrastructure**, not AI filtering.

---

## Evidence model

Each agent step produces:
- Decision (ALLOW / ANONYMIZE / OBSERVE / DENY)
- Policy ID and version
- Context hash
- Hash-chained, append-only record

Artifacts:
- Machine-verifiable JSON
- Human-readable PDF
- Offline verification supported

Evidence exists **because control exists**, not as post-hoc logging.

---

## Deployment

WraithVector is deployed in the customer’s environment:
- On-premise
- Or private cloud

The institution retains:
- Operational control
- Custody of evidence
- Cryptographic verification

No vendor lock-in.  
No external dependency for auditability.

---

## This repository

This repository contains:
- The runtime governance architecture
- Policy and evidence examples
- A minimal demo showing:
  - An AI action
  - A policy-based block
  - Generated cryptographic evidence

See `/demo` and `/evidence`.

---

## Status

A functional MVP exists:
- Runtime interception
- Deterministic policy enforcement
- Fail-closed blocking
- Cryptographic evidence generation

The current focus is **regulated pilots** with financial and critical-infrastructure organizations.

---

## Why this matters

WraithVector allows organizations to answer one question with certainty:

> *Can we prove that our AI systems were technically prevented from doing the wrong thing?*

If the answer is not cryptographically provable, it is not compliant.
