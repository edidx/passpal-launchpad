# PassPal Launchpad

**PassPal** is a hosted trust decision interface that turns targeted proof requests into decision-ready business outcomes.

This repository is the **public launchpad** and **reviewer-facing technical home** for PassPal.

---

## One-line summary

**PassPal turns targeted proof requests into decision-ready trust.**

---

## What PassPal does

PassPal helps a service, verifier, reviewer, or partner:

- request the **minimum useful proof**
- evaluate trust-sensitive workflow inputs
- return a **decision-ready receipt**
- support the next action without becoming another wallet or document vault

PassPal is designed for flows where identity alone is not enough and the relying party needs a clearer trust outcome.

---

## What PassPal is not

PassPal is **not**:

- another wallet
- a raw document storage product
- a generic public-profile platform
- a vague trust-score toy

PassPal is an **orchestration and decision layer**.

---

## Current MVP wedge

**Current wedge:** Verified Work / Remote Worker TrustPass

Current flow direction:

1. A partner launches a trust-sensitive flow
2. A user completes a proof or review step
3. PassPal requests the **minimum useful trust inputs**
4. PassPal evaluates the workflow
5. PassPal returns a **decision-ready receipt**
6. The partner can:
   - continue
   - ask for one more proof
   - escalate
   - stop

This wedge is the current product focus.

---

## Core output

**Primary output: PassPal Receipt**

A PassPal Receipt is the decision artifact produced by the flow.

Typical receipt fields include:

- receipt ID
- action
- requested inputs
- received inputs
- decision summary
- outcome
- freshness / expiry
- next action

The goal is to produce something more useful than a simple **verified / not verified** result.

---

## Product stack

### PassPal
The **trust decision interface**

Human-facing runtime and product surface for trust-sensitive actions.

### Passpod
The **trust protocol**

The protocol and orchestration logic layer behind PassPal.

### DIDX
The **trust registry**

The public trust surface and registry layer where trust state becomes easier to read.

---

## Current status

### Live now
- Verified Work / Remote Worker trust direction
- DIDX public trust-surface direction
- decision-oriented flow framing

### In active build
- clearer PassPal Flow surface
- clearer PassPal Receipt surface
- stronger Launchpad / reviewer-facing packaging
- tighter API and documentation structure

### Planned next
- Embed
- Studio
- Ops
- broader reusable policy-pack structure

---

## Quick links

### English
- [English docs](docs/en/README.md)
- [Product overview](docs/en/overview/product-overview.md)
- [Current wedge](docs/en/overview/current-wedge.md)
- [Remote Worker flow](docs/en/flows/remote-worker-flow.md)
- [Receipt model](docs/en/flows/receipt-model.md)
- [UNFOLD readiness](docs/en/launchpad/unfold-readiness.md)

### Français
- [Documentation française](docs/fr/README.md)

### Deutsch
- [Deutsche Dokumentation](docs/de/README.md)

### 한국어
- [한국어 문서](docs/kr/README.md)

---

## Repository purpose

This repository exists to make PassPal easier to understand, review, and discuss.

It is meant to help:

- ecosystem reviewers
- interoperability partners
- relying-party / verifier reviewers
- potential pilot partners
- technical stakeholders evaluating the current wedge

This repository is **not** presented as the full internal production source of truth.

Its role is to provide:

- product overview
- architecture direction
- current wedge explanation
- sample payloads
- sample receipt shape
- API preview
- launchpad and readiness notes

---

## Repository structure

```text
docs/
  en/
  fr/
  de/
  kr/
examples/
openapi/
