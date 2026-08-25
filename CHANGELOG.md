# Public changelog

The latest customer-facing release notes are published with each immutable
[GitHub release](https://github.com/arafayrs95/quill-terminal-releases/releases) and on
the [Quill Terminal download page](https://quillterminal.app/download).

## 0.12.2 — 2026-08-24

- Added a guarded, exact-deployment hosted customer journey covering Paddle
  Sandbox checkout, purchase email, license activation, native use/restart,
  plan changes, device replacement, cancellation, refund, support delivery,
  authenticated downloads, and expired-access enforcement.
- Expanded Admin with currency-aware revenue, chargeback-fee accounting,
  recent adjustments, unresolved webhook visibility, purchase-email delivery
  detail, acquisition sources, 14-day trial metrics, and explicit metric scope.
- Preserved grandfathered subscriptions during Paddle price rotation while
  keeping new checkout and plan changes pinned to current prices.
- Added branded sign-in error and magic-link states, Facebook launch-source
  attribution, safer email-link attribution continuity, narrow-screen docs,
  keyboard/focus accessibility, reduced-motion handling, and clearer privacy
  disclosure for non-secret feedback metadata.
- Added guarded production/staging migrations and the founder operations guide
  for release, billing, refund, email, Admin, and incident procedures.
- Published all six native targets with enforced licensing, installers,
  SHA-256 checksums, Sigstore evidence, CycloneDX SBOM, and native acceptance.

## 0.12.1 — 2026-08-20

- Completed the native TUI launch audit across editor, provider, Unicode,
  overlay, keyboard, pipe handoff, licensing, and terminal-restoration paths.
- Added robust pipe-to-new-instance and pipe-to-active-instance workflows.
- Improved keyboard-only navigation and consistent large History, Templates,
  and information overlays.
- Fixed overlay rendering with complex emoji, glyph, CJK, and bidirectional
  compose content.
- Improved Codex CLI input-background fidelity inside the embedded terminal.
- Published native installers/archives for six OS/architecture targets with
  checksums, Sigstore evidence, SBOM, and post-publication acceptance.

Earlier release notes remain available from the GitHub Releases page.
