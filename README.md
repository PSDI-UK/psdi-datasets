# **PSDI Phase 2 PF3: Physical Chemistry Properties Data Collection**
### **Datasets**

**Last updated:** 2025-04-08.  

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
</div></b>

---

## **General Information**

This folder contains a series of curated dataset derived from the **Physical Chemistry Properties Data Collection** containing information related to Melting Points, Boiling Points, Solubility, Mole Fraction, Henrys Law Constants and Critical Micelle Concentration's (CMC).

---

## **Dataset Overview**

The datasets are divided into two types. Datasets derived from the Physical Chemistry Properties Data Collection and datasets derived from the book NSRDS-NBS 36.

The following datasets are derived from Physical Chemistry Properties Data Collection. These data sets each consit of two files. A list of the compounds contained in the dataset (DATASETNAME_Compouncs.csv) and a a list of records containing the appropriate data (DATASETNAME_records.csv).

1. Compouds with both MP AND BP data (`/MP_BP`)
2. Compounds with LogS data (`/LogS`)
3. Compounds with both Solubility AND Micibility data (`/LogS_Misc`)
4. Compounds without cannoical names
5. Compounds with multiple solubility records in the same solvent with entries that differ by more than 0.5 (`/LogSsameSolvDiffer`)
6. Compounds with LogS OR HLC data (`/LogS_HLC`)
7. Compounds with LogS AND HLC data (`/LogSandHLC`)
8. Compounds with HLC data (`/HLC`)

These datasets are contained within the zip file `datasets.zip`

The following datasets are derived from NSRDS-NBS 36 and extracted into machine readable format. The ...compounds.csv file lists all the compounds and their ID information listed in the NSRDS-NBS 36 book. The ...Values.csv table lists all the CMC values for each of those compounds,

1. CMC compounds (`CNC_compunds.csv`
2. NIST CMC table (`NIST_Table_Of_Critical_Micelle_Concentration_Values.csv`)

These datasets are contained within the zip file `CMC datasets.zip`

---


## **License**

CC-BY-4.0 https://creativecommons.org/licenses/by/4.0/
