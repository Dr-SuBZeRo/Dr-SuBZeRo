# SuBZeRo GitHub Portfolio Improvement Plan

**Owner:** SuBZeRo  
**Portfolio:** https://github.com/Dr-SuBZeRo  
**Developer website:** https://dr-subzero.github.io/  
**Last reviewed:** 20 November 2026

## Purpose

Create a coherent, trustworthy developer portfolio that explains what SuBZeRo builds, helps visitors evaluate the software, and makes it straightforward to install, test, report issues, and follow releases.

Prioritise evidence of maintained software over visual decoration or inflated feature claims.

## Positioning

**Identity:** Physician | Independent Android Developer | Product Builder  
**Focus:** Native Android applications using Kotlin, Jetpack Compose, and Material 3.

**Product principles:** free to use; no ads, subscriptions, or in-app purchases; privacy-focused; offline-first where workflows permit; no mandatory registration; local data ownership and user-controlled backup where applicable.

These are product goals. Each repository must document its actual permissions, network behaviour, and implemented capabilities.

## Project portfolio

| Project | Purpose | Portfolio placement | Priority |
|---|---|---|---|
| MargiQ | Retail/pharmacy pricing, GST, profit and supplier comparisons | Featured / established | Maintain releases, screenshots and installation |
| CashQ | Offline Indian Rupee note and coin counter | Featured / established | Document backup roadmap, permissions and tested behaviour |
| WalletQ | Personal and household finance | Featured / active development | Separate implemented foundations from planned workflows |
| StockQ | Inventory, purchasing and supplier workflows | Featured / development | Improve metadata, status, screenshots and roadmap |
| ClinicQ | Clinic operations and patient workflow management | In development | Publish scope, architecture, privacy and progress |
| MargiQ Windows | Shared Android and Windows direction | Future initiative | Track in MargiQ issue #4; do not present as released |

## Roadmap

### Phase 1 — Profile and discovery
- [x] Refresh profile README with all four featured products.
- [x] Separate active projects from work in progress.
- [x] Link developer website and project repositories.
- [ ] Pin the six most useful repositories.
- [ ] Review GitHub profile name, bio, location, website, and social preview.
- [ ] Verify every profile link and external image/widget.

### Phase 2 — Repository metadata
- [ ] Add concise descriptions to every public repository.
- [ ] Apply consistent, relevant GitHub topics.
- [ ] Add website links consistently.
- [ ] Confirm license files match intended licensing policy.
- [ ] Add or verify social preview images.

Suggested descriptions:
- **MargiQ:** Native Android profit margin, GST, supplier discount and product comparison calculator for Indian retail and pharmacy workflows.
- **CashQ:** Offline-first Indian Rupee cash counter for Android with note and coin counting, saved sessions and sharing.
- **WalletQ:** Free, privacy-focused Android app for personal and household money management.
- **StockQ:** Offline-first Android inventory and purchase management toolkit for Indian retailers and small businesses.
- **ClinicQ:** Android clinic management project for appointments, patient records and daily clinic operations.
- **Dr-SuBZeRo.github.io:** Official SuBZeRo developer portfolio website.

### Phase 3 — Documentation consistency
Each app repository should maintain:
- Clear overview and intended audience.
- Accurate status: released, active development, planned, or archived.
- Verified features separated from planned work.
- Current screenshots and short feature walkthrough.
- Installation instructions and release links.
- Minimum Android version and verified build requirements.
- Privacy and permissions explanation.
- Backup, restore, and data ownership details where applicable.
- Verified build/test commands.
- Support instructions, issue templates, and contribution guidance.
- Changelog or release notes for public releases.

### Phase 4 — Release readiness
- [ ] Use version tags and concise release notes.
- [ ] Publish signed production APK/AAB assets where appropriate; never publish signing keys.
- [ ] Provide SHA-256 checksums for downloadable assets.
- [ ] Maintain a repeatable release checklist.
- [ ] Test clean install, upgrade, backup/restore, and critical workflows.
- [ ] Use CI for build, unit tests, and lint where practical.
- [ ] Review F-Droid metadata and reproducible-build requirements before submission.
- [ ] Keep GitHub Releases as a transparent distribution channel while preparing other stores.

### Phase 5 — Developer website
- [ ] Give each featured project a clear section or dedicated page.
- [ ] Show real screenshots, platform, status, repository and release links.
- [ ] Check mobile navigation, keyboard access, contrast and loading performance.
- [ ] Provide a clear support route without mandatory registration.
- [ ] Keep website project information aligned with GitHub.

## Profile pinning recommendation

1. MargiQ
2. CashQ
3. WalletQ
4. StockQ
5. ClinicQ
6. Dr-SuBZeRo.github.io

The profile README repository is displayed automatically as the profile README; use the remaining pin slot for the website or the most useful active project.

## Quality and documentation rules

1. Never describe a planned feature as implemented.
2. Never claim offline operation without checking network dependencies and permissions.
3. Never claim zero telemetry or zero data collection without verifying dependencies and runtime behaviour.
4. Keep screenshots current with the released UI.
5. Prefer dynamic release badges over hardcoded version numbers.
6. Do not use badges that imply an unverified build, test, security, or release status.
7. Prefer concise, maintainable documentation.
8. Keep issue trackers actionable with labels, reproduction steps, and expected versus actual behaviour.

## Maintenance cadence

| Frequency | Maintenance |
|---|---|
| Every release | Update changelog, release notes, screenshots when UI changes, and release badges |
| Monthly | Review project status, open issues, broken links, dependencies and documentation drift |
| Quarterly | Review pinned repositories, website content, store distribution progress and privacy claims |

## Definition of done

- Visitors understand the developer identity and product focus quickly.
- Each featured app has accurate purpose, status, screenshots, installation and support paths.
- Planned and implemented features are never confused.
- Repository descriptions, topics, license and website links are consistent.
- Releases can be installed and upgraded using documented steps.
- Privacy claims are supported by implementation evidence.
- Website and GitHub profile tell the same story.

---

**Guiding principle:** Build fewer products well, document them honestly, and make them easy to evaluate and use.
