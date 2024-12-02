# Extracted tables and cleaning details from the 2023 report

## Table dimension_CRMsOverTime

***Table from Annex 4, pg. 61-62 - showing the tri-yearly evolution of CRM scores by material (and HREE, LREE, and PGM materials in their respective groupings).***

Unpivoted by the year column.

Replaced 'PGMs' to 'PGM', 'HREEs' to 'HREE', and 'LREEs' to 'LREE'.

The 'aluminium/bauxite' category is actually new for 2023 as it was actually two separate categories in earlier assessment 'aluminium' and 'bauxite' [pg. 3]. To reflect this, the 'aluminium' scores for 2023 are moved to a newly created 'aluminium/bauxite' category, and the 'aluminium' scores are replaced with '-'.

## Table dimension_ScreenedMatGroupings

***This table shows material groupings for screened materials based on the table in page 2.***

The 'aluminium/bauxite' category is actually new for 2023 as it was actually two separate categories in earlier assessment 'aluminium' and 'bauxite' [pg. 3]. To reflect this, the 'aluminium' and 'bauxite' materials are added to 'other non-ferrous metals'.

As some materials can have more than one category, different permutations of material categories for different materials have been created in different columns. For example, some assessments aggregate REEs, and/or HREEs & LREEs in direct comparisons with single materials.

## Table fact_MaterialUseShares

***Table from Appendix 6, pg. 64-Material use shares. No changes to data.***

## Table fact_GlobalSupplyShares&t

***Table from Appendix 7, pg. 78 - Global supply shares & trade-related variable.***

Added another column for the stage 'E' (extraction) or 'P' (processing). Made some minor changes to the country column:

- replaced 'CHN' to 'China' for Krypton's 'P' stage
- replaced 'DEU' with 'Germany' for Krypton's 'P' stage
- replaced 'Korea S.' with 'Korea, South' for Bismuth's 'P' stage
- replaced 'RUS' with 'Russia' for Krypton's 'P' stage
- replaced 'UKR' with 'Ukraine' for Krypton's 'P' stage
- replaced 'USA' with 'United States' for Krypton's 'P' stage

## Table fact_EUSupplyShares&t

***Table from Appendix 7, pg. 78 - EU Sourcing shares (>=1%) and trade-related variable.***

Added another column for the stage 'E' (extraction) or 'P' (processing).

- replaced 'Hongkong' with 'Hong Kong' for Neon's 'P' stage
- replaced 'DRC' with 'Congo, D.R.' for Natural teak wood's and Tantalum's 'E' stage