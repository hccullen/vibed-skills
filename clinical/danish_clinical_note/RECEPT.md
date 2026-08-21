# Prescription and Pharmacy Reference

Reference for the `danish-clinical-note` skill. Sourced from:

- **Forordningslære** (Klinisk Farmakologisk Afdeling, Aarhus Universitetshospital, September 2021)
- **Bekendtgørelse om recepter og dosisdispensering af lægemidler** (Receptbekendtgørelsen, 12/06/2020)
- **Vejledning om ordination og håndtering af lægemidler** (12/02/2015)
- **Vejledning om ordination af afhængighedsskabende lægemidler** (19/06/2019)

## Receptformer

- **Elektroniske recepter:** Standard. Udstedes via FMK. A§4-præparater and magistrelle ordinationer must be electronic (with few exceptions).
- **Papirrecept:** Only in særlige tilfælde. Cannot genudleveres.
- **Telefaxrecept:** Must use traditional receptblanket, mærket "Telefaxrecept", cannot genudleveres.
- **Telefonrecept:** Only when særlige forhold taler for it. Must be indtelefoneret by the læge personally (cannot be delegated). Lægens CPR-nummer must be oplyst. Cannot genudleveres. Apoteket keeps a copy for 3 months.

## Traditional Recept Structure

```
[Påtrykte udstederdata incl. tlf.nr.]
[Ydernummer/afdelingskode, autorisations-id]
[Patientens navn]
[Adresse]
[CPR-nr.]
[Dato]

#
Rp. [lægemiddelform] [handelsnavn] [styrke]
No.: [mængde]
d.s.: [brugsanvisning/dosering og indikation]
[Tilskud?] [Ej S?] [Trafikfarlig Δ?]
[Udleveres X gange med Y interval — kun elektronisk]

[Håndskreven underskrift]
```

## Elements of the Recept

| Element | Danish | Meaning |
|---|---|---|
| Invocatio | # | Double-cross, marks start. Traditional. |
| Rp. | Recipe | "Tag" — instruction to pharmacist. R., Rec. also used. |
| Ordinatio | | The drug. For specialiteter: brand name (e.g. Furix®), not generic alone. Add firma name if ambiguous. Form before name (*tabl. Furix 70 mg*) or after (*Furix tabletter*). Styrke if multiple strengths. |
| No. | Numero | Quantity to dispense (*100 stk.*) |
| d.s. | Detur signatura | "Udlever med påskriften" — brugsanvisning in letforståeligt dansk, printed on medicinpakke. Must include: dosering (enkeltdosis + døgndosis), indikation, administration where relevant. |
| Ej S | Ej substitution | Pharmacy cannot substitute to cheapest equivalent. Patient pays price difference. |
| Tilskud | | Write under d.s. when patient qualifies for klausuleret tilskud. |
| Trafikfarlig Δ | | If the medicine can affect driving ability. |
| IMM | In Manus Medicus | When prescribing to oneself: "Til eget brug" or "IMM". |

## Brugsanvisning (d.s.)

Must be in **letforståeligt dansk** (for the patient). Must contain:
- Dosering: both enkeltdosis (per gang) and døgndosis (per day, or other time unit)
- Indikation: what disease/symptom the medicine is for
- Administration: how to use it (*indåndes*, *påsmøres*, *opløses i vand*, *indtages med måltid*) where relevant

If very long, the læge may give it to the patient directly and write *"Dosering efter skriftlig anvisning"* on the recept.

## Special Rules

- **Afgivende afvigelser:** When dosis, antal, indikation, styrke, administrationsmåde deviate from usual practice, the læge must either underline the deviation or write values in both numbers and words to show it is intentional.
- **Off-label:** Use outside the approved produktresumé. Patient must be informed thoroughly. Lægen must journalføre indikation, begrundelse for off-label, and informerede samtykke.
- **Magistrelle:** Lægen determines the sammensætning (active + hjælpestoffer, mængder, form). Must be electronic (from 1 April 2018). Skærpet informationspligt and indberetningspligt for bivirkninger.
- **Recept gyldighed:** Max 2 år. Can be shortened by the læge. Papirrecept: one use only. Gruppe B elektronisk: can genudleveres if anført.

## Lægemiddelformer — Abbreviations

| Lægemiddelform | Forkortelse |
|---|---|
| Ampuller | amp. |
| Aqua (vand) | aq. |
| Kapsler | caps. |
| Creme | cr. |
| Opløsning | dil. |
| Dråber | dr. |
| Emulsion | emuls. |
| Ekstrakt | extr. |
| Granulat | gran. |
| Implantat | implant. |
| Infusionsvæske | infund. |
| Injektion | inj. |
| Lagenulae (hætteglas) | lag. |
| Liniment | lin. |
| Mikstur | mixt. |
| Pasta | past. |
| Pulver | pulv. |
| Resoribletter | resoribl. |
| Suppositorier (stikpiller) | supp. |
| Tabletter | tabl. |
| Tinktur | tinct. |
| Salve (unguentum) | ung. |
| Vaccine | vacc. |
| Vagitorier | vagit. |

## Andre recept-forkortelser

| Udtryk | Forkortelse |
|---|---|
| Detur (udleveres) | d. |
| In Manus Medicus (i lægens hænder) | IMM |
| Misce (bland) | m. |
| Numero (antal) | No |
| Recipe (tag) | Rp. |
| Reiteretur (kan genudleveres) | reit. |
| Signatura (mærkes med brugsanvisningen) | s. |

## Udleveringsgrupper

| Gruppe | Regler | Eksempel |
|---|---|---|
| A§4 | Kun elektronisk. Udleveres én gang. Særlig overvågning. | Morfinpræparater |
| A | Udleveres én gang. (Kan udleveres i mindre portioner.) | Methotrexat |
| B | Papir/telefon/fax: én gang. Elektronisk: kan genudleveres. | Centyl m. kaliumklorid |
| BEGR | Kun sygehuse. | Infliximab |
| NB-S | Kun sygehuse/speciallæger. | Acitretin, ketamin |
| GH | Medicinske gasser i håndkøb. | Lattergas |
| HA | Håndkøb, apoteksforbeholdt. | Kaleorid |
| HF | Håndkøb, frihandel. | Magnesia |
| HX | Håndkøb, ikke apoteksforbeholdt. Én pakke/dag. | Ibuprofen |
| HA18/HX18 | Håndkøb, aldersgrænse 18 år. | Paracetamol |

## FMK — Det Fælles Medicinkort

FMK is a samlet elektronisk oversigt over each citizen's medicinordinationer, recepter, and registered vacciner. Integrated into EPJ systems.

Contains:
- Detailed information about all ordinationer, vaccinationer, and købt medicin
- Patient's praktiserende læge
- Which læge ordinerede each medicine
- Complete overview of elektroniske recepter + papir/fax/telefon recepter (last 2 years)
- Medicine purchased on recept at apoteket (last 2 years)
- Medicintilskud information
- Interaktionskontrol (in some EPJ systems)
- Lægemiddel-cave (intolerances)
- Access log

### Ajourføring

FMK must be ajourført:
- At all contacts where changes are made (including ambulante besøg on sygehuse)
- At henvisning from praktiserende læge to indlæggelse/sygehusafdeling/other læge
- At udskrivning from sygehus

An ajourføring marks that FMK reflects the medicin the patient currently takes. It is not a medicingennemgang, but a markering of current medicin + a tilkendegivelse that there are no åbenlyse fejl.

## Afhængighedsskabende Lægemidler

Four groups:
1. Morfin and morfinlignende (opioide analgetika)
2. Benzodiazepiner and benzodiazepinreceptor-acting substances
3. Centralstimulerende midler with narrow indication
4. Visse andre with afhængigheds-/misbrugspotentiale

### Key Rules

- Before starting treatment: lay a **behandlingsplan** with the patient (effect, bivirkninger, expected duration)
- Ordination and fornyelse: **personligt fremmøde** — cannot be renewed by phone, email, or via sekretær
- Do not prescribe to other than sædvanlige patienter unless nødvendiggjort — then only enough to reach egen læge
- Must inform patient's sædvanlige læge (can be done without samtykke — lægen acts as stedfortræder)
- Must assess kørekort fitness — if not betryggende, kørselsforbud; if patient won't comply, contact Tilsyn og Rådgivning
- Tilsyn: jævnlig kontrol of A§4 ordinationer and benzodiazepiner; stikprøvekontrol based on apotek/Lægemiddelstyrelsen data

## Medicintilskudsregler

### Generelle Tilskud

1. **Alment tilskud:** Automatic, regardless of indication. Marked ● on pro.medicin.dk.
2. **Klausuleret tilskud (receptpligtig):** For specific diseases/groups. Lægen writes "Tilskud" on recepten (or confirms in electronic module). Marked ⊕.
3. **Klausuleret tilskud (håndkøb):** For pensionister or specific diseases. Lægen writes "Tilskud". Marked ■.
4. **Medicinsk cannabis:** Særligt tilskud. Marked *.

### Individuelle Tilskud

Must be sought by a læge via fmk-online.dk:

1. **Enkelttilskud:** For medicine not otherwise tilskudsberettiget, when of særlig behandlingsmæssig betydning and other treatments insufficient. Can be retroactive (max 180 days), tidsbegrænset or livslang.
2. **Forhøjet tilskud:** When patient cannot tolerate the cheapest medicine in a substitutionsgruppe. Livslang. Must seek for each pakningsstørrelse og styrke.
3. **Terminaltilskud:** 100% tilskud for dying patients choosing hjemme/hospice. Lægen signs a terminalerklæring. Covers all præparater in a substitutionsgruppe + ikke-receptpligtig medicin on recept.

### Substitution

Apoteket must udlevere the cheapest synonym. Exceptions:
- Lægen wrote "Ej S" — patient pays price difference
- Patient requests different præparat — patient pays difference
- Price difference under bagatelgrænse — apoteket may choose
