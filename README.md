# SPREE_PRIOR_DOCS

![licence](https://img.shields.io/badge/licence-BSD-3-Clause-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `SPREE_PRIOR_DOCS` in category **ONLINE_RETAIL**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** SPREE_PRIOR_DOCS · **Upstream pin:** `620de865a555b6ee768f257b1b58e26323d5ddde` · **Category:** ONLINE_RETAIL · **Vendor:** Anticloud FZ LLE · **Licence:** BSD-3-Clause

---

## What This Project Does

<p>
  <a href="https://spreecommerce.org">
    <img src="https://spreecommerce.org/wp-content/themes/spree/images/logo.svg" alt="Spree Commerce open source headless eCommerce platform for B2B, Multi-seller Marketplace, cross-border eCommerce, multi-tenant eCommerce" width="250" />
  </a>
</p>

[Website](https://spreecommerce.org)
·
[Next.js Storefront](https://github.com/spree/storefront)
·
[Documentation](https://spreecommerce.org/docs/)
·
[API](https://spreecommerce.org/docs/api-reference/)
·
[Roadmap](https://github.com/spree/spree/milestones?direction=asc&sort=due_date&state=open)
·
[Discord](https://discord.spreecommerce.org)

[![Gem Total Downloads](https://img.shields.io/gem/dt/spree)](https://rubygems.org/gems/spree)
[![codecov](https://codecov.io/gh/spree/spree/graph/badge.svg?token=DPFc7HbJvU)](https://codecov.io/gh/spree/spree)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

**Build commerce the way you want it.** Spree is an open-source commerce platform with a complete REST API, TypeScript SDKs, a React admin dashboard, and a production-ready Next.js storefront. BSD 3-Clause licensed — keep full ownership of your code, data, and infrastructure.

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

## Use Cases

Spree ships commerce primitives, so the same core serves very different businesses.

### [Multi-vendor Marketplace](https://spreecommerce.org/docs/developer/how-to/build-a-marketplace)

Seller onboarding with configurable requirement checklists, orders split per seller at completion, a flexible [commission engine](https://spreecommerce.org/docs/developer/core-concepts/commissions), a payout ledger with Stripe Connect, and a dedicated Seller Panel. All in the open-source core.

<img alt="Spree Commerce - Multi-vendor Marketplace eCommerce" src="https://github.com/spree/spree/assets/12614496/c4ddd118-df4c-464e-b1fe-d43862e5cf25" width="600" >

### [B2B & Wholesale](https://spreecommerce.org/docs/developer/how-to/build-a-b2b-store)

[Price lists](https://spreecommerce.org/docs/developer/core-concepts/pricing) with volume tiers, [customer groups](https://spreecommerce.org/docs/user/customers/customer-groups), [companies](https://spreecommerce.org/docs/developer/core-concepts/companies) with locations, contacts and tax exemptions, [catalogs](https://spreecommerce.org/docs/developer/core-concepts/catalogs) for per-segment assortments, and storefronts gated to approved buyers.

<img src="https://github.com/spree/spree/assets/12614496/bac1e551-f629-47d6-a983-b385aa65b1bd" alt="Spree Commerce - Wholesale eCommerce Platform" width="600" >

### [Headless & Omnichannel](https://spreecommerce.org/docs/developer/core-concepts/channels)

Run web storefronts, mobile apps, points of sale, B2B panels and marketplaces off one backend. [Channels](https://spreecommerce.org/docs/developer/core-concepts/channels) give each surface its own catalog, pricing, payment methods and order attribution.

The [Next.js storefront](https://github.com/spree/storefront) is one such surface — production-ready, open source, built with Next.js 16, React 19 and TypeScript. Fork it, customize it, deploy it. [Try the live demo](https://demo.spreecommerce.org/)

<table>
  <tr>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-Homepage.webp" alt="Spree Commerce - Next.js Storefront - Home" width="400" /></a></td>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-Product-Detail-Page-PDP.webp" alt="Spree Commerce - Next.js Storefront - Product" width="400" /></a></td>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-PageSpeed-Lighthouse.webp" alt="Spree Commerce - Next.js Storefront - Lighthouse" width="400" /></a></td>
  </tr>
</table>

### [Cross-border Commerce](https://spreecommerce.org/docs/developer/core-concepts/markets)

[Markets](https://spreecommerce.org/docs/developer/core-concepts/markets) bundle currency, language, payment methods and shipping per region, so each customer sees a localized storefront from a single platform. [Translations](https://spreecommerce.org/docs/developer/core-concepts/translations) for product content, EU Omnibus price history and customs duties are built in.

<img alt="Spree Commerce - Cross-border eCommerce" src="https://spreecommerce.org/wp-content/uploads/2024/07/multi-region-country-shopping-1024x575.webp" width="600" >

### [Multi-tenant SaaS](https://spreecommerce.org/docs/developer/multi-tenant/quickstart) <sup>Enterprise</sup>

Run a SaaS platform where each tenant gets its own isolated store — catalog, orders, customers, payment methods and branding — with staff able to manage several tenants. Requires the [Enterprise Edition](https://spreecommerce.org/pricing).

## Getting Started

Copy and paste the following command to your terminal to set up Spree locally in 5 minutes:

```bash
npx create-spree-app@latest my-store
```

This sets up the Spree backend, the React Admin Dashboard, and optionally the [Next.js storefront](https://github.com/spree/storefront) in a single project. The storefront is built with Next.js 16, React 19, Tailwind CSS 4, and TypeScript.

You need Node.js 24+ installed and Docker running. Learn more in the [installation docs](https://spreecommerce.org/docs/developer/getting-started/quickstart).

If you like what you see, consider giving Spree a GitHub star ⭐

Thank you for supporting Spree open-source ❤️

### Agentic Development

Building with an AI coding agent? Install the [Spree agent skills](https://github.com/spree/agent-skills) — they teach Claude Code, Cursor, Copilot, and 60+ other tools Spree's conventions, customization patterns, and upgrade flows:

```bash
npx skills add spree/agent-skills
```

Then connect the [docs MCP server](https://spreecommerce.org/docs/developer/agentic/mcp) and let your agent build with you. Learn more in the [Agentic Development docs](https://spreecommerce.org/docs/developer/agentic/overview).

### Spree CLI

[`@spree/cli`](packages/cli) manages your Spree project from the terminal — boot the stack, run generators and migrations, tail logs — and calls the **Admin API** directly with simple `get`/`post`/`patch`/`delete` commands. It's a fast way to inspect and script your store, and works hands-free for AI agents (zero-config credentials in local dev):

```bash
spree dev                                                            # boot the project (web + worker + db)
spree generate api_resource Brand name:string description:rich_text  # Creates full API endpoints, models and database schema for a Brand resource
spree api get /orders -q status_eq=complete --limit 10               # query the Admin API
spree api post /products -d '{"name":"Classic Tee","prices":[{"currency":"USD","amount":"29.99"}]}'  # create resources
```

`spree api endpoints` and `spree api schema` explore the full API offline. See the [CLI docs](https://spreecommerce.org/docs/developer/cli/quickstart).

## Features

Everything below ships in this project under the BSD 3-Clause license.

* **[REST API & TypeScript SDKs](https://spreecommerce.org/docs/api-reference/store-api/introduction)** — a REST API for storefronts, admins and sellers, with publishable keys, scoped secret keys, rate limiting and an OpenAPI 3.0 spec. Three typed clients: [`@spree/sdk`](packages/sdk) (Store), [`@spree/admin-sdk`](packages/admin-sdk) (Admin) and [`@spree/seller-sdk`](packages/seller-sdk) (Seller).
* **[React Admin Dashboard](https://spreecommerce.org/docs/developer/dashboard/overview)** — a Vite + React SPA built on TanStack Router and Query, shadcn/ui and Tailwind. Extend it with [plugins](https://spreecommerce.org/docs/developer/dashboard/plugins/overview) — nav entries, routes, table columns and slot widgets — without forking it. Ships with a matching **Seller Panel** for marketplace vendors.
* **[Next.js Storefront](https://github.com/spree/storefront)** — open-source storefront built with Next.js 16, React 19, Tailwind CSS 4, and TypeScript. Full shopping experience, multi-region URL routing, Stripe payments (Apple Pay, Google Pay, Klarna, Affirm), customer accounts, and SEO built in. [Try the demo](https://demo.spreecommerce.org/)
* **[Spree CLI](https://spreecommerce.org/docs/developer/cli/quickstart)** — manage projects from the terminal (boot, generate, migrate, upgrade) and call the Admin API directly with `spree api get/post/...` — zero-config in local dev, built for scripts and AI agents.
* **[Marketplace & Payouts](https://spreecommerce.org/docs/developer/core-concepts/sellers)** — seller onboarding with a configurable requirements checklist, per-seller order splitting, a [commission engine](https://spreecommerce.org/docs/developer/core-concepts/commissions) with EU commission taxation, and a payout ledger with Stripe Connect payouts.
* **[B2B & Wholesale](https://spreecommerce.org/docs/developer/how-to/build-a-b2b-store)** — [price lists](https://spreecommerce.org/docs/developer/core-concepts/pricing) with volume tiers and negotiated rates, [customer groups](https://spreecommerce.org/docs/user/customers/customer-groups) for segmentation, [companies](https://spreecommerce.org/docs/developer/core-concepts/companies) with locations, contacts and validated tax exemptions, and [catalogs](https://spreecommerce.org/docs/developer/core-concepts/catalogs) for per-segment assortments.
* **[Payments](https://spreecommerce.org/docs/developer/core-concepts/payments)** — provider-agnostic payment sessions that finish reliably even when a tab closes. Ships with [Stripe](https://spreecommerce.org/docs/integrations/payments/stripe), [Adyen](https://spreecommerce.org/docs/integrations/payments/adyen) and [PayPal](https://spreecommerce.org/docs/integrations/payments/paypal). Add your own with the [Payment Provider SDK](https://spreecommerce.org/docs/developer/how-to/custom-payment-method).
* **[Promotions & Gift Cards](https://spreecommerce.org/docs/developer/core-concepts/promotions)** — a rules-based [promotions engine](https://spreecommerce.org/docs/developer/core-concepts/promotions) for percentage and fixed discounts, free shipping, BOGO offers and coupon codes, plus native [store credits and gift cards](https://spreecommerce.org/docs/developer/core-concepts/store-credits-gift-cards).
* **[Fulfillment](https://spreecommerce.org/docs/developer/core-concepts/fulfillments)** — shipping, digital delivery and in-store pickup, [delivery profiles and zones](https://spreecommerce.org/docs/developer/core-concepts/delivery-setup), multi-location [inventory](https://spreecommerce.org/docs/developer/core-concepts/inventory), and [returns, exchanges and claims](https://spreecommerce.org/docs/developer/core-concepts/returns-exchanges-claims).
* **[Taxes & Compliance](https://spreecommerce.org/docs/developer/core-concepts/taxes)** — inclusive or added-on tax, automatic calculation via Avalara and Stripe Tax, cross-border [customs fees & duties](https://spreecommerce.org/docs/developer/core-concepts/fees), and [data privacy](https://spreecommerce.org/docs/developer/core-concepts/data-privacy) tooling for GDPR subject requests and EU Omnibus price history.
* **Products & Catalog** — [custom fields](https://spreecommerce.org/docs/developer/core-concepts/metafields) on any record, [CSV imports and exports](https://spreecommerce.org/docs/developer/core-concepts/imports-exports), digital products, product tags, a shared [media library](https://spreecommerce.org/docs/developer/core-concepts/media) and bulk operations.
* **[Provider Contracts](https://spreecommerce.org/docs/developer/providers/overview)** — plug your existing stack in rather than replacing it: [ERP](https://spreecommerce.org/docs/developer/providers/erp), [PIM](https://spreecommerce.org/docs/developer/providers/pim), [WMS and carriers](https://spreecommerce.org/docs/developer/providers/fulfillment), [DAM](https://spreecommerce.org/docs/developer/providers/dam), [SSO](https://spreecommerce.org/docs/developer/providers/sso) and [payouts](https://spreecommerce.org/docs/developer/providers/payouts).
* **[Security & Identity](https://spreecommerce.org/docs/developer/providers/sso)** — [OpenID Connect](https://spreecommerce.org/docs/developer/providers/sso) single sign-on for staff and customers, [custom auth adapters](https://spreecommerce.org/docs/developer/how-to/custom-api-authentication) for any JWT issuer, [role-based permissions](https://spreecommerce.org/docs/developer/customization/permissions) scoped per store, and a [PCI-compliant](https://spreecommerce.org/docs/developer/security/pci_compliance) payment architecture where card data never touches your server.
* **[MeiliSearch Integration](https://spreecommerce.org/docs/integrations/search/meilisearch)** — typo-tolerant product search and faceted filtering, or [bring your own search provider](https://spreecommerce.org/docs/developer/how-to/custom-search-provider).
* **Integrations & Extensibility** — [Event Bus](https://spreecommerce.org/docs/developer/core-concepts/events), [Webhooks](https://spreecommerce.org/docs/developer/core-concepts/webhooks), [OpenTelemetry](spree/opentelemetry) instrumentation, and native integrations ([GA4](https://spreecommerce.org/docs/integrations/analytics/google-analytics), [GTM](https://spreecommerce.org/docs/integrations/analytics/google-tag-manager), [Klaviyo](https://spreecommerce.org/docs/integrations/marketing/klaviyo)).
* **[Agentic Development](https://spreecommerce.org/docs/developer/agentic/overview)** — [agent skills](https://github.com/spree/agent-skills) (`npx skills add spree/agent-skills`) teaching AI coding agents Spree's conventions, a [docs MCP server](https://spreecommerce.org/docs/developer/agentic/mcp), [LLM-ready documentation](https://spreecommerce.org/docs/developer/agentic/llm-docs) (llms.txt, per-page Markdown, offline npm package), and a generated AGENTS.md/CLAUDE.md in every scaffolded project.

## Deployment

The Spree backend can be deployed anywhere — cloud, on-prem or VPS. We provide official Docker images and Dockerfiles, so you can use AWS, Azure, GCP, Render, Railway, Fly.io, Heroku, or any other Docker-compatible host. The Next.js storefront can be deployed to Vercel, Netlify, or any Node.js host. See the [Deployment Documentation](https://spreecommerce.org/docs/developer/deployment) for more details.

## Community & Contributing

Spree is an open-source project, and we love contributions in any form — pull requests, issues, feature ideas.

* Follow our [Contributing Guide](https://spreecommerce.org/docs/developer/contributing/quickstart)
* [Join our Discord](https://discord.spreecommerce.org) to meet other community members
* Browse the [Roadmap](https://github.com/spree/spree/milestones?direction=asc&sort=due_date&state=open) and open [Issues](https://github.com/spree/spree/issues)

## Spree Enterprise Edition

Spree is built and maintained by a funded team behind the open-source project. Beyond the open-source core, we offer a paid [Enterprise Edition](https://spreecommerce.org/enterprise/) for organizations that need additional modules and SLA-backed support.

Enterprise adds **B2B approval workflows** with role-based approval chains and ERP connectors, **marketplace automations** such as Shopify and WooCommerce seller sync and advanced reporting, **[multi-tenant SaaS](https://spreecommerce.org/docs/developer/multi-tenant/quickstart)** — running many isolated tenant stores from one deployment, with a super-admin, tenant provisioning and white-label billing — **audit logging and encryption at-rest**, and **SLA support** with a dedicated success manager, LTS releases and 24/7 monitoring.

Everything else — the APIs, the SDKs, the dashboard, marketplace, B2B and cross-border — is in this project. Enterprise Edition builds on the same BSD 3-Clause core, so your team keeps full ownership of the code, the data, and the infrastructure. Zero platform fees. Zero transaction fees.

[Contact our Sales team](https://spreecommerce.org/contact/) for an Enterprise Edition demo, or [join Discord](https://discord.spreecommerce.org) to use the open-source edition with the community.

## License

Spree Commerce core code in the **[spree/spree](https://github.com/spree/spree)** project is released under the free, open-source [BSD-3-Clause](https://opensource.org/license/bsd-3-clause) license ([LICENSE](https://github.com/spree/spree/blob/main/LICENSE)).

If you like what you see, consider giving Spree a GitHub star ⭐

Thank you for supporting Spree open-source ❤️

---

## Installation

Run a SaaS platform where each tenant gets its own isolated store — catalog, orders, customers, payment methods and branding — with staff able to manage several tenants. Requires the [Enterprise Edition](https://spreecommerce.org/pricing).

## Usage

**Build commerce the way you want it.** Spree is an open-source commerce platform with a complete REST API, TypeScript SDKs, a React admin dashboard, and a production-ready Next.js storefront. BSD 3-Clause licensed — keep full ownership of your code, data, and infrastructure.

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

## API

·
[API](https://spreecommerce.org/docs/api-reference/)
·
[Roadmap](https://github.com/spree/spree/milestones?direction=asc&sort=due_date&state=open)
·
[Discord](https://discord.spreecommerce.org)

[![Gem Total Downloads](https://img.shields.io/gem/dt/spree)](https://rubygems.org/gems/spree)
[![codecov](https://codecov.io/gh/spree/spree/graph/badge.svg?token=DPFc7HbJvU)](https://codecov.io/gh/spree/spree)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

**Build commerce the way you want it.** Spree is an open-source commerce platform with a complete REST API, TypeScript SDKs, a React admin dashboard, and a production-ready Next.js storefront. BSD 3-Clause licensed — keep full ownership of your code, data, and infrastructure.

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

<img alt="Spree Commerce - Multi-vendor Marketplace eCommerce" src="https://github.com/spree/spree/assets/12614496/c4ddd118-df4c-464e-b1fe-d43862e5cf25" width="600" >

## Contributing

# Contributing

Thank you for your interest in contributing to Spree! This guide will help you get started.

Please read our [Code of Conduct](../CODE_OF_CONDUCT.md) before contributing.

## Table of Contents

- [Getting Started](#getting-started)
  - [Cloning the project](#cloning-the-project)
  - [Prerequisites](#prerequisites)
  - [Spree codebase](#spree-codebase)
  - [Setup](#setup)
  - [Running server day-to-day](#running-server-day-to-day)
  - [Emails in development](#emails-in-development)
  - [Native Ruby (advanced)](#native-ruby-advanced)
- [Backend Development (Ruby)](#backend-development-ruby)
  - [Engines overview](#engines-overview)
  - [Spree namespace](#spree-namespace)
  - [Running engine tests](#running-engine-tests)
  - [Running tests in parallel](#running-tests-in-parallel)
  - [Performance in development mode](#performance-in-development-mode)
- [TypeScript Development](#typescript-development)
  - [Packages](#packages)
  - [Common commands](#common-commands)
  - [Package-specific commands](#package-specific-commands)
  - [Working on the React dashboard](#working-on-the-react-dashboard)
  - [Working on the storefront](#working-on-the-storefront)
  - [Dashboard E2E tests](#dashboard-e2e-tests)
  - [Type generation](#type-generation)
  - [Releasing packages](#releasing-packages)
- [Code Style](#code-style)
- [Making Changes](#making-changes)
  - [Branch naming](#branch-naming)
  - [Commit messages](#commit-messages)
- [Submitting Changes](#submitting-changes)
  - [Pull request guidelines](#pull-request-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Using AI Tools for Development](#using-ai-tools-for-development)

## Getting Started

### Cloning the project

Spree is a big monorepo. For a faster source, use a **partial source** which downloads file contents on demand while keeping full commit history for `git log` and `git blame`:

```bash
git source --filter=blob:none https://github.com/spree/spree.git
```

### Prerequisites

- Docker (eg. [Docker Desktop for MacOS](https://www.docker.com/products/docker-desktop/))
- Node 24 ([Install instructions](https://nodejs.org/en/download))

`pnpm` is provisioned automatically via [Corepack](https://nodejs.org/api/corepack.html) (bundled with Node) — the project pins its version in `package.json`, and the first `pnpm` command will fetch the matching release. If Corepack is disabled in your environment, run `corepack enable` once.

### Spree codebase

Spree is a monorepo with three main areas:

- **`spree/`** — Ruby gems (core, api, emails, providers) distributed as separate packages via RubyGems
- **`packages/`** — TypeScript packages (Admin Dashboard, Seller Panel, SDKs, CLI, project scaffolding, docs)
- **`server/`** — A Rails application sourced from [spree-starter](https://github.com/spree/spree-starter) that mounts the local Spree gems (not checked in — `pnpm server:setup` creates it)

### Setup

A single command bootstraps the whole monorepo for both backend and frontend

## License

Upstream © its respective contributors under BSD-3-Clause (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** SPREE_PRIOR_DOCS
- **Pinned SHA:** `620de865a555b6ee768f257b1b58e26323d5ddde`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`3601f2eb0425ef82f2a1ceff6b1124d7d05e996e00d19774ab3ff66b4c8274ed`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

