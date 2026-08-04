# Inari

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

Inari Agriculture, Inc. — "The SEEDesign company" — is a Cambridge, Massachusetts agricultural
biotechnology company founded by Flagship Pioneering in 2016, with additional sites in West Lafayette,
Indiana and Ghent, Belgium. Its SEEDesign platform combines genomics, artificial intelligence and
predictive design with a multiplex gene-editing toolbox to accelerate crop improvement in soybean, corn
and wheat. Inari runs a partner-first, business-to-business model, licensing designed seed to independent
seed companies and breeders rather than selling to farmers directly.

Not to be confused with the unrelated medical-device company Inari Medical, the customer-feedback SaaS
at useinari.com, or the insurance software vendor at inari.io.

- Website: https://inari.com/
- News: https://inari.com/news/
- Secondary market listing: https://forgeglobal.com/inari_stock/

## API surface

**None.** As of 2026-08-01 Inari publishes no API, no developer portal, and no machine-readable API
contract. Contract discovery probed `inari.com`, `www.inari.com` and `api.inari.com` for OpenAPI,
Swagger, GraphQL, MCP and A2A surfaces and found nothing; every candidate API subdomain is NXDOMAIN.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/inari-llms.txt` | searched — verbatim from https://inari.com/llms.txt |
| Well-known index | `well-known/inari-well-known.yml` | probed — all paths 404 (recorded negative) |
| Domain security | `security/inari-domain-security.yml` | probed — TLS 1.3, HSTS 1y, CAA, SPF, DMARC p=reject, no DNSSEC |
