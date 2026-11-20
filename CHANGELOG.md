# B4~M4L — Changelog

Changes to the **public documentation website** are recorded here. Device software versions and their development histories are managed independently.

## Post-0.13.3 maintenance — 2026-11-16 to 2026-11-20 (no new release)

- **2026-11-16 · [PR #3](https://github.com/BeerBelgio/b4-m4l/pull/3) MERGED:** added Open Graph/Twitter metadata to homepage, Bridge, CONSEQUENCE OF TIME and Privacy, with two 1200×630 social preview PNGs. Actual LinkedIn preview rendering was not independently verified.
- **2026-11-20 · [PR #5](https://github.com/BeerBelgio/b4-m4l/pull/5) MERGED:** aligned the public CONSEQUENCE OF TIME HELP, version history and JSON/JS manifests to the **0.1.7 REV14 private candidate**, retaining the 0.1.6.5 musical/UI illustrated baseline and the known Remote Unmap limitation. M5 QA is documented, four Intel smoke tests are owner-reported PASS, and HELP H4 was checked by the owner on the public HTTPS page. No public device download or Ableton/Max redistribution clearance is implied.
- **2026-11-20 · [PR #6](https://github.com/BeerBelgio/b4-m4l/pull/6) and [PR #7](https://github.com/BeerBelgio/b4-m4l/pull/7) MERGED:** restored full **Under the hood** and **Troubleshooting** quick-navigation labels, including the Bridge `#architecture` link, without changing device HELP content or builds. [GitHub Pages deployment](https://github.com/BeerBelgio/b4-m4l/actions/runs/44726467727) completed successfully on `main@7ea800f8`; the owner reported a positive live visual check.
- **Version boundary:** the GitHub Release/tag **0.13.3 FINAL (2026-10-23)** remains the approved website release baseline. Later maintenance commits are deployed on `main` but have no new formal release/tag; Bridge and CONSEQUENCE OF TIME remain separate testing devices, not publicly distributed through this repository.

## 0.13.3 — FINAL website baseline · 2026-10-23

- Warm-white Bridge HTML hero title; original SVG artwork retained.
- Shorter Live/LFO UNMAP testing note in all five HELP languages.
- Closer mobile documentation/language controls and compact, keyboard-scrollable version histories with their existing newest-first order.
- NEW LANGUAGE action reuses language feedback email, restores the selected locale and offers an accessible mailto fallback.
- Redundant history introductions removed; guide coverage, testing and distribution boundaries retained elsewhere.
- Approved for website FINAL after the merged 0.13.3 Pages deployment and owner verification that the live Bridge `#help` includes the revised UNMAP note and NEW LANGUAGE action. Bridge H4 is satisfied for the identified embedded testing candidate's public documentation; device Intel, redistribution and device FINAL remain separate.


## 0.13.2 — Documentation update (published on GitHub Pages; formal GitHub Release pending)

- Adopted the approved product name Bridge across headings, accessible names, support text and page metadata while preserving the public slug, technical identifiers and existing artwork.
- Aligned the Bridge 1.3 guide, manifest, JS mirror, validator and static fallback with the documented complete-folder testing package. Added the scoped Live/LFO UNMAP note in editorial EN/IT and automatic DE/ES/FR.
- Grouped milestones under each device version, retaining dates and earlier development history. Added verified scoped M5 packaging milestones while keeping Intel, redistribution, HELP acceptance and public availability separate.
- Kept the CONSEQUENCE OF TIME illustrated guide on 0.1.6.5 and explicitly distinguished newer private 0.1.6.9 testing.
- Preserved the approved Max-style editor, responsive layout, local fonts and licences, artwork, Privacy content, canonical URLs and sitemap.

## 0.13.1 — Maintenance update (deployed for evaluation; release pending)

### Accessibility and responsive UI
- Limited translations and their downloads to device HELP content; homepage, Privacy and product presentation stay English.
- Added intrinsic dimensions to homepage wordmarks and destination-specific accessible names to device CTA links.
- Placed EXPLORE DEVICES directly after the mobile wordmark in the DOM, preserving the desktop composition and session layout schema.
- Centred the mobile footer signature with the original middle dot; kept device-title accents upright.
- Applied the approved QUICK GUIDE colour inversion, arranged mobile HELP/documentation/language objects and centred accordion symbols geometrically.
- Restored device development histories independently of testing/distribution status. Current illustrated guide targets remain Bridge 1.3 / DEV3 and CONSEQUENCE OF TIME 0.1.6.5.

### Layout stability
- Reserved the approved desktop canvas, toolbar and default object geometry before deferred editor initialization. Saved positions, drag/resize constraints and LOCK / EDIT / RESET remain supported.


### Performance
- Preserved the Barlow Condensed WOFF2 delivery implemented on `main` before this maintenance candidate. The existing TTF source files and font licences remain available; no font conversion was newly performed by 0.13.1.
- Stabilized initial homepage geometry, avoiding unintended shifts without changing the approved desktop layout or editor behavior.

## 0.13 — Initial public release (2026-10-20)

The first public release of **B4~M4L**, BeerBelgio's documentation and support website for Max for Live devices.

### What's included

- A patch-inspired, interactive homepage with movable and resizable objects, animated connections and LOCK / EDIT / RESET controls on supported desktop browsers.
- Dedicated pages for **Bridge** and **CONSEQUENCE OF TIME**, with device overviews, illustrated guides, compatibility and status information, changelogs and support links.
- Documentation in English and Italian, with automatic German, Spanish and French HELP translations.
- Responsive layouts for desktop and smaller screens, local font assets and browser-side preferences.
- Stable device HELP URLs designed for links from the devices themselves.
- Site-specific canonical URLs, sharing metadata and an XML sitemap, coordinated with the BeerBelgio hub's indexing structure.
- A public Privacy notice and a standalone GitHub Pages deployment without third-party runtime dependencies.

### Device status at launch

The website is publicly available, but **the devices documented here remain in testing and are not being distributed through this repository**.

- **Bridge:** 1.3 testing candidate (internal build identifier: DEV3-2026-10-19).
- **CONSEQUENCE OF TIME:** 0.1.6.5 testing candidate.

This release establishes the public website baseline. Later entries will describe changes made *after* 0.13.
