---
# MIOP terms
methodology_category: omics analysis
project: "US Geological Survey Mesophotic and Deep Benthic Communities (MDBC) Protocols"
purpose: PCR [OBI:0000415]
analyses: PCR [OBI:0000415]
geographic_location: Atlantic Ocean [GAZ:00000344], Gulf of Mexico [GAZ:00002853]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149], polymerase chain reaction [OBI:0000415]
target: 18S [NCIT:C48172]
creator: Luke Thompson
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], agarose gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 240
personnel_required: 1
language: en
issued: 2024-08-22
audience: scientists
publisher: NOAA Atlantic Oceanographic and Meteorological Laboratory
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
thermocycler: Eppendorf Mastercycler Nexus Thermal Cycler
amplificationReactionVolume: 13.25
assay_name: ssu18sv9
assay_validation: not provided
targetTaxonomicAssay: 18S rRNA gene sequencing targeting the V9 region using primers 1391F and EukBr
targetTaxonomicScope: Eukaryotes, with a focus on microbial eukaryotic lineages
target_gene: 18S rRNA
target_subfragment: V9
ampliconSize: 127
pcr_primer_forward: GTACACACCGCCCGTC
pcr_primer_reverse: TGATCCTTCTGCAGGTTCACCTAC
pcr_primer_name_forward: 1391F
pcr_primer_name_reverse: EukBr
pcr_primer_reference_forward: 10.1371/journal.pone.0006372
pcr_primer_reference_reverse: 10.1371/journal.pone.0006372
pcr_primer_vol_forward: 2.5
pcr_primer_vol_reverse: 2.5
pcr_primer_conc_forward: 1.0
pcr_primer_conc_reverse: 1.0
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: Kapa HiFi HotStart ReadyMix
custom_mm: PCR reactions were run in 13.25 uL reaction volumes, with 2.0 uL of DNA, 6.25 uL of Kapa HiFi HotStart ReadyMix, and 2.5 uL of each primer (1 uM).
pcr_dna_vol: 2.0
pcr_rep: 1
nucl_acid_amp: not provided
pcr_cond: initial denaturation:95_3;denaturation:95_0.5;annealing:63_0.5;elongation:72_0.5;final elongation:72_5;30
annealingTemp: 63
pcr_cycles: 30
pcr_analysis_software: not provided
pcr_method_additional: not provided
barcoding_pcr_appr: two-step PCR
pcr2_thermocycler: not provided
pcr2_amplificationReactionVolume: 50
pcr2_commercial_mm: 2x KAPA HiFi HotStart Ready Mix
pcr2_custom_mm: not applicable
pcr2_dna_vol: 20
pcr2_cond: initial denaturation:95_3;denaturation:95_0.5;annealing:55_0.5;elongation:72_0.5;final elongation:72_5;8
pcr2_annealingTemp: 55
pcr2_cycles: 8
pcr2_analysis_software: not applicable
pcr2_method_additional: not applicable
sequencing_location: University of Oregon's Genomics and Cell Characterization Core Facility (GC3F)
platform: ILLUMINA
instrument: Illumina NovaSeq 6000 SP [OBI:0002630]
seq_kit: missing
lib_layout: paired
adapter_forward: TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG
adapter_reverse: GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG
lib_screen: not provided
lib_conc_meth: not provided
seq_method_additional: not applicable
---

# USGS/MDBC PCR Protocol 18S rRNA V9 (Lane-Medlin)

***WARNING: DETAILS BELOW HAVE NOT BEEN UPDATED. PLEASE USE ABOVE VALUES IN YAML FRONT MATTER.***

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Cassia Busch | USGS/MDBC | <https://orcid.org/xxxx> | 2024-08-22 |
| Kara Jones | USGS/MDBC | <https://orcid.org/xxxx> | 2024-08-22 |
| Alexis Weinnig | NOAA/NMFS | <https://orcid.org/xxxx> | 2024-08-22 |
| Luke Thompson | NOAA/AOML, MSU/NGI | <https://orcid.org/0000-0002-3911-1280> | 2025-12-15 |
| Sammy Harding | NOAA/AOML, MSU/NGI | <https://orcid.org/0009-0008-8885-6140> | 2025-12-17 |

## RELATED PROTOCOLS

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
| Not provided |  |  |  |

## RELATED EXTERNAL PROTOCOLS

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Not provided |  |  |  |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-12-15 | Initial release |
| 1.0.1 | 2025-12-15 | Updated YAML front matter - note that details in main text still reflect AOML parameters and have not been updated |
| 1.0.2 | 2025-12-17 | Updated entire protocol to reflect USGS parameters |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| USGS | United States Geological Survey |
| NOAA | National Oceanographic and Atmospheric Administration |
| MSU | Mississippi State University |
| NGI | Northern Gulf Institute |
| PCR | Polymerase chain reaction |
| eDNA | environmental DNA |
| NTC | No template control |
| EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty is filter extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water is run in place of DNA on a PCR. |

## BACKGROUND

### Summary

This protocol describes steps for performing PCR for [18S rRNA](target_gene) [V9](target_subfragment) marker gene regions using eDNA extracted from Sterivex by USGS. The PCR protocol includes a primary PCR step and a secondary PCR step.

### Method description and rationale

This protocol is used for PCR amplifying the [18S rRNA](target_gene) [V9](target_subfragment) marker gene regions of environmental DNA. It is highly reproducible and can easily be adapted for any number of samples (i.e. a full 96-well plate or a few samples).

### Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the [18S rRNA](target_gene) marker gene region of any eDNA sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used such as wearing PPE to avoid skin or eye contact.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes and programming/running PCR thermal cyclers.

### Time needed to execute the procedure

Protocol takes about 4 hours ([240](time_required) minutes) including thermal cycler run time.

## EQUIPMENT

For 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 100-1000 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.1-2.5 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 uL 8-Channel Pipette |Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| **Consumable equipment** |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| 96-well PCR Plate | | Armadillo PCR Plate, 96-well, clear, clear wells | ThermoFisher | 3 | |
| PCR Plate Seal | AlumaSeal II Sealing Foils for PCR and Cold Storage | VWR | 2 | Can be substituted with generic, can use tightly-fitted strip caps in place of seal |
| 1000µL Filter Tips | OT-2 Filter Tips, 1000µL | Opentrons | 1 | (box) Can be substituted with generic |
| 200µL Filter Tips | OT-2 Filter Tips, 200µL | Opentrons | 2 | (boxes) Can be substituted with generic |
| 10 ul Filter tips | TipOne Pipette Tips, 10 uL | TipOne | 2 | (boxes) Can be substituted with generic |
| Kapa HiFi Hotstart ReadyMix | Kapa HiFi Hotstart ReadyMix  | Roche | 0.6 | (mL) |
| Molecular water | Invitrogen RT-PCR Grade Water | Fisher Scientific | 1 vial | |
| Forward Primer - 1391F | 18S 1391F Fluidigm Primer | IDT | 105 | (ul (1uM)) Primer must be diluted from 100uM stocks to 1uM |
| Reverse Primer - EukBR | 18S EukBR Fluidigm Primer | IDT | 105 | (ul (1uM)) Primer must be diluted from 100uM stocks to 1uM |
| 2X Kapa HiFi Hotstart ReadyMix | 2X Kapa HiFi Hotstart ReadyMix | Roche | 2.4 | (mL) |
| Index Primer Mix | Illumina Compatible Index Mix (not specified) | missing | 0.48 | (mL) |
| **Chemicals** |
| RNase AWAY | RNase AWAY Surface Decontaminant | ThermoFisher Scientific | 1 | (bottle) Used to sterilize lab surfaces and equipment |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Must be molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Dilute primers from 100 uM to 1 uM.
2. Set up PCR under hood by wiping off all surfaces, pipettes, and racks with RNase AWAY and UV sterilizing for 5-10 mins.
3. Map out order of samples on 96-well PCR plate. Make sure to leave a space for a no template control (NTC) and positive control.

#### PCR

1. Add the following volumes to each well of a 96-well plate:

- 6.25 uL Kapa HiFi Hotstart ReadyMix
- 2.5 ul Fwd primer (1 μM) - GTACACACCGCCCGTC
- 2.5 ul Rev primer (1 μM) - TGATCCTTCTGCAGGTTCACCTAC

| PCR Primer Name | Direction | Sequence (5’ -> 3’) |
| ----- | ----- | ----- | ----- | ----- |
| 1391F | forward | GTACACACCGCCCGTC |
| EukBr | reverse | TGATCCTTCTGCAGGTTCACCTAC |

2. Add 2.0 ul of sample DNA (or molecular water for NTC) to respective wells for a total reaction volume of 13.25 ul per well. Pipette up and down to fully distribute DNA into master mix.
3. Seal plate with PCR plate seal or strip caps.
4. Load plate onto thermal cycler and select program to run the following steps:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 95°C | 180s | 1x |
| Denaturation | 95°C | 30s | 30x |
| Annealing | 63°C | 30s | 30x |
| Extension | 72°C | 30s | 30x |
| Final Extension | 72°C | 5min | 1x |
| Hold | 12°C | ∞ | |

#### PCR 2

1. Add the following volumes to each well of a 96-well plate:

- 25 uL 2X Kapa HiFi Hotstart ReadyMix
- 5uL Index Primer Mix

2. Add 20 uL of amplified DNA sample to respective wells for a total reaction volume of 50 uL per well. Pipette up and down to fully distribute DNA into master mix.
3. Seal plate with PCR plate seal or strip caps.
4. Load plate onto thermal cycler and select program to run the following steps:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 95°C | 180s | 1x |
| Denaturation | 95°C | 30s | 8x |
| Annealing | 55°C | 30s | 8x |
| Extension | 72°C | 30s | 8x |
| Final Extension | 72°C | 5min | 1x |
| Hold | 12°C | ∞ | |

### Basic troubleshooting guide

Low Volume Post-PCR

- If using strip-caps, ensure they are tightly fitting on wells. Any gap in the lid will allow for some volume to evaporate during the PCR process on the thermal cycler. If using PCR plate seals, spin down the plate after taking it off the thermal cycler to ensure all condensation is drawn back into the well.

Contamination

- If there are contamination bands appearing on the gel, run another PCR ensuring full sterilization of work spaces and equipment under the hood and use new vials of Kapa HiFi Hotstart ReadyMix and molecular water. If diluted primers are contaminated, use freshly-made aliquot of primers. 

## REFERENCES
Not applicable.

## APPENDIX A: DATASHEETS
Not applicable.
