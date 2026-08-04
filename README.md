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

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, Japan

## APIs

- **HUSCAP Institutional Repository** — Open-access repository of journal articles, conference materials, dissertations, and research data with JPCOAR metadata and persistent identifiers (Handle, DOI). Docs: https://eprints.lib.hokudai.ac.jp/
- **HUSCAP XML Sitemaps** — Public, robots.txt-permitted XML sitemap index for programmatic discovery of repository records. Docs: https://eprints.lib.hokudai.ac.jp/sitemap/sitemapindex.xml

## Plans

- [plans/hokkaido-plans-pricing.yml](plans/hokkaido-plans-pricing.yml)

## Rate Limits

- [rate-limits/hokkaido-rate-limits.yml](rate-limits/hokkaido-rate-limits.yml)

## FinOps

- [finops/hokkaido-finops.yml](finops/hokkaido-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.global.hokudai.ac.jp/
- LinkedIn: https://www.linkedin.com/school/hokkaidouni/
- Plans: plans/hokkaido-plans-pricing.yml
- Rate Limits: rate-limits/hokkaido-rate-limits.yml
- FinOps: finops/hokkaido-finops.yml
- Review: review.yml

## Notes

- Verification caveats: All cataloged endpoints were probed live on 2026-06-03. The HUSCAP repository migrated to a new platform in December 2025; the legacy DSpace OAI-PMH endpoint (`/dspace-oai/request`) now returns 404 and no replacement OAI-PMH base URL was publicly documented at review time. The repository's existence and JPCOAR metadata compliance are confirmed, but a live OAI-PMH harvesting URL on the new system could not be verified.
- Hokkaido University publishes no dedicated developer portal or documented public REST API. Institutional systems (ELMS LMS, syllabus search, researcher directory) are web UIs without documented programmatic interfaces.
- The `github.com/hokkaido` GitHub organization is unrelated to the university and is intentionally not cataloged here.

## Maintainers

- Kin Lane — kin@apievangelist.com
