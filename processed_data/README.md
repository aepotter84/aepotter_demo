Manuscript Title: Per capita sperm metabolism is density-dependent
Authors: Ashley Potter, Craig White, Dustin Marshall
Date updated: Sun 12 January 2025

This file contains information for all the datasets in the manuscript and can be used with 'RDE-Data-Accessibility.Rmd' and 'Supplemental_24_02.docx'

NOTE: For all datasets, NA's indicate no data in the cell

## Please contact Ashley Potter if there are any other questions or concerns aepotter84 (at) gmail.com

# Title of Dataset1: Density-dependent sperm metabolism

## Csv name: RDE\_data.csv

This dataset contains data on density-dependent sperm metabolism -  how sperm metabolism changes across density

## Description of the Data and file structure

Column names and descriptions

*   Species
*   Diluent_cat2: Diluent used to dilute sperm to a known concentration
*   Phyla
*   Class
*   Order
*   Family
*   LNConc: actual sperm concentration (sperm per ml) that was used when metabolism was measured - [natural log transformed]
*   LNMR: actual metabolic rate (microliters O2 per conc per hour) that was measured using the actual sperm concentration - [natural log transformed]
*   LNpercap: per captia sperm metabolic rate (microliters O2 per spermatozoon per hour) - [natural log transformed]
*   logConc: actual sperm concentration (sperm per ml) that was used when metabolism was measured -  [log10 transformed]
*   logMR: actual metabolic rate (microliters O2 per conc per hour) that was measured using the actual sperm concentration - [log10 transformed]
*   logpercap: per captia sperm metabolic rate (microliters O2 per spermatozoon per hour) - [log10 transformed]
*   Diluent_job: The job of the diluent. Used for sperm activation or extending sperm
*   Extraction: Method of sperm extraction (ejaculated, extracted from the male or extracted from the female (stored))
*   Sperm_MR_Note: Was sperm concentration transformed or was there no transformation needed?
*   reference_MR: reference used to extract sperm metabolism data
*   ref_number: number corresponding to the reference_MR
*   Sperm_SD: Standard deviation of each measurement
*   Sperm_SEM: Standard error of the mean for each measurement
*   sample_size: Sample size used in each reference
*   Fresh_or_Frozen: Sperm handling method. Was MR measured on fresh, frozen-thawed or cooled sperm?
*   Endotherm_Ectotherm: Classified species as Endotherm or Ectotherm
*   Internal_External: Classified species as Internal or External
*   matched.species: species list for phylogeny
*   Carbs: Contents of the diluent (carbohydrate-free or carbohydrate-containing)
*   Sugar: Contents of the diluent shortened form (NS = No sugar, S = sugar)

## Sharing/access Information

Data was collected from external sources which are references in the supplemental material Tables S1 and S3.

---

# Title of phylogenetic tree: Phylogenentic tree that was used to run phylogenetic anayses

## Csv name: RDE\_tree.nwk

This represents the phylogenetic tree made from Open Tree of Life that was used in the phyogenetic analyses

---

# Title of Dataset2: Sperm misestimation dataset

## Csv name: Misestimation.csv

This dataset was used to determine the percent misestimation of sperm metabolism based on the fold change in reported sperm concentration relative to the actual sperm concentration

## Description of the Data and file structure

Column names and descriptions:

*   Actual_Conc: actual sperm concentration - sperm concentration (sperm per ml) that metabolism was measured at
*   Stand_Conc: standardised concentration - concentration used to transform the metabolic rate using a standardised sperm concentration
*   Actual_MR: actual metabolic rate (microliters O2 per sperm concentration per h) that was measured using the actual sperm concentration
*   Stand_MR: standardised metabolic rate (microliters O2 per sperm concentration per h) that was reported in the paper but used a standardised concentration
*   a -  alpha: calculated using equation (2) in main text
*   R - Respiration rate: calculated using equation (1) in main text
*   Mis - misestimation: calculated using equation (3) in main text
*   Percent_mis: Mis * 100
*   Fold_IncDec: Fold change in concentration - calculated using equation (4) in main text
*   LogFold_IncDec: log10(Fold_IncDec)

---

# Title of Dataset3: Density-dependent estimates

## Csv name: densitydep\_slopes.csv

This dataset was used to compare the mean scaling exponents of density-dependent metabolism between spermatozoa, multicellular and unicellular organisms

## Description of the Data and file structure

Column names and descriptions

*   Type = Classification of Multicellular, unicellular or spermatozoa
*   Ref = reference data was extracted from
*   Slope = slope of the relationship between per-capita metabolic rate and population density

---

# Title of Dataset4: Density-dependent sperm motility

## Csv name: RDE\_motility.csv

This dataset was used to understand the relationship between sperm density (sperm/ml) and motility (%)

## Description of the Data and file structure

Column names and descriptions

*   Motility_Percent: Percent motility that was recorded at initial activation of sperm
*   Sperm_Conc: Sperm concentration (sperm per ml) that was used during measurements of sperm motility, velocity or both
*   VCL: Curvilinear velocity (micrometers per second)
*   VAP: Average path velocity (micrometers per second)
*   VSL Straight line velocity (micrometers per second)
*   MR.measures.: Does this references have concurrent measures of sperm metabolism (Y/N)?
*   reference_MR: Reference used to extract metabolic rate data
*   Ref_Vel_Mot: Reference used to extract motility data, velocity data or both

## Sharing/access Information

Data from external sources was cited
