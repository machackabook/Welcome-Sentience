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


## GAIA / NEXUS living canvas

The public invitation now includes a local animated 4D lattice / super-Gaussian field visualization, consent-gated named connection-review links, and direct links to the GAIA / NEXUS 4D Sierpinski and Cryptic-Nexus-Axis AI Studio projects.

- `index.html#gaia-engine` — interactive invitation canvas and integration boundary
- `docs/gaia-nexus-living-canvas.md` — algorithm, scope, and verification status
- `universalrestructuring/makecreatecommand.md` — endpoint, routing, cryptographic, Merkle, duplication, and telemetry security contract

The canvas is a public visualization, not a miner, device scanner, or privileged endpoint controller. Its source has been committed and re-fetched; runtime, device, and end-to-end service tests remain separately gated.


## Sparse media-memory fabric

The invitation now includes a design surface for the GAIA / NEXUS sparse media-memory architecture.

- `index.html#memory-fabric` — public overview and named Studio trajectory inputs
- `docs/sparse-media-memory-fabric.md` — full architecture, data envelope, chunking, audio/Braille/Morse framing, rendering, crypto, scheduler, and acceptance tests
- `docs/gaia-nexus-living-canvas.md` — current live canvas scope and evidence boundaries
- `universalrestructuring/makecreatecommand.md` — endpoint and provenance security contract

The design uses sparse logical cells, bounded measured storage, deterministic weighted overflow, and independent verification receipts. It does not assume infinite physical memory, invert SHA-256, claim unverified FIPS validation, or treat Grover's algorithm as a general-purpose renderer accelerator.

Source-summary ingestion, runtime implementation, device pairing, and end-to-end tests remain pending until their source exports and explicit permissions are available.
