# Analysis of Doctoral Degrees Cross the United States

## Overview
This repository contains an analysis of the distribution of doctoral degrees across the United States. The research uses data obtained from IPUMS USA and applies a ratio estimators approach to estimate the total number of respondents in each state based on the proportion of doctorates in California.

## Data
The data was sourced from the IPUMS USA database [here](https://usa.ipums.org). After creating an IPUMS USA account, the relevant dataset was constructed using the following steps:

1. Go to the **Get Data** section on the IPUMS homepage.
2. Select the **ACS 2022** sample and deselect all other default options.
3. Under **Harmonized Variables**:
   - Select `STATEICP` under **Geographic**.
   - Select `SEX`, `EDUC`, and `EDUCD` under **Demographic**.
4. View your cart and create a data extract as a CSV file.
5. Download and unzip the data to retrieve the file `usa_00002.csv`.

## File Structure

The repository is structured as follows:

- **`paper`**: Contains the Quarto document (`paper.qmd`), the compiled PDF (`paper.pdf`), and the bibliography file (`references.bib`) used for the research paper.
- **`data`**:
  - `usa_00002.csv`: The raw dataset extracted from IPUMS USA (not uploaded).
- **`reflection4.Rproj`**: The R project file for replicating the analysis.

## Statement on LLM Usage

No parts of this analysis, including code or documentation, were written using Language Learning Models (LLMs).
