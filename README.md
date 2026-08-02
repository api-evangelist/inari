# Inari

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
