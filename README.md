# WellSky (wellsky)

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

WellSky provides care coordination and home health software with REST APIs for managing patient referrals, authorizations, visit scheduling, clinical documentation, and billing workflows across home health, hospice, palliative care, personal care, and specialty pharmacy settings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wellsky/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wellsky/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Healthcare
- Home Health
- Hospice
- Care Coordination
- FHIR
- Clinical Documentation
- Billing
- EHR

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### WellSky CareTend API

Integration hub API for WellSky's CareTend home infusion and specialty pharmacy platform, providing programmatic access to patient management, billing authorizations, clinical visits, inventory, purchase orders, and document workflows.

- **Human URL:** [https://caretendapi.readme.io/](https://caretendapi.readme.io/)
- **Base URL:** `https://api.wellsky.com`

#### Tags

- Home Infusion
- Specialty Pharmacy
- Patient Management
- Billing
- Inventory

#### Properties

- [Documentation](https://caretendapi.readme.io/)
- [Authentication](https://caretendapi.readme.io/docs/getting-started)

### WellSky FHIR API

FHIR R4-compliant API built on the US Core Implementation Guide, providing read access to patient health data including demographics, conditions, medications, lab results, care plans, and clinical documents for ConnectEHR interoperability.

- **Human URL:** [https://wellsky.dynamicfhir.com/wellsky/basepractice/r4/Home/ApiDocumentation](https://wellsky.dynamicfhir.com/wellsky/basepractice/r4/Home/ApiDocumentation)
- **Base URL:** `https://wellsky.dynamicfhir.com/fhir/wellsky/basepractice/r4`

#### Tags

- FHIR
- EHR
- Interoperability
- USCDI
- Clinical Data

#### Properties

- [Documentation](https://wellsky.dynamicfhir.com/wellsky/basepractice/r4/Home/ApiDocumentation)

### WellSky Hospice and Palliative API

FHIR R4 interoperability API for EHR partners integrating with WellSky's Consolo hospice and palliative care platform, supporting patient demographics, care plans, medication requests, observations, encounters, and CEHRT data-blocking compliance requirements.

- **Human URL:** [https://mediwareinc.github.io/consolo.interop-api-docs/](https://mediwareinc.github.io/consolo.interop-api-docs/)
- **Base URL:** `https://mediwareinc.github.io/consolo.interop-api-docs/`

#### Tags

- Hospice
- Palliative Care
- FHIR
- EHR Integration
- CEHRT

#### Properties

- [Documentation](https://mediwareinc.github.io/consolo.interop-api-docs/)

### WellSky Personal Care Connect API

FHIR-compliant API for WellSky Personal Care software platform enabling data integration and interoperability for home care agencies, built on OAuth 2.0 client credentials flow for scheduling, care worker management, and visit data.

- **Human URL:** [https://apidocs.clearcareonline.com/](https://apidocs.clearcareonline.com/)
- **Base URL:** `https://apidocs.clearcareonline.com/`

#### Tags

- Personal Care
- Home Care
- Scheduling
- FHIR

#### Properties

- [Documentation](https://apidocs.clearcareonline.com/)
- [Terms of Service](https://wellsky.com/clearcare-connect-api-terms/)

## Common Properties

- [Blog](https://wellsky.com/blog/)
- [Support](https://wellsky.com/support/)
- [Plans](plans/wellsky-plans-pricing.yml)
- [Rate Limits](rate-limits/wellsky-rate-limits.yml)
- [Fin Ops](finops/wellsky-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
