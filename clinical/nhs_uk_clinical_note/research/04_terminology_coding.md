# NHS UK Clinical Terminology, Coding Systems & Interoperability Standards

> Research compiled from primary sources: SNOMED International, WHO, NHS England, NHS Digital (now part of NHS England), PRSB, HL7, NHS.uk.
> Date: August 2026

---

## Table of Contents

1. [SNOMED CT](#1-snomed-ct)
2. [Read Codes (Legacy)](#2-read-codes-legacy)
3. [ICD-10 / ICD-11](#3-icd-10--icd-11)
4. [OPCS-4](#4-opcs-4)
5. [dm+d (Dictionary of Medicines and Devices)](#5-dmd-dictionary-of-medicines-and-devices)
6. [NHS Interoperability & Record Standards](#6-nhs-interoperability--record-standards)
7. [Clinical Safety](#7-clinical-safety)
8. [Other Key NHS Systems Doctors Interact With](#8-other-key-nhs-systems-doctors-interact-with)

---

## 1. SNOMED CT

### 1.1 What SNOMED CT Is

SNOMED CT (Systematized Nomenclature of Medicine Clinical Terms) is described by its owner as:

> "the most comprehensive, multilingual clinical healthcare terminology in the world" — a "resource with comprehensive, scientifically validated clinical content" that "enables consistent representation of clinical content in electronic health records" and is "mapped to other international standards" and "in use in more than eighty countries."

**Source:** SNOMED International, "What is SNOMED CT?" — https://www.snomed.org/what-is-snomed-ct

The International Edition is "released monthly" and "includes more than 360,000 concepts" (SNOMED International, same source).

### 1.2 Ownership and Maintenance

SNOMED CT is owned, administered, and developed by **SNOMED International**, a not-for-profit organisation:

> "SNOMED International is a not-for-profit organization that owns, administers and develops SNOMED CT, the world's most comprehensive clinical terminology."

**Source:** SNOMED International, "About us" — https://www.snomed.org/about-us

SNOMED International was established in 2007 as the **International Health Terminology Standards Development Organisation (IHTSDO)** and is "Registered in England and Wales | Company Registration Number 9915820" (SNOMED International, footer of all pages).

The organisation is a membership body:

> "Our organization was established as the International Health Terminology Standards Development Organisation in 2007. The founding 9 charter Members were Australia, Canada, Denmark, Lithuania, Sweden, the Netherlands, New Zealand, the United Kingdom and the United States."

**Source:** SNOMED International, "Members" — https://www.snomed.org/members

As of 2026, the organisation "has grown to 53 Members and has issued Affiliate Licenses to more than 50,000 individuals and organisations" (same source).

### 1.3 UK Licensing and National Release Centre

The United Kingdom is a **founder member** of SNOMED International. Its representative is **NHS England** (on behalf of the UK countries):

> "The United Kingdom is a founder member of SNOMED International, and its representative is NHS England, on behalf of the UK countries."

**Source:** SNOMED International, "United Kingdom" member page — https://www.snomed.org/members/united-kingdom

NHS England serves as the **UK National Release Centre**:

> "NHS England is the UK Member's National Release Centre for the creation of, and delegated authority to license, SNOMED CT UK Edition and derivatives. This role is undertaken by NHS England's Technology and Information Standards service."

The **Technology and Information Standards (TIS) UK Strategic Board** "sets the strategic direction for terminology and includes representatives from England, Northern Ireland, Scotland and Wales" (same source).

### 1.4 Structure: Concepts, Descriptions, Relationships

SNOMED International describes the core component types:

> "The SNOMED CT logical model defines the way in which each type of SNOMED CT component and derivative is related and represented. The core component types in SNOMED CT are concepts, descriptions and relationships."

**Source:** SNOMED International, "What is SNOMED CT?" — https://www.snomed.org/what-is-snomed-ct

**Concepts:**
> "Every concept represents a unique clinical meaning, which is referenced using a unique, numeric and machine readable SNOMED CT identifier. The identifier provides an unambiguous unique reference to each concept and does not have any ascribed human interpretable meaning."

**Relationships:**
> "A relationship represents an association between two concepts. Relationships are used to logically define the meaning of a concept in a way that can be processed by a computer. A third concept, called a relationship type (or attribute), is used to represent the meaning of the association between the source and destination concepts."

**Descriptions:**
> "Descriptions are the human readable terms that are associated with clinical ideas. Each description has a description type and may be marked 'preferred for use' in particular languages or dialects. A fully specified name (FSN) is a type of description which uniquely and fully captures the meaning of the clinical idea. Synonyms are descriptions that allow the same concept to be expressed in different ways, each of which are associated with the same concept ID."

A fourth core component type, **Reference Sets**, is also documented:

> "Reference Sets — used to group Concepts or Descriptions into sets, including reference sets and cross-maps to other classifications and standards."

**Source (Reference Sets):** Wikipedia, "SNOMED CT", citing SNOMED International documentation — https://en.wikipedia.org/wiki/SNOMED_CT

### 1.5 SNOMED CT Hierarchy — Top-Level Hierarchies

SNOMED CT concepts are organised into top-level hierarchies. The key top-level hierarchies include (from SNOMED International documentation and the SNOMED CT browser):

| Hierarchy | Semantic Tag(s) | Description |
|-----------|----------------|-------------|
| **Clinical finding** | (clinical finding), (disorder) | Diseases, symptoms, clinical findings |
| **Procedure** | (procedure) | Actions performed on patients |
| **Situation with explicit context** | (situation) | Contextual concepts (e.g., "history of", "family history of") |
| **Body structure** | (body structure), (body morphologic structure) | Anatomical structures |
| **Pharmaceutical / biologic product** | (product), (medicinal product), (medicinal product form), (clinical drug) | Medicines and products |
| **Observable entity** | (observable entity) | Things that can be observed/measured |
| **Event** | (event) | Administrative and clinical events |
| **Specimen** | (specimen) | Specimens for testing |
| **Environment / geographical location** | (environment), (geographic location) | Locations |
| **Social context** | (social concept) | Social/occupational context |
| **Organism** | (organism) | Living organisms |
| **Substance** | (substance) | Chemical substances |
| **Record artifact** | (record artifact) | Documents and records |
| **Physical object** | (physical object), (device) | Physical items and devices |
| **Physical force** | (physical force) | Physical forces |
| **Qualifier value** | (qualifier value) | Values used to qualify other concepts |
| **Special concept** | (special concept) | Special navigation concepts |
| **Staging and scales** | (staging scale) | Cancer staging and assessment scales |
| **Linkage concept** | (linkage concept) | Relationship types / attributes |
| **Metadata** | various | Administrative metadata |

**Source:** SNOMED International browser (snomedbrowser.com / SNOMED CT browser); Wikipedia "SNOMED CT" article detailing top-level hierarchies (https://en.wikipedia.org/wiki/SNOMED_CT); SNOMED CT Glossary entries at docs.snomed.org

The "Situation with explicit context" hierarchy is notable — it handles concepts like "History of myocardial infarction" or "Family history of diabetes" where clinical context is encoded into the concept itself. This is sometimes criticised as "epistemic intrusion" — context that ideally should be in the information model rather than the terminology (Wikipedia/SNOMED CT).

### 1.6 Use in NHS Primary and Secondary Care — Replacement of Read Codes

SNOMED CT replaced **Read codes** (Read v2 and CTV3) as the mandated clinical terminology in NHS primary care. The transition timeline is documented on the SNOMED International UK member page:

> "All NHS provider organisations are expected to assume paperless running by 1 April 2018 and are expected to adopt SNOMED CT in the direct care process by 1 April 2020."

And specifically:

> "SNOMED CT must be utilised in place of Read codes before 1 April 2018 across Primary care settings. For Secondary Care, Acute Care, Mental Health, Community systems, Dentistry and other systems used in the direct management of care of an individual must use SNOMED CT as the clinical terminology before 1 April 2020."

**Source:** SNOMED International, "United Kingdom" — https://www.snomed.org/members/united-kingdom; NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

The National Information Board framework is cited:

> "Endorses the move to adopt a single terminology, SNOMED CT [...] States that partners will actively collaborate to ensure that all primary care systems adopt SNOMED CT by the end of December 2016 [...] States that the entire health system should adopt SNOMED CT by April 2020"

**Source:** SNOMED International, "United Kingdom" member page (citing National Information Board "Personalised Health and Care 2020: A Framework for Action")

### 1.7 SNOMED CT Coding for Problems/Diagnoses and Reference Sets

**Reference Sets (Refsets)** are a key SNOMED CT mechanism for creating subsets of concepts for specific purposes. From the SNOMED CT Glossary at docs.snomed.org:

A reference set (refset) is a mechanism for "grouping Concepts or Descriptions into sets, including reference sets and cross-maps to other classifications and standards" (SNOMED CT structure, Wikipedia citing SNOMED International documentation).

Reference sets serve multiple purposes:
- **Language reference sets** — identify which descriptions are preferred/acceptable for a given language/dialect
- **Simple reference sets** — group concepts for a particular use case
- **Module dependency reference sets** — track dependencies between modules
- **Mapping reference sets** — cross-map to other code systems (e.g., ICD-10, OPCS-4)
- **Historical reference sets** — indicate replacement concepts for retired concepts
- **Annotation reference sets** — add annotations to concepts

**Key UK Reference Sets:**

- **GP/GPSoC Refsets**: Created for the GP Systems of Choice (GPSoC) programme. These define subsets of SNOMED CT used in GP clinical systems — e.g., the set of codes available for recording diagnoses, medications, and observations in primary care EPRs. These are maintained by NHS England (formerly NHS Digital) as part of the UK SNOMED CT Edition.

- **Order Entry Refset**: A reference set supporting computerised provider order entry (CPOE), defining which SNOMED CT concepts are appropriate for ordering tests, medications, and procedures.

- **UK Edition**: The SNOMED CT UK Edition is the national extension containing UK-specific content:

> "The UK Edition is now available in both RF1 and RF2 formats, with around 88,000 UK clinical concepts and 380,000 UK drugs."

**Source:** SNOMED International, "United Kingdom" — https://www.snomed.org/members/united-kingdom

The UK Edition is released through the **Terminology Reference data Update Distribution (TRUD)** service.

### 1.8 SNOMED CT Maps to Other Terminologies

> "SNOMED CT is a terminology that can cross-map to other international terminologies, classifications and code systems. Maps are associations between particular concepts or terms in one system and concepts or terms in another system that have the same (or similar) meaning."

Benefits include: "Data reuse: SNOMED CT based clinical data can be reused to report statistical and management data using other terminologies, classifications and code systems" and "Interoperability among international terminologies, classifications and code systems."

**Source:** SNOMED International, "Use SNOMED CT" — https://www.snomed.org/use-snomed-ct

SNOMED CT cross-maps to: ICD-9-CM, ICD-10, ICD-O-3, ICD-10-AM, Laboratory LOINC, and OPCS-4 (Wikipedia/SNOMED CT, citing SNOMED International).

---

## 2. Read Codes (Legacy)

### 2.1 What Read Codes Were

Read codes were "a clinical terminology system that was in widespread use in General Practice in the United Kingdom until around 2018, when NHS England switched to using SNOMED CT" (Wikipedia, "Read code").

**Read v2 (5-byte Read):**
- Developed from Read v1 (4-byte Read), originally created by Dr James Read, a Loughborough GP, in the early 1980s
- 5-character alphanumeric codes in a monohierarchical structure
- The October 2010 release contained "82,967 discrete 5-byte codes"
- Mandated for use in NHS general practice in April 1999

**CTV3 (Clinical Terms Version 3 / Read v3):**
- Introduced a polyhierarchical structure (parent-child relationships in a separate table)
- Concepts and terms had separate identifiers
- Supported post-coordination (qualifying concepts with additional codes)
- The October 2010 release contained "298,102 discrete concept codes of which 55,829 were marked as inactive"

**Source:** Wikipedia, "Read code" — https://en.wikipedia.org/wiki/Read_code (citing Benson, T. 2011; Bentley et al. 1996; NHS Connecting for Health)

### 2.2 Where Read Codes Still Appear

Read codes remain in historical GP records and legacy systems. They were the core clinical terminology used in UK primary care until the SNOMED CT transition. Data migration involved mapping tables:

> "The creation of mapping tables from antecedent versions of SNOMED for pathology content as well as Read to SNOMED CT mapping tables for laboratory result reporting."

**Source:** SNOMED International, "United Kingdom" — https://www.snomed.org/members/united-kingdom

### 2.3 Deprecation and Withdrawal

The deprecation and withdrawal timeline was formalised by the Standardisation Committee for Care Information (SCCI) in August 2014:

- **Read v2**: Deprecation date December 2010; final updated release 1 April 2016; complete withdrawal 1 April 2020
- **CTV3**: Deprecation date 1 September 2014; final updated release 1 April 2018; complete withdrawal 1 April 2020
- **Read Drug and Appliance Dictionary (DAAD)**: Final publication 1 April 2016, replaced by dm+d

**Source:** Wikipedia, "Read code", citing SCCI Information Standards Notices and NHS Digital — https://en.wikipedia.org/wiki/Read_code

### 2.4 Relationship Between Read Codes and SNOMED CT

> "SNOMED CT was created in 2001 out of a technical, editorial and content merger of CTV3 and SNOMED RT, an American system. A significant part of the International Core content of SNOMED CT derives directly from CTV3."

**Source:** Wikipedia, "Read code" — https://en.wikipedia.org/wiki/Read_code

The SNOMED CT Glossary entry at docs.snomed.org confirms: "Clinical Terms Version 3 (CTV3)" was the predecessor terminology that was merged with SNOMED RT to create SNOMED CT.

---

## 3. ICD-10 / ICD-11

### 3.1 ICD-10 for Secondary Care Hospital Coding

ICD-10 (International Statistical Classification of Diseases and Related Health Problems, 10th Revision) is used in NHS secondary care for **statistical and secondary uses coding**, primarily through **Hospital Episode Statistics (HES)**. Clinical coders (not doctors) assign ICD-10 codes from clinical documentation after patient discharge.

The WHO describes ICD's role:

> "Clinical terms coded with ICD are the main basis for health recording and statistics on disease in primary, secondary and tertiary care, as well as on cause of death certificates. These data and statistics support payment systems, service planning, administration of quality and safety, and health services research."

**Source:** WHO, "International Classification of Diseases (ICD)" — https://www.who.int/standards/classifications/classification-of-diseases

The ICD-10 browser is available at: https://icd.who.int/browse10 (latest version: 2019)

### 3.2 WHO ICD-10 vs NHS-Modified ICD-10

The UK uses a **NHS-modified version of ICD-10** with additional clinical coding instructions and national adaptations. The **Clinical Classifications Service** (formerly part of NHS Digital, now within NHS England) maintains the UK version and publishes:

- **National Clinical Coding Standards ICD-10** — a reference book on how to use the classification
- **ICD-10 and OPCS-4 Classifications Content Changes** — minor changes and coding advice disseminated through this publication (formerly "The Coding Clinic")

**Source:** Wikipedia, "OPCS-4", citing NHS Digital Clinical Classifications Service — https://en.wikipedia.org/wiki/OPCS-4

### 3.3 ICD-11 — WHO Adoption and UK Status

**ICD-11** was adopted by the 72nd World Health Assembly in May 2019 and came into effect on 1 January 2022:

> "The latest version of the ICD, ICD-11, was adopted by the 72nd World Health Assembly in 2019 and came into effect on 1st January 2022."

**Source:** WHO, "Classification of Diseases" — https://www.who.int/standards/classifications/classification-of-diseases

WHO's ICD-11 Implementation FAQ confirms:

> "WHO stopped maintaining ICD-10 in 2018, and future enhancements will be introduced only in ICD-11."

> "The new Revision of ICD was endorsed by the World Health Assembly at the 72nd meeting in 2019, and came into effect globally on 1 January 2022."

**Source:** WHO, "ICD-11 Implementation" FAQ — https://www.who.int/standards/classifications/frequently-asked-questions/icd-11-implementation

As of May 2024, WHO reported: "132 Member States and areas are at various phases of implementing the new classification system. Specifically, 72 countries have commenced the implementation process [...] 14 countries and areas have begun to collect or report data using ICD-11 coding" (WHO, Classification of Diseases page).

The ICD-11 browser is at: https://icd.who.int/browse11

**UK adoption status:** The UK has not yet fully transitioned to ICD-11 for statutory hospital coding. As of 2026, NHS hospital coding in England continues to use ICD-10 (NHS-modified). WHO's FAQ notes: "Countries can continue to use ICD-10 for as long as necessary, but prompt adoption of ICD-11 is encouraged."

### 3.4 SNOMED CT vs ICD-10 — Key Differences

| | SNOMED CT | ICD-10 |
|---|-----------|--------|
| **Type** | Clinical terminology | Statistical classification |
| **Purpose** | Recording clinical detail in the EHR | Aggregating data for statistics, reimbursement, epidemiology |
| **Who uses it** | Clinicians (during care) | Clinical coders (after care, from documentation) |
| **Hierarchy** | Polyhierarchical (multiple parents) | Monohierarchical (single parent) |
| **Granularity** | Very detailed (360,000+ concepts) | Less detailed (~14,000 codes) |
| **Postcoordination** | Supported | Not supported in ICD-10 (supported in ICD-11) |

WHO's FAQ addresses this distinction:

> "SNOMED CT enables information input into an EHR system during the course of patient care, while ICD facilitates information retrieval, or output, for secondary data purposes."

**Source:** WHO ICD-11 FAQ, Q35; Wikipedia/SNOMED CT citing AHIMA

WHO further clarifies:

> "ICD-11 is a standalone system and does not require additional external terminology or classification systems."

> "The outcomes of the WHO–SNOMED Int. collaboration for mapping ICD-11 and SNOMED CT are still under discussion and are not guaranteed. ICD-11 and ICD-10 are the primary documentation and classification systems for official reporting nationally to WHO."

**Source:** WHO ICD-11 FAQ, Q34-Q36 — https://www.who.int/standards/classifications/frequently-asked-questions/icd-11-implementation

---

## 4. OPCS-4

### 4.1 What OPCS-4 Is

**OPCS-4** (OPCS Classification of Interventions and Procedures version 4) is:

> "the procedural classification used by clinical coders within National Health Service (NHS) hospitals of NHS England, NHS Scotland, NHS Wales and Health and Social Care in Northern Ireland."

It is based on the earlier Office of Population Censuses and Surveys Classification of Surgical Operations and Procedures (4th revision) and retains the OPCS abbreviation.

**Source:** Wikipedia, "OPCS-4" — https://en.wikipedia.org/wiki/OPCS-4 (citing NHS Digital and the NHS Data Dictionary)

### 4.2 Who Maintains OPCS-4

> "Organization: NHS Digital"

> "On 1 April 2013, the Health and Social Care Information Centre's (HSCIC) Clinical Classifications Service (CCS) became responsible for the revision and maintenance of OPCS-4. On 1 April 2016, HSCIC was rebranded to NHS Digital; responsibility for OPCS-4 remains with NHS Digital. NHS Digital merged with NHS England 1 February 2023."

**Source:** Wikipedia, "OPCS-4" — https://en.wikipedia.org/wiki/OPCS-4 (citing NHS Digital and Computer Weekly)

The latest version is **OPCS-4.10**, mandated from 1 April 2023. The OPCS-4 classification is accessed via the NHS England Classifications Browser: https://classbrowser.nhs.uk/#/book/OPCS-4.10

### 4.3 How OPCS-4 Is Used

OPCS-4 codifies "operations, procedures and interventions performed during in-patient stays, day case surgery and some out-patient treatments in NHS hospitals" (Wikipedia, OPCS-4).

It is used alongside ICD-10 in the **Hospital Episode Statistics (HES)** dataset. ICD-10 codes diagnoses; OPCS-4 codes procedures. Both are assigned by **clinical coders** after discharge, from the clinical documentation — not by doctors at the point of care.

**Structure:**
- Volume I — Tabular List: 24 chapters (A–Z, excluding I and O), with alphanumeric 4-character codes (e.g., A01.1)
- Volume II — Alphabetical Index: look-up index for codes
- **National Clinical Coding Standards OPCS-4** — guidance book on how to use the classification

**Code structure:** First character is always a letter (indicating the chapter), characters 2-4 are numbers, with a full stop separating the 3rd and 4th characters (e.g., `A01.1`). There are no three-character codes (unlike ICD-10).

The long-term plan is to replace OPCS-4 with SNOMED CT for procedure coding (Wikipedia, OPCS-4, citing Department of Health).

---

## 5. dm+d (Dictionary of Medicines and Devices)

### 5.1 What dm+d Is

The **Dictionary of Medicines and Devices (dm+d)** is the NHS dictionary of medicines and devices used for prescribing and reimbursement. It is a **SNOMED CT-based** terminology that codes medicines, appliances, and medical devices.

dm+d is maintained by the **NHS Business Services Authority (NHSBSA)** in collaboration with **NHS Digital** (now NHS England). It provides:
- Unique identifiers for medicinal products and devices
- Codes for use in electronic prescribing systems
- Data for reimbursement and pricing (Drug Tariff)
- VMP (Virtual Medicinal Product), AMP (Actual Medicinal Product), VMPP (Virtual Medicinal Product Pack), AMPP (Actual Medicinal Product Pack), and VTM (Virtual Therapeutic Molecule) concept types

### 5.2 dm+d and SNOMED CT Relationship

dm+d is built upon SNOMED CT's pharmaceutical/biologic product hierarchy. The Read Codes Drug and Appliance Dictionary (DAAD) was withdrawn and replaced by dm+d, which is itself based on SNOMED CT:

> "The Read Codes Drug and Appliance Dictionary (DAAD) was published for the final time on 1 April 2016 [...] The intent of NHS Digital is to migrate users to the Drugs and Medicines Dictionary (dm+d), which itself is based upon SNOMED CT."

**Source:** Wikipedia, "Read code" — https://en.wikipedia.org/wiki/Read_code (citing NHS Digital)

The SNOMED International UK member page confirms the scale of medicines coding:

> "over 156 million electronic prescription messages are transacted monthly using SNOMED CT"

> "around 88,000 UK clinical concepts and 380,000 UK drugs"

**Source:** SNOMED International, "United Kingdom" — https://www.snomed.org/members/united-kingdom

### 5.3 How dm+d Codes Medicines

dm+d uses a hierarchical model:
- **VTM (Virtual Therapeutic Molecule)** — the generic molecule/active ingredient
- **VMP (Virtual Medicinal Product)** — a specific formulation/dose of a VTM
- **VMPP (Virtual Medicinal Product Pack)** — a specific pack size of a VMP
- **AMP (Actual Medicinal Product)** — a branded product from a specific manufacturer
- **AMPP (Actual Medicinal Product Pack)** — a specific pack of an AMP

dm+d data is distributed through the **TRUD (Terminology Reference data Update Distribution)** service.

---

## 6. NHS Interoperability & Record Standards

### 6.1 PRSB (Professional Record Standards Body)

The **Professional Record Standards Body (PRSB)** is the organisation responsible for defining information record standards for health and social care in England:

> "PRSB record standards exist to support the safe and efficient exchange of information across health and care services. They set out what information should be recorded about a person and shared between services to ensure seamless, joined-up care. Built for use in IT systems, the standards are flexible and can be implemented in any system used locally."

**Source:** PRSB, "Standards" — https://theprsb.org/standards/

PRSB defines three types of standards:
1. **Information record standards** — "define the information needed in a person's health and care record, such as their allergies, vaccinations and medications"
2. **Data and terminology standards** — including SNOMED CT for clinical terms and data standards for formatting (e.g., date formats, ethnic category codes)
3. **Technical standards and specifications** — "specify how information defined in a record standard is to be held or moved between systems" using FHIR

**Source:** PRSB, "Standards explained" — https://theprsb.org/standardsexplained/

#### PRSB Standard Structure

Each PRSB standard contains:
- **Sections** — logical organisation of content
- **Elements** — data items
- **Record entries** — sets of information (e.g., medication name + dose)
- **Conformance (MRO)** — Mandatory (MUST), Required (SHOULD), Optional (MAY)
- **Value Sets** — valid values (e.g., SNOMED CT codes, free text, numbers)
- **Implementation guidance** — how to use sections and elements
- **Business rules** — requirements for clinical systems
- **Clinical safety case report** — addressing DCB0129 requirements
- **Hazard log** — identified hazards

**Source:** PRSB, "PRSB information record standards" — https://theprsb.org/standardsexplained/prsbinformationrecordstandards/

#### Core Information Standard / Clinical Record Headings

PRSB's **Core Information Standard** brings together key building blocks used across all standards: medications, allergies, vaccinations, and key personal details (GP surgery, date of birth, NHS number). PRSB has developed standards for particular situations including:
- Childhood
- Maternity care
- Discharge from hospital to GP (eDischarge / Transfer of Care)
- Long-term conditions
- Care home transfers
- End of life care
- Personalised care and support plan
- About me (information a person wants to share)

#### Transfer of Care Standards

NHS England documents the Transfer of Care standards:

> "Developing standards to support the move from paper to electronic transfers of care for: Discharge from inpatient care; Discharge from mental health; A&E attendance; Outpatient clinic letters"

> "The Transfer of Care message should contain structured narrative, coded content. The message should be human readable, machine readable and machine to machine transferable, once scrutinised by the GP."

> "When transferring or discharging a Service User from an inpatient or day case or accident and emergency Service, the Provider must within 24 hours following that transfer or discharge issue a Discharge Summary to the Service User's GP and/or Referrer"

**Source:** NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

Transfer of Care FHIR specifications are published on the NHS Developer website.

### 6.2 FHIR (HL7 FHIR) in the NHS

**HL7 FHIR** (Fast Healthcare Interoperability Resources) is the standard for health care data exchange published by HL7:

> "FHIR is a standard for health care data exchange, published by HL7."

The current version is **FHIR R4** (v4.0.1, October 2019), described as "Release 4 — Mixed Normative and STU" in its permanent home at: http://hl7.org/fhir/R4/

**Source:** HL7 International, FHIR R4 specification — https://hl7.org/fhir/R4/

#### CareConnect (Now Deprecated)

NHS England and NHS Digital developed **CareConnect** FHIR profiles:

> "CareConnect Open APIs have been developed by NHS Digital and INTEROPen to support the delivery of care by opening up information and data held across different clinical care settings. The CareConnect Open APIs use nationally defined FHIR resources and are a method of transferring records from a source to a recipient."

**Source:** NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

The NHS Standard Contract required: "with effect from 1 April 2020, Care Connect APIs" (same source).

**CareConnect deprecation:** CareConnect profiles (based on FHIR STU3/DSTU2) have been superseded by the **FHIR UK Core** profiles based on FHIR R4. The PRSB standards explained page references:

> "Technical standards specify how information defined in a record standard is to be held or moved between systems. These can be based on Fast Healthcare Interoperability Resources (FHIR) [...] Examples include FHIR UK Core APIs, Transfer of Care Inpatient Discharge – FHIR API"

**Source:** PRSB, "Standards explained" — https://theprsb.org/standardsexplained/

This confirms the transition from CareConnect to **FHIR UK Core** (based on FHIR R4) as the current NHS FHIR profile standard.

### 6.3 GP2GP — Electronic Transfer of GP Records

**GP2GP** is the NHS service for the electronic transfer of patient records between GP practices. When a patient registers with a new GP, their electronic health record is transferred from their previous practice using the GP2GP service. This ensures continuity of care by making the patient's medical history available at the new practice.

GP2GP transfers records between the major GP clinical systems (EMIS Web, SystmOne, Vision) using a structured document format that includes coded data (SNOMED CT concepts, medications from dm+d) and free-text narrative.

**Source:** NHS Digital, GP2GP service — https://digital.nhs.uk/services/gp2gp (accessed via reference; content confirmed from NHS England interoperability documentation)

### 6.4 Summary Care Record (SCR)

The **Summary Care Record (SCR)** is an electronic summary of key patient information available to authorised NHS staff across care settings. It contains:
- Medications
- Allergies
- Adverse reactions
- Additional information (at patient request)

The SCR is created automatically from GP records and accessible via the NHS Spine. It is designed for use in urgent and emergency care settings where the clinician may not have access to the patient's full GP record.

### 6.5 GP Connect

**GP Connect** is a set of FHIR-based APIs that allow authorised healthcare professionals to access GP record data across different GP system suppliers. It enables:
- Structured record retrieval (medications, allergies, immunisations, problems, encounters)
- Appointment booking and management
- Patient record access across different GP systems

GP Connect is built on FHIR R4 and is part of the NHS Digital API catalogue.

**Source:** NHS Digital, GP Connect service — https://digital.nhs.uk/services/gp-connect (referenced from NHS England interoperability documentation)

### 6.6 National Record Locator (NRL)

The **National Record Locator (NRL)** is an NHS service that enables healthcare professionals to discover and locate patient documents held across different care settings. It acts as a pointer/index service — it tells clinicians that a document exists and where to find it, but does not store the document itself.

The NHS England interoperability page describes its role alongside CareConnect:

> "When combined with other capabilities (such as National Record Locator Service (NRLS) CareConnect Open API will enable clinicians in one care setting to view records from across other care settings (i.e. a clinician in A&E accessing a patient's medical record from an out of area service)"

**Source:** NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

---

## 7. Clinical Safety

### 7.1 DCB0129 — Clinical Risk Management for Manufacturers

**DCB0129** (formally "Clinical Risk Management: its Application in the Manufacture of Health IT Systems") is the NHS information standard that requires manufacturers of health IT systems to apply clinical risk management throughout the software development lifecycle. It is derived from **ISO 14971** (the international standard for application of risk management to medical devices).

Key requirements include:
- Maintaining a **Clinical Safety Case Report** documenting the safety of the system
- Maintaining a **Hazard Log** identifying and tracking clinical hazards and mitigations
- Conducting clinical risk management activities throughout the development lifecycle

The PRSB documents this connection:

> "Clinical safety case report – this report addresses the requirements of DCB 0129 V4.2 Clinical Risk Management: it's Application in the Manufacture of Health IT Systems."

> "Suppliers developing software to implement these standards are therefore still expected to fully apply DCB0129."

**Source:** PRSB, "PRSB information record standards" — https://theprsb.org/standardsexplained/prsbinformationrecordstandards/

DCB0129 is published as an NHS Information Standard by NHS Digital (now NHS England): https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb0129

### 7.2 DCB0160 — Clinical Risk Management for Deployment

**DCB0160** (formally "Clinical Risk Management: its Application in the Deployment of Health IT Systems") is the companion standard to DCB0129. It requires **deploying organisations** (NHS trusts, GP practices, etc.) to apply clinical risk management when implementing health IT systems.

> "Organisations involved in the deployment of such software are still expected to fully apply DCB0160."

**Source:** PRSB, "PRSB information record standards" — https://theprsb.org/standardsexplained/prsbinformationrecordstandards/

DCB0160 requires deploying organisations to:
- Conduct deployment-specific clinical risk assessments
- Create a local safety case
- Maintain a local hazard log
- Ensure safe deployment, testing, and go-live

**Source:** NHS Digital (NHS England), DCB0160 Information Standard — https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb0160

### 7.3 Clinical Safety Officer Role

The **Clinical Safety Officer (CSO)** is the role responsible for clinical safety within health IT development and deployment organisations. The CSO ensures compliance with DCB0129 and DCB0160.

PRSB offers accredited CSO training:

> "PRSB are partnering with Ethos to offer an online foundation programme [...] Once completed you will be certified as an accredited CSO."

The training covers:
- "DCB 0129 / DCB 0160 compliance"
- "Hands-on with hazard identification and evaluation"
- "Understand risk control and measurements"
- "Understand the safety reports and the review process"
- "Differentiate between standards and medical devices regulation"

> "Suppliers and care providers are encouraged and compelled to implement health and care standards for legislation purposes, supplier accreditation, procurement policy and to enable information sharing across integrated care systems. Full conformance with some standards is a legal requirement from 2024."

**Source:** PRSB, "Clinical safety officer training" — https://theprsb.org/clinicalsafetyofficertraining/

---

## 8. Other Key NHS Systems Doctors Interact With

### 8.1 NHS Spine and the Personal Demographics Service (PDS)

The **NHS Spine** is the national central infrastructure service that connects IT systems across the NHS. It provides:
- **Personal Demographics Service (PDS)** — the national electronic database of NHS patient demographics
- **Summary Care Record (SCR)** application
- **Electronic Prescription Service (EPS)**
- **GP2GP** record transfer
- **Spine Messaging** — secure messaging between NHS systems

### 8.2 NHS Number

The **NHS Number** is the unique identifier for patients in England, Wales, and the Isle of Man:

> "An NHS number is a 10-digit number, like 999 123 4567."

> "Your NHS number is unique to you. It helps healthcare staff and service providers identify you correctly and match your details to your health records."

**Source:** NHS.uk, "What is an NHS number?" — https://www.nhs.uk/using-the-nhs/about-the-nhs/what-is-an-nhs-number/

**Format and check digit:**
- 10 digits in total
- The first 9 digits are the identifier; the 10th digit is a **check digit** calculated using a modulus 11 algorithm
- Displayed as 3-3-4 (e.g., `999 123 4567`)
- Assigned at birth or first NHS registration
- Valid for life (unless changed due to adoption or gender reassignment)

> "If you have an NHS number, it does not mean you're automatically entitled to the free use of all NHS services."

> "You do not need your NHS number to use NHS services."

The NHS Number is required by the NHS Standard Contract:

> "The Provider must ensure that, with effect from 1 April 2020, the Service User's verified NHS Number is available to all clinical Staff when engaged in the provision of any Service to that Service User – this is stated in the 2019/20 Standard Contract"

**Source:** NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

### 8.3 NHS App and NHS Login

#### NHS App

The **NHS App** is the patient-facing digital service for NHS users in England:

> "Use the NHS App to manage your healthcare using a phone, tablet or computer."

> "To use the NHS App, you must be aged 13 or over and registered with a GP surgery in England."

**Source:** NHS.uk, "NHS App" — https://www.nhs.uk/nhs-app/

From 2027, **NHS Online** will extend the NHS App to deliver specialist care remotely:

> "From 2027, NHS Online will give people in England the option to receive planned care through the NHS App."

**Source:** NHS England, "NHS Online" — https://www.england.nhs.uk/digitaltechnology/nhs-online/

#### NHS Login

**NHS login** is the identity authentication service for NHS digital services:

> "NHS login allows you to access lots of different health and care websites and apps with just one set of login details. You can securely access many digital health and care services with one email address and password."

Setup requires: an email address, a mobile/landline number, and for full access: proof of identity (passport, driving licence, or European national identity card, or GP registration details including Linkage Key, ODS Code, and Account ID).

Two-step verification is required for added security.

**Source:** NHS login Help Centre, "Set up NHS login" — https://help.login.nhs.uk/setupnhslogin/

### 8.4 Choose and Book / e-Referral Service (e-RS)

The **NHS e-Referral Service (e-RS)** (formerly "Choose and Book") is:

> "a national digital platform used to refer patients from primary care into elective care services."

> "e-RS allows patients to choose their first outpatient hospital or clinic appointment and book it in the GP surgery, online or on the phone."

From 1 October 2018, the NHS Standard Contract mandated e-RS as the only method for GP referrals:

> "all NHS providers will need to use e-RS as the only method of making and receiving referrals from GPs to consultant-led first outpatient appointments. Accepting referrals not made using e-RS could result in commissioners withholding payment for this activity."

**Source:** NHS England, "NHS e-Referral Service" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/nhs-e-referral-service/

### 8.5 GP Clinical Systems

The three major GP clinical system suppliers in England are:

| System | Supplier | Notes |
|--------|----------|-------|
| **EMIS Web** | EMIS Health Group | Widely used in primary care; supports SNOMED CT, dm+d, GP2GP, GP Connect |
| **SystmOne** | TPP (The Phoenix Partnership) | Widely used in both primary and community care; supports SNOMED CT, dm+d, GP2GP, GP Connect |
| **Vision** | Vision Health (formerly INPS) | Smaller market share; supports SNOMED CT, dm+d, GP2GP, GP Connect |

All three systems use SNOMED CT as their clinical terminology (since the April 2018 mandate), support dm+d for medicines coding, and participate in GP2GP record transfer and GP Connect APIs. They all store structured coded data alongside free-text narrative.

### 8.6 Hospital EPRs

Major hospital Electronic Patient Record (EPR) systems used in the NHS:

| System | Supplier | Notes |
|--------|----------|-------|
| **Millennium** | Oracle Health (formerly Cerner) | Widely deployed in large NHS trusts; supports SNOMED CT, ICD-10, OPCS-4 |
| **Epic** | Epic Systems Corporation | Deployed in several large teaching trusts (e.g., Cambridge, Oxford, UCLH); supports SNOMED CT, ICD-10, OPCS-4 |
| **Lorenzo** | DXC Technology (formerly CSC) | Deployed in some trusts; was part of the NPfIT programme |
| **Meditech** | MEDITECH | Used in a smaller number of NHS trusts |

Hospital EPRs typically use SNOMED CT for clinical documentation at the point of care (where implemented), while ICD-10 and OPCS-4 codes are assigned by clinical coders after discharge for HES submission and Payment by Results (PbR).

### 8.7 NHS England Interoperability Priority Areas

NHS England has identified seven priority areas for interoperability (from the Chief Clinical Information Officer):

1. **NHS number/Citizen ID** — "real-time access to the NHS Number at the point of care"
2. **Medications** — "all medication messages in the NHS to be interoperable and machine readable"
3. **Staff ID** — "ensuring that there is a consistent way to identify and authenticate staff"
4. **Dates and scheduling** — "a consistent set of interoperability standards for dates and scheduling information"
5. **Basic observations** — "a consistent set of interoperability standards for the sharing of a core set of structured observations"
6. **Basic pathology** — "a consistent set of interoperability standards for the sharing of a core set of pathology tests"
7. **Diagnostic coding** — "implementation of SNOMED CT across the wider service"

**Source:** NHS England, "Interoperability" — https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/

---

## Summary of Key Transitions and Deprecations

| Item | Status | Date | Notes |
|------|--------|------|-------|
| Read v2 (5-byte) | Withdrawn | 1 April 2020 | Replaced by SNOMED CT; final release April 2016 |
| CTV3 (Read v3) | Withdrawn | 1 April 2020 | Replaced by SNOMED CT; final release April 2018 |
| Read DAAD | Withdrawn | 1 April 2016 | Replaced by dm+d |
| CareConnect FHIR profiles | Deprecated | ~2021-2022 | Replaced by FHIR UK Core (R4) |
| ICD-10 (WHO) | Frozen | 2018 | WHO stopped maintaining; ICD-11 is the current revision |
| ICD-11 | In effect | 1 January 2022 | UK not yet transitioned for statutory hospital coding |
| OPCS-4.10 | Current | From 1 April 2023 | Latest mandated version; long-term plan to replace with SNOMED CT |
| SNOMED CT in primary care | Mandated | 1 April 2018 | Replaced Read codes |
| SNOMED CT in secondary care | Mandated | 1 April 2020 | Replaced Read codes in secondary, mental health, community, dentistry |

---

## Source Index

| Source | URL | Topics Covered |
|--------|-----|----------------|
| SNOMED International — What is SNOMED CT? | https://www.snomed.org/what-is-snomed-ct | Structure, components, benefits |
| SNOMED International — About us | https://www.snomed.org/about-us | Ownership, organisation |
| SNOMED International — Members | https://www.snomed.org/members | Membership, IHTSDO history |
| SNOMED International — United Kingdom | https://www.snomed.org/members/united-kingdom | UK release centre, transition dates, UK Edition |
| SNOMED International — Use SNOMED CT | https://www.snomed.org/use-snomed-ct | Maps, release cycle, translations |
| SNOMED CT Document Library | https://docs.snomed.org | Glossary, technical documentation |
| WHO — Classification of Diseases | https://www.who.int/standards/classifications/classification-of-diseases | ICD-10, ICD-11, history |
| WHO — ICD-11 Implementation FAQ | https://www.who.int/standards/classifications/frequently-asked-questions/icd-11-implementation | ICD-11 timeline, SNOMED relationship |
| WHO — ICD-10 Browser | https://icd.who.int/browse10 | ICD-10 online |
| PRSB — Standards | https://theprsb.org/standards/ | Published standards list |
| PRSB — Standards explained | https://theprsb.org/standardsexplained/ | Types of standards, FHIR, SNOMED CT |
| PRSB — Information record standards | https://theprsb.org/standardsexplained/prsbinformationrecordstandards/ | Standard structure, DCB0129/DCB0160 |
| PRSB — Clinical Safety Officer training | https://theprsb.org/clinicalsafetyofficertraining/ | CSO role, DCB0129/0160 training |
| NHS England — Interoperability | https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/interoperability/ | Transfer of Care, CareConnect, SNOMED CT mandates |
| NHS England — e-Referral Service | https://www.england.nhs.uk/digitaltechnology/connecteddigitalsystems/nhs-e-referral-service/ | e-RS, Choose and Book |
| NHS England — NHS Online | https://www.england.nhs.uk/digitaltechnology/nhs-online/ | NHS Online service from 2027 |
| NHS.uk — NHS App | https://www.nhs.uk/nhs-app/ | Patient app |
| NHS.uk — NHS Number | https://www.nhs.uk/using-the-nhs/about-the-nhs/what-is-an-nhs-number/ | NHS Number description |
| NHS login Help Centre | https://help.login.nhs.uk/setupnhslogin/ | NHS login setup |
| HL7 International — FHIR R4 | https://hl7.org/fhir/R4/ | FHIR specification |
| Wikipedia — OPCS-4 | https://en.wikipedia.org/wiki/OPCS-4 | OPCS-4 structure, history, NHS Digital |
| Wikipedia — Read code | https://en.wikipedia.org/wiki/Read_code | Read v2, CTV3, deprecation, SNOMED CT merger |
| Wikipedia — SNOMED CT | https://en.wikipedia.org/wiki/SNOMED_CT | Structure, top-level hierarchies, ICD comparison |

---

*This document was compiled from primary sources accessed August 2026. Where NHS Digital (digital.nhs.uk) pages returned HTTP 403 to automated fetching, information was confirmed via NHS England (england.nhs.uk), SNOMED International, PRSB, and WHO primary sources, supplemented by Wikipedia articles citing NHS Digital as their source.*
