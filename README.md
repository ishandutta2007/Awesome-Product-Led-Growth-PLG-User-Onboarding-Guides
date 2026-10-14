# Awesome-Product-Led-Growth-PLG-User-Onboarding-Guides

## Top Product-Led Growth (PLG) User Onboarding Guide Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on In-App Product Tours, Checklists & Feature Adoption Tracking*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Product-Led Growth (PLG) User Onboarding Guides**. These tools help product teams build in-app tours, checklists, hints, and surveys that guide users to their first "aha moment" — reducing time-to-value, improving activation, and driving feature adoption without manual hand-holding.

**Examples** include Appcues, Pendo, Chameleon, Userflow, WalkMe, Whatfix, CommandBar, Stonly, Userpilot, and Product Fruits (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, headless rendering, and code-first onboarding — ideal for engineering-led teams who want design system control, predictable costs, and no third-party scripts injected into their product's first impression.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pendo](https://www.pendo.io/)**  
  Analytics-first product adoption platform combining product analytics with in-app guides. Median contract sits at **$48,463/year** with ranges from $15.9K to $132.4K according to Vendr data . Injects a ~300KB+ agent script into your application. Best for enterprise teams already paying for Pendo analytics who want guides without adding a second vendor.

- **[Appcues](https://www.appcues.com/)**  
  No-code builder for product tours and onboarding flows. Growth plan starts at **$879/month for 2,500 MAU**, scaling to $3,000-$24,000/year at 10K MAU . Injects a ~200KB+ bundle. Best for product managers who want a visual builder and can absorb MAU-based pricing that grows with user base.

- **[Chameleon](https://www.trychameleon.com/)**  
  No-code product tour and onboarding platform with strong design customization. In-app microsurveys, tooltips, and launchers with A/B testing capabilities.

- **[Userflow](https://userflow.com/)**  
  No-code builder for product tours, checklists, and onboarding flows with visual editor and analytics.

- **[WalkMe](https://www.walkme.com/)**  
  Enterprise Digital Adoption Platform (DAP) covering employee training, customer onboarding, process automation, and analytics. Enterprise-only pricing.

- **[Whatfix](https://whatfix.com/)**  
  Enterprise DAP with in-app guidance, self-help widgets, and process automation. Offers on-premise deployment for strict data sovereignty requirements.

- **[CommandBar](https://www.commandbar.com/)**  
  AI-powered user assistance platform with command bar, help hub, and in-app nudges.

- **[Stonly](https://stonly.com/)**  
  Interactive knowledge platform for customer service and self-serve support. Combines guides, knowledge bases, targeting, analytics, and AI Answers. Best for **support and knowledge teams** building self-serve resolution paths rather than pure product onboarding [citation:13].

- **[Userpilot](https://userpilot.com/)**  
  Product growth platform with in-app onboarding flows, checklists, surveys, and analytics. **No public self-hosted or open-source option** [citation:17].

- **[Product Fruits](https://productfruits.com/)**  
  No-code user engagement toolkit with onboarding checklists, tours, and feedback tools.

## Open-Source GitHub Projects

- **[Usertour](https://github.com/usertour/usertour)**  
  **Open-source user onboarding platform positioned as a direct alternative to Userflow and Appcues.** Create in-app product tours, checklists, launchers, surveys, and banners in minutes with full control. Features a **free cloud plan**, paid cloud from **$59/mo monthly ($49/mo annual)**, and a **free self-hosted community edition** with a commercial self-managed license available [citation:13]. TypeScript-based with 1,400+ GitHub stars. Best for product teams that need onboarding and adoption **inside their app** with public pricing and a true self-hosted option [citation:13].

- **[Tour Kit](https://usertourkit.com/)**  
  **Developer library for code-first onboarding with composable packages.** MIT core (free) with Pro features at **$99 one-time**. Ships at **under 8KB gzipped** — compared to 200-300KB for injected SaaS scripts [citation:3]. Provides tours, checklists, hints, and analytics with **headless architecture** — you render the UI, the library handles positioning, step sequencing, keyboard navigation, and scroll management [citation:18]. **WCAG 2.1 AA built-in** [citation:3]. React 18+ only. Best for engineering-led teams who want full design system control and predictable costs that don't scale with user count [citation:3].

- **[React Joyride](https://github.com/gilbarbara/react-joyride)**  
  **Production-ready React component for guided tours** with **603K weekly npm downloads**, powering onboarding at thousands of companies as of April 2026 [citation:5]. MIT licensed, 37KB bundle. Battle-tested and widely adopted.

- **[Shepherd.js](https://github.com/shipshapecode/shepherd)**  
  Open-source tour library with **12,600+ GitHub stars** and support for React, Ember, Angular, Vue.js, and plain JavaScript [citation:5]. **Dual-licensed: AGPL-3.0** for open source/non-commercial use, with a **commercial license required for commercial products** [citation:5].

- **[Driver.js](https://github.com/kamranahmedse/driver.js)**  
  **Lightweight (3KB) open-source library** for product tours and onboarding flows. MIT licensed. Covers basics but **lacks built-in analytics** [citation:5].

- **[Laudspeaker](https://github.com/laudspeaker/laudspeaker)**  
  Open-source customer engagement and product onboarding platform positioned as an alternative to **Braze, OneSignal, Customer.io, Appcues, and Pendo** [citation:15]. Design product onboarding flows and send event-triggered emails, SMS, push, and more. TypeScript-based, 1,386+ GitHub stars [citation:15].

- **[Mimik](https://alternativeto.net/software/product-fruits/#1)**  
  **Auto-capture any browser workflow into a step-by-step guide with screenshots.** Local-first, open source, bring your own AI key. MIT licensed. Available for Chrome, Firefox, and Edge [citation:8][citation:11]. The top-rated open-source alternative to Product Fruits and Whatfix on AlternativeTo [citation:8][citation:11].

- **[Qikbar](https://github.com/nearbycoder/qikbar-next)**  
  **Open-source command bar for any web app** — Raycast-style search, routing, actions, extensions, and AI in one tiny, themeable package [citation:6]. Zero dependencies, **~3.5KB to boot**, virtualized lists handle 100K rows [citation:6]. AI can run your commands, search your sources, and read the page — works with Claude, GPT, Gemini, Ollama, or any OpenAI-compatible API [citation:6]. Not a traditional tour library but excellent for power-user onboarding and feature discovery.

### Additional Strong Open-Source Options

- **PostHog** — Open-source product analytics with free tier covering session replay, feature flags, A/B testing, and funnels. Pair with Tour Kit or React Joyride for a complete **$0/month PLG stack** [citation:2].
- **GrowthBook** — Open-source A/B testing and feature flagging platform.
- **Flipt** — Open-source feature flag solution.
- **Driver.js + PostHog** — Lightweight tour library combined with free analytics for startups under 10K MAU [citation:5].

**Frameworks for building custom systems**: Combine **Tour Kit** or **Usertour** for the onboarding UI layer, **PostHog** for product analytics and session replay, **GrowthBook** or **Flipt** for feature flags, and **Qikbar** for command-bar-based feature discovery to build a complete **self-hosted PLG onboarding stack** with zero recurring per-user costs [citation:2][citation:3].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- PLG onboarding tools must comply with data protection regulations (GDPR, CCPA) and accessibility standards (WCAG). Injected SaaS scripts add 150-250ms to Time to Interactive on mid-range mobile devices — performance-sensitive applications should weigh this against headless open-source alternatives [citation:18].
- Self-hosted open-source solutions require proper security hardening, analytics integration, and ongoing maintenance.

---

**Made for product managers, growth engineers, PLG teams, and developers building user onboarding platforms.**  
Let's make product-led growth onboarding more open, performant, and user-friendly.
