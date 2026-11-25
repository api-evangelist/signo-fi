# Signo

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Signo provides AI-powered agents that continuously monitor your DeFi positions across multiple protocols, surfacing risks, opportunities, and actionable plans. Users can configure agents to watch specific assets, set limits, and receive automated signals with recommended trades or protective actions. The platform offers a web interface and integrates with wallets, supporting assets like USDC, ETH, and various yield strategies. Signo aims to simplify DeFi management by automating monitoring and decision support, helping users stay on top of market movements 24/7.

**Areas:** DeFi · AI · Monitoring · Automation · Finance

## Signo on APIs.io

Everything profiled for Signo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/signo-fi/](https://apis.io/providers/signo-fi/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Signo Account API](https://apis.io/apis/signo-fi/signo-fi-account-api/) — Usage, credit balance, and capability discovery.
- [Signo Agents API](https://apis.io/apis/signo-fi/signo-fi-agents-api/) — Programmatic alerts (price / yield / health-factor / portfolio-move / schedule / a plain-English condition) scoped to your tenant. Not metered by credits —…
- [Signo Create an agent API](https://apis.io/apis/signo-fi/signo-fi-create-an-agent-api/) — No API key needed. Any assistant can create a Notify or Prepare agent for a wallet it does not control, or request an early-access Execute permission for an…
- [Signo Execution API](https://apis.io/apis/signo-fi/signo-fi-execution-api/) — Re-quote and simulate steps at sign time.
- [Signo Partner surfaces API](https://apis.io/apis/signo-fi/signo-fi-partner-surfaces-api/) — Catalog-backed, contextual Signo agents embedded in partner pages. Keep the `sg_` key on the partner backend: catalog and resolve responses are…
- [Signo Planning API](https://apis.io/apis/signo-fi/signo-fi-planning-api/) — Turn intent into signable transactions.
- [Signo Positions API](https://apis.io/apis/signo-fi/signo-fi-positions-api/) — A wallet's addressable positions, each row carrying the canonical composite `id` a `position` subject is named by. Requires the `agents` scope (the same…
- [Signo Shield API](https://apis.io/apis/signo-fi/signo-fi-shield-api/) — Read a Shield proposal, its authorized permission and its execution runs. Partner key required; a proposal is readable only by the tenant that drafted it.
- [Signo Telegram API](https://apis.io/apis/signo-fi/signo-fi-telegram-api/) — Wallet Telegram link state for partner Turn on buttons. Requires the `agents` scope (there is no separate telegram scope). Never returns chat ids or usernames.
- [Signo Webhook delivery API](https://apis.io/apis/signo-fi/signo-fi-webhook-delivery-api/) — Register an HTTPS endpoint that agent triggers are pushed to, and pull/replay trigger history. See the `webhooks` section below for the delivery contract…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Signo Fi Webhooks](https://apis.io/asyncapis/signo-fi/signo-fi-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Signo Agentic Access](https://apis.io/agentic-access/signo-fi/signo-fi-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AgentPatchRequest](https://apis.io/schemas/signo-fi/signo-fi-agent-patch-request/)
- [IntentRequest](https://apis.io/schemas/signo-fi/signo-fi-intent-request/)
- [IntentResponse](https://apis.io/schemas/signo-fi/signo-fi-intent-response/)
- [ReencodeResponse](https://apis.io/schemas/signo-fi/signo-fi-reencode-response/)
- [ShieldPermissionRequest](https://apis.io/schemas/signo-fi/signo-fi-shield-permission-request/)
- [SimulateResponse](https://apis.io/schemas/signo-fi/signo-fi-simulate-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Signo Fi Context](https://apis.io/jsonld/signo-fi/signo-fi-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Signo API Rules](https://apis.io/rules/signo-fi/signo-fi-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Signo Authentication](https://apis.io/security/signo-fi/signo-fi-authentication/)
- [Signo Domain Security](https://apis.io/security/signo-fi/signo-fi-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Signo Plans Pricing](https://apis.io/plans/signo-fi/signo-fi-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://signo.fi/)
- [Documentation](https://docs.signo.fi/)
- [Getting started](https://docs.signo.fi/get-started)
- [API reference](https://docs.signo.fi/api-reference)
- [Pricing](https://signo.fi/pricing)
- [Blog](https://signo.fi/blog)
- [Terms of service](https://signo.fi/legal/terms)
- [Privacy policy](https://signo.fi/legal/privacy)
- [GitHub](https://github.com/FlipLabsAI)

## API Evangelist rating

**Kin Score 55.5** — strong · rubric 0.28.0 · scored 2026-11-24

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 71.7 |
| Contract governance | 79.1 |
| Operational transparency | 11.9 |
| Developer ergonomics | 49.3 |
| Access clarity | 48.5 |

**Agent readiness 62.8** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 17.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/signo-fi/](https://apis.io/providers/signo-fi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Signo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/signo-fi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
