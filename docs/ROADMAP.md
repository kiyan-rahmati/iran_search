# ARYA Product Roadmap

## Phase 0 — Start-page prototype (current)
- [x] Persian RTL, responsive design
- [x] Faravahar-inspired visual identity
- [x] Live clock, Persian date, greeting
- [x] Scenic background rotation
- [x] Search engine selector
- [x] Add/remove-free quick links (custom links currently add-only)
- [x] Theme toggle

## Phase 1 — Product polish
- [ ] Replace remote wallpaper URLs with licensed/self-hosted Iranian photography
- [ ] Add shortcut editing and deletion
- [ ] Add keyboard shortcut (/) to focus search
- [ ] Add user-selectable background schedule and reduced-motion setting
- [ ] Add favorites and import/export settings

## Phase 2 — Backend and identity
- [ ] ASP.NET Core API
- [ ] User accounts and sync
- [ ] Settings storage and encrypted secrets
- [ ] Privacy policy and telemetry opt-in

## Phase 3 — Iranian discovery layer
- [ ] Search suggestions and curated Iranian sites
- [ ] News / weather / calendar cards from reputable APIs
- [ ] Local content catalog and transparent source labels

## Phase 4 — Business model (only after user value)
- [ ] Optional sponsorships, clearly labeled
- [ ] Premium customization, sync, and productivity features
- [ ] Never sell user search history; minimize data collection

## Technical direction
The current prototype is static HTML/CSS/JS. For a production service, move to a maintainable component architecture (e.g. Vue or React) and ASP.NET Core backend only when needed. Keep third-party search redirects clearly disclosed. Avoid claiming that ARYA itself indexes the web until a search backend is actually built.
