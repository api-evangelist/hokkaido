# Hokkaido University

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

Hokkaido University (北海道大学) is a national research university in Sapporo, Japan, founded in 1876 as Sapporo Agricultural College, a member of Japan's Designated National University group and ranked #173 in the QS World University Rankings 2025. It operates 12 undergraduate schools, 21 graduate schools and numerous research institutes. Its public programmable footprint is small and honest: the university publishes no developer portal, no API gateway and no documented public REST API — api., data., opendata., developer. and status.hokudai.ac.jp all fail to resolve, and the WordPress REST API on its English site is explicitly disabled. What it does operate, and what this profile is built on, is scholarly identity infrastructure. It runs its own SAML 2.0 / Shibboleth identity provider registered in GakuNin, the Japanese national academic access federation; it holds Handle System prefix 2115 and JaLC DOI prefix 10.14943 for the HUSCAP institutional repository; and it publishes crawlable XML sitemaps for both HUSCAP and its main web estate. HUSCAP's OAI-PMH endpoint is the one real regression: IRDB still harvests the repository by OAI-PMH, but no base URL has been publicly documented since the December 2025 platform migration and eighteen candidate paths were probed unsuccessfully.

**Areas:** Education · Higher Education · University · Japan · National University · Research · Open Access · Institutional Repository · Identity Federation · Shibboleth · Research Computing · Course Catalog

## Hokkaido University on APIs.io

Everything profiled for Hokkaido University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hokkaido/](https://apis.io/providers/hokkaido/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Hokkaido University SAML 2.0 Identity Provider](https://apis.io/apis/hokkaido/saml-idp/) — Hokkaido University's own Shibboleth/SAML 2.0 identity provider, entityID https://shib-idp01.iic.hokudai.ac.jp/idp/shibboleth, scope hokudai.ac.jp,…
- [GakuNin Academic Access Management Federation](https://apis.io/apis/hokkaido/gakunin/) — Membership of GakuNin (学術認証フェデレーション), the Japanese national academic identity federation operated by the National Institute of Informatics. The aggregate at…
- [HUSCAP XML Sitemaps](https://apis.io/apis/hokkaido/huscap-sitemap/) — Publicly crawlable XML sitemap index for HUSCAP, the Hokkaido University Collection of Scholarly and Academic Papers, providing a machine-readable list of…
- [Hokkaido University Web Sitemaps](https://apis.io/apis/hokkaido/web-sitemaps/) — XML sitemaps for the university's two public web estates — the 2.4 MB sitemap.xml on the Japanese site and the WordPress core sitemap index on the English…
- [Handle System Prefix 2115](https://apis.io/apis/hokkaido/handle-2115/) — Hokkaido University Library holds Handle System naming authority prefix 2115, which mints the persistent identifiers on every HUSCAP record…
- [JaLC DOI Prefix 10.14943](https://apis.io/apis/hokkaido/jalc-doi-10-14943/) — Hokkaido University registers DOIs through JaLC, the Japan Link Center, under prefix 10.14943. Confirmed from the DOI Registration Agency resolver…
- [ROR Registry Record](https://apis.io/apis/hokkaido/ror/) — Research Organization Registry record https://ror.org/02e16g702, types education and funder, established 1876, located Sapporo, Japan. Carries the…
- [Crossref Member 5618 — Department of Mathematics](https://apis.io/apis/hokkaido/crossref-5618/) — Crossref membership held at department level, not institution level. Member 5618, "Department of Mathematics, Hokkaido University", prefix 10.14492, 1,820…
- [Hokkaido University Syllabus Search (学務システム)](https://apis.io/apis/hokkaido/syllabus/) — Public course catalog and syllabus search, institution-operated on the gakumu.academic.hokudai.ac.jp host. Live and open to the public, but web-only — an…
- [Interdisciplinary Large-scale Computing System (HUCC)](https://apis.io/apis/hokkaido/hucc/) — The Information Initiative Center's supercomputer and research cloud service — Grand Chariot 2 and the research cloud system — documented in Japanese and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hokkaido Context](https://apis.io/jsonld/hokkaido/hokkaido-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Hokkaido Domain Security](https://apis.io/security/hokkaido/hokkaido-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hokkaido Plans Pricing](https://apis.io/plans/hokkaido/hokkaido-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hokkaido Rate Limits](https://apis.io/rate-limits/hokkaido/hokkaido-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hokkaido Finops](https://apis.io/finops/hokkaido/hokkaido-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hokudai.ac.jp/)
- [Support](https://www.lib.hokudai.ac.jp/support/huscap/)
- [Privacy policy](https://www.global.hokudai.ac.jp/privacy-policy/)

## API Evangelist rating

**Kin Score 20.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 17.3 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 15.8 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hokkaido/](https://apis.io/providers/hokkaido/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hokkaido University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hokkaido/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
