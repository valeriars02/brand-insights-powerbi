# BRAND Insights: Brand Familiarity and Liking (2020–2024)

## Project overview

This project explores changes in consumer familiarity and liking for selected brands between 2020 and 2024. The analysis uses the BRAND (Brand Recognition and Attitude Norms Database) dataset and prepares a focused dataset for a Power BI report.

## Research question

How did average brand familiarity and liking change from 2020 to 2024 for Netflix, Humana, Pfizer, M·A·C, and Boston Scientific?

## Dataset

The BRAND dataset contains aggregated survey responses from U.S. residents.

- **Source:** [ResearchBox](https://researchbox.org/1892)
- **Original study:** Raffaelli et al., [BRAND: Brand recognition and attitude norms database](https://doi.org/10.3758/s13428-024-02525-x)
- **Dataset license:** CC BY 4.0

The Excel workbook is not included in this repository. Download it from the source above before running the notebook.

## Methods and tools

The notebook uses Python, pandas, and Google Colab to:

- Inspect the workbook and its multi-row headers.
- Prepare an analysis table and review missing data.
- Compare familiarity and liking scores between 2020 and 2024.
- Calculate the score differences for five selected brands.
- Export a CSV file for use in Power BI.

## Preliminary findings

- Familiarity increased the most for Boston Scientific (+1.88), Pfizer (+1.73), and Humana (+1.43).
- M·A·C familiarity decreased (-1.43), while Netflix remained nearly unchanged (+0.01).
- Liking decreased for Netflix (-0.49), Pfizer (-0.28), and Humana (-0.18).
- M·A·C liking remained unchanged, while Boston Scientific increased (+0.54).

These are descriptive differences between average scores. They do not establish why the scores changed.

## How to run the notebook

1. Download `BRAND_dataset.xlsx` from [ResearchBox](https://researchbox.org/1892).
2. Open the `.ipynb` notebook in Google Colab.
3. Run the cells in order and upload the Excel workbook when prompted.
4. The notebook will generate and download `brand_insights_powerbi.csv`.

## Limitations

- The survey responses came from U.S. residents; the results should not be generalized to consumers in Mexico.
- The number of responses varies by brand, measure, and year.
- The data contains aggregated scores and does not track the same respondents over time.
- The analysis focuses on five selected brands and does not represent their entire industries.

## Project status

The exploratory analysis, XLSX export, and Power BI report are complete.
