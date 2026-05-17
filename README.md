<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/Upstream-Intelligence/.github/main/.github/assets/upstream-wordmark-dark.svg">
  <img src="https://raw.githubusercontent.com/Upstream-Intelligence/.github/main/.github/assets/upstream-wordmark-light.svg"
       alt="Upstream" width="220" />
</picture>

# awesome-payer-risk

**Curated resources for healthcare payer risk, denial prevention, and revenue cycle management.**

[![License](https://img.shields.io/badge/license-CC0_1.0-0454F1)](LICENSE)
[![upstream.cx](https://img.shields.io/badge/upstream-cx-0454F1)](https://upstream.cx)
[![Newsletter](https://img.shields.io/badge/newsletter-subscribe-0454F1)](https://upstream.cx/newsletter)
[![Contribute](https://img.shields.io/badge/PRs-welcome-0454F1)](./CONTRIBUTING.md)

</div>

---

> Curated resources for healthcare payer risk, denial prevention, and revenue cycle management.

Healthcare revenue cycle management is fragmented. Payer policies live in PDFs buried on MACs websites. Appeal templates exist in consulting decks behind paywalls. Good tools are hard to find. This list pulls the best public resources into one place.

Contributions welcome. Open a PR with your addition.

---

## Contents

- [Payer Policy Resources](#payer-policy-resources)
- [Denial Appeal Resources](#denial-appeal-resources)
- [RCM Tools](#rcm-tools)
- [Coding and Billing References](#coding-and-billing-references)
- [Community and Professional Associations](#community-and-professional-associations)
- [Upstream Intelligence Resources](#upstream-intelligence-resources)

---

## Payer Policy Resources

- [CMS LCD Database](https://www.cms.gov/medicare-coverage-database/search/search.aspx): Search Local Coverage Determinations by contractor, CPT code, or diagnosis. The ground truth for Medicare coverage rules by jurisdiction.
- [CMS NCD Database](https://www.cms.gov/medicare-coverage-database/search/search.aspx?searchType=NCD): National Coverage Determinations. Applies uniformly across all Medicare Administrative Contractors.
- [CMS NCCI Edits](https://www.cms.gov/medicare/coding-billing/national-correct-coding-initiative-ncci-edits): Procedure-to-Procedure and Medically Unlikely Edits. Updated quarterly. Check before submitting paired CPT codes.
- [CMS Physician Fee Schedule Lookup](https://www.cms.gov/medicare/payment/fee-schedules/physician): Current RVUs, facility and non-facility rates, geographic practice cost indices.
- [CMS CARC and RARC Codes](https://www.cms.gov/medicare/payment/claims-and-appeals/claim-adjustment-reason-codes): Claim Adjustment Reason Codes and Remittance Advice Remark Codes. Reference for decoding 835 denial responses.
- [MAC Contractor Websites](https://www.cms.gov/medicare/medicare-contracting/medicare-administrative-contractors/who-are-macs): List of all Medicare Administrative Contractors by jurisdiction. Each MAC publishes its own LCDs and billing articles.
- [CMS Federal Register API](https://www.federalregister.gov/developers/documentation/api/v1): Machine-readable access to Medicare proposed and final rules. Useful for tracking regulatory changes that affect reimbursement.
- [NPPES NPI Registry](https://npiregistry.cms.hhs.gov/): Provider validation lookup. Verify provider taxonomy codes and practice addresses before claim submission.
- [CMS SynPUF (Synthetic Public Use Files)](https://www.cms.gov/data-research/statistics-trends-and-reports/medicare-claims-synthetic-public-use-files): Synthetic Medicare claims data for building and testing denial prediction models without real patient data.
- [Noridian LCD Search](https://www.cms.gov/medicare-coverage-database/search/search.aspx?Cntrctr=1&SearchType=Advanced&CntrctrSelected=373%7C0&s=30&DocType=LCD): Noridian (Jurisdiction E and F) LCDs. One of the largest MAC jurisdictions.
- [Palmetto GBA LCDs](https://www.palmettogba.com/palmetto/providers.nsf/content/HH_OHC_LCDs): Palmetto GBA (Jurisdiction J) LCDs covering Southeast US.
- [Aetna Clinical Policy Bulletins](https://www.aetna.com/health-care-professionals/clinical-policy-bulletins.html): Aetna's publicly searchable medical, dental, and pharmacy coverage policies. No account required to browse.
- [Anthem Provider Medical Policies](https://www.anthem.com/provider/policies/clinical-guidelines/): Elevance / Anthem medical policies and clinical UM guidelines by plan. Publicly accessible; covers commercial and Medicare Advantage lines.
- [BCBS Federal Employee Program Medical Policies](https://fepblue.org/benefit-plans/medical-policies-and-utilization-management-guidelines): FEP Blue's publicly posted medical policies and UM guidelines for the largest single federal health plan.
- [UnitedHealthcare Commercial Medical Policies](https://www.uhcprovider.com/en/policies-protocols/commercial-policies.html): UHC's publicly browsable commercial medical and drug policies, reimbursement policies, and clinical guidelines by affiliate plan.
- [CMS Internet-Only Manuals (IOMs)](https://www.cms.gov/regulations-and-guidance/guidance/manuals/internet-only-manuals-ioms): CMS operational manuals including the Claims Processing Manual (Pub. 100-04). Definitive rules for how MACs adjudicate claims.

---

## Denial Appeal Resources

- [AMA CPT Code Lookup](https://www.ama-assn.org/practice-management/cpt/cpt-overview-and-code-approval): Official CPT code descriptions from the American Medical Association. Use for appeal letters requiring precise procedure language.
- [MGMA Denial Management Resources](https://www.mgma.com/data/benchmarking-data/denial-management): Medical Group Management Association denial benchmarks and appeal guides. Membership required for full access.
- [AHA Coding Clinic](https://www.ahacentraloffice.org/): American Hospital Association guidance on ICD-10 coding. Reference for clinical documentation improvement appeals.
- [HCPCS Code Lookup (CMS)](https://www.cms.gov/medicare/coding-billing/healthcare-common-procedure-system): Healthcare Common Procedure Coding System codes. Covers DME, supplies, and procedures not in CPT.
- [CMS Timely Filing Requirements](https://www.cms.gov/medicare/medicare-contracting/contractorlearningresources/downloads/ja0801.pdf): Medicare timely filing rules by claim type. Know the window before you draft the appeal.
- [OIG Compliance Guidance](https://oig.hhs.gov/compliance/compliance-guidance/): Office of Inspector General compliance program guidance. Useful for building documentation practices that survive audits.
- [CMS Medicare Appeals Process](https://www.cms.gov/medicare/appeals-grievances/medappeals): Official five-level Medicare appeals process. Know the deadlines and the escalation path.
- [Noridian Self-Service Denial Appeals](https://noridianmedicare.com/web/jadme/topics/denials-and-appeals): Noridian-specific denial appeal filing instructions. Faster than calling.
- [C2C Innovative Solutions  -  Medicare QIC](https://www.c2cinc.com/): CMS-contracted Qualified Independent Contractor handling Part A/B reconsideration appeals (Level 2). Submit appeals and track decisions here.
- [Medicare.gov Appeals Guide](https://www.medicare.gov/appeals/): CMS consumer-facing walkthrough of all five Medicare appeal levels with deadlines, forms, and escalation instructions.
- [Patient Advocate Foundation Resources](https://www.patientadvocate.org/explore-our-resources/): Free appeal letter templates, case management intake, and denial navigation guides for patients and billing staff.

---

## RCM Tools

### Free CMS APIs and Data

- [CMS Data at the Point of Care (DPC) API](https://dpc.cms.gov/): CMS bulk FHIR API giving providers access to their patients' historical Medicare claims data. Free; supports proactive denial avoidance workflows.
- [Synthea Synthetic Patient Generator](https://github.com/synthetichealth/synthea): Open-source simulator producing realistic synthetic patient records in FHIR, HL7, and CSV. Build and test denial-prediction models without PHI.

### Open Source

- [upstream-community](https://github.com/Upstream-Intelligence/upstream-community): Reference ML implementations for denial prediction, payer clustering, and drift detection using public CMS data. MIT licensed.
- [simple-hl7](https://github.com/fernandojsg/simple-hl7): HL7 v2 message parsing in Node.js. Useful for building claim ingestion pipelines.
- [hl7apy](https://github.com/crs4/hl7apy): Python HL7 v2 parser. Handles ADT, ORM, and ORU message types.
- [python-x12](https://github.com/LinuxForHealth/x12): EDI X12 transaction parsing for 837 (claim) and 835 (remittance) files. Foundational for any 835-based denial analysis.
- [health-patterns](https://github.com/LinuxForHealth/health-patterns): IBM's open source healthcare integration patterns including FHIR ingestion pipelines.
- [HAPI FHIR](https://github.com/hapifhir/hapi-fhir): Java-based FHIR server implementation. Used widely for EHR integration.

### Commercial (Notable)

- [Adonis](https://www.adonis.health/): Revenue cycle workflow orchestration. Billing team task management and denial queuing.
- [Waystar](https://www.waystar.com/): Clearinghouse plus RCM analytics. Claims submission, eligibility, and remittance management.
- [Availity](https://www.availity.com/): Clearinghouse and eligibility verification platform. Wide payer network coverage.
- [Omega Healthcare](https://www.omegahealthcare.com/): Offshore RCM services with technology layer. Used by mid-market practices.
- [Collectly](https://www.collectly.com/): Patient payment optimization and propensity scoring.
- [Trizetto Provider Solutions](https://www.trizetto.com/): Eligibility and claim status workflows.

---

## Coding and Billing References

- [AMA CPT Modifier Guide](https://www.ama-assn.org/system/files/2023-modifier-guide.pdf): Complete CPT modifier reference. Essential for pre-submission modifier auditing.
- [CMS ICD-10-CM Tabular List](https://www.cms.gov/medicare/coding-billing/icd-10-codes): Official ICD-10-CM code set. Updated annually in October.
- [CMS ICD-10-PCS](https://www.cms.gov/medicare/coding-billing/icd-10-codes/2024-icd-10-pcs): Procedure coding for inpatient hospital claims.
- [NCCI Policy Manual](https://www.cms.gov/medicare/coding-billing/national-correct-coding-initiative-ncci-edits/downloads): Full explanatory manual for the NCCI edits. Explains why edit pairs exist, not just what they are.
- [CMS MUE Adjudication Indicator Table](https://www.cms.gov/medicare/coding-billing/national-correct-coding-initiative-ncci-edits/mue): Medically Unlikely Edit values per CPT code. Billing above these flags automatic review.
- [ABA Coding and Billing Resources (BACB)](https://www.bacb.com/practitioners/billing-and-insurance/): Behavior Analyst Certification Board guidance on CPT codes 97151-97158 and H-codes for ABA services.
- [APTA Coding Resources](https://www.apta.org/your-practice/payment/coding): American Physical Therapy Association coding guides. PT/OT specific CPT code guidance.
- [ADA CDT Code Lookup](https://www.ada.org/publications/cdt): Current Dental Terminology. Official code set for dental claims.

---

## Community and Professional Associations

- [HBMA (Healthcare Business Management Association)](https://www.hbma.org/): Trade association for medical billing companies. Training, certification, and best practice guides.
- [MGMA (Medical Group Management Association)](https://www.mgma.com/): Practice management association. Annual cost and revenue benchmarking surveys worth referencing in appeals.
- [AMBA (American Medical Billing Association)](https://www.ambanet.net/): Certification and training for medical billers. CPCO credential for compliance officers.
- [AHIMA (American Health Information Management Association)](https://www.ahima.org/): Health information and coding professionals. ICD-10 coding guidance and audit resources.
- [HIMSS](https://www.himss.org/): Health IT industry association. Revenue cycle technology research and reports.
- [NAHAM (National Association of Healthcare Access Management)](https://www.naham.org/): Patient access and registration best practices.
- [RevCycle Intelligence](https://revcycleintelligence.com/): Industry news site covering payer policy changes, CMS rule updates, and denial trends. Free.
- [Becker's RCM and Billing](https://www.beckershospitalreview.com/finance.html): Hospital review coverage of revenue cycle topics. Free newsletter available.
- [RISE Network](https://www.risenetwork.com/): Risk adjustment and quality improvement network for Medicare Advantage and ACA plans.

---

## Upstream Intelligence Resources

- [Upstream Care Intelligence Platform](https://upstream.cx): Detects payer behavior shifts before they hit cash flow. Pre-submission claim risk scoring, denial drift detection, payer behavioral fingerprinting. Eight specialties.
- [upstream-mcp](https://github.com/Upstream-Intelligence/upstream-mcp): Model Context Protocol server. Brings Upstream payer intelligence directly into Claude. Free tier: 500 calls per month.
- [upstream-skills](https://github.com/Upstream-Intelligence/upstream-skills): Claude Code skill pack for billing teams. Denial decoder, appeal drafter, claim scanner, payer intel, NCCI checker. MIT licensed.
- [upstream-community](https://github.com/Upstream-Intelligence/upstream-community): Reference ML implementations for denial prediction, payer clustering, and drift detection. Public CMS data only. MIT licensed.
- [Upstream Blog](https://blog.upstream.cx): Monthly deep dives on payer behavior, regulatory changes, and operator playbooks.
- [Upstream Newsletter](https://upstream.cx/newsletter): Monthly network signals digest. What the operator network is seeing right now in payer behavior.
- [Pioneer Program](https://upstream.cx/pioneer): $49/mo locked for life. Founding 5 seats.
- [Free Claim Audit](https://upstream.cx/audit): Upload one claim file, get denial pattern analysis back. No credit card.
- [API Documentation](https://upstream.cx/developers): REST API reference. OpenAPI spec, webhook contracts, rate limits.

---

## Contributing

Open a PR. Add links in the correct section. Format: `- [Name](url): One sentence description. No fluff.`

Rules:
- Public resources only. No paywalled content without a note.
- No affiliate links.
- Descriptions state what the resource does, not how great it is.
- Keep each section alphabetical where possible.

---

## Related

Part of the [Upstream Intelligence ecosystem](https://github.com/Upstream-Intelligence).

- [upstream-mcp](https://github.com/Upstream-Intelligence/upstream-mcp) — MCP server for Claude
- [upstream-skills](https://github.com/Upstream-Intelligence/upstream-skills) — Claude Code skills for billing teams
- [upstream-community](https://github.com/Upstream-Intelligence/upstream-community) — open ML methodology
- **awesome-payer-risk** — you are here

Product: [upstream.cx](https://upstream.cx) · [Newsletter](https://upstream.cx/newsletter) · [Pricing](https://upstream.cx/pricing)

---

Maintained by [Upstream Intelligence](https://upstream.cx): the Care Intelligence Platform for healthcare practices. [upstream.cx/newsletter](https://upstream.cx/newsletter) for monthly payer behavior updates.
