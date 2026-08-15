# Research Project: AI Integration Challenges in Australian Retail

## Overview

This repository contains the data, analysis code, figures, and original published source workbooks used for a preliminary research project examining **Artificial Intelligence (AI) integration challenges in Australian retail business operations**.

The project uses a **secondary-data-only research design**. All empirical observations used in the analysis were retrieved from **published and publicly accessible data sources**. No interviews, surveys, focus groups, private organisational records, or unpublished participant data were collected.

The published data were cleaned, harmonised, transformed, and analysed using Python to investigate patterns associated with:

* AI adoption
* digital readiness
* data and analytics capability
* workforce skills
* ICT management capability
* cybersecurity
* innovation
* financial and operational barriers
* responsible AI integration readiness

Researcher-created analytical variables, indexes, classifications, model outputs, and scenario estimates are clearly distinguished from the original published data.

---

## Repository Structure

```text
Research-Project/
│
├── data/
│
├── figures/
│
├── official_source_workbooks/
│
└── Bikash_RES614_Complete_Analysis.ipynb
```

### `data/`

The `data` folder contains the **cleaned, processed, harmonised, and researcher-created analytical datasets** used in the Python analysis.

These files were produced from values extracted from published secondary datasets.

Depending on the analysis, the folder includes datasets relating to:

* Australian industry-level AI use
* digital technology adoption
* cloud technology
* data analytics
* customer relationship management systems
* enterprise resource planning systems
* ICT limitations
* workforce and digital skills shortages
* cybersecurity incidents
* cybersecurity controls
* ICT management practices
* innovation activity
* business barriers
* retail industry performance
* retail business entries and exits
* business survival
* retail turnover
* AI adoption scenarios
* model predictions
* factor importance
* researcher-created AI readiness and challenge measures

The processed datasets do **not** represent newly surveyed businesses.

They are analytical datasets constructed from published observations so that information from different published sources can be compared and analysed consistently.

Where variables were transformed, normalised, combined, or used to construct an index, the procedure is documented in the Jupyter Notebook.

---

### `figures/`

The `figures` folder contains charts and visualisations generated from the analysed secondary data.

These figures support the interpretation of:

* AI adoption across industries
* Retail Trade compared with other Australian industries
* changes between published reporting periods
* digital readiness indicators
* skills and capability constraints
* cybersecurity exposure
* ICT barriers
* AI integration challenge scores
* predictive model results
* factor-importance results
* actual versus predicted AI adoption
* scenario analysis

The figures were generated programmatically from the processed datasets rather than manually altering the underlying observations.

---

### `official_source_workbooks/`

The `official_source_workbooks` folder contains copies of the **original published data files** used as the empirical basis for the analysis.

The principal sources include published datasets from organisations such as:

* **Australian Bureau of Statistics (ABS)**
* **Australian Government / National AI Centre**

The ABS source workbooks contain published industry-level statistics relating to areas such as:

* artificial intelligence use
* information and communication technology
* cloud technology
* data analytics
* digital platforms
* workforce skills
* ICT capability
* cybersecurity
* innovation
* business practices
* business barriers
* retail business performance

These original source files are retained in the repository to provide **data provenance, transparency, traceability, and reproducibility**.

The values contained in these workbooks were published by the respective data providers. They were not created or estimated by the researcher.

---

### `Bikash_RES614_Complete_Analysis.ipynb`

This is the main **Jupyter Notebook** containing the complete Python analytical workflow.

The notebook documents the process from published data to research findings.

It includes:

1. Data loading
2. Source and provenance checking
3. Missing-value assessment
4. Data cleaning
5. Data harmonisation
6. Variable selection
7. Retail Trade extraction
8. Cross-industry comparison
9. Descriptive statistics
10. Change-over-time analysis
11. Construction of analytical indicators
12. AI Integration Readiness and Challenge Index development
13. Index sensitivity analysis
14. Correlation analysis
15. Predictive modelling
16. Model validation
17. Regression coefficient interpretation
18. Random Forest analysis
19. Gini feature importance
20. Permutation importance
21. Actual-versus-predicted comparisons
22. Retail industry contextual analysis
23. Scenario analysis
24. Generation of research figures
25. Interpretation of findings
26. Documentation of analytical limitations

The notebook is intended to provide a transparent and reproducible record of the secondary-data analysis.

---

## Research Focus

The research examines the following broad question:

> **What technological, organisational, workforce, governance, and business factors influence responsible AI integration in Australian retail business operations?**

The analysis also explores whether published historical indicators of digital and organisational capability contain useful information for understanding later differences in AI adoption between Australian industries.

Retail Trade remains the primary industry of interest, while other industries are used as comparative observations.

---

## Secondary Data Approach

An important principle of this research is the distinction between **literature** and **analysable secondary data**.

Peer-reviewed journal articles are primarily used to:

* establish theoretical foundations
* identify previous findings
* critically evaluate existing research
* develop the research problem
* identify the research gap
* interpret the empirical results

The quantitative empirical analysis, however, is based on **published datasets and published statistical tables**.

A journal article is not treated as an empirical secondary dataset merely because it reports results. Where a published study provides an accessible dataset, that dataset may be considered separately for secondary analysis.

---

## Data Integrity

No artificial business observations were added to the empirical dataset simply to increase the sample size.

The project distinguishes between three types of information:

### Published observations

Values directly obtained from published secondary datasets.

Examples include published percentages relating to AI use, skills shortages, cybersecurity, digital technologies, innovation, and business barriers.

### Researcher-derived variables

Variables calculated from published observations.

Examples include:

* percentage-point changes
* normalised values
* rankings
* composite indicators
* readiness scores
* challenge scores

These calculations are documented in the notebook.

### Analytical scenarios

Some future values may be presented as scenario estimates.

These are clearly labelled as **illustrative scenarios rather than observed published data or validated forecasts**.

They are used to explore possible future pathways rather than to claim that a specific future outcome will occur.

---

## AI Integration Readiness and Challenge Analysis

A researcher-created analytical framework is used to examine different dimensions of AI integration capability.

The framework considers areas such as:

* digital foundations
* analytical maturity
* workforce capability
* management capability
* cybersecurity and governance
* innovation capacity
* financial and operational barriers

The resulting challenge or readiness scores are **not official ABS or Australian Government indicators**.

They are research constructs developed from published variables for exploratory comparison.

Sensitivity analysis is used to examine whether conclusions change materially when alternative weighting assumptions are applied.

---

## Predictive Analysis

The notebook also contains exploratory predictive modelling.

Historical published industry-level indicators are used as predictor variables, while later published AI-use statistics are used as the outcome variable.

Models examined include approaches such as:

* Ridge Regression
* Elastic Net
* Random Forest
* Extra Trees

Model performance is assessed using methods appropriate to the small industry-level dataset, including leave-one-industry-out cross-validation.

Feature interpretation includes:

* standardised regression coefficients
* Gini feature importance
* permutation importance

These methods are used to identify variables that appear most informative for explaining differences in industry-level AI adoption.

---

## Important Interpretation Note

The predictive analysis is **exploratory**.

The number of industry-level observations is limited, and the data are primarily aggregated repeated cross-sectional statistics.

Therefore:

* the models do not establish causation
* the findings should not be interpreted as predictions for individual retail businesses
* aggregate industry relationships may hide substantial differences between individual organisations
* feature importance does not prove that a variable independently causes AI adoption
* scenario results should not be interpreted as guaranteed future outcomes

The models are used to demonstrate a transparent preliminary analytical process and to identify areas suitable for deeper future research.

---

## Reproducibility

To reproduce the analysis:

1. Download or clone the complete repository.
2. Keep the folder structure unchanged.
3. Open `Bikash_RES614_Complete_Analysis.ipynb`.
4. Run the notebook from the repository root directory.
5. Ensure that the required Python libraries are installed.
6. Run the notebook cells sequentially.

Common Python packages used include:

```text
pandas
numpy
matplotlib
scikit-learn
```

The notebook reads processed datasets from the `data/` directory and generates the analytical results and figures.

---

## Data Provenance

The repository retains both:

* original published source files, and
* researcher-created processed datasets.

This allows each important analytical variable to be traced back to its published source.

Where possible, the analytical files include information such as:

* publisher
* reference period
* source dataset
* source table
* variable definition
* measurement unit
* transformation applied
* original source location

This approach supports transparency and reproducibility.

---

## Ethical Considerations

This research uses secondary data only.

No human participants were recruited and no primary data were collected.

The project does not contain:

* interview recordings
* interview transcripts
* survey responses collected by the researcher
* participant names
* personal identifiers
* confidential organisational records
* sensitive individual-level information

The analysis focuses on published and predominantly aggregated industry-level information.

---

## Current Project Stage

This repository represents the analytical component of a **preliminary research thesis draft**.

The present stage focuses on:

* identifying appropriate published secondary datasets
* constructing a reproducible analytical dataset
* conducting exploratory analysis
* evaluating AI integration challenges
* identifying potentially important explanatory factors
* developing a preliminary research framework

Further analytical development, additional datasets, expanded validation, and more advanced visualisation may be undertaken in later stages of the research.

---

## Future Development

Potential future work includes:

* adding further compatible published datasets
* extending the number of reporting periods
* testing the framework with more granular data
* examining business-size differences
* examining state or regional variation where compatible data become available
* strengthening predictive validation
* testing alternative index construction methods
* developing an interactive Power BI dashboard
* comparing secondary-data findings with future primary research
* validating the proposed AI integration framework with Australian retail organisations

---

## Researcher

**Bikash Poudel**

RES614 Preliminary Research Thesis
Torrens University Australia

---

## Disclaimer

This repository has been prepared for academic research purposes.

Published datasets remain the intellectual property of their respective publishers and should be used subject to the conditions specified by those organisations.

Researcher-created processed datasets, analytical indexes, model outputs, visualisations, and interpretations should be understood within the methodological limitations documented in the research thesis and Jupyter Notebook.

The presence of a source file in this repository does not imply that the original publisher endorses the research findings or interpretations.
