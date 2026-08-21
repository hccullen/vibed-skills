# UK NHS Prescribing: Conventions, Notation, and Regulatory Framework

**Research compiled:** 21 August 2026  
**Scope:** England (with notes on Wales, Scotland, Northern Ireland where relevant)  
**Purpose:** Inform the prescribing section (RECEPT.md equivalent) of a UK clinical note skill

---

> **Convention used throughout this document:**
> - **[LAW]** = Statute, statutory instrument, or regulation  
> - **[GUIDANCE]** = BNF, NICE, GMC, MHRA, NHS England published guidance  
> - **[CONVENTION]** = Established professional practice not codified in law or formal guidance

---

## 1. The Prescription Form / FP10

### 1.1 FP10 — Structure and Fields

**[GUIDANCE]** The FP10 is the standard NHS prescription form used in England. NHSBSA describes it as follows:

> "FP10 prescriptions are purchased by NHS organisations including Hospital Trusts, and are distributed free of charge to medical and non medical prescribers, NHS dentists and other organisations as required. Xerox (UK) Ltd supply our national stationery in England and Wales."  
> — NHSBSA, "Prescription forms" (https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/prescribing-and-dispensing/prescription-forms)

**[GUIDANCE]** The FP10 form contains the following key fields (synthesised from BNF "Prescription writing" guidance and HEE London "Medicines Management" guidance):

| Field | Details | Legal requirement? |
|-------|---------|-------------------|
| Patient name and address | Must be stated | Yes (POM) |
| Patient age/date of birth | Age mandatory for children under 12 | Yes for under-12s |
| Prescriber name and address | Must be stated, address must be within UK | Yes |
| Type of prescriber | Indication of prescriber type | Yes |
| Date of prescription | Must be dated | Yes |
| Prescriber signature | Must be handwritten in ink (computer-generated facsimile signatures do not meet legal requirement) | Yes |
| Drug name | Approved (non-proprietary) title, written in full, not abbreviated | Convention/Guidance |
| Form and strength | e.g. tablets, 125 mg/5 mL | Yes for CDs |
| Quantity to be supplied | Number of days or exact amount | Convention |
| Dose and frequency | e.g. "40 mg four times daily" | Convention (Guidance) |
| Exemption declaration (reverse) | Patient ticks applicable box and signs | Required for dispensing |

**Source:** BNF, "Prescription writing" (https://bnf.nice.org.uk/medicines-guidance/prescription-writing/)

> "Prescriptions should be written legibly in ink or otherwise so as to be indelible (it is permissible to issue carbon copies of NHS prescriptions as long as they are signed in ink), should be dated, should state the name and address of the patient, the address of the prescriber, an indication of the type of prescriber, and should be signed in ink by the prescriber (computer-generated facsimile signatures do not meet the legal requirement). The age and the date of birth of the patient should preferably be stated, and it is a legal requirement in the case of prescription-only medicines to state the age for children under 12 years."

### 1.2 FP10 Variants

**[GUIDANCE]** Multiple FP10 variants exist, distinguished by colour and prescriber type. The following table is drawn from Community Pharmacy England (CPE) and Geeky Medics:

| Code | Form colour | Issued by | Notes |
|------|------------|-----------|-------|
| FP10 / FP10NC / FP10SS / FP10HNC | **Green** | GPs, nurse prescribers, AHP prescribers, pharmacist prescribers, hospital doctors (outpatient) | FP10SS = single-sheet; FP10HNC = hospital/non-medical prescriber |
| FP10MDA | **Blue** | Prescribers managing substance misuse patients | Instalment dispensing for treating addiction |
| FP10SP / FP10PN | **Lilac** | Community/independent nurse prescribers and AHP prescribers | |
| FP10D | **Yellow** | Dentists | |
| FP10P-REC | — | Out of Hours (OOH) Centre prescribers | Non-FP10 supply form |
| FP10PCD | — | Private prescribers for Schedule 2/3 CDs | Private CD prescription form |

**Sources:**
- Geeky Medics, "Prescribing in Primary Care" (https://geekymedics.com/prescribing-in-primary-care)
- CPE, "Prescription form validity" (https://cpe.org.uk/dispensing-and-supply/prescription-processing/receiving-a-prescription/is-this-prescription-form-valid)
- HEE London, "NHS Primary Care Prescription (FP10)" (https://london.hee.nhs.uk/medicines-management-nhs-primary-care-prescription-fp10)

### 1.3 Electronic Prescription Service (EPS)

**[GUIDANCE]** NHS England / NHS Digital describe EPS:

> "The Electronic Prescription Service (EPS) allows prescribers to send prescriptions electronically to a dispenser, such as a pharmacy, nominated by the patient. This makes the prescribing and dispensing process more efficient and convenient for patients and healthcare workers."  
> — NHS Digital, "Electronic Prescription Service" (https://digital.nhs.uk/services/electronic-prescription-service)

> "EPS is already widely used in primary care with over 95% of all prescriptions in England now being produced electronically. EPS is not a clinical prescribing system. It is only responsible for managing the workflow of prescriptions from prescribers to dispensers."  
> — NHS Digital, same source

> "Since November 2019 it has been a requirement for all eligible prescriptions to be issued from general practice via EPS."  
> — NHS England, "Electronic prescription service (EPS)" (https://www.england.nhs.uk/long-read/electronic-prescription-service-eps/)

**[LAW]** The legal basis for mandating EPS is the National Health Service (General Medical Services Contracts (Prescription of Drugs etc.) Regulations 2004, as amended by S.I. 2018/1114 (November 2019).

The prescriber records the same clinical information as on a paper FP10: drug name, form, strength, quantity, dose, frequency, and any endorsement information. The patient nominates a dispenser (pharmacy). The prescription is sent via the NHS Spine to the nominated pharmacy. Related services include:
- **Care Identity Service (CIS)** for authentication
- **Signing Service** for electronic signatures
- **Real-Time Exemption Checking (RTEC)** for charge exemptions
- **Prescription Tracker** for tracking status

### 1.4 Repeat Dispensing vs Acute Prescribing

**[CONVENTION/GUIDANCE]** HEE London describes the distinction:

> "For patients with stable long-term conditions, medicines can be requested without seeing the prescriber in primary care up until their clinical review date. Patients can also instruct their nominated pharmacy to download their repeat prescription using EPS."  
> — HEE London (https://london.hee.nhs.uk/medicines-management-nhs-primary-care-prescription-fp10)

> "The clinical review date is set by the prescriber and should not exceed 12 months, as recommended by CQC."

> "To increase safety and reduce waste, the quantity prescribed of the individual repeat prescriptions should not generally exceed a supply of 56 or 60 days, with some Clinical Commissioning Groups (CCGs) stipulating 28 or 30 days."

**[GUIDANCE]** Electronic Repeat Dispensing (eRD) is the EPS equivalent: a single electronic prescription authorises multiple supplies at set intervals, without the patient needing to re-request each time.

> "Electronic repeat dispensing (eRD) is a process that allows patients to receive repeated supplies of their regular medicines without having to request a new prescription each time. The prescription is valid for a specified period (up to 12 months)."  
> — NHS England (https://www.england.nhs.uk/long-read/electronic-repeat-dispensing-erd/)

### 1.5 Private Prescriptions (FP10PCD) vs NHS

**[GUIDANCE]** BNF states:

> "Private prescriptions for Controlled Drugs in Schedules 2 and 3 must be written on specially designated forms which are provided by local NHS England area teams in England (form FP10PCD), local NHS Health Boards in Scotland (form PPCD) and Wales (form W10PCD); in addition, prescriptions must specify the prescriber's identification number."  
> — BNF, "Controlled drugs and drug dependence" (https://bnf.nice.org.uk/medicines-guidance/controlled-drugs-and-drug-dependence/)

**[GUIDANCE]** HEE London notes:

> "All legal prescription writing requirements apply to private prescriptions. The prescription can be written on any piece of paper. If a Schedule 2 or 3 controlled drug is prescribed for dispensing in the community, a special form (FP10PCD) must be used by the prescriber."  
> — HEE London (https://london.hee.nhs.uk/medicines-management-nhs-primary-care-prescription-fp10)

> "Medicines that are not Controlled Drugs should not be prescribed on the same form as a Schedule 2 or 3 Controlled Drug. This is because the form needs to be sent to the relevant NHS agency so the pharmacist would be unable to comply with the requirement to keep private prescriptions for a POM for two years."  
> — BNF, "Controlled drugs and drug dependence"

---

## 2. Prescription Notation and Conventions

### 2.1 How a UK Prescription Item Is Written

**[GUIDANCE]** The BNF "Prescription writing" guidance sets out the structure of a prescription item:

1. **Drug name** — written clearly, not abbreviated, using approved (non-proprietary) titles only
2. **Form** — e.g. tablets, capsules, oral solution
3. **Strength** — e.g. 125 mg/5 mL (liquid strengths must be clearly stated)
4. **Quantity to be supplied** — may be stated as number of days or exact amount
5. **Dose and frequency** — e.g. "40 mg four times daily"
6. **Route** — where appropriate

**Source:** BNF, "Prescription writing" (https://bnf.nice.org.uk/medicines-guidance/prescription-writing/)

Key conventions from BNF prescription writing guidance:

> "1. The strength or quantity to be contained in capsules, lozenges, tablets etc. should be stated by the prescriber. In particular, strength of liquid preparations should be clearly stated (e.g. 125 mg/5 mL)."

> "2. Quantities of 1 gram or more should be written as 1 g, 1.5 g etc. Quantities less than 1 gram should be written in milligrams, e.g. 500 mg, not 0.5 g. Quantities less than 1 mg should be written in micrograms, e.g. 100 micrograms, not 0.1 mg. The unnecessary use of decimal points should be avoided, e.g. 3 mg, not 3.0 mg. When decimals are unavoidable a zero should be written in front of the decimal point where there is no other figure, e.g. 0.5 mL, not .5 mL."

> "3. 'Micrograms' and 'nanograms' should **not** be abbreviated. Similarly 'units' should **not** be abbreviated."

> "4. The term 'millilitre' (ml or mL) is used in medicine and pharmacy, and cubic centimetre, c.c., or cm³ should not be used."

> "5. Dose and dose frequency should be stated; in the case of preparations to be taken 'as required' a **minimum dose interval** should be specified."

> "6. The names of drugs and preparations should be written clearly and **not** abbreviated, using approved titles **only**; **avoid** creating generic titles for modified-release preparations."

> "7. The quantity to be supplied may be stated by indicating the number of days of treatment required in the box provided on NHS forms."

> "8. Although directions should preferably be in **English without abbreviation**, it is recognised that some Latin abbreviations are used."

### 2.2 Latin Abbreviations Used in UK Prescribing

**[GUIDANCE]** The BNF provides an authoritative list of Latin abbreviations that are still recognised in UK prescribing. The BNF states:

> "Directions should be in English without abbreviation. However, Latin abbreviations have been used when prescribing. The following is a list of appropriate abbreviations. It should be noted that the English version is not always an exact translation."  
> — BNF, "Abbreviations and Symbols" (https://bnf.nice.org.uk/about/abbreviations-and-symbols/)

| Abbreviation | Latin | English meaning |
|-------------|-------|----------------|
| a.c. | ante cibum | before food |
| b.d. | bis die | twice daily |
| o.d. | omni die | every day |
| o.m. | omni mane | every morning |
| o.n. | omni nocte | every night |
| p.c. | post cibum | after food |
| p.r.n. | pro re nata | when required |
| q.d.s. | quater die sumendum | to be taken four times daily |
| q.q.h. | quarta quaque hora | every four hours |
| stat | — | immediately |
| t.d.s. | ter die sumendum | to be taken three times daily |
| t.i.d. | ter in die | three times daily |

**[CONVENTION]** In practice, the following abbreviations are commonly used in UK prescribing (though BNF recommends English without abbreviation):

| Abbreviation | Meaning | Notes |
|-------------|---------|-------|
| OD | once daily (omni die) | BNF lists as o.d.; caution: "OD" can be confused with "ocular dexter" (right eye) |
| BD | twice daily (bis die) | BNF lists as b.d. |
| TDS | three times daily (ter die sumendum) | BNF lists as t.d.s. |
| QDS | four times daily (quater die sumendum) | BNF lists as q.d.s. |
| PRN | when required (pro re nata) | BNF lists as p.r.n. |
| PO | by mouth (per os) | Not in BNF Latin list but widely used |
| IV | intravenous | BNF uses i/v |
| IM | intramuscular | BNF uses i/m |
| SC | subcutaneous | Widely used |
| NG | nasogastric | Widely used |
| PR | per rectum | Widely used |
| PV | per vaginam | Widely used |
| SL | sublingual | Widely used |
| TOP | topical | Widely used |
| STAT | immediately | BNF lists as stat |
| mane | in the morning | BNF: o.m. (omni mane) |
| nocte | at night | BNF: o.n. (omni nocte) |

### 2.3 "Do Not Use" Abbreviations — NPSA / NHS England Enduring Standards

**[GUIDANCE]** The NHS National Patient Safety Agency (NPSA) issued alerts (now maintained as enduring standards by NHS England) on safe prescribing. The key enduring standards relevant to abbreviations are:

> "when prescribing insulin, the term 'units' is used in all contexts. Abbreviations such as U or IU are never used"  
> — NHS England, "Medication safety — Enduring standards" (https://www.england.nhs.uk/patient-safety/patient-safety-insight/patient-safety-alerts/enduring-standards/standards-that-remain-valid/medication-safety/)

This references the original NPSA Patient Safety Alert on insulin (NPSA/2010/RRR013).

**[GUIDANCE]** BNF prescription writing guidance explicitly prohibits abbreviation of certain units:

> "'Micrograms' and 'nanograms' should **not** be abbreviated. Similarly 'units' should **not** be abbreviated."  
> — BNF, "Prescription writing"

**[CONVENTION]** The following abbreviations are widely discouraged in UK prescribing practice (drawing from NPSA guidance and BNF recommendations):

| Do not use | Use instead | Reason |
|-----------|-------------|--------|
| U or IU | units | "U" can be mistaken for "0"; "IU" confused with "IV" |
| μg or mcg | micrograms | "μg" can be misread as "mg" (1000× error) |
| ng (abbreviated) | nanograms | Should be written in full |
| OD (for once daily) | once daily | "OD" ambiguous (can mean "right eye" — oculus dexter) |
| c.c. or cm³ | mL | Should not be used in medicine |
| 3.0 mg | 3 mg | Unnecessary decimal point; trailing zero can be misread as 30 |
| .5 mL | 0.5 mL | Leading zero should always be present |

**[GUIDANCE]** NHS England enduring standards also reference:
- Methotrexate: must be prescribed once weekly, not daily (MHRA guidance supersedes the earlier NPSA alert)
- Valproate: pregnancy prevention programme requirements (Valproate Safety Implementation Group guidance supersedes earlier alert)
- The principles of safe prescribing apply to all medications; the "units" rule is extended to heparin and other medicines

### 2.4 Units and Dose Expression Conventions

**[GUIDANCE]** Summary of BNF dose expression conventions:

| Convention | Rule |
|-----------|------|
| ≥ 1 g | Write as "1 g", "1.5 g" etc. |
| < 1 g | Write in milligrams, e.g. "500 mg", not "0.5 g" |
| < 1 mg | Write in micrograms, e.g. "100 micrograms", not "0.1 mg" |
| Micrograms/nanograms | Never abbreviated — write in full |
| Units (e.g. insulin) | Never abbreviated — write "units" in full |
| mL | Use "mL" or "ml"; never "c.c." or "cm³" |
| Decimal points | Avoid where possible; if used, always include leading zero (0.5 mL not .5 mL); avoid trailing zeros (3 mg not 3.0 mg) |
| "As directed" | For instructions "as directed" and "when required", the maximum daily dose should normally be specified |
| Dose for liquids | State in terms of mass of active drug (e.g. "125 mg 3 times daily") not volume ("5 mL") except for compound preparations |
| Oral syringe | Supplied when doses are not multiples of 5 mL |
| Quantity for liquids | Elixirs/mixtures: 50/100/150 mL (5 mL dose); Adult mixtures: 200/300 mL (10 mL dose); Ear/eye/nasal drops: 10 mL |

---

## 3. BNF (British National Formulary)

### 3.1 What the BNF Is and How It Is Published

**[GUIDANCE]** The BNF is described on the NICE BNF website:

> "British National Formulary (BNF) — Key information on the selection, prescribing, dispensing and administration of medicines."  
> — NICE BNF (https://bnf.nice.org.uk/)

**[GUIDANCE]** Publication details:

> "BNF content is copyright © BMJ Publishing Group Ltd and Pharmaceutical Press, the Royal Pharmaceutical Society's knowledge business."  
> — NICE BNF footer

> "BNF and BNFC are published jointly by BMJ Group, Pharmaceutical Press, RCPCH, and NPPG."  
> — Pharmaceutical Press (https://www.pharmaceuticalpress.com/bnf-and-bnfc)

> "Since 1949 British National Formulary (BNF) has been the UK's most trusted and authoritative healthcare resource, helping to ensure the safe and effective use of medicines at the point of care. The updated BNF book is published twice a year, in March and September."  
> — Pharmaceutical Press (https://www.pharmaceuticalpress.com/bnf-and-bnfc/books/)

The BNF is:
- Published jointly by **BMJ Publishing Group Ltd** and **Pharmaceutical Press** (the Royal Pharmaceutical Society's knowledge business)
- Available online via NICE at bnf.nice.org.uk (free to access for non-commercial use in the UK)
- Also available in print (published biannually, March and September) and as an app
- The BNF for Children (BNFC) is published annually by BMJ Group, Pharmaceutical Press, RCPCH Publications Ltd, and NPPG
- NICE accredited the BNF production process in September 2016, renewed in 2021

### 3.2 BNF Structure and Monograph Layout

**[GUIDANCE]** The BNF is organised by body system. The table of contents includes:

- Preface, Acknowledgements
- How BNF publications are constructed
- Guidance on prescribing
- Prescription writing
- Emergency supply of medicines
- Controlled drugs and drug dependence
- Adverse reactions to drugs
- Guidance on intravenous infusions
- Medicines optimisation
- Antimicrobial stewardship
- Prescribing in special populations (children, hepatic impairment, renal impairment, pregnancy, breast-feeding, palliative care, elderly)
- Drugs organised by body system (chapters 1–15 approximately):
  1. Gastro-intestinal system
  2. Cardiovascular system
  3. Respiratory system
  4. Central nervous system
  5. Infections
  6. Endocrine system
  7. Obstetrics, gynaecology, and urinary-tract disorders
  8. Malignant disease and immunosuppression
  9. Nutrition and blood
  10. Musculoskeletal and joint diseases
  11. Eye
  12. Ear, nose, and oropharynx
  13. Skin
  14. Immunological products and vaccines
  15. Anaesthesia
- Borderline substances
- Wound management
- Medical devices
- Dental Practitioners' Formulary
- Nurse Prescribers' Formulary
- Non-medical prescribing
- Index of proprietary manufacturers
- Special-order manufacturers

Each drug monograph describes: uses (indications), doses, cautions, contra-indications, side-effects, medicinal forms, and other considerations.

**Source:** Wikipedia, "British National Formulary" (https://en.wikipedia.org/wiki/British_National_Formulary); BNF NICE website.

### 3.3 BNF Cautions/Advisory Labels for Dispensers

**[GUIDANCE]** The BNF includes a system of numbered cautionary and advisory labels that the prescriber can specify for the dispenser to apply to dispensed medicines. The labels are:

| Label no. | Wording |
|-----------|---------|
| 1 | Warning: This medicine may make you sleepy |
| 2 | Warning: This medicine may make you sleepy. If this happens, do not drive or use tools or machines. Do not drink alcohol |
| 3 | Warning: This medicine may make you sleepy. If this happens, do not drive or use tools or machines |
| 4 | Warning: Do not drink alcohol |
| 5 | Do not take indigestion remedies 2 hours before or after you take this medicine |
| 6 | Do not take indigestion remedies, or medicines containing iron or zinc, 2 hours before or after you take this medicine |
| 7 | Do not take milk, indigestion remedies, or medicines containing iron or zinc, 2 hours before or after you take this medicine |
| 8 | Warning: Do not stop taking this medicine unless your doctor tells you to stop |
| 9 | Space the doses evenly throughout the day. Keep taking this medicine until the course is finished, unless you are told to stop |
| 10 | Warning: Read the additional information given with this medicine |
| 11 | Protect your skin from sunlight — even on a bright but cloudy day. Do not use sunbeds |
| 12 | Do not take anything containing aspirin while taking this medicine |
| 13 | Dissolve or mix with water before taking |
| 14 | This medicine may colour your urine. This is harmless |
| 15 | Caution: flammable. Keep your body away from fire or flames after you have put on the medicine |
| 16 | Dissolve the tablet under your tongue — do not swallow. Store the tablets in this bottle with the cap tightly closed. Get a new supply 8 weeks after opening |
| 17 | Do not take more than . . . in 24 hours |
| 18 | Do not take more than . . . in 24 hours. Also, do not take more than . . . in any one week |
| 19 | Warning: This medicine makes you sleepy. If you still feel sleepy the next day, do not drive or use tools or machines. Do not drink alcohol |
| 21 | Take with or just after food, or a meal |
| 22 | Take 30 to 60 minutes before food |
| 23 | Take this medicine when your stomach is empty. This means an hour before food or 2 hours after food |
| 24 | Suck or chew this medicine |
| 25 | Swallow this medicine whole. Do not chew or crush |
| 26 | Dissolve this medicine under your tongue |
| 27 | Take with a full glass of water |
| 28 | Spread thinly on the affected skin only |
| 29 | Do not take more than 2 at any one time. Do not take more than 8 in 24 hours |
| 30 | Contains paracetamol. Do not take anything else containing paracetamol while taking this medicine. Talk to a doctor at once if you take too much of this medicine, even if you feel well |
| 32 | Contains aspirin. Do not take anything else containing aspirin while taking this medicine |

**Source:** BNF, "Cautionary and advisory labels" (https://bnf.nice.org.uk/about/labels/)

The prescriber can also endorse "NCL" (no cautionary labels) when recommended cautionary labels are not required.

---

## 4. Controlled Drugs (CDs)

### 4.1 Misuse of Drugs Act 1971 and Misuse of Drugs Regulations 2001

**[LAW]** The Misuse of Drugs Act 1971 prohibits production, supply, and possession of controlled drugs. The Misuse of Drugs Regulations 2001 (S.I. 2001/3998) provides exceptions allowing lawful possession and use for medical, dental, and veterinary purposes.

> "The Misuse of Drugs Act, 1971 as amended prohibits certain activities in relation to 'Controlled Drugs', in particular their manufacture, supply, and possession (except where permitted by the 2001 Regulations or under licence from the Secretary of State)."  
> — BNF, "Controlled drugs and drug dependence" (https://bnf.nice.org.uk/medicines-guidance/controlled-drugs-and-drug-dependence/)

**[LAW]** Under the Act, drugs are classified into three classes based on harmfulness:

> "**Class A** includes: alfentanil, cocaine, diamorphine hydrochloride (heroin), dipipanone hydrochloride, fentanyl, lysergide (LSD), methadone hydrochloride, 3,4-methylenedioxymethamfetamine (MDMA, 'ecstasy'), morphine, opium, oxycodone hydrochloride, pethidine hydrochloride, phencyclidine, remifentanil, and class B substances when prepared for injection."

> "**Class B** includes: oral amfetamines, barbiturates, cannabis, Sativex®, codeine phosphate, dihydrocodeine tartrate, ethylmorphine, glutethimide, ketamine, nabilone, pentazocine, phenmetrazine, and pholcodine."

> "**Class C** includes: certain drugs related to the amfetamines such as benzfetamine and chlorphentermine, buprenorphine, mazindol, meprobamate, pemoline, pipradrol, most benzodiazepines, tramadol hydrochloride, zaleplon, zolpidem tartrate, zopiclone, androgenic and anabolic steroids, clenbuterol, chorionic gonadotrophin (HCG), non-human chorionic gonadotrophin, somatotropin, somatrem, somatropin, gabapentin, pregabalin and nitrous oxide."

### 4.2 Schedules 1–5

**[LAW]** The Misuse of Drugs Regulations 2001 divide controlled drugs into five Schedules, each specifying requirements for import, export, production, supply, possession, prescribing, and record keeping.

> "In the 2001 regulations, drugs are divided into five Schedules, each specifying the requirements governing such activities as import, export, production, supply, possession, prescribing, and record keeping which apply to them."  
> — BNF, "Controlled drugs and drug dependence"

| Schedule | Description | Examples | Key requirements |
|----------|-------------|----------|-----------------|
| **Schedule 1** | Drugs not used medicinally; hallucinogenic | LSD, ecstasy-type substances, raw opium, cannabis (non-medicinal) | Home Office licence required for production/possession/supply; CD register for any received/supplied by pharmacy |
| **Schedule 2** | Opiates, major stimulants, cocaine, ketamine, cannabis-based products for medicinal use | Morphine, diamorphine (heroin), methadone, oxycodone, pethidine, fentanyl, amfetamines, cocaine, ketamine, methylphenidate | Full CD requirements: prescriptions, safe custody (CD cabinet), CD register; valid 28 days |
| **Schedule 3** | Barbiturates (except secobarbital), buprenorphine, gabapentin, midazolam, pentazocine, pregabalin, temazepam, tramadol, phentermine | Buprenorphine, temazepam, midazolam, pregabalin, gabapentin, tramadol | Special prescription requirements; safe custody for some (buprenorphine, temazepam); no CD register needed; invoice retention 2 years; valid 28 days |
| **Schedule 4 Part I** | Benzodiazepines (except temazepam/midazolam), non-benzodiazepine hypnotics, Sativex® | Diazepam, lorazepam, zopiclone, zolpidem, zaleplon | Minimal control; no CD prescription requirements; no safe custody; no register (except Sativex®) |
| **Schedule 4 Part II** | Androgenic and anabolic steroids, growth hormones | Testosterone, nandrolone, somatropin | Minimal control; not illegal to possess; illegal to supply |
| **Schedule 5** | Preparations with low CD content; exempt from most controls | Codeine, pholcodine, morphine (low-strength preparations), nitrous oxide | Virtually no CD requirements; invoice retention 2 years; valid 6 months |

**Sources:**
- BNF, "Controlled drugs and drug dependence" (https://bnf.nice.org.uk/medicines-guidance/controlled-drugs-and-drug-dependence/)
- Misuse of Drugs Regulations 2001 (S.I. 2001/3998) (https://www.legislation.gov.uk/uksi/2001/3998/contents)
- CQC, "Controlled drugs in care homes" (https://www.cqc.org.uk/guidance-regulation/adult-social-care/medicines-information-adult-social-care-services/controlled-drugs-care-homes)
- UK Parliament, "Misuse of drugs: regulation and enforcement" (https://researchbriefings.files.parliament.uk/documents/CBP-10154/CBP-10154.pdf)

> "The Misuse of Drugs Regulations 2001 categorise controlled drugs into 5 schedules. The schedules correspond to the level of therapeutic usefulness and the potential for harm from misuse, with lower schedules having higher risk."  
> — CQC (same URL)

### 4.3 FP10 for Controlled Drugs — Extra Requirements

**[LAW]** Prescriptions for Schedule 2 and 3 CDs must meet additional legal requirements beyond those for standard POMs. BNF states:

> "Prescriptions for Controlled Drugs that are subject to prescription requirements (all preparations in Schedules 2 and 3) must be indelible, must be _signed_ by the prescriber, include the _date_ on which they were signed, and specify the prescriber's _address_ (must be within the UK). A computer-generated prescription is acceptable, but the prescriber's signature must be handwritten. Advanced electronic signatures can be accepted for Schedule 2 and 3 Controlled Drugs where the Electronic Prescribing Service (EPS) is used."

All CD prescriptions must state:
- Name and address of the patient (PO Box acceptable)
- The **form** (dosage form — e.g. "tablets" must be included even if implicit in the brand name)
- Where appropriate, the **strength** (when more than one strength exists)
- For liquids: the total volume in millilitres **in both words and figures**
- For dosage units (tablets, capsules, ampoules): the total number **in both words and figures** (e.g. "10 tablets [of 10 mg]" rather than "100 mg total quantity")
- The **dose**, which must be clearly defined ("one as directed" constitutes a dose but "as directed" does not)
- "for dental treatment only" if issued by a dentist

> "A pharmacist is **not** allowed to dispense a Controlled Drug unless all the information required by law is given on the prescription."

**[GUIDANCE]** The Department of Health and Scottish Government have issued a strong recommendation:

> "The maximum quantity of Schedule 2, 3 or 4 Controlled Drugs prescribed should not exceed 30 days; exceptionally, to cover a justifiable clinical need and after consideration of any risk, a prescription can be issued for a longer period, but the reasons for the decision should be recorded on the patient's notes."

**[LAW]** Prescription validity:
> "A prescription for a Controlled Drug in Schedules 2, 3, or 4 is valid for 28 days after the date stated thereon. Schedule 5 prescriptions are valid for 6 months from the appropriate date."

### 4.4 Instalment Prescribing (FP10MDA)

**[LAW]** Prescriptions for Schedule 2 or 3 CDs can be dispensed by instalments. BNF states:

> "An instalment prescription must have an instalment direction including both the dose and the instalment amount specified separately on the prescription, and it must also state the interval between each time the medicine can be supplied."

> "The first instalment must be dispensed no later than 28 days after the appropriate day and the remainder should be dispensed in accordance with the instructions on the prescription."

The **FP10MDA** (blue form in England) is used for instalment dispensing, primarily for opioid substitution therapy.

**[LAW]** Repeatable prescriptions:
> "Only Schedule 4 and 5 Controlled Drugs are permitted on repeatable prescriptions."

### 4.5 Controlled Drugs Accountable Officer (CDAO)

**[LAW]** The Health Act 2006 introduced the concept of the "accountable officer":

> "The Health Act 2006 introduced the concept of the 'accountable officer' with responsibility for the management of Controlled Drugs and related governance issues in their organisation."  
> — BNF, "Controlled drugs and drug dependence"

**[LAW]** The Controlled Drugs (Supervision of Management and Use) Regulations 2013:

> "Most recently, in 2013 The Controlled Drugs (Supervision of Management and Use) Regulations were published to ensure good governance concerning the safe management and use of Controlled Drugs in England and Scotland."  
> — BNF, same source

The CDAO is responsible for:
- Monitoring CD use within their organisation
- Ensuring appropriate governance arrangements
- Investigating concerns about CD management
- Reporting to NHS England

### 4.6 Requisitions (FP10RECD)

**[CONVENTION]** Requisitions for controlled drugs use form FP10RECD (or equivalent). These are used by authorised healthcare professionals to obtain stocks of controlled drugs for administration/supply in their professional capacity. The BNF references prescription security requirements and the need for prescribers to maintain records of serial numbers of prescription forms.

---

## 5. Drug Tariff

### 5.1 What the Drug Tariff Is

**[GUIDANCE]** The Drug Tariff is produced monthly by the NHSBSA:

> "The Drug Tariff is produced monthly by the Pharmaceutical Directorate of the NHS Business Services Authority (NHSBSA) for the Secretary of State. The Drug Tariff provides information on what will be paid to pharmacy owners for providing NHS Services. This encompasses both reimbursement (i.e. the cost of drugs and appliances supplied against an NHS prescription) and remuneration (i.e. the fees for providing NHS services)."  
> — CPE, "Using The Drug Tariff" (https://cpe.org.uk/dispensing-and-supply/dispensing-process/drug-tariff-resources/virtual-drug-tariff/)

> "Prescription Services produces the Drug Tariff on a monthly basis on behalf of the Department of Health and Social Care. It's supplied primarily to pharmacists"  
> — NHSBSA (https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/drug-tariff)

### 5.2 Drug Tariff Structure (Parts I–VIII and beyond)

**[GUIDANCE]** The Drug Tariff is structured into Parts, each covering different aspects of reimbursement and supply:

| Part | Content |
|------|---------|
| Part I | General information (prescription charges, exemption criteria, items incurring multiple charges) |
| Part II | Services to be provided by pharmacy contractors (NHS services, remuneration) |
| Part III | Professional obligations (dispensing, endorsements, containers, labels) |
| Part IV | Drugs and other substances (restrictions on prescribing certain items) |
| Part V | Appliances (stoma, incontinence, wound management) |
| Part VIA | Prices of drugs for which no discount deduction is made |
| Part VIIA | Drug Tariff prices for generically prescribed drugs, divided into Categories A, C, and M |
| Part VIIB | Prices of drugs not listed in Part VIIIA or Part VIIIB |
| Part VIIIA | Generic drug reimbursement prices (Category M — calculated based on manufacturer prices) |
| Part VIIIB | Selected drugs and appliances with fixed prices |
| Part VIII(A) | Drug Tariff — Category M prices (generic medicines) |
| Part IX | Wound management and elasticated garments |
| Part X | Containers |
| Part XII | Drug Tariff — endorsements |
| Part XVI(A) | HRT PPC medicines list |

**Sources:**
- CPE, "Using The Drug Tariff" (https://cpe.org.uk/dispensing-and-supply/dispensing-process/drug-tariff-resources/virtual-drug-tariff/)
- NHSBSA, "Drug Tariff Part VIII" (https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/drug-tariff/drug-tariff-part-viii)
- Gov.uk consultation response (https://www.gov.uk/government/consultations/community-pharmacy-drug-reimbursement-reform/outcome/community-pharmacy-drug-reimbursement-reform-consultation-response)

**[GUIDANCE]** Category descriptions from CPE:

> "Category A includes popular generics, which are widely available. The Department of Health and Social Care calculates the reimbursement price based on information submitted."

> "Category C products are the products not generally available as a generic."

> "Category M" — the reimbursement price is calculated from information submitted by manufacturers.

### 5.3 Generic vs Brand Prescribing — The "Do Not Switch" List

**[GUIDANCE]** The NHS has a policy of generic prescribing as the default. The Specialist Pharmacy Service (SPS) states:

> "Prescribing medicines by generic name is generally preferred but there are some clinical circumstances when brand-name prescribing is warranted."  
> — SPS, "Prescribing by generic or brand name" (https://www.sps.nhs.uk/articles/prescribing-by-generic-or-brand-name/)

> "The NHS has a policy of prescribing medicines by their generic name unless there is a clinical reason why the medicine must be prescribed by brand."

**[GUIDANCE]** The BNF states:

> "Where non-proprietary ('generic') titles are given, they should be used in prescribing. This will enable any suitable product to be dispensed, thereby saving delay to the patient and sometimes expense to the health service. The only exception is where there is a demonstrable difference in clinical effect between each manufacturer's version of the formulation, making it important that the patient should always receive the same brand; in such cases, the brand name or the manufacturer should be stated."  
> — BNF, "Guidance on prescribing" (https://bnf.nice.org.uk/medicines-guidance/guidance-on-prescribing/)

**[GUIDANCE]** SPS identifies four main situations where brand prescribing is **necessary**:

1. **Bioavailability differences** — where bioavailability differs between brands, particularly narrow therapeutic index drugs
   - Examples: **ciclosporin, lithium, beclometasone pressurised metered dose inhalers, carbamazepine for epilepsy**

2. **Release profile variations** — where modified release (MR) preparations are not interchangeable
   - Examples: **morphine MR** (12-hourly vs 24-hourly), **methylphenidate MR**, **diltiazem MR**, **nifedipine MR**

3. **Specific devices** — when administration devices have different instructions
   - Examples: **adrenaline auto-injectors, dry powder inhalers, insulin injection devices**

4. **Biologics and biosimilars** — MHRA advises biologic medicines should be prescribed by brand name
   - Examples: **insulins, low molecular weight heparins, somatropin, monoclonal antibodies**

**[GUIDANCE]** BNF confirms for biological medicines:

> "Biological medicines must be prescribed by brand name and the brand name specified on the prescription should be dispensed in order to avoid inadvertent switching. Automatic substitution of brands at the point of dispensing is not appropriate for biological medicines."  
> — BNF, "Guidance on prescribing"

**[GUIDANCE]** The MHRA advises on biosimilar products:

> "Biological medicines, including biosimilar medicines, should be prescribed by brand name."  
> — MHRA, Drug Safety Update (https://www.gov.uk/drug-safety-update/biosimilar-products), cited in SPS guidance

**[GUIDANCE]** Additional drugs commonly prescribed by brand name (SPS "Example medicines to prescribe by brand name"):

| Therapeutic area | Examples |
|-----------------|----------|
| Allergy/immunology | Adrenaline (auto-injectors) |
| Anaesthesia/pain | Opioid patches, opioids MR |
| Cardiovascular | Metolazone, diltiazem MR, nifedipine MR, enoxaparin |
| Endocrinology | All insulins |
| Gastrointestinal | Mesalazine |
| Mental health | Lithium, methylphenidate MR |
| Neurology | Antiseizure (antiepileptic) medications |
| Organ transplantation | Ciclosporin, tacrolimus |
| Respiratory | Inhalers, tiotropium |

**Source:** SPS (https://www.sps.nhs.uk/articles/example-medicines-to-prescribe-by-brand-name/)

---

## 6. Prescribing Safely — The Regulatory Framework

### 6.1 GMC "Good Practice in Prescribing and Managing Medicines and Devices"

**[GUIDANCE]** The current GMC guidance is:

> "Good practice in proposing, prescribing, providing and managing medicines and devices" — Published 18 February 2021, came into effect 5 April 2021, updated 15 March 2022, and 13 December 2024.  
> — GMC (https://www.gmc-uk.org/professional-standards/the-professional-standards/good-practice-in-prescribing-and-managing-medicines-and-devices)

**[GUIDANCE]** The previous (2013) version contained specific key requirements that were carried forward:

> "9 You must be familiar with the guidance in the British National Formulary (BNF) and British National Formulary for Children (BNFC), which contain essential information to help you prescribe, monitor, supply, and administer medicines."

> "10 You should follow the advice in the BNF on prescription writing and make sure your prescriptions and orders are clear, in accordance with the relevant statutory requirements and include your name legibly. You should also consider including clinical indications on your prescriptions."

> "16 In providing clinical care you must: a) prescribe drugs or treatment, including repeat prescriptions, only when you have adequate knowledge of the patient's health, and are satisfied that the drugs or treatment serve the patient's needs."

**Source:** GMC archived 2013 version (https://www.gmc-uk.org/-/media/gmc-site/ethical-guidance/good-practice-in-prescribing-and-managing-medicines-and-devices-2013---2021_pdf-85692995.pdf)

The 2021 guidance is structured into sections:
- About this guidance (1–7)
- Keeping up to date and ensuring safe prescribing (7–18)
- Deciding if it is safe to prescribe (19–57) — including mode of consultation, patient information, consent
- Controlled drugs and other medicines where additional safeguards are needed (58–72)
- Prescribing for yourself or those close to you
- Shared care (73–81) — prescribing based on a colleague's recommendation, shared care arrangements
- Raising concerns (82–84)
- Reporting adverse drug reactions (85–91) — Yellow Card scheme
- Reviewing medicines (92–96)
- Repeat prescribing (97–101)
- Prescribing unlicensed medicines (102–108)
- Sports medicine (109)

### 6.2 Non-Medical Prescribing

**[LAW]** The Human Medicines Regulations 2012 (S.I. 2012/1916) provide the legal framework for who may prescribe. Non-medical prescribing has been expanded through a series of legislative amendments.

**[GUIDANCE]** The CQC describes the types of non-medical prescribing:

> "Non-medical prescribers can be either independent or supplementary prescribers. An independent prescriber is able to prescribe, on their own initiative, any medicine within their scope of practice and relevant legislation."  
> — CQC, "GP mythbuster 95: Non-medical prescribing" (https://www.cqc.org.uk/guidance-providers/gps/gp-mythbusters/gp-mythbuster-95-non-medical-prescribing)

**[GUIDANCE]** The RCN describes the main types:

#### Independent Prescribers (IPs)
> "Independent prescribers are nurses or midwives who have completed an NMC-approved prescribing programme (formerly referred to as v300). They may prescribe any medicine, including controlled drugs (Schedules 2–5) and unlicensed medicines provided this is within their scope of competence."  
> — RCN, "Non-medical prescribers" (https://www.rcn.org.uk/Get-Help/RCN-advice/non-medical-prescribers)

The following professions can qualify as **independent prescribers**:

| Profession | Scope of independent prescribing |
|-----------|-------------------------------|
| **Nurses/Midwives** | Any medicine for any condition within competence, including CDs (Schedules 2–5), except diamorphine, dipipanone, or cocaine for treatment of addiction |
| **Pharmacists** | Any medicine for any condition within competence, including CDs (Schedules 2–5), except diamorphine, dipipanone, or cocaine for treatment of addiction |
| **Physiotherapists** | Any licensed medicine within competence; limited range of CDs |
| **Podiatrists/Chiropodists** | Any licensed medicine within competence; limited range of CDs |
| **Paramedics** | Any licensed medicine within competence; limited range of CDs (since Dec 2023) |
| **Optometrists** | Any licensed medicine for ocular conditions; cannot prescribe CDs |
| **Therapeutic Radiographers** | Any licensed medicine within competence; limited range of CDs (since Dec 2023) |

**Sources:**
- RCN (https://www.rcn.org.uk/Get-Help/RCN-advice/non-medical-prescribers)
- NI Department of Health (https://www.health-ni.gov.uk/articles/prescribing-non-medical-healthcare-professionals)
- CQC (https://www.cqc.org.uk/guidance-providers/gps/gp-mythbusters/gp-mythbuster-95-non-medical-prescribing)

#### Supplementary Prescribers (SPs)
> "Supplementary prescribing is a voluntary partnership between the independent prescriber, the supplementary prescriber and the patient."  
> — RCN

> "Supplementary prescribers may prescribe any medicine (including controlled drugs), within the framework of a patient-specific clinical management plan, which has been agreed with a doctor."  
> — NI Department of Health

Supplementary prescribers include: nurses, midwives, pharmacists, physiotherapists, podiatrists, paramedics, radiographers, dietitians, and optometrists.

#### Community Practitioner Nurse Prescribers (CPNP)
> "These are nurses who have completed an NMC approved Community Practitioner Nurse Prescribing qualification (previously known as v100 or v150) and are registered as a CPNP with the NMC. They are permitted to prescribe from the Nurse Prescribers' Formulary for Community Practitioners."  
> — RCN

### 6.3 NICE Medicines Optimisation Guidance (NG5)

**[GUIDANCE]** NICE Clinical Guideline NG5:

> "Medicines optimisation: the safe and effective use of medicines to enable the best possible outcomes" — NICE guideline NG5, published 4 March 2015.  
> — NICE (https://www.nice.org.uk/guidance/NG5)

> "This guideline covers safe and effective use of medicines in health and social care for people taking 1 or more medicines. It aims to ensure that medicines provide the greatest possible benefit to people by encouraging medicines reconciliation, medication review, and the use of patient decision aids."

Key recommendations cover:
- Systems for identifying, reporting and learning from medicines-related patient safety incidents
- Medicines-related communication systems for when patients move between care settings
- **Medicines reconciliation** — when a patient moves from one care setting to another
- **Medication review**
- Self-management plans
- Patient decision aids

> "Medicines optimisation is defined as 'a person-centred approach to safe and effective medicines use, to ensure people obtain the best possible outcomes from their medicines.'"  
> — NICE NG5 (https://www.nice.org.uk/guidance/NG5/chapter/introduction)

**[GUIDANCE]** The Royal Pharmaceutical Society's four guiding principles for medicines optimisation (referenced in NG5):

> 1. Aim to understand the patient's experience
> 2. Evidence based choice of medicines
> 3. Ensure medicines use is as safe as possible
> 4. Make medicines optimisation part of routine practice

> — RPS, "Medicines optimisation: helping patients make the most of medicines" (May 2013)

**[GUIDANCE]** NICE NG5 was reviewed in March 2019 — no update required.

> "We will not update the following guidelines on medicines adherence and medicines optimisation"  
> — NICE 2019 surveillance decision (https://www.ncbi.nlm.nih.gov/books/NBK552083)

### 6.4 MHRA Drug Safety Updates and Black Triangle (▼) Monitoring

**[GUIDANCE]** The MHRA describes the Black Triangle scheme:

> "When medicines come onto the market, we may have relatively limited information about their safety from clinical trials. Therefore, effective surveillance after marketing is essential for the identification of rare adverse effects."  
> — MHRA, "The Black Triangle Scheme (▼ or ▼*)" (https://www.gov.uk/drug-safety-update/the-black-triangle-scheme-or)

> "New medicines are intensively monitored to ensure that any new safety hazards are identified promptly. The Commission on Human Medicines (CHM) and the MHRA encourages the reporting of all suspected reactions to newer drugs and vaccines, which are denoted by an inverted Black Triangle symbol (▼)."

**[GUIDANCE]** A Black Triangle symbol is assigned if the drug meets any of these criteria:
- A new active substance or a biosimilar medicine
- A new combination of medicines or active substances
- A new route of administration
- A new drug-delivery system
- An established medicine which is to be used in a new patient population

> "All similar biological medicines (biosimilars) have a Black Triangle symbol because although any such product has been developed to be similar to an existing biological product, it may not have an identical structure and thereby requires intensive monitoring of safety and efficacy."

The symbol appears in:
- Drug Safety Update
- The BNF and Nurse Prescribers' Formulary (NPF)
- Monthly Index of Medical Specialities (MIMS)
- Electronic Medicines Compendium (emc)
- Advertising material

> "The MHRA assesses the Black Triangle status of a product usually 2 years after marketing; however, there is no standard time for a product to retain Black Triangle status. The symbol is not removed until the safety of the drug is well established."

> "Report ALL suspected adverse reactions to Black Triangle drugs."

The **Yellow Card Scheme** is the mechanism for reporting suspected adverse drug reactions to the MHRA.

> "Drug Safety Update is a monthly newsletter from the MHRA and CHM, and aims to provide information and advice about the safe use of medicines. It is intended for all healthcare professionals who work in the UK."  
> — RDTC (https://rdtc.nhs.uk/yellow-card/mhra-chm-safety-information/)

### 6.5 Off-Label Prescribing Rules in the UK

**[GUIDANCE]** The GMC guidance states:

> "Medicines should usually be prescribed in accordance with the terms of their licence."  
> — GMC (archived 2013 guidance, principle carried forward in 2021 version)

**[GUIDANCE]** The BNF states:

> "Prescribing medicines outside the recommendations of their marketing authorisation alters (and probably increases) the prescriber's professional responsibility and potential liability. The prescriber should be able to justify and feel competent in using such medicines, and also inform the patient or the patient's carer that the prescribed medicine is unlicensed."  
> — BNF, "Guidance on prescribing" (https://bnf.nice.org.uk/medicines-guidance/guidance-on-prescribing/)

> "Where an unlicensed drug is included in BNF, this is indicated in the unlicensed use section of the drug monograph. When BNF suggests a use that is outside the terms defined by the licence ('off-label' use), this too is indicated. Unlicensed or off-label use may be necessary if the clinical need cannot be met by licensed medicines; such use should be supported by appropriate evidence and experience."

**[GUIDANCE]** The GMC 2021 guidance section on "Prescribing unlicensed medicines" (paragraphs 102–108) covers:
- The prescriber must be satisfied that an alternative licensed medicine would not meet the patient's needs
- The prescriber must be satisfied there is sufficient evidence or experience of using the medicine to demonstrate safety and efficacy
- The patient must be informed that the medicine is unlicensed/off-label
- In emergencies or where there is no realistic alternative, it may not be practical to draw attention to the licence status
- Where prescribing is supported by authoritative clinical guidance, it may be sufficient to describe in general terms why the medicine is not licensed

---

## 7. Prescribing Charges and Exemptions

### 7.1 NHS Prescription Charges (Current)

**[LAW]** Prescription charges in England are set under The National Health Service (Charges for Drugs and Appliances) Regulations 2015 (S.I. 2015/570), as amended, made under powers conferred by the NHS Act 2006.

> "From 1 May 2024, the medicine prescription charge in England is £9.90. On 28 April 2025, the government announced it would freeze prescription charges at this cost."  
> — UK Parliament, Commons Library (https://commonslibrary.parliament.uk/constituency-casework-nhs-prescription-charges-in-england/)

**[GUIDANCE]** The NHS website confirms:

> "The current prescription charge is £9.90 per item. Prescription charges are for each item not each prescription. For example, if your prescription has 3 medicines on it you will have to pay the prescription charge 3 times."  
> — NHS (https://www.nhs.uk/nhs-services/prescriptions/nhs-prescription-charges)

> "Some items are always free, including contraception and medicines prescribed for hospital inpatients."

> "Most prescriptions are valid for 6 months from the date they are signed by a doctor or nurse. Prescriptions for most controlled drugs, such as morphine, are valid for 28 days."

**[LAW]** The charge is frozen for 2025/26:

> "For 2025/26, the NHS prescription charge remains at £9.90 per item."  
> — CPE (https://cpe.org.uk/dispensing-and-supply/prescription-processing/receiving-a-prescription/patient-charges/prescription-prepayment-certificates-ppcs)

> "The Department of Health and Social Care has said this means around 89% of NHS prescription items are dispensed in the community free of charge."  
> — UK Parliament, Commons Library

### 7.2 Prescription Prepayment Certificate (PPC)

**[LAW]** The National Health Service (Charges for Drugs and Appliances) (Amendment) Regulations 2024 (S.I. 2024/456) sets PPC costs.

**[GUIDANCE]** NHSBSA confirms:

> "A PPC could save you money if you pay for your NHS prescriptions. The certificate covers all your NHS prescriptions for a set price. You will save money if you need more than 3 items in 3 months, or 11 items in 12 months."  
> — NHSBSA (https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/nhs-prescription-prepayment-certificate-ppc)

| PPC type | Cost | Saves money if you need |
|----------|------|----------------------|
| 3-month standard PPC | £32.05 | 4 or more items in 3 months |
| 12-month standard PPC | £114.50 | 12 or more items in a year |
| 12-month HRT PPC | £19.80 | More than 2 eligible HRT items in 12 months |

> "The HRT PPC covers certain HRT medicines for a set price of £19.80 (the same price as 2 prescribed items) and is valid for 12 months."  
> — NHSBSA

PPCs can be purchased online, by phone (0300 330 1341), or at some pharmacies. 12-month PPCs can be paid in 10 monthly instalments by Direct Debit.

### 7.3 Exemption Categories

**[LAW]** Exemption from NHS prescription charges is governed by the NHS (Charges for Drugs and Appliances) Regulations 2015, as amended.

**[GUIDANCE]** The following categories entitle patients to free NHS prescriptions in England:

#### Age-based exemptions
- Under 16
- 16, 17, or 18 and in full-time education
- 60 or over

#### Pregnancy / maternity
- Pregnant or have had a baby in the previous 12 months, with a valid **maternity exemption certificate** (MatEx)

#### Medical conditions (with valid medical exemption certificate, form FP92A)

The NHSBSA lists the qualifying conditions:

> "You're entitled to a 10-year medical exemption certificate if you have any of these conditions:
> - a permanent fistula (for example, caecostomy, colostomy, laryngostomy or ileostomy) which needs continuous surgical dressing or an appliance
> - a form of hypoadrenalism (for example, Addison's Disease) for which specific substitution therapy is essential
> - diabetes insipidus and other forms of hypopituitarism
> - diabetes mellitus, except where treatment is by diet alone
> - hypoparathyroidism
> - myasthenia gravis
> - myxoedema (that is, hypothyroidism which needs thyroid hormone replacement)
> - epilepsy which needs continuous anticonvulsive therapy
> - a continuing physical disability which means you cannot go out without the help of another person"  
> — NHSBSA (https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/medical-exemption-certificates)

#### Cancer-related treatments
> "You're entitled to a 5-year medical exemption certificate if you're undergoing any treatments for:
> - cancer
> - the effects of cancer
> - the effects of cancer treatment"  
> — NHSBSA (same source)

#### Benefits-based exemptions
Free prescriptions for those receiving:
- Income Support
- Income-based Jobseeker's Allowance
- Income-related Employment and Support Allowance
- Pension Credit Guarantee Credit
- Universal Credit (and meet the criteria)

Also entitled if under 20 and a dependent of someone receiving these benefits.

#### Other exemptions
- Valid **War Pension exemption certificate** (for prescriptions related to accepted disability)
- **HC2 certificate** (full help under the NHS Low Income Scheme)
- **HC3 certificate** (limited help under the NHS Low Income Scheme)
- Prescribed a free-of-charge contraceptive
- Prescribed treatment for a sexually transmitted infection
- Hospital inpatient (medicines administered by hospital staff)

#### Prescription exemption categories on the FP10 form (reverse side boxes):
Patients tick the relevant box on the back of the FP10 and sign the declaration:
- Box A: 60 or over
- Box B: Under 16
- Box C: 16–18 and in full-time education
- Box D: Pregnant / had baby in last 12 months (MatEx)
- Box E: Medical exemption certificate
- Box F: War Pension exemption
- Box G: HC2 certificate (full help)
- Box H: Income Support (note: from April 2026, this box is being removed as benefit transitions to Universal Credit)
- Box K: Income-based Jobseeker's Allowance (also being removed April 2026)
- Box L: Income-related ESA
- Box M: Pension Credit Guarantee Credit
- Box N: Tax credit exemption certificate
- Box P: Universal Credit (meeting criteria)

**[LAW]** Penalty charges for false exemption claims:

> "If a patient claims for a free prescription that they are not entitled to, the NHS Business Services Authority can charge for the treatment retrospectively and can issue a penalty charge. The cost of a penalty charge is either £100 or five times the cost of the treatment (whichever is smaller), in addition to the original charge. Where a person fails to pay the penalty within 28 days, the penalty charge is increased by 50%."  
> — UK Parliament, Commons Library (citing the National Health Service (Penalty Charge) Regulations 1999, S.I. 1999/2794)

### 7.4 Free Prescriptions in Devolved Nations

**[GUIDANCE]** Prescriptions are free of charge in Wales, Scotland, and Northern Ireland.

> "Prescriptions are free of charge in Scotland, Wales and Northern Ireland."  
> — UK Parliament, Commons Library

---

## Appendix A: Summary of Legal Framework

| Legislation/regulation | Citation | Relevance |
|----------------------|----------|-----------|
| Misuse of Drugs Act 1971 | UKPGA 1971 c.38 | Prohibits production/supply/possession of controlled drugs; defines Class A/B/C |
| Misuse of Drugs Regulations 2001 | S.I. 2001/3998 | Defines Schedules 1–5; permits medical use of CDs; prescription requirements |
| Misuse of Drugs (Supply to Addicts) Regulations 1997 | — | Restrictions on prescribing diamorphine/dipipanone/cocaine for addiction |
| Health Act 2006 | UKPGA 2006 c.28 | Introduced accountable officer concept for CDs |
| Controlled Drugs (Supervision of Management and Use) Regulations 2013 | — | CDAO governance requirements (England and Scotland) |
| Human Medicines Regulations 2012 | S.I. 2012/1916 | Legal framework for medicines, including prescribing rights |
| NHS Act 2006 | UKPGA 2006 c.41 | Powers for prescription charges and exemptions |
| NHS (Charges for Drugs and Appliances) Regulations 2015 | S.I. 2015/570 | Sets prescription charges in England |
| NHS (Charges for Drugs and Appliances) (Amendment) Regulations 2024 | S.I. 2024/456 | PPC costs |
| NHS (Penalty Charge) Regulations 1999 | S.I. 1999/2794 | Penalty charges for false exemption claims |
| GMS Contracts (Prescription of Drugs etc.) Regulations 2004 (as amended 2018) | S.I. 2018/1114 | Mandates EPS for eligible prescriptions from November 2019 |

## Appendix B: Key Primary Source URLs

| Source | URL |
|--------|-----|
| BNF (NICE) | https://bnf.nice.org.uk/ |
| BNF Prescription writing | https://bnf.nice.org.uk/medicines-guidance/prescription-writing/ |
| BNF Guidance on prescribing | https://bnf.nice.org.uk/medicines-guidance/guidance-on-prescribing/ |
| BNF Controlled drugs and drug dependence | https://bnf.nice.org.uk/medicines-guidance/controlled-drugs-and-drug-dependence/ |
| BNF Abbreviations and symbols | https://bnf.nice.org.uk/about/abbreviations-and-symbols/ |
| BNF Cautionary and advisory labels | https://bnf.nice.org.uk/about/labels/ |
| BNF Medicines optimisation | https://bnf.nice.org.uk/medicines-guidance/medicines-optimisation/ |
| NICE NG5 | https://www.nice.org.uk/guidance/NG5 |
| GMC Prescribing guidance (2021) | https://www.gmc-uk.org/professional-standards/the-professional-standards/good-practice-in-prescribing-and-managing-medicines-and-devices |
| MHRA Black Triangle | https://www.gov.uk/drug-safety-update/the-black-triangle-scheme-or |
| MHRA Drug Safety Update | https://www.gov.uk/drug-safety-update |
| NHSBSA Prescription forms | https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/prescribing-and-dispensing/prescription-forms |
| NHSBSA Drug Tariff | https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/drug-tariff |
| NHSBSA PPC | https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/nhs-prescription-prepayment-certificate-ppc |
| NHSBSA Medical exemption certificates | https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/medical-exemption-certificates |
| NHS Prescription charges | https://www.nhs.uk/nhs-services/prescriptions/nhs-prescription-charges |
| NHS Digital EPS | https://digital.nhs.uk/services/electronic-prescription-service |
| NHS England EPS guidance | https://www.england.nhs.uk/long-read/electronic-prescription-service-eps/ |
| NHS England Medication safety enduring standards | https://www.england.nhs.uk/patient-safety/patient-safety-insight/patient-safety-alerts/enduring-standards/standards-that-remain-valid/medication-safety/ |
| Misuse of Drugs Regulations 2001 | https://www.legislation.gov.uk/uksi/2001/3998/contents |
| Human Medicines Regulations 2012 | https://www.legislation.gov.uk/uksi/2012/1916/contents/made |
| SPS Prescribing by generic or brand name | https://www.sps.nhs.uk/articles/prescribing-by-generic-or-brand-name/ |
| CPE Drug Tariff guidance | https://cpe.org.uk/dispensing-and-supply/dispensing-process/drug-tariff-resources/virtual-drug-tariff/ |
| CPE Prescription form validity | https://cpe.org.uk/dispensing-and-supply/prescription-processing/receiving-a-prescription/is-this-prescription-form-valid |
| RCN Non-medical prescribers | https://www.rcn.org.uk/Get-Help/RCN-advice/non-medical-prescribers |
| CQC Non-medical prescribing | https://www.cqc.org.uk/guidance-providers/gps/gp-mythbusters/gp-mythbuster-95-non-medical-prescribing |
| UK Parliament: NHS prescription charges in England | https://commonslibrary.parliament.uk/constituency-casework-nhs-prescription-charges-in-england/ |
| Pharmaceutical Press (BNF publications) | https://www.pharmaceuticalpress.com/bnf-and-bnfc/ |
