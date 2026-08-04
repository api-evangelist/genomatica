# Genomatica

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

Genomatica (which markets itself as Geno) is a San Diego, California biotechnology and sustainable
materials company founded in 1998 that engineers microbes and fermentation processes to make widely
used chemical building blocks from plants instead of fossil fuels — Geno BDO (bio-based
1,4-butanediol, licensed to partners including BASF and Novamont), Brontide butylene glycol, Avela
(R)-1,3-butanediol, plant-based nylon-6 intermediates developed with lululemon and manufacturing
partners such as Hyosung and Sojitz, plus palm-oil alternatives and fragrance building blocks.

**API surface: none published.** Genomatica licenses process technology to chemical producers rather
than operating a software platform. Probes on 2026-08-04 found no public API, developer portal,
OpenAPI/AsyncAPI/GraphQL contract, SDK, MCP server, `llms.txt`, or A2A agent card on any Genomatica
host. The only OpenAPI endpoint found anywhere is `https://productportal.genomatica.com/swagger.json`,
which belongs to a Genomatica-branded storefront running the third-party Agilis Commerce platform and
returns HTTP 401 behind `WWW-Authenticate: Basic realm="Openapi Specification"` — credential-gated, so
nothing could be harvested. Every probed URL and its HTTP status is recorded in
[`well-known/genomatica-well-known.yml`](well-known/genomatica-well-known.yml).

- https://www.genomatica.com/
- https://github.com/genomatica
- https://forgeglobal.com/genomatica_stock/ (secondary-market listing this profile was harvested from)
