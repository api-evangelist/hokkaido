# Hokkaido University (hokkaido)

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
