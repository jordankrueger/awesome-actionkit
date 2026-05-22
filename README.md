# Awesome ActionKit [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](contributing.md)
![Last Commit](https://img.shields.io/github/last-commit/jordankrueger/awesome-actionkit.svg)

> A curated list of tools, snippets, integrations, consultants, and guides for [ActionKit](https://actionkit.com), the campaign and advocacy platform used by progressive organizations.

ActionKit is powerful, but much of its best tooling is scattered — surfaced only in Slack threads, ClientCon sessions, or vendor blog posts. This list collects what's out there in one place.

> [!NOTE]
> This is a community-maintained project. It is not affiliated with, endorsed by, or operated by ActionKit or NGP VAN. Entries are curated by [@jordankrueger](https://github.com/jordankrueger) ([CampaignHelp](https://campaign.help)); some entries link to AK-authored resources, but inclusion does not imply AK staff involvement in this list.

## Contents

- [Community](#community)
- [Snippets and templates](#snippets-and-templates)
- [Tooling and dashboards](#tooling-and-dashboards)
- [SQL and reporting](#sql-and-reporting)
- [Data and deliverability](#data-and-deliverability)
- [Commercial add-ons](#commercial-add-ons)
- [Consultants and services](#consultants-and-services)
- [Guides and tutorials](#guides-and-tutorials)
- [Integrations](#integrations)

## Community

- [The AK Club](https://theak.club) - Private Circle.so community for ActionKit users, hosted by CampaignHelp. Members can re-enter at [hub.theak.club](https://hub.theak.club/feed).

## Snippets and templates

- [ak-redirect-blocks](https://github.com/CampaignHelp/ak-redirect-blocks) - Recipe book for dynamic after-action redirect URLs using ActionKit's Django-template support. Includes a donation-URL parameters reference.
- [ak-mailing-blocks](https://github.com/CampaignHelp/ak-mailing-blocks) - Ready-to-paste HTML building blocks for ActionKit mailings: CTA buttons, donation arrays, and a dark-mode-safe email wrapper. Tiered so non-developers can edit from the AK admin. Includes an [interactive playground](https://campaignhelp.github.io/ak-mailing-blocks/playground/) for tweaking colors and copying HTML without editing files.
- [ActionKit Production Template](https://jordankrueger.com/#ak-template) - Annotated Google Doc template for planning and tracking ActionKit production work, from the Email Strategy Summit session. Watch the walkthrough video or get the link via email signup `CH`.

## Tooling and dashboards

- [AK Health Check](https://github.com/CampaignHelp/ak-health-check) - Open-source diagnostic tool that audits an ActionKit instance for common configuration and deliverability issues.
- [Workbench for ActionKit](https://akworkbench.com) - Browser-based toolkit that runs inside the ActionKit admin for inspecting pages, mailings, and user data.
- [akapi-fetch.js](https://greenthumbsoftware.com/making-actionkit-api-calls-from-interactive-dashboards-with-akapi-fetch-js/) - JavaScript helper library for making ActionKit REST API calls from interactive dashboards.
- [sticky-akid.js](https://greenthumbsoftware.com/recognizing-actionkit-users-with-sticky-akid-js/) - JavaScript snippet that persists ActionKit user identification across sessions and pages.
- [Petition Delivery Formatter](https://github.com/jordankrueger/petition-delivery-formatter) - Offline web app that converts a signature CSV into a formatted PDF for in-person delivery.

## SQL and reporting

- [SQLpedia](https://clientcon.actionkit.com/go/sqlpedia) - ActionKit's official LLM context file covering schema, query semantics, performance tips, and prompting guidance for AI-assisted reporting on ActionKit data.
- [Passing lists into ActionKit query reports](https://thirdbearsolutions.com/blog/passing-lists-actionkit-query-reports/) - Technique for accepting user-input lists in custom query reports.

## Data and deliverability

- [Deliverability Landscape Update (Randall Farmer, ClientCon 2026)](https://docs.google.com/presentation/d/16yOPzMAtHc7sRxZwOR-fRpaOfms9cJgjHuTkO37Q-Rw/edit) - ActionKit's 2026 deliverability briefing: KumoMTA migration, Microsoft January 2026 blocks, Gmail image-prefetching reduction, Comcast/Yahoo merger, and election-year sender-reputation guidance.

## Commercial add-ons

- [AK Help](https://akhelp.campaign.help) - AI help agent trained on ActionKit documentation.
- [Stratosphere](https://thirdbearsolutions.com/stratosphere) - Dashboards and member insights built on ActionKit data. Offered by Third Bear Solutions with a free tier and a paid tier (advanced dashboards, custom views, dedicated support).

## Consultants and services

- [CampaignHelp](https://campaign.help) - ActionKit consulting, implementation, and deliverability. Curator of this list.
- [Green Thumb Software](https://greenthumbsoftware.com) - ActionKit consulting led by Simon Cavalletto, a longtime ActionKit engineer.
- [Third Bear Solutions](https://thirdbearsolutions.com) - ActionKit consulting firm operating since 2010; makers of Stratosphere.
- [Mycelium Strategies](https://www.linkedin.com/in/mark-ristaino-b7034015a/) - Data analytics for social justice organizations, including UltraViolet, The Intercept, ActionKit, and 350.org.
- [Supraluminique](https://fasterthanlight.tech) - ActionKit consulting practice run by Shannon Turner.

## Guides and tutorials

- [ActionKit Donation Push API quirks](https://thirdbear.substack.com/p/actionkit-donation-push-api-quirks) - Third Bear's working notes on edge cases and gotchas in the Donation Push API.
- [Aggregating values server-side in ActionKit templates](https://thirdbearsolutions.com/blog/aggregating-values-server-side-actionkit-templates/) - Third Bear walkthrough for summing pledge and donation totals inside templates for display.
- [Complex template logic with `{% record %}` and `{% with %}`](https://thirdbearsolutions.com/blog/complex-template-logic-record-and/) - Third Bear guide to advanced Django-template patterns used inside ActionKit pages and emails.
- [Custom public API endpoints for ActionKit data](https://thirdbearsolutions.com/blog/custom-public-api-endpoints-actionkit-data/) - Third Bear technique for defining JSON/JSONP endpoints via templatesets, with CORS support.
- [Cmd-Return / Ctrl-Enter to submit any AK admin form](https://docs.actionkit.com/docs/manual/releases/2016.html#hidden-feature-call-out) - Hidden keyboard shortcut from the 2016 release notes. Holding Shift submits via the first alternate button (e.g. submit-and-next-page). Surfaced again by Simon Cavalletto on The AK Club, June 2025.
- [Customizing your Pre-flight Dashboard](https://blog.actionkit.com/customizing-your-pre-flight-dashboard/) - ActionKit's walkthrough of the `draft_dash` feature for admin-page customization.
- [Using LLMs with ActionKit (Tim Caro-Bruce, ClientCon 2026)](https://docs.google.com/presentation/d/1Sto-KBKVWm8dCe5b14Y95GKd_5MKG_Y3aSe1S99gpUM/edit) - Practical, AK-staff-led talk on safely using LLMs against ActionKit data. Covers context attachment, schema sharing, assumption-listing, verification, and building org memory (CLAUDE.md / AGENTS.md / custom skills). Source of SQLpedia.
- [Cutting Out the Middleman: Helping Supporters Email Decision-Makers Directly](https://thirdbear.substack.com/p/cutting-out-the-middleman-helping) - Third Bear walkthrough for building `mailto:` advocacy campaigns where supporters contact decision-makers straight from their own inbox.
- [Development workflow for ActionKit templatesets](https://thirdbearsolutions.com/blog/development-workflow-actionkit-templatesets/) - Third Bear's local development workflow for editing templatesets with live preview.
- [Don't Let Recurring Donors Lapse](https://blog.actionkit.com/dont-let-recurring-donors-lapse-updated/) - ActionKit's step-by-step workflow for re-engaging recurring donors with expiring or failed credit cards, using built-in reports, targeted mailings, and self-service update pages.
- [Reusable code snippets in ActionKit templates](https://thirdbearsolutions.com/blog/reusable-code-snippets-actionkit-templates/) - Third Bear guide to building modular, reusable components with custom snippet overrides.
- [Staying in the Loop: Tracking Email Advocacy Actions](https://thirdbear.substack.com/p/staying-in-the-loop-tracking-email) - Third Bear guide to tracking supporter email advocacy using BCC lines and inbound email processing, so organizations can monitor outreach without disrupting the sender's experience.

## Integrations

Platforms with documented ActionKit integrations.

- [ActBlue](https://secure.actblue.com) - Fundraising and donation processor.
- [Mobilize](https://www.mobilize.us) - Event management platform that syncs events and RSVPs with ActionKit.
- [ControlShift](https://www.controlshiftlabs.com) - Distributed petition and campaign platform.
- [NEW/MODE](https://newmode.net) - Multi-channel advocacy engagement: calls, emails, letters.
- [ShareProgress](https://shareprogress.org) - Share-action testing and optimization.
- [CallPower](https://www.callpower.org) - Phone-action tool for legislative advocacy.
- [GetThru](https://www.getthru.io) - Peer-to-peer SMS and phone banking.
- [Grassroots Unwired](https://www.grassrootsunwired.com) - Field canvassing and mobile data collection.
- [NGP VAN](https://www.ngpvan.com) - Voter and donor data platform; ActionKit's parent-adjacent.

## Contributing

Pull requests are welcome for new entries, corrections, and fixes. See the contributing guide in this repo.

---

Curated by [@jordankrueger](https://github.com/jordankrueger).
