# UK NHS Prescribing — Notation, Conventions, and Regulatory Framework

The prescribing detail underpinning the SKILL.md. **LAW** (statute/regulation) is distinguished from **GUIDANCE** (BNF/NICE/GMC/MHRA) and **CONVENTION** (established practice).

---

## 1. The FP10 and the Electronic Prescription Service (EPS)

### FP10 — the standard NHS prescription form (England)

**GUIDANCE.** The FP10 is the standard NHS prescription form. Key legal fields (BNF "Prescription writing"):

| Field | Requirement |
|-------|-------------|
| Patient name and address | Must be stated |
| Patient age/date of birth | Age **mandatory** for children under 12 (legal requirement for POMs) |
| Prescriber name and address | Must be stated; address must be within the UK |
| Type of prescriber | Indication of prescriber type |
| Date | Must be dated |
| Signature | Must be **handwritten in ink** (computer-generated facsimile signatures do not meet the legal requirement) |

> "Prescriptions should be written legibly in ink or otherwise so as to be indelible... should be dated, should state the name and address of the patient, the address of the prescriber, an indication of the type of prescriber, and should be signed in ink by the prescriber." — BNF, Prescription writing (https://bnf.nice.org.uk/medicines-guidance/prescription-writing/)

### FP10 variants

| Code | Colour | Issued by |
|------|--------|-----------|
| FP10 / FP10SS / FP10HNC | **Green** | GPs, nurse/AHP/pharmacist prescribers, hospital doctors (outpatient) |
| FP10MDA | **Blue** | Prescribers managing substance misuse (instalment dispensing) |
| FP10SP / FP10PN | **Lilac** | Community/independent nurse and AHP prescribers |
| FP10D | **Yellow** | Dentists |
| FP10PCD | — | Private prescribers for Schedule 2/3 Controlled Drugs |

### EPS

**GUIDANCE.** EPS sends prescriptions electronically to a patient-nominated dispenser. Over 95% of prescriptions in England are now electronic. Since November 2019 it has been a **requirement** for all eligible prescriptions from general practice (S.I. 2018/1114).

**LAW.** Advanced electronic signatures can be accepted for Schedule 2 and 3 Controlled Drug prescriptions where EPS is used.

The prescriber records the same clinical information as on a paper FP10. Related services: Care Identity Service (authentication), Signing Service (electronic signatures), Real-Time Exemption Checking (RTEC).

### Repeat dispensing

**GUIDANCE.** For stable long-term conditions, the clinical review date (set by the prescriber) should not exceed 12 months. Electronic Repeat Dispensing (eRD) authorises multiple supplies at set intervals from a single electronic prescription (valid up to 12 months). Quantity per repeat should generally not exceed 28/30/56/60 days.

---

## 2. Prescription Notation — How a UK Prescription Item Is Written

**GUIDANCE (BNF "Prescription writing").** The structure of a prescription item:

1. **Drug name** — approved (non-proprietary) title, written in full, not abbreviated
2. **Form** — e.g. tablets, capsules, oral solution
3. **Strength** — e.g. 125 mg/5 mL (liquid strengths must be clearly stated)
4. **Quantity to be supplied** — number of days or exact amount
5. **Dose and frequency** — e.g. "40 mg four times daily"
6. **Route** — where appropriate

### Safe dose expression (BNF)

| Convention | Rule |
|-----------|------|
| ≥ 1 g | Write "1 g", "1.5 g" etc. |
| < 1 g | Write in milligrams — "500 mg", not "0.5 g" |
| < 1 mg | Write in micrograms — "100 micrograms", not "0.1 mg" |
| Micrograms / nanograms | **Never abbreviated** — write in full |
| Units (e.g. insulin) | **Never abbreviated** — write "units" in full |
| Volume | Use "mL" or "ml"; never "c.c." or "cm³" |
| Decimals | Avoid where possible; if used, always leading zero (0.5 mL not .5 mL); never trailing zero (3 mg not 3.0 mg) |
| "As directed" / "when required" | Specify a **minimum dose interval**; for "as directed", specify the maximum daily dose |
| Liquid doses | State in terms of mass of active drug ("125 mg 3 times daily") not volume ("5 mL"), except for compound preparations |

---

## 3. Latin Abbreviations in UK Prescribing

**GUIDANCE (BNF "Abbreviations and Symbols").** The BNF states directions should preferably be in **English without abbreviation**, but recognises some Latin abbreviations:

| Abbreviation | Latin | English meaning |
|-------------|-------|-----------------|
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

**CONVENTION** — abbreviations commonly used in UK prescribing (not all in the BNF Latin list):

| Abbreviation | Meaning | Caution |
|-------------|---------|---------|
| OD | once daily | "OD" can mean right eye (oculus dexter) — avoid |
| BD | twice daily | |
| TDS | three times daily | |
| QDS | four times daily | |
| PRN | when required | |
| PO | by mouth (per os) | |
| IV | intravenous | BNF: i/v |
| IM | intramuscular | BNF: i/m |
| SC | subcutaneous | |
| NG | nasogastric | |
| PR | per rectum | |
| PV | per vaginam | |
| SL | sublingual | |
| TOP | topical | |
| mane | in the morning | BNF: o.m. |
| nocte | at night | BNF: o.n. |

---

## 4. "Do Not Use" Abbreviations — NPSA / NHS England Enduring Standards

**GUIDANCE.** The NPSA Patient Safety Alerts (now maintained as NHS England enduring standards) and BNF prohibit:

| Do not use | Use instead | Reason |
|-----------|-------------|--------|
| U or IU | units | "U" mistaken for "0"; "IU" confused with "IV" |
| μg or mcg | micrograms | misread as "mg" (1000× error) |
| ng (abbreviated) | nanograms | write in full |
| OD (for once daily) | once daily | "OD" = right eye (oculus dexter) |
| c.c. or cm³ | mL | should not be used in medicine |
| 3.0 mg | 3 mg | trailing zero misread as 30 |
| .5 mL | 0.5 mL | always include a leading zero |
| MS | morphine sulfate / magnesium sulfate | ambiguous |
| MgSO4 / MSO4 | write in full | ambiguous |
| QD, QOD | daily / every other day | confused with QDS |

**Enduring standards (NHS England):** "units" must be used for insulin in all contexts (never U/IU). Methotrexate must be prescribed **once weekly**. Valproate requires a pregnancy prevention programme. The "units" rule extends to heparin and other medicines.

---

## 5. The BNF (British National Formulary)

**GUIDANCE.** The BNF is the authoritative UK prescribing reference.

- Published jointly by **BMJ Publishing Group Ltd** and **Pharmaceutical Press** (the Royal Pharmaceutical Society's knowledge business)
- Available free via NICE at https://bnf.nice.org.uk/
- Print published biannually (March and September)
- The **BNFC** (BNF for Children) published annually by BMJ Group, Pharmaceutical Press, RCPCH, and NPPG
- Organised by body system (chapters 1–15: GI, cardiovascular, respiratory, CNS, infections, endocrine, obstetrics/gynaecology/urinary, malignant disease/immunosuppression, nutrition and blood, musculoskeletal, eye, ear/nose/oropharynx, skin, immunological products and vaccines, anaesthesia)

Each drug monograph describes: uses (indications), doses, cautions, contra-indications, side-effects, medicinal forms, and other considerations. Unlicensed or off-label use is indicated within the monograph.

### BNF cautionary and advisory labels

The BNF includes numbered cautionary/advisory labels the dispenser applies to dispensed medicines. Examples:

| Label | Wording |
|-------|---------|
| 1 | Warning: This medicine may make you sleepy |
| 4 | Warning: Do not drink alcohol |
| 8 | Warning: Do not stop taking this medicine unless your doctor tells you to stop |
| 9 | Space the doses evenly throughout the day. Keep taking this medicine until the course is finished |
| 21 | Take with or just after food, or a meal |
| 25 | Swallow this medicine whole. Do not chew or crush |
| 30 | Contains paracetamol. Do not take anything else containing paracetamol while taking this medicine |

Full list: https://bnf.nice.org.uk/about/labels/

---

## 6. Controlled Drugs (CDs)

### Misuse of Drugs Act 1971 and Misuse of Drugs Regulations 2001

**LAW.** The Misuse of Drugs Act 1971 prohibits production, supply, and possession of controlled drugs. The Misuse of Drugs Regulations 2001 (S.I. 2001/3998) provide exceptions for medical, dental, and veterinary use, dividing CDs into **five Schedules**:

| Schedule | Description | Examples | Key requirements |
|----------|-------------|----------|-----------------|
| **1** | Not used medicinally; hallucinogenic | LSD, ecstasy, raw opium, cannabis (non-medicinal) | Home Office licence; CD register |
| **2** | Opiates, major stimulants, cocaine, ketamine | Morphine, diamorphine, methadone, oxycodone, fentanyl, amfetamines, cocaine, ketamine, methylphenidate | Full CD requirements: prescription, safe custody (CD cabinet), CD register; **28-day validity** |
| **3** | Barbiturates (excl. secobarbital), buprenorphine, gabapentin, midazolam, pregabalin, temazepam, tramadol | Buprenorphine, temazepam, midazolam, pregabalin, gabapentin, tramadol | Special prescription requirements; safe custody for some; invoice retention 2 years; **28-day validity** |
| **4 Part I** | Benzodiazepines (excl. temazepam/midazolam), non-benzodiazepine hypnotics | Diazepam, lorazepam, zopiclone, zolpidem | Minimal control; no CD prescription requirements; no register (except Sativex) |
| **4 Part II** | Androgenic and anabolic steroids, growth hormones | Testosterone, nandrolone, somatropin | Minimal control; not illegal to possess; illegal to supply |
| **5** | Low-CD-content preparations | Codeine, pholcodine, low-strength morphine preparations | Virtually no CD requirements; invoice retention 2 years; **6-month validity** |

**Drug Classes** (Misuse of Drugs Act 1971, by harmfulness):
- **Class A:** alfentanil, cocaine, diamorphine (heroin), fentanyl, LSD, methadone, morphine, oxycodone, MDMA; Class B substances prepared for injection
- **Class B:** amfetamines (oral), barbiturates, cannabis, codeine, dihydrocodeine, ketamine, pholcodine
- **Class C:** benzodiazepines, buprenorphine, tramadol, gabapentin, pregabalin, zopiclone, zolpidem, anabolic steroids, nitrous oxide

### FP10 for CDs — extra requirements (Schedules 2 and 3)

**LAW.** Prescriptions for Schedule 2 and 3 CDs must meet additional legal requirements:

- Indelible, signed by the prescriber, dated, prescriber address within the UK
- The **form** (dosage form — e.g. "tablets" must be stated even if implicit in the brand name)
- The **strength** (when more than one strength exists)
- For liquids: total volume in millilitres **in both words and figures**
- For dosage units (tablets, capsules, ampoules): total number **in both words and figures**
- The **dose** must be clearly defined ("one as directed" constitutes a dose; "as directed" does not)
- "for dental treatment only" if issued by a dentist

> "A pharmacist is not allowed to dispense a Controlled Drug unless all the information required by law is given on the prescription." — BNF

**Validity:** Schedule 2/3/4 CD prescriptions are valid for **28 days**. Schedule 5 for **6 months**.

**Maximum quantity:** should not exceed 30 days; if longer is justified, record the reasons in the patient's notes.

### Instalment prescribing (FP10MDA)

**LAW.** The blue FP10MDA is used for instalment dispensing (primarily opioid substitution therapy). Must state dose and instalment amount separately, and the interval between each supply. First instalment dispensed no later than 28 days after the appropriate day.

Only Schedule 4 and 5 CDs are permitted on repeatable prescriptions.

### Controlled Drugs Accountable Officer (CDAO)

**LAW.** The Health Act 2006 introduced the accountable officer concept; the Controlled Drugs (Supervision of Management and Use) Regulations 2013 set out the CDAO governance requirements (England and Scotland). The CDAO monitors CD use, ensures governance, investigates concerns, and reports to NHS England.

---

## 7. Drug Tariff

**GUIDANCE.** The Drug Tariff is produced **monthly** by the NHSBSA for the Secretary of State. It sets reimbursement (cost of drugs/appliances supplied against NHS prescriptions) and remuneration (fees for NHS services).

### Structure

| Part | Content |
|------|---------|
| I | General information (charges, exemptions) |
| II | Services by pharmacy contractors |
| III | Professional obligations (dispensing, endorsements, containers, labels) |
| IV | Drugs and other substances (restrictions on prescribing) |
| V | Appliances (stoma, incontinence, wound management) |
| VIA | Prices of drugs with no discount deduction |
| VIIA | Generic drug prices — Categories A, C, M |
| VIIIA | Generic drug reimbursement prices (Category M) |
| VIIIB | Selected drugs/appliances with fixed prices |
| IX | Wound management and elasticated garments |

**Category A:** popular generics, widely available. **Category C:** products not generally available as a generic. **Category M:** reimbursement price calculated from manufacturer-submitted information.

---

## 8. Generic vs Brand Prescribing — the "Do Not Switch" List

**GUIDANCE.** Generic prescribing is the NHS default. Brand prescribing is required where there is a demonstrable difference in clinical effect between manufacturers' versions.

> "Where non-proprietary ('generic') titles are given, they should be used in prescribing... The only exception is where there is a demonstrable difference in clinical effect between each manufacturer's version of the formulation." — BNF, Guidance on prescribing

### Brand prescribing required (SPS / MHRA guidance)

| Reason | Examples |
|--------|----------|
| **Bioavailability differences** (narrow therapeutic index) | ciclosporin, lithium, carbamazepine (for epilepsy), beclometasone MDI |
| **Release profile variations** (MR not interchangeable) | morphine MR, methylphenidate MR, diltiazem MR, nifedipine MR |
| **Specific devices** | adrenaline auto-injectors, dry powder inhalers, insulin injection devices |
| **Biologics and biosimilars** (MHRA: prescribe by brand) | all insulins, low molecular weight heparins, somatropin, monoclonal antibodies |
| **Other** | mesalazine, metolazone, tiotropium, antiepileptics generally |

> "Biological medicines must be prescribed by brand name... Automatic substitution of brands at the point of dispensing is not appropriate for biological medicines." — BNF

---

## 9. GMC Prescribing Guidance (2021, updated 2024)

**GUIDANCE.** "Good practice in proposing, prescribing, providing and managing medicines and devices" — in effect 5 April 2021, updated 13 December 2024.

Key requirements (carried forward from 2013 version):
- Be familiar with the BNF and BNFC
- Follow BNF advice on prescription writing; ensure prescriptions are clear and include your name legibly; consider including clinical indications
- Prescribe only with adequate knowledge of the patient's health and when the treatment serves the patient's needs
- Sections cover: keeping up to date (7–18), deciding if safe to prescribe (19–57), controlled drugs (58–72), shared care (73–81), adverse drug reactions / Yellow Card (85–91), reviewing medicines (92–96), repeat prescribing (97–101), unlicensed medicines (102–108)

### Off-label prescribing

**GUIDANCE.** "Medicines should usually be prescribed in accordance with the terms of their licence." Prescribing outside the licence increases professional responsibility and potential liability. The prescriber must:
- Be satisfied that an alternative licensed medicine would not meet the patient's needs
- Be satisfied there is sufficient evidence/experience to demonstrate safety and efficacy
- Inform the patient that the medicine is unlicensed/off-label
- Record the indication, justification, and consent

---

## 10. Non-Medical Prescribing

**LAW.** The Human Medicines Regulations 2012 (S.I. 2012/1916) provides the legal framework for who may prescribe.

| Profession | Independent prescribing scope |
|-----------|------------------------------|
| **Nurses / Midwives** | Any medicine, including CDs (Schedules 2–5), except diamorphine, dipipanone, or cocaine for addiction |
| **Pharmacists** | Any medicine, including CDs (Schedules 2–5), except diamorphine, dipipanone, or cocaine for addiction |
| **Physiotherapists** | Any licensed medicine within competence; limited range of CDs |
| **Podiatrists** | Any licensed medicine within competence; limited range of CDs |
| **Paramedics** | Any licensed medicine within competence; limited range of CDs (since Dec 2023) |
| **Optometrists** | Any licensed medicine for ocular conditions; cannot prescribe CDs |
| **Therapeutic Radiographers** | Any licensed medicine within competence; limited range of CDs (since Dec 2023) |

**Supplementary prescribers** (nurses, midwives, pharmacists, physiotherapists, podiatrists, paramedics, radiographers, dietitians, optometrists) may prescribe any medicine (including CDs) within a patient-specific **clinical management plan** agreed with a doctor.

---

## 11. NICE Medicines Optimisation (NG5) and MHRA Monitoring

### NICE NG5 (March 2015)

**GUIDANCE.** "Medicines optimisation: the safe and effective use of medicines to enable the best possible outcomes" — https://www.nice.org.uk/guidance/NG5

Key recommendations: medicines reconciliation when patients move between care settings; medication review; communication systems across care settings; patient decision aids; systems for reporting medicines-related safety incidents.

RPS four principles of medicines optimisation:
1. Understand the patient's experience
2. Evidence-based choice of medicines
3. Ensure medicines use is as safe as possible
4. Make medicines optimisation part of routine practice

### MHRA Black Triangle (▼) and Yellow Card

**GUIDANCE.** New medicines are intensively monitored. The Black Triangle symbol (▼) is assigned to: new active substances; biosimilars; new combinations; new routes of administration; new drug-delivery systems; established medicines in new patient populations.

- **Report ALL suspected adverse reactions** to Black Triangle drugs via the **Yellow Card Scheme**
- Symbol appears in: BNF, MIMS, emc, Drug Safety Update, advertising
- MHRA assesses status usually 2 years post-marketing; not removed until safety is well established

Drug Safety Update is the MHRA/CHM monthly newsletter for UK healthcare professionals.

---

## 12. Prescription Charges and Exemptions

### Charges (England, 2025/26)

**LAW.** Set under the NHS (Charges for Drugs and Appliances) Regulations 2015 (S.I. 2015/570), as amended. Frozen for 2025/26.

| Item | Cost |
|------|------|
| Prescription charge per item | £9.90 |
| 3-month PPC | £32.05 |
| 12-month PPC | £114.50 |
| 12-month HRT PPC | £19.80 |

~89% of NHS prescription items are dispensed free of charge. Prescriptions are **free** in Wales, Scotland, and Northern Ireland.

### Exemption categories

**Age:** under 16; 16–18 in full-time education; 60 or over.

**Pregnancy/maternity:** pregnant or had baby in previous 12 months (MatEx certificate).

**Medical conditions (10-year FP92A certificate):**
- permanent fistula requiring continuous surgical dressing or appliance
- hypoadrenalism (e.g. Addison's Disease) requiring substitution therapy
- diabetes insipidus and other forms of hypopituitarism
- diabetes mellitus (except diet-treated)
- hypoparathyroidism
- myasthenia gravis
- myxoedema (hypothyroidism needing thyroid hormone replacement)
- epilepsy needing continuous anticonvulsive therapy
- continuing physical disability preventing going out without help

**Cancer treatment (5-year certificate):** cancer, effects of cancer, effects of cancer treatment.

**Benefits-based:** Income Support; income-based JSA; income-related ESA; Pension Credit Guarantee Credit; Universal Credit (meeting criteria).

**Other:** War Pension exemption; HC2 (full help, NHS Low Income Scheme); HC3 (limited help); free contraception; STI treatment; hospital inpatient.

**LAW.** False exemption claims incur a penalty charge: the greater of £100 or five times the treatment cost, plus the original charge; increases by 50% if unpaid after 28 days (NHS (Penalty Charge) Regulations 1999, S.I. 1999/2794).

---

## Summary of Legal Framework

| Legislation / regulation | Citation |
|--------------------------|---------|
| Misuse of Drugs Act 1971 | UKPGA 1971 c.38 — Classes A/B/C |
| Misuse of Drugs Regulations 2001 | S.I. 2001/3998 — Schedules 1–5 |
| Misuse of Drugs (Supply to Addicts) Regulations 1997 | — diamorphine/dipipanone/cocaine for addiction |
| Health Act 2006 | UKPGA 2006 c.28 — accountable officer |
| Controlled Drugs (Supervision of Management and Use) Regulations 2013 | — CDAO governance |
| Human Medicines Regulations 2012 | S.I. 2012/1916 — prescribing rights |
| NHS Act 2006 | UKPGA 2006 c.41 — charges and exemptions |
| NHS (Charges for Drugs and Appliances) Regulations 2015 | S.I. 2015/570 — prescription charges |
| NHS (Charges for Drugs and Appliances) (Amendment) Regulations 2024 | S.I. 2024/456 — PPC costs |
| NHS (Penalty Charge) Regulations 1999 | S.I. 1999/2794 — false exemption penalties |
| GMS Contracts (Prescription of Drugs etc.) Regs 2004 (as amended 2018) | S.I. 2018/1114 — mandates EPS |

## Key Source URLs

| Source | URL |
|--------|-----|
| BNF (NICE) | https://bnf.nice.org.uk/ |
| BNF Prescription writing | https://bnf.nice.org.uk/medicines-guidance/prescription-writing/ |
| BNF Guidance on prescribing | https://bnf.nice.org.uk/medicines-guidance/guidance-on-prescribing/ |
| BNF Controlled drugs and drug dependence | https://bnf.nice.org.uk/medicines-guidance/controlled-drugs-and-drug-dependence/ |
| BNF Abbreviations and symbols | https://bnf.nice.org.uk/about/abbreviations-and-symbols/ |
| BNF Cautionary and advisory labels | https://bnf.nice.org.uk/about/labels/ |
| NICE NG5 | https://www.nice.org.uk/guidance/NG5 |
| GMC Prescribing guidance (2021) | https://www.gmc-uk.org/professional-standards/the-professional-standards/good-practice-in-prescribing-and-managing-medicines-and-devices |
| MHRA Black Triangle | https://www.gov.uk/drug-safety-update/the-black-triangle-scheme-or |
| NHS England Medication safety enduring standards | https://www.england.nhs.uk/patient-safety/patient-safety-insight/patient-safety-alerts/enduring-standards/standards-that-remain-valid/medication-safety/ |
| SPS Prescribing by generic or brand name | https://www.sps.nhs.uk/articles/prescribing-by-generic-or-brand-name/ |
| NHSBSA Prescription forms | https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/prescribing-and-dispensing/prescription-forms |
| NHSBSA Drug Tariff | https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/drug-tariff |
| NHSBSA PPC | https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/nhs-prescription-prepayment-certificate-ppc |
| NHSBSA Medical exemption certificates | https://www.nhsbsa.nhs.uk/help-nhs-prescription-costs/medical-exemption-certificates |
| Misuse of Drugs Regulations 2001 | https://www.legislation.gov.uk/uksi/2001/3998/contents |
| Human Medicines Regulations 2012 | https://www.legislation.gov.uk/uksi/2012/1916/contents/made |
