# Changelog

All notable changes to **this documentation repository** are recorded here. This tracks the
public documentation site, not the internal version history of the TRACE application itself.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-09-06

### Added

- **Simulation Mode documentation** (`docs/simulation.md`): the 13 configurable digital/analog
  signal patterns, ready-made scenarios, manual events, and simulated communication interruption
  added in TRACE v1.9.0, plus a new screenshot and matching FAQ entries.

### Changed

- Rewrote `ROADMAP.md`: TRACE is already free with all current features included, so the old
  "1.0 — licensing" milestone no longer applied. Replaced the four-stage plan with a factual
  Shipped / Exploring split, and synced the README's inline summary and `docs/roadmap.md` to
  match.
- Corrected `docs/chain-map.md` and `docs/pinouts.md`, which still overstated what the
  application does (automatic fault localization instead of reachability/latency; a longer
  aspirational connector list instead of the four standards TRACE actually supports).
- Fixed remaining "closed-source commercial software" wording in `CONTRIBUTING.md` and
  `LICENSE.md` — TRACE is free, not a paid commercial license.
- Pointed `origin` at the repository's current canonical name (`wramirezrg/trace`).

## [1.1.0] - 2026-09-04

### Changed

- Replaced every screenshot and the banner/social-preview image, which still showed the old
  Diagrix application, with current TRACE screenshots and branding.
- Updated `docs/monitor.md` and the README feature list to cover engineering units per tag,
  conditional recording triggers, and the configurable per-graph sampling interval added in
  TRACE 1.7.0.
- Fixed leftover "Diagrix" wording and stale contact links in the issue templates.

## [1.0.0] - 2026-07-26

### Added

- Initial public documentation release.
- Product overview, feature documentation for Live Monitoring, Replay, Chain Map, and the
  Pinout Library.
- Screenshot gallery.
- Public roadmap and FAQ.
- Community health files: contributing guidelines, security policy, issue templates.
