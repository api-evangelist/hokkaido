# Hokkaido University (hokkaido)

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

Hokkaido University (北海道大学) is a national research university in Sapporo, Japan, founded in 1876 as Sapporo Agricultural College and ranked #173 in the QS World University Rankings 2025. This repository is an [APIs.json](http://apisjson.org) provider profile cataloging the university's public, machine-readable developer and API footprint, which is centered on its open-access scholarly infrastructure.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/hokkaido/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hokkaido-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party
- Class: university · Public Research University

## Tags

Education, Higher Education, University, Japan, National University, Research, Open Access, Institutional Repository, Identity Federation, Shibboleth, Research Computing, Course Catalog, Persistent Identifiers

## Surfaces

Every entry carries an operator, because for a university the question is never "is there a
contract" but "who runs the thing the contract describes".

**Institution-operated**

- **Hokkaido University SAML 2.0 Identity Provider** — entityID `https://shib-idp01.iic.hokudai.ac.jp/idp/shibboleth`, scope `hokudai.ac.jp`, registered in GakuNin as PI0008JP since 2010-03-16. Live metadata: https://aidipigakunin2.oicte.hokudai.ac.jp/saml/saml2/idp/metadata.php
- **HUSCAP XML Sitemaps** — https://eprints.lib.hokudai.ac.jp/sitemap/sitemapindex.xml
- **Hokkaido University Web Sitemaps** — https://www.hokudai.ac.jp/sitemap.xml
- **Syllabus Search (学務システム)** — https://gakumu.academic.hokudai.ac.jp/Portal/Public/Syllabus/SearchMain.aspx — public, web-only, no machine-readable export
- **Interdisciplinary Large-scale Computing System (HUCC)** — https://www.hucc.hokudai.ac.jp/en/overview/ilcs/ — no public allocation or job API

**Federation**

- **GakuNin** (学術認証フェデレーション, operated by NII) — https://metadata.gakunin.nii.ac.jp/gakunin-metadata.xml — 650 entities, four of them Hokkaido's (one IdP, three SPs on hokudai.ac.jp hosts)

**Registry memberships**

- **Handle System prefix 2115** — https://hdl.handle.net/api/handles/0.NA/2115
- **JaLC DOI prefix 10.14943** — https://api.japanlinkcenter.org/dois/10.14943/bfhhs.165.l129
- **ROR** — https://ror.org/02e16g702
- **Crossref member 5618** — Department of Mathematics only, prefix 10.14492

## Artifacts

- [authentication/hokkaido-saml-idp.yml](authentication/hokkaido-saml-idp.yml)
- [conformance/hokkaido-conformance.yml](conformance/hokkaido-conformance.yml)
- [json-ld/hokkaido-context.jsonld](json-ld/hokkaido-context.jsonld)
- [security/hokkaido-domain-security.yml](security/hokkaido-domain-security.yml)
- [plans/hokkaido-plans-pricing.yml](plans/hokkaido-plans-pricing.yml)
- [rate-limits/hokkaido-rate-limits.yml](rate-limits/hokkaido-rate-limits.yml)
- [finops/hokkaido-finops.yml](finops/hokkaido-finops.yml)
- [review.yml](review.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Notes

- **No public API.** Hokkaido University publishes no developer portal, no API gateway and no
  documented public REST API. `api.`, `data.`, `opendata.`, `developer.` and `status.hokudai.ac.jp`
  do not resolve; `/llms.txt`, `/.well-known/apis.json`, `/.well-known/security.txt` and
  `/.well-known/openid-configuration` all return 404; and the WordPress REST API on the English
  global site is explicitly disabled (`{"code":"rest_disabled"}`).
- **The strongest surface is identity, not data.** The university's own Shibboleth/SAML identity
  provider, registered in the Japanese national academic federation, is institution-operated,
  machine-readable and first-party — its metadata is served from a hokudai.ac.jp host under a
  certificate issued to `O=Hokkaido University`. The June 2026 profile missed it entirely.
- **OAI-PMH remains the open regression.** IRDB entry 524 confirms HUSCAP is still harvested by
  OAI-PMH, so a base URL exists, but the legacy DSpace endpoint has returned 404 since the
  December 2025 platform migration and eighteen candidate paths on the replacement platform were
  probed on 2026-09-01 without success. Publishing the endpoint is the single highest-value fix
  available to the university.
- **DOIs are JaLC, not DataCite or Crossref.** The library states this explicitly. `api.datacite.org`
  returns zero clients for Hokkaido; the only Crossref membership is the Department of Mathematics.
- No vendor contract is attributed to this institution, and none needed removing — this repository
  has never carried an OpenAPI definition.
- The `github.com/hokkaido` and `github.com/hokudai` GitHub organizations are not the university's
  and are intentionally not cataloged here.

## Maintainers

- Kin Lane — kin@apievangelist.com
