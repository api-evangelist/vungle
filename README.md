# Vungle

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

Vungle is a mobile app monetization and user-acquisition platform, now operated as part of Liftoff (the merged Liftoff + Vungle mobile growth company). Vungle's in-app advertising SDKs help mobile publishers monetize with performance-focused ad formats (video, interactive, and playable ads), while Liftoff's advertiser APIs let growth teams launch and manage user-acquisition campaigns, assemble creatives, ingest audiences, and pull automated performance reporting. The programmatic surface is documented at docs.liftoff.io and includes a Reporting API, a closed-beta Campaign Management API, an Audiences Integration API, a GDPR Opt-Out API, and a server-to-server (S2S) postback integration. All advertiser APIs authenticate with an HTTP Basic API key and secret issued by a Liftoff Account Manager.

**Areas:** Company · Advertising · Mobile · Monetization · User Acquisition · AdTech · Analytics · Reporting

## Vungle on APIs.io

Everything profiled for Vungle is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vungle/](https://apis.io/providers/vungle/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Liftoff Reporting API](https://apis.io/apis/vungle/liftoff-reporting-api/) — Automated access to Vungle/Liftoff campaign performance reports — impressions, clicks, installs, and in-app events — with configurable groupings, metrics,…
- [Liftoff Campaign Management API](https://apis.io/apis/vungle/liftoff-campaign-management-api/) — Closed-beta API to programmatically launch UA expansion campaigns, manage spend and targeting, upload assets, and assemble creatives. Standard REST/JSON at…
- [Liftoff Audiences Integration API](https://apis.io/apis/vungle/liftoff-audiences-integration-api/) — Audience ingestion/validation API for partners working on behalf of multiple clients, at https://analytics.liftoff.io/audiences/v1.
- [Liftoff GDPR Opt-Out API](https://apis.io/apis/vungle/liftoff-gdpr-opt-out-api/) — Submit GDPR-compliant opt-out requests to remove user data by device ID, at https://analytics.liftoff.io/opt_out/v3.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Vungle S2S Webhooks](https://apis.io/asyncapis/vungle/vungle-s2s-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [vungle](https://apis.io/servers/vungle/vungle/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Vungle Authentication](https://apis.io/security/vungle/vungle-authentication/)
- [Vungle Domain Security](https://apis.io/security/vungle/vungle-domain-security/)

#### Rate limits (1)

Published request limits.

- [Vungle Rate Limits](https://apis.io/rate-limits/vungle/vungle-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://vungle.com)
- [Documentation](https://docs.liftoff.io/)
- [Getting started](https://docs.liftoff.io/advertiser)
- [Blog](https://liftoff.io/blog)
- [Terms of service](https://liftoff.io/terms-of-service)
- [Privacy policy](https://liftoff.io/privacy-policy)
- [GitHub](https://github.com/Vungle)

## API Evangelist rating

**Kin Score 39.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 39.0 |
| Contract governance | 4.5 |
| Operational transparency | 31.6 |
| Developer ergonomics | 59.5 |
| Access clarity | 21.1 |

**Agent readiness 25.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vungle/](https://apis.io/providers/vungle/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vungle: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vungle/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
