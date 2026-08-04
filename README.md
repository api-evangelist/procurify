# Procurify (procurify)

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

Procurify is an intelligent spend management and procure-to-pay platform that provides organizations with unprecedented visibility and control over business spend. The platform offers a RESTful API enabling developers to integrate procurement workflows — including purchase requests, approvals, purchase orders, vendor management, and budget tracking — into their own systems. Authentication is handled via OAuth 2.0 client credentials flow, with tokens scoped to the requesting domain and user. The API supports core spend management resources such as requisitions, purchase orders, accounts payable, receipts, account codes, vendors, and catalog items, all consuming and returning JSON. Procurify does not support webhooks; all integrations are pull-based through the REST endpoints documented at developer.procurify.com.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/procurify/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=procurify-api-evangelist&utm_content=repo

## Tags

- Spend Management
- Procurement
- Purchase Orders
- Accounts Payable
- Vendor Management
- Budget Tracking
- Procure-to-Pay
- ERP Integration

## APIs

| Name | Description | URL |
|------|-------------|-----|
| Procurify API | RESTful API for managing spend management workflows including purchase requests, approvals, purchase orders, vendor management, accounts payable, receipts, and budget tracking. | https://developer.procurify.com/ |

## Plans, Rate Limits, and FinOps

| Resource | Description | Link |
|----------|-------------|------|
| Plans and Pricing | Flexible quote-based pricing; API access bundled with platform subscription | [plans/procurify-plans-pricing.yml](plans/procurify-plans-pricing.yml) |
| Rate Limits | Token expiry 24h; no publicly disclosed numerical rate limits; contact support for large integrations | [rate-limits/procurify-rate-limits.yml](rate-limits/procurify-rate-limits.yml) |
| FinOps | FOCUS-aligned spend tracking for procurement OpEx, vendor spend, AP, and budget management | [finops/procurify-finops.yml](finops/procurify-finops.yml) |

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://www.procurify.com/ |
| Documentation | https://developer.procurify.com/ |
| GitHub Org | https://github.com/procurify |
| LinkedIn | https://www.linkedin.com/company/procurify |
| Blog | https://www.procurify.com/blog/ |
| Pricing | https://www.procurify.com/pricing/ |
| Status Page | https://status.procurify.com/ |
| X | https://x.com/procurify |
| Knowledge Base | https://success.procurify.com/en/articles/9002277-does-procurify-offer-api |
| Integrations | https://www.procurify.com/procure-to-pay/integrations/api/ |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
