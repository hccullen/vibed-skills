# NHS UK Clinical Terminology, Coding & Interoperability

The coding and digital standards underpinning the SKILL.md. Doctors record clinical content using **SNOMED CT**; clinical coders assign **ICD-10** and **OPCS-4** for statistical/secondary uses after discharge.

---

## 1. SNOMED CT

### What it is and who owns it

SNOMED CT (Systematized Nomenclature of Medicine Clinical Terms) is "the most comprehensive, multilingual clinical healthcare terminology in the world" — over 360,000 concepts, released monthly.

- **Owner:** SNOMED International (not-for-profit, established 2007 as the International Health Terminology Standards Development Organisation, IHTSDO; registered in England and Wales)
- **UK Member / National Release Centre:** NHS England (on behalf of the UK countries). The UK is a **founder member**.
- **URL:** https://www.snomed.org/what-is-snomed-ct

### Structure: concepts, descriptions, relationships, reference sets

| Component | What it is |
|-----------|-----------|
| **Concept** | A unique clinical meaning, referenced by a unique numeric SNOMED CT identifier |
| **Description** | Human-readable terms associated with a concept — fully specified name (FSN) and synonyms |
| **Relationship** | An association between two concepts (e.g. "is-a"), defined by a relationship type |
| **Reference Set (Refset)** | A mechanism for grouping concepts/descriptions into sets — language refsets, simple refsets, mapping refsets, etc. |

### Top-level hierarchies

| Hierarchy | Examples |
|-----------|---------|
| Clinical finding / disorder | diseases, symptoms, clinical findings |
| Procedure | actions performed on patients |
| Situation with explicit context | "history of", "family history of" |
| Body structure | anatomical structures |
| Pharmaceutical / biologic product | medicines and products |
| Observable entity | things that can be observed/measured |
| Event | administrative and clinical events |
| Specimen | specimens for testing |
| Substance | chemical substances |
| Record artifact | documents and records |

### Use in the NHS — replacement of Read codes

SNOMED CT replaced Read codes as the mandated clinical terminology:
- **Primary care:** SNOMED CT mandated by **1 April 2018** (replaced Read v2 / CTV3)
- **Secondary care, mental health, community, dentistry:** SNOMED CT mandated by **1 April 2020**

The **UK Edition** contains ~88,000 UK clinical concepts and ~380,000 UK drugs, distributed via the **TRUD** (Terminology Reference data Update Distribution) service.

**Key UK reference sets:** GP/GPSoC refsets (subsets for GP systems), Order Entry refset (for CPOE), and cross-maps to ICD-10 and OPCS-4.

---

## 2. Read Codes (Legacy)

Read codes (Read v2 / CTV3) were the legacy UK primary care terminology, created by Dr James Read in the 1980s. CTV3 was merged with SNOMED RT to create SNOMED CT in 2001.

| Version | Status |
|---------|--------|
| Read v2 (5-byte) | Withdrawn 1 April 2020 (final release April 2016) |
| CTV3 (Read v3) | Withdrawn 1 April 2020 (final release April 2018) |
| Read DAAD | Withdrawn 1 April 2016 (replaced by dm+d) |

Read codes may still appear in **historical GP records** migrated into SNOMED-based systems.

---

## 3. ICD-10 / ICD-11

### ICD-10 — secondary care hospital coding

ICD-10 (International Statistical Classification of Diseases, 10th Revision) is used for **statistical and secondary uses coding** in NHS hospitals, primarily through **Hospital Episode Statistics (HES)**. Codes are assigned by **clinical coders** (not doctors) from clinical documentation after discharge.

- The UK uses an **NHS-modified version of ICD-10** with national coding standards, maintained by the Clinical Classifications Service (now within NHS England)
- WHO ICD-10 browser: https://icd.who.int/browse10

### ICD-11

ICD-11 was adopted by the 72nd World Health Assembly in May 2019 and came into effect on 1 January 2022. WHO stopped maintaining ICD-10 in 2018. The **UK has not yet transitioned** to ICD-11 for statutory hospital coding (as of 2026). ICD-11 browser: https://icd.who.int/browse11

### SNOMED CT vs ICD-10

| | SNOMED CT | ICD-10 |
|---|-----------|--------|
| **Type** | Clinical terminology | Statistical classification |
| **Purpose** | Recording clinical detail in the EHR | Aggregating data for statistics, reimbursement, epidemiology |
| **Who uses it** | Clinicians (during care) | Clinical coders (after care, from documentation) |
| **Hierarchy** | Polyhierarchical | Monohierarchical |
| **Granularity** | 360,000+ concepts | ~14,000 codes |

> "SNOMED CT enables information input into an EHR system during the course of patient care, while ICD facilitates information retrieval, or output, for secondary data purposes." — WHO

---

## 4. OPCS-4

**OPCS-4** (OPCS Classification of Interventions and Procedures version 4) is the procedural classification used by clinical coders in NHS hospitals, alongside ICD-10 (which codes diagnoses). Both are assigned by clinical coders after discharge — not by doctors at the point of care.

- **Maintained by:** NHS England (formerly NHS Digital, Clinical Classifications Service)
- **Current version:** OPCS-4.10 (from 1 April 2023) — https://classbrowser.nhs.uk/#/book/OPCS-4.10
- **Code structure:** first character is a letter (chapter), characters 2–4 are numbers, with a full stop separating 3rd and 4th characters (e.g. `A01.1`)
- **Long-term plan:** replace with SNOMED CT for procedure coding

---

## 5. dm+d (Dictionary of Medicines and Devices)

The **dm+d** is the NHS dictionary of medicines and devices for prescribing and reimbursement. It is **SNOMED CT-based** and maintained by the NHSBSA in collaboration with NHS England. It replaced the Read DAAD.

dm+d concept types:
- **VTM** (Virtual Therapeutic Molecule) — generic molecule/active ingredient
- **VMP** (Virtual Medicinal Product) — a specific formulation/dose of a VTM
- **VMPP** (Virtual Medicinal Product Pack) — a specific pack size of a VMP
- **AMP** (Actual Medicinal Product) — a branded product from a specific manufacturer
- **AMPP** (Actual Medicinal Product Pack) — a specific pack of an AMP

Distributed via TRUD. Over 156 million electronic prescription messages transact monthly using SNOMED CT / dm+d.

---

## 6. NHS Interoperability & Record Standards

### PRSB (Professional Record Standards Body)

**URL:** https://theprsb.org/standards/

The PRSB defines information record standards — what to record and share. Three types:
1. **Information record standards** — define information needed in a person's record (allergies, vaccinations, medications)
2. **Data and terminology standards** — SNOMED CT for clinical terms; data standards for formatting
3. **Technical standards and specifications** — how information is held/moved between systems, using FHIR

Each standard specifies: sections, elements, record entries, conformance (**MRO**: Mandatory/SHOULD/Optional), value sets (SNOMED CT codes), implementation guidance, business rules, clinical safety case report (DCB0129), and hazard log.

**Core Information Standard** building blocks: medications, allergies, vaccinations, NHS number, GP details, date of birth.

### Transfer of Care standards

NHS England defines Transfer of Care standards for: discharge from inpatient care; discharge from mental health; A&E attendance; outpatient clinic letters. Messages must be **human readable, machine readable, and machine-to-machine transferable**. Discharge summaries must be issued to the GP/referrer **within 24 hours** of transfer.

---

## 7. FHIR in the NHS

**HL7 FHIR** (Fast Healthcare Interoperability Resources) is the NHS interoperability standard.

- **Current version:** FHIR R4 (v4.0.1) — https://hl7.org/fhir/R4/
- **CareConnect** (FHIR STU3 profiles, developed by NHS Digital / INTEROPen) — **deprecated**, replaced by **FHIR UK Core** (R4 profiles)
- Transfer of Care FHIR specifications (eDischarge, outpatient letters) use FHIR

PRSB: "Technical standards specify how information defined in a record standard is to be held or moved between systems. These can be based on Fast Healthcare Interoperability Resources (FHIR)... Examples include FHIR UK Core APIs, Transfer of Care Inpatient Discharge – FHIR API."

---

## 8. Clinical Safety — DCB0129 and DCB0160

| Standard | Applies to | Requirement |
|----------|-----------|-------------|
| **DCB0129** | Manufacturers of health IT systems | Clinical risk management throughout software development lifecycle; maintain a Clinical Safety Case Report and Hazard Log. Derived from ISO 14971 |
| **DCB0160** | Deploying organisations (NHS trusts, GP practices) | Deployment-specific clinical risk assessments; local safety case; local hazard log; safe deployment, testing, go-live |

**Clinical Safety Officer (CSO):** the role responsible for clinical safety; ensures DCB0129/DCB0160 compliance. PRSB offers accredited CSO training covering both standards.

> "Full conformance with some standards is a legal requirement from 2024." — PRSB

---

## 9. NHS Systems Doctors Interact With

### NHS Spine and Personal Demographics Service (PDS)

The **NHS Spine** is the national central infrastructure connecting NHS IT systems. It provides:
- **Personal Demographics Service (PDS)** — national database of NHS patient demographics
- **Summary Care Record (SCR)** application
- **Electronic Prescription Service (EPS)**
- **GP2GP** record transfer
- **Spine Messaging** — secure messaging

### NHS Number

- 10-digit unique identifier for patients in England, Wales, and Isle of Man
- First 9 digits are the identifier; the 10th is a **modulus 11 check digit**
- Displayed as 3-3-4 (e.g. `999 123 4567`)
- Required by the NHS Standard Contract for all clinical staff from 1 April 2020
- Patients do not need it to access services

### Summary Care Record (SCR)

An electronic summary of key patient information (medications, allergies, adverse reactions, additional information at patient request), created from GP records and accessible via the NHS Spine. Designed for use in urgent/emergency care.

### GP Connect

FHIR-based APIs (FHIR R4) allowing authorised healthcare professionals to access GP record data across different GP system suppliers — structured record retrieval (medications, allergies, immunisations, problems, encounters), appointment booking, and record access.

### GP2GP

Electronic transfer of patient records between GP practices when a patient registers with a new GP. Transfers coded data (SNOMED CT, dm+d) and free-text narrative between EMIS Web, SystmOne, and Vision.

### National Record Locator (NRL)

A pointer/index service enabling clinicians to discover and locate patient documents held across different care settings. It tells clinicians a document exists and where to find it; it does not store the document itself.

### NHS e-Referral Service (e-RS)

The national digital platform for GP-to-consultant referrals (formerly "Choose and Book"). Mandated as the only method for GP referrals to first outpatient appointments from 1 October 2018.

### NHS App and NHS login

- **NHS App:** patient-facing service for those 13+ registered with a GP in England
- **NHS login:** single sign-on for health apps, with two-step verification
- **NHS Online:** from 2027, will extend the NHS App to deliver planned care remotely

---

## 10. GP and Hospital Clinical Systems

### GP clinical systems

| System | Supplier |
|--------|----------|
| **EMIS Web** | EMIS Health Group |
| **SystmOne** | TPP (The Phoenix Partnership) |
| **Vision** | Vision Health (formerly INPS) |

All three use SNOMED CT (since April 2018), support dm+d for medicines, and participate in GP2GP and GP Connect. They store structured coded data alongside free-text narrative.

### Hospital EPRs

| System | Supplier |
|--------|----------|
| **Millennium** | Oracle Health (formerly Cerner) |
| **Epic** | Epic Systems Corporation |
| **Lorenzo** | DXC Technology (formerly CSC) |
| **Meditech** | MEDITECH |

Hospital EPRs use SNOMED CT for clinical documentation at the point of care (where implemented). ICD-10 and OPCS-4 codes are assigned by clinical coders after discharge for HES submission and Payment by Results (PbR).

---

## Summary of Key Transitions and Deprecations

| Item | Status | Date |
|------|--------|------|
| Read v2 (5-byte) | Withdrawn | 1 April 2020 |
| CTV3 (Read v3) | Withdrawn | 1 April 2020 |
| Read DAAD | Withdrawn | 1 April 2016 (replaced by dm+d) |
| CareConnect FHIR profiles | Deprecated | ~2021–2022 (replaced by FHIR UK Core R4) |
| ICD-10 (WHO) | Frozen | 2018 (WHO stopped maintaining) |
| ICD-11 | In effect | 1 January 2022 (UK not yet transitioned) |
| OPCS-4.10 | Current | From 1 April 2023 |
| SNOMED CT in primary care | Mandated | 1 April 2018 |
| SNOMED CT in secondary care | Mandated | 1 April 2020 |

---

## Source Index

| Source | URL |
|--------|-----|
| SNOMED International — What is SNOMED CT? | https://www.snomed.org/what-is-snomed-ct |
| SNOMED International — About us | https://www.snomed.org/about-us |
| SNOMED International — United Kingdom | https://www.snomed.org/members/united-kingdom |
| SNOMED International — Use SNOMED CT | https://www.snomed.org/use-snomed-ct |
| SNOMED CT Document Library | https://docs.snomed.org |
| WHO — Classification of Diseases | https://www.who.int/standards/classifications/classification-of-diseases |
| WHO — ICD-11 Implementation FAQ | https://www.who.int/standards/classifications/frequently-asked-questions/icd-11-implementation |
| WHO — ICD-10 Browser | https://icd.who.int/browse10 |
| PRSB — Standards | https://theprsb.org/standards/ |
| PRSB — Standards explained | https://theprsb.org/standardsexplained/ |
| PRSB — Information record standards | https://theprsb.org/standardsexplained/prsbinformationrecordstandards/ |
| PRSB — Clinical Safety Officer training | https://theprsb.org/clinicalsafetyofficertraining/ |
| NHS England — Interoperability | https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/ |
| NHS England — e-Referral Service | https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/nhs-e-referral-service/ |
| NHS England — NHS Online | https://www.england.nhs.uk/digitaltechnology/nhs-online/ |
| NHS.uk — NHS App | https://www.nhs.uk/nhs-app/ |
| NHS.uk — NHS Number | https://www.nhs.uk/using-the-nhs/about-the-nhs/what-is-an-nhs-number/ |
| NHS login Help Centre | https://help.login.nhs.uk/setupnhslogin/ |
| HL7 International — FHIR R4 | https://hl7.org/fhir/R4/ |
| NHS Digital — DCB0129 | https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb0129 |
| NHS Digital — DCB0160 | https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb0160 |
