# EU-Critical-Raw-Materials-CRM-Reports-Datasets
Unofficial repository for the datasets in reports from the European Commission on the EU Critical Raw Materials.

This repository contains datasets from several Critical Raw Materials (CRMs) reports published on the European Commission's web page for CRMs ([Link](https://single-market-economy.ec.europa.eu/sectors/raw-materials/areas-specific-interest/critical-raw-materials_en)). The data is a combination of Eurostat data, expert interviews, and calculation results by the respective authors of the reports. The aim is to simplify the extraction of data in the reports for analytics, for example using a data connector for visualisation tools. This "raw" data differs from the Raw Material Information System ([Link](https://rmis.jrc.ec.europa.eu/)) as gives the user more freedom to visualise and use the data in any way that they see fit, while respecting the licensing (see the licensing section below).

## Introduction & Background

Critical Raw Materials for the EU are, as per the European Commission's definition, materials that pose a significant supply risk and/or are of high economically importance for the EU. Every third year, since 2011, the European Commission publishes new evaluation reports for CRMs for EU on the European Commission's web page ([Link](https://single-market-economy.ec.europa.eu/sectors/raw-materials/areas-specific-interest/critical-raw-materials_en)). 

##### Methodology & the Change in Methodology from 2017 Onward

With the 2017 CRM report, an additional methodology report ([Link](https://op.europa.eu/en/publication-detail/-/publication/2d43b7e2-66ac-11e7-b2f2-01aa75ed71a1/language-en/format-PDF/source-32064602)) was published and the general methodology was also updated for the CRM evaluation. Refer to the individual tri-yearly reports for specifics regarding the methodologies used to determine the CRMs for that year. In short, the methodology for the years 2017, 2020, and 2023 use a methodology covered in the referenced 2017 methodology report. 

Again, all documents can be accessed from the European Commissions page on CRMs ([Link](https://single-market-economy.ec.europa.eu/sectors/raw-materials/areas-specific-interest/critical-raw-materials_en))

##### CRMs vs. Strategic Raw Materials (SRMs) & the Introduction of the Critical Raw Materials Act (CRMA) and Accompanying Regulation

In 2023, a list of Strategic Raw Materials (SRMs) was published in conjunction with the CRMs. In the same motion, the European Commission introduced the Critical Raw Materials Act (CRMA) ([Link](https://single-market-economy.ec.europa.eu/sectors/raw-materials/areas-specific-interest/critical-raw-materials/critical-raw-materials-act_en)). In April of 2024, an accompanying regulation (Regulation (EU) 2024/1252) ([Link](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401252)) went into effect which aims to "[establish] a framework for ensuring a secure and sustainable supply of critical raw materials". 

With respect to resources, industry, and sustainability, perhaps the most important part of the legislation is the introduction of benchmarks to be followed by the member states in the EU. It is of high importance to separate the CRMs and SRMs in this regard, as the legislature states, in Article 5, that the benchmarks outlined in the CRMA apply specifically to Strategic Raw Materials (SRMs).

The list of SRMs can be found in Annex I of the Regulation ([Link](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401252))

## Data Sources

The references for the data in the repo are as follows:

* "European Commission, Study on the critical raw materials for the EU 2023 – Final Report" ([Link](https://op.europa.eu/en/publication-detail/-/publication/57318397-fdd4-11ed-a05c-01aa75ed71a1))
* "European Commission, Study on the EU’s list of Critical Raw Materials – Final Report (2020)" ([Link](https://ec.europa.eu/docsroom/documents/42883/attachments/1/translations/en/renditions/native))
* "European Commission, Study on the review of the list of critical raw materials (2017)" ([Link](https://op.europa.eu/en/publication-detail/-/publication/08fdab5f-9766-11e7-b92d-01aa75ed71a1/language-en))
* "European Commission, Report on Critical Raw Materials for the EU (2014)" ([Link](https://ec.europa.eu/docsroom/documents/10010/attachments/1/translations))

## Licensing & Data Ownership

* **The European Commission website** applies the Creative Commons Attribution 4.0 International License ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)) to the reports belonging to the Commission.
* **"European Commission, Study on the critical raw materials for the EU 2023 – Final Report."** Reproduction is authorized, provided the source is acknowledged.
* **"European Commission, Study on the EU’s list of Critical Raw Materials – Final Report (2020)"** Reproduction is authorized, provided the source is acknowledged.
* **This GitHub Repository:** This repository is licensed under the Creative Commons Attribution 4.0 International License ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). 

The author of this repository have not made any intentional changes to the data in the reports referenced, with the exception of data cleaning for the purpose of reuseability of the data. All data cleaning changes are logged in `changes.csv` .

> Note: While this repository is based on data from the EU report(s), any modifications or additions made in this repository are also licensed under CC BY 4.0. 

## On updates

The European Commission updates the list of CRMs every third year from 2011. As such, another CRM report from the European Commission is expected in 2026.
