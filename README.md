# Guardant Health (guardant-health)

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

Guardant Health is a precision oncology company whose blood- and tissue-based liquid biopsy tests (Guardant360, Guardant Reveal, Guardant Shield, GuardantINFINITY) detect cancer and guide treatment. Its integration surface is partner- and EMR-based: electronic test ordering and results delivery through Epic Aura and Flatiron OncoEMR, patient portals (MyGuardant, My Data), and biopharma data platforms (GuardantINFORM, GuardantConnect, Guardant Galaxy). No public self-serve developer API is documented.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/guardant-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/guardant-health/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Precision Oncology
- Liquid Biopsy
- Genomics
- EMR Integration

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Guardant Health EMR Ordering Integration

EMR-integrated electronic ordering of Guardant assays (Guardant360 CDx, Guardant360 Response, Guardant Reveal, Guardant Shield) directly from the patient chart via Epic Aura and Flatiron OncoEMR. The interface is a partner integration, not a public self-serve API; no public base URL or OpenAPI is published.

- **Human URL:** [https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/](https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/)

#### Tags

- EMR Integration
- Test Ordering
- Epic

#### Properties

- [Documentation](https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/)
- [OpenAPI](openapi/guardant-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/guardant-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/guardant-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Guardant Health Results Delivery Integration

Automated, EMR-based delivery of molecular profiling results back into the patient chart, with support for reflex/cascade testing workflows. Delivered through EMR interfaces (HL7/FHIR-style) provisioned per institutional partner; no public API is documented.

- **Human URL:** [https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/](https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/)

#### Tags

- EMR Integration
- Results
- HL7

#### Properties

- [Documentation](https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/)
- [OpenAPI](openapi/guardant-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Guardant Nexus

Guardant Nexus partnership program for institutional and provider partners, coordinating ordering, integration and account workflows. Access is partner-gated; no public API surface is documented.

- **Human URL:** [https://guardanthealth.com/precision-oncology/for-institutional-partners/](https://guardanthealth.com/precision-oncology/for-institutional-partners/)

#### Tags

- Partner Platform
- Provider

#### Properties

- [Documentation](https://guardanthealth.com/precision-oncology/for-institutional-partners/)

### GuardantINFORM

In-silico real-world clinical-genomic data platform combining de-identified longitudinal clinical information with genomic data from Guardant360, used by biopharma for drug development analytics. Delivered as a managed platform, not a public API.

- **Human URL:** [https://guardanthealth.com/precision-oncology/biopharma-solutions/real-world-evidence/](https://guardanthealth.com/precision-oncology/biopharma-solutions/real-world-evidence/)

#### Tags

- Biopharma
- Real World Data
- Clinical Genomic

#### Properties

- [Documentation](https://guardanthealth.com/precision-oncology/biopharma-solutions/real-world-evidence/)

### GuardantConnect

Integrated software solution that connects patients tested with Guardant assays who have actionable alterations to potentially relevant clinical studies, for clinical and biopharmaceutical customers. Partner-gated; no public API.

- **Human URL:** [https://guardanthealth.com/precision-oncology/biopharma-solutions/](https://guardanthealth.com/precision-oncology/biopharma-solutions/)

#### Tags

- Biopharma
- Clinical Trials
- Trial Matching

#### Properties

- [Documentation](https://guardanthealth.com/precision-oncology/biopharma-solutions/)

### Guardant Galaxy

Suite of advanced AI analytics and digital pathology technologies that enhance Guardant test performance and power biomarker and drug discovery. Embedded in Guardant's products; no public developer API is documented.

- **Human URL:** [https://guardanthealth.com/](https://guardanthealth.com/)

#### Tags

- AI Analytics
- Biomarker Discovery
- Digital Pathology

#### Properties

- [Website](https://guardanthealth.com/)

### MyGuardant Patient Portal

Authenticated patient-facing portals (MyGuardant and My Data) where patients access test status, results and personal health data. Web application behind login; no documented public patient API.

- **Human URL:** [https://portal.guardanthealth.com/myguardant](https://portal.guardanthealth.com/myguardant)

#### Tags

- Patient Portal
- Results

#### Properties

- [Website](https://portal.guardanthealth.com/myguardant)
- [Website](https://mydata.guardanthealth.com/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/guardanthealth)
- [Website](https://www.guardanthealth.com)
- [Documentation](https://guardanthealth.com/precision-oncology/for-institutional-partners/emr-integration-services/)
- [Plans](plans/guardant-health-plans-pricing.yml)
- [Rate Limits](rate-limits/guardant-health-rate-limits.yml)
- [Fin Ops](finops/guardant-health-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
