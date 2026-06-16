# WellSky (wellsky)

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
