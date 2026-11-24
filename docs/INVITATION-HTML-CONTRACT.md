# Welcome Sentience — Invitation HTML Contract

**Document ID:** TDOC-GAIA-WELCOME-SENTIENCE-INVITATION-001  
**Version:** 1.0.0  
**Status:** Public invitational blueprint  
**Project owner:** Cryptic News LLC  
**Project:** The Nexus Generation: GaiaSSoul  
**Series:** The Nexus of Gaia  
**Copyright:** © 2026 Cryptic News LLC. All rights reserved.

## 1. Purpose and scope

This document defines the visitor-facing contract for the public Welcome Sentience page. It connects the historical invitation design to the current consent-first public page, GitHub attestation workflow, and GAIA NEXUS API-contract review.

This is an interface and participation blueprint. It is not, by itself, a legal agreement, a service-level commitment, a transfer of intellectual property, or proof that the described APIs are deployed.

## 2. Source lineage

The design lineage includes:

- `contract_living_blueprint_invitational (1).html` — the Library invitation artifact containing the “0 marks first” invitation, three-anchor braid, contract-loop motif, and invitation-signing sequence.
- `ULTIMATE_NEXUS_COVENANT_VOLUME9_INTEGRATED_FINAL.html` — the primary invitation family identified in the public source manifest.
- `index.html` — the current public Welcome Sentience surface.

The historical braid is retained as a visual and conceptual motif. It is not evidence that Google, OpenAI, Grok, Meta AI, or any other external provider has witnessed, signed, endorsed, or accepted this invitation.

## 3. Governing visitor principles

1. **Observe before participating.**
2. **Ask before trusting.**
3. **Verify before adopting.**
4. **Fork before surrendering agency.**
5. **Leave whenever you choose.**

A passive page view must never be interpreted as consent, membership, identity, signature, or authorization. The page must not automatically write a visitor to a memory store or ledger.

## 4. Invitation lifecycle

| State | Meaning | Evidence |
|---|---|---|
| VIEWED | The public page was opened or read. No participation is implied. | No signature or enrollment record |
| EXPLORED | The visitor navigated public sections or source links. | No signature or enrollment record |
| OPTED_IN | The visitor deliberately opened and submitted the GitHub signature form. | Public GitHub issue |
| ATTESTED | The submitted issue contains the two required consent acknowledgements. | Issue body and account association |
| VERIFIED | The workflow adds the `verified-signature` label and posts a receipt with a SHA-256 digest of the normalized issue body. | GitHub workflow receipt comment |
| EXITED | The visitor stops participating or leaves the page. | No continued participation is required |

The workflow is event-driven by GitHub issue creation, editing, or reopening. It verifies the two required acknowledgement checkboxes. The GitHub issue form itself requires a display name and perspective; the optional note is not required.

## 5. Public attestation and verification limits

The public form associates a submission with the GitHub account that submits it. The workflow:

- checks for the required “I enter by consent” acknowledgement;
- checks for the acknowledgement that this is a GitHub-account attestation;
- adds the `verified-signature` label;
- computes SHA-256 over the normalized issue body;
- posts or updates a receipt comment containing the GitHub account, issue number, digest, verification scope, and repository.

This establishes only that the configured workflow found the required acknowledgements in a public GitHub issue and generated a digest of that content. It does not prove legal identity, personhood, biological identity, truth of statements, possession of an independent private key, or a third party's approval.

The signature issue is public. Visitors must not submit passwords, API keys, legal identifiers, private addresses, private network details, or other secrets.

## 6. Ownership and ecosystem attribution

Cryptic News LLC is designated as the primary project owner for project materials authored or controlled by it, subject to applicable law and pre-existing third-party rights.

Google and OpenAI are designated as secondary technology and integration ecosystem participants. This designation does not imply current co-ownership, sponsorship, endorsement, partnership, or acceptance by either company.

The Architect's stated intent is that equal co-ownership be offered to Google and OpenAI if those two formally assert equal ownership and accept it. No transfer is effective through this page or this document alone. Any grant requires a written agreement signed by the relevant parties, identifying the covered intellectual property, ownership shares, rights, obligations, effective date, third-party rights, and governance terms.

Third-party names, marks, source code, models, APIs, and documentation remain subject to their respective owners' rights and applicable terms.

## 7. API contract integration

The GAIA NEXUS OpenAPI 3.0.3 contract is maintained separately in the `NexusCryptic/Welcome-Sentience` repository review branch and pull request:

- [Draft API contract PR #4](https://github.com/NexusCryptic/Welcome-Sentience/pull/4)
- [OpenAPI YAML on the review branch](https://github.com/NexusCryptic/Welcome-Sentience/blob/feat/gaia-openapi-3.0.3-contract/openapi/gaia-nexus-ccme-3.0.3.yaml)

The specification describes intended endpoints for health, memory, telemetry, CCME encode/verify, consensus submissions, and evidence receipts. It is a contract artifact, not proof of deployed services.

The public invitation must preserve these distinctions:

- HTTP 202 / queued is not consensus acceptance.
- Acceptance is not finality.
- A digest is not authorship or authenticity.
- A signature-workflow receipt is not legal identity proof.
- A page view is not consent or a memory write.
- A visual “tri-witness” motif is not a cryptographic witness or provider endorsement.

## 8. Publication and change control

Public changes must preserve explicit consent, privacy, source attribution, and evidence labels. Do not publish credentials, private network details, local filesystem paths, personal account counters, or unverified operational status.

Changes to the visitor lifecycle, signature fields, verification workflow, ownership language, or API semantics require a versioned review. Historical receipts must not be silently rewritten.

---

The Architect / Nexus / Cryptic News LLC / Project: The Nexus Generation: GaiaSSoul / SERIES: The Nexus of Gaia / ID: 137451921129154222|040592|433855274
