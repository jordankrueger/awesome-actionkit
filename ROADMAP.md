# Roadmap

The phases below are how the curator is growing this list. Suggestions and contributions are welcome at any phase — see [contributing.md](contributing.md).

Status legend: ✅ done · 🚧 in progress · ⏳ pending external reply · 📋 planned

## Phase 1 — v1 published ✅

Public repo at github.com/jordankrueger/awesome-actionkit. README organized into 9 sections, awesome-list badge, CC0 license, ~25 entries seeded.

## Phase 2 — Fill empty sections ✅

The "SQL and reporting" and "Data and deliverability" sections shipped with placeholders. Both filled 2026-04-29: SQLpedia under *SQL and reporting*, Randall Farmer's *Deliverability Landscape Update* under *Data and deliverability*. Every section now has at least one entry. Additional sourcing from CampaignHelp's own SQL recipes, Third Bear, Green Thumb, AK blog, and broader community continues as Phase 5/6 work.

## Phase 3 — Confirm pending inclusions ⏳

Several entries depend on external confirmations sent April 22, 2026. Tracking:

- ✅ ActionKit (Karin Roland + Randall Farmer): SQLpedia listing + 2025/2026 ClientCon slide-deck linkability — confirmed 2026-04-29. Canonical SQLpedia URL is `clientcon.actionkit.com/go/sqlpedia` (stable redirect, file location may move). Slides are good to share.
- Third Bear Solutions: Stratosphere free/paid tier accuracy, descriptions
- Green Thumb Software (Simon Cavalletto): descriptions, missed tools
- ActionKit (Jesse Erlbaum): public URL for the 2025 *Extending ActionKit: Tools that integrate* deck

Action: follow up after one week of silence; remove or adjust entries based on responses.

## Phase 4 — Direct outreach to AK orgs 📋

Reach out to large ActionKit orgs (MomsRising, UltraViolet, Color of Change, MoveOn, Care2, ACLU, Sierra Club, NRDC, others) and ask whether they have internal tooling, SQL recipes, or snippets they'd be willing to publish. Most won't — but a single high-quality contribution from one of these orgs is a meaningful addition.

## Phase 5 — Community outreach for contributions 📋

Promote the list and invite contributions in:

- The AK Club (Circle.so community)
- RadComms
- GameChanger Salon

Direct asks to listed consultants (Green Thumb, Third Bear, Mycelium, Supraluminique) for additions in their areas of strength.

## Phase 6 — Mine ClientCon 2026 sessions for entries 🚧

The ClientCon 2026 slide index ([clientcon.actionkit.com/survey/get-slides-cc26/](https://clientcon.actionkit.com/survey/get-slides-cc26/?rd=1)) and individual decks are candidate entries — sharing approved by AK 2026-04-29:

- ✅ Tim Caro-Bruce — *Using LLMs with ActionKit* — added under *Guides and tutorials* 2026-04-29 (SQLpedia separately under *SQL and reporting*)
- ✅ Randall Farmer — *Deliverability Landscape Update* — added under *Data and deliverability* 2026-04-29
- ⏸ Perrin Harkins — *Automations* — held; AK Automations feature isn't released yet, so listing the deck would be premature. Revisit when the feature ships.
- ⏳ Jesse Erlbaum — *Extending ActionKit: Tools that integrate* (2025) — held pending Jesse's reply on a public URL (cc25 deck links require auth)

If a deck can be linked publicly, add it under *Guides and tutorials*. If it can't, document the topic and link to the parent ClientCon archive.

## Phase 7 — Submit to sindresorhus/awesome 📋

Once sections are populated, the list passes `awesome-lint`, and the curator-owned entry share is balanced by community contributions, open a PR to add Awesome-ActionKit to the main awesome-list. Increases discoverability and inbound traffic.

## Phase 8 — Ongoing maintenance 📋

Quarterly:

- Run `awesome-lint` and fix any new violations
- Pass through every link, retire dead ones, replace authwalled ones
- Review entries for currency (e.g., consultants who've changed firms, products that have shut down)
- Cap the list around ~50 entries — curation, not catalog

---

This roadmap describes the curator's plans; PRs that don't match a phase are still welcome if they fit [what belongs here](contributing.md).
