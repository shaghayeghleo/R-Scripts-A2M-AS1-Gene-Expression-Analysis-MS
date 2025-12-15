# R Scripts: LncRNA A2M-AS1 Gene Expression Analysis in Multiple Sclerosis (MS) Patients

## Description
This repository contains the **R scripts and analysis pipeline** used in the study titled: **"Initial evaluation of LncRNA A2M-AS1 gene expression in multiple sclerosis patients"** (Mohammadi et al., 2024, Advanced Biomedical Research).

The primary goal of this analysis was to investigate the expression levels of the long non-coding RNA (lncRNA) A2M-AS1 in patients diagnosed with Multiple Sclerosis (MS) compared to healthy controls. This work contributes to understanding potential molecular biomarkers associated with MS pathogenesis.

## Research Objective
The study aimed to evaluate and compare the relative expression levels of the A2M-AS1 gene in peripheral blood samples from MS patients versus healthy individuals using quantitative real-time PCR (qPCR). The analysis focused on identifying any statistically significant differences that might suggest a role for A2M-AS1 in MS.

## Methods (Overview)
1.  **Sample Collection:** Peripheral blood samples were collected from MS patients and healthy controls.
2.  **RNA Extraction:** Total RNA was extracted from the blood samples.
3.  **cDNA Synthesis:** Complementary DNA (cDNA) was synthesized from the extracted RNA.
4.  **qPCR:** Quantitative real-time PCR was performed to measure A2M-AS1 expression levels using specific primers.
5.  **Data Analysis:** R software was used for statistical analysis, including:
    *   Data cleaning and preprocessing.
    *   Relative quantification (e.g., using 2^(-ΔΔCt) method or similar).
    *   Statistical tests (e.g., t-test, Mann-Whitney U test) to compare expression levels between groups.
    *   Data visualization (e.g., boxplots, bar charts, correlation plots).

## Repository Contents
*   `README.md`: This file.
*   `analysis_script.R`: An example R script demonstrating the core analytical steps (data processing, statistical testing, visualization) relevant to the study.
*   `sample_data.csv`: (Optional) An example dataset format (simulated data for demonstration purposes only).
*   `requirements.R`: (Optional) An R script listing required packages (e.g., `ggplot2`, `dplyr`, `stats`).

## Key Findings
*   The study evaluated A2M-AS1 expression in MS patients.
*   Statistical analysis was performed to assess differences compared to controls.
*   Detailed results and their implications are discussed in the published manuscript.

## Citation
If you use or reference this analysis or its concepts, please cite the original publication:

> Mohammadi, S., et al. (2024). Initial evaluation of LncRNA A2M-AS1 gene expression in multiple sclerosis patients. *Advanced Biomedical Research*. DOI: [10.4103/abr.abr_422_23](https://doi.org/10.4103/abr.abr_422_23)

## Keywords
`R`, `Bioinformatics`, `Gene Expression`, `qPCR`, `Multiple Sclerosis`, `LncRNA`, `A2M-AS1`, `Statistical Analysis`, `Data Visualization`

*This repository is maintained by Shaghayegh Mohammadi. For inquiries, please contact via [GitHub](https://github.com/shaghayeghleo) or [Email](mailto:shaghayeghmohammadi9898@gmail.com).*
