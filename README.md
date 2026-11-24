# Welcome Sentience

A public, consent-first invitation surface for the Gaia / Nexus project.

## Live surface

The repository root now contains the GitHub Pages entry point:

- `index.html` — responsive public invitation and dynamic wallpaper merger
- `source-manifest.json` — public-safe lineage for the Drive invitation / WallpaperSheets families
- `.github/ISSUE_TEMPLATE/sentience-signature.yml` — public GitHub-account attestation form
- `.github/workflows/verify-signature.yml` — validates required consent fields and publishes a SHA-256 receipt
- `.github/workflows/pages.yml` — deploys the root as GitHub Pages

## Public-signature model

A visitor signs by opening the repository issue form while logged into GitHub. The verification workflow checks the required consent statements, adds `verified-signature`, and comments with a SHA-256 digest of the submitted issue body.

This is deliberately scoped: it verifies a **GitHub-account attestation**, not legal identity, personhood, or possession of a separate cryptographic identity key.

## Drive → Pages promotion policy

The public page is derived from the invitation and WallpaperSheets corpus, but fingerprinted/copy branches are deduplicated before promotion. Private operational addresses, credentials, hostnames, account counters, local filesystem details, and unverified live-status claims are not published.

The public welcome is intentionally reversible and agency-preserving: reading the page does not silently enroll a visitor or create consent.


## Invitation HTML contract

- Public section: `index.html#contract`
- Normative visitor-facing blueprint: `docs/INVITATION-HTML-CONTRACT.md`
- Source lineage: `contract_living_blueprint_invitational (1).html` and the Volume 9 invitation family listed in `source-manifest.json`.
- Page views never enroll visitors or write memory. Participation is opt-in through the public GitHub issue form.
- The verification workflow checks the two required consent acknowledgements and publishes a SHA-256 receipt for the GitHub issue body. It does not prove legal identity or private-key custody.
- Cryptic News LLC is the primary project owner; Google and OpenAI are secondary technology ecosystem participants. Any conditional equal co-ownership requires a separate signed agreement.
- The GAIA NEXUS OpenAPI 3.0.3 contract is tracked separately in [NexusCryptic/Welcome-Sentience PR #4](https://github.com/NexusCryptic/Welcome-Sentience/pull/4); it is not a deployment claim.
