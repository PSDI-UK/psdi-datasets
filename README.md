# **PSDI Phase 2 PF3: Physical Chemistry Properties Data Collection**
### **Datasets**

**Last updated:** 2025-04-22.  

---

## **Author Information**

<meta charset="utf-8"><b style="font-weight:normal;" id="psdi-table"><div dir="ltr" style="margin-left:0pt;" align="left">
Author Name | Institute | Email | ORCID 
-- | -- | -- | --
Joshua Cheung | University of Southampton | jc10g22@soton.ac.uk | [0009-0003-9952-3468](https://orcid.org/0009-0003-9952-3468)
Joanna Grundy | University of Southampton | j.grundy@soton.ac.uk | [0000-0003-2583-5680](https://orcid.org/0000-0003-2583-5680)
Jeremy Frey | University of Southampton | j.g.frey@soton.ac.uk | [0000-0003-0842-4302](https://orcid.org/0000-0003-0842-4302)
Samuel Munday | Data Revival | samuel@data-revival.com | [0009-0009-9897-333X](https://orcid.org/0000-0001-5404-6934)
Ashley Unitt | Data Revival | ashley@data-revival.com | [0009-0003-9952-3468](https://orcid.org/0009-0007-0037-0035)
Matthew Partridge | University of Southampton | m.c.partridge@soton.ac.uk | [0000-0001-5280-8309](https://orcid.org/0000-0001-5280-8309)
William Poole | University of Southampton | wp1g16@soton.ac.uk | [0009-0003-2441-8794](https://orcid.org/0009-0003-2441-8794)
Thomas Allam | University of Southampton | ta1u18@soton.ac.uk | [0009-0009-9897-333X](https://orcid.org/0009-0009-9897-333X)
</div></b>

---

## **General Information**

This folder contains a series of curated dataset derived from the **Physical Chemistry Properties Data Collection** containing information related to Melting Points, Boiling Points, Solubility, Mole Fraction, Henrys Law Constants, **Critical Micelle Concentration's (CMC)**, and **Electonic supplementary Exemplar**.

---

## **Dataset Overview**

The datasets are divided into three types. Datasets derived from the Physical Chemistry Properties Data Collection, datasets derived from the book NSRDS-NBS 36 and datasets formed from supplementary information of the paper - "Towards the Prediction of Antimicrobial Efficacy for Hydrogen Bonded, Self-Associating Amphiphiles".

The following datasets are derived from Physical Chemistry Properties Data Collection. These data sets each consit of two files. A list of the compounds contained in the dataset (DATASETNAME_Compouncs.csv) and a a list of records containing the appropriate data (DATASETNAME_records.csv).

1. Compouds with both MP AND BP data (`Data_Collection_DataSets/MP_BP`)
2. Compounds with LogS data (`/LogS`)
3. Compounds with both Solubility AND Micibility data (`Data_Collection_DataSets/LogS_Misc`)
4. Compounds without cannoical names
5. Compounds with multiple solubility records in the same solvent with entries that differ by more than 0.5 (`Data_Collection_DataSets/LogSsameSolvDiffer`)
6. Compounds with LogS OR HLC data (`Data_Collection_DataSets/LogS_HLC`)
7. Compounds with LogS AND HLC data (`Data_Collection_DataSets/LogSandHLC`)
8. Compounds with HLC data (`Data_Collection_DataSets/HLC`)

These datasets are contained within the zip file `datasets.zip`

The following datasets are derived from NSRDS-NBS 36 and extracted into machine readable format. The ...compounds.csv file lists all the compounds and their ID information listed in the NSRDS-NBS 36 book. The ...Values.csv table lists all the CMC values for each of those compounds,

1. CMC compounds (`CMC_DataSets/CNC_compunds.csv`)
2. NIST CMC table (`CMC_DataSets/NIST_Table_Of_Critical_Micelle_Concentration_Values.csv`)

These datasets are contained within the zip file `CMC datasets.zip`

The following dataset is derrived from the supplementary information of the paper - Towards the Prediction of Antimicrobial Efficacy for Hydrogen Bonded, Self-Associating Amphiphiles (https://doi.org/10.1002/cmdc.202000533).

1. Supplementary data (`ESI_Case_Study/towards_supplementary_info_cmc.pdf`)
2. Images and JSON output (`ESI_Case_Study/Images and JSON/`)

These datasets are contained within the zip file `ESI_Case_Study.zip`


## **License**

CC-BY-4.0 https://creativecommons.org/licenses/by/4.0/
