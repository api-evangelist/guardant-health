# Guardant Health (guardant-health)

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
