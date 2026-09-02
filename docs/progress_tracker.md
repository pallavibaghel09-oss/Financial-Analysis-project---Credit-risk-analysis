# Financial Analysis -- Credit Risk Analysis

## Project Progress Tracker

> **Purpose:** Track the progress of the Credit Risk Analysis project
> phase by phase, document completed work, record pending activities,
> and maintain a clear audit trail for the GitHub repository.

------------------------------------------------------------------------

## 1. Project Information

  Field                   Details
  ----------------------- ------------------------------------------------
  **Project Name**        Financial Analysis -- Credit Risk Analysis
  **Project Type**        Financial Analysis / Credit Risk Analysis
  **Primary Dataset**     `credit_risk_dataset (2).xlsx`
  **Data Source**         Kaggle
  **Current Phase**       **Phase 1 -- Data Collection & Project Setup**
  **Repository Status**   Project structure created
  **Last Updated**        01-Sep-2026

------------------------------------------------------------------------

## 2. Project Status

**Overall Progress:** ` In Progress`

**Current Phase:** `Phase 1 – Data Collection & Project Setup`

**Current Status:** 🟡 In Progress

### Status Legend

-   ⬜ Not Started
-   🟡 In Progress
-   🟢 Completed
-   🔵 Under Review
-   🔴 Blocked
-   ⚪ Not Applicable

------------------------------------------------------------------------

# 3. Project Roadmap

  Phase   Phase Name                                Status             Progress
  ------- ----------------------------------------- ---------------- ----------
  1       Data Collection & Project Setup           🟢 Completed            100%
  2       Data Understanding & Data Dictionary      ⬜ Not Started           0%
  3       Data Cleaning & Preparation               ⬜ Not Started           0%
  4       Exploratory Data Analysis (EDA)           ⬜ Not Started           0%
  5       Financial & Credit Risk Analysis          ⬜ Not Started           0%
  6       Risk Segmentation & Risk Indicators       ⬜ Not Started           0%
  7       Visualization & Dashboard                 ⬜ Not Started           0%
  8       Key Findings & Business Recommendations   ⬜ Not Started           0%
  9       Validation & Quality Review               ⬜ Not Started           0%
  10      Documentation & GitHub Finalization       ⬜ Not Started           0%

> **Progress rule:** Update the percentage only when meaningful tasks
> within a phase are completed. Do not treat the percentage as an exact
> mathematical measure unless you have defined task weights.

------------------------------------------------------------------------

# 4. Repository Structure

The project repository has been created with the following structure:

``` text
Financial Analysis project - Credit risk analysis/
│
├── analysis/
├── dashboard/
├── data/
├── docs/
├── images/
├── .gitattributes
└── Readme.md
```

### Planned Use of Folders

  -----------------------------------------------------------------------
  Folder                              Purpose
  ----------------------------------- -----------------------------------
  `analysis/`                         ExcelAnalysis files, calculations,
                                      notebooks, and
                                      analytical outputs

  `dashboard/`                        Final dashboard files and
                                      dashboard-related outputs

  `data/`                             Raw, cleaned, and processed
                                      datasets

  `docs/`                             Project documentation, methodology,
                                      issue log, assumptions, data
                                      dictionary, and progress tracker

  `images/`                           Charts, screenshots, dashboard
                                      images, and supporting visuals

  `.gitattributes`                    Git configuration for repository
                                      file handling

  `Readme.md`                         Main GitHub project documentation
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 5. Phase 1 -- Data Collection & Project Setup

**Status:** 🟢 Completed

**Phase Objective:** Obtain the appropriate credit-risk dataset, verify
its source and accessibility, establish the project repository, and
prepare the structure required for the analysis.

### 5.1 Project Setup Checklist

-   [x] Define project topic: Credit Risk Analysis
-   [x] Create GitHub/local project repository
-   [x] Create `analysis` folder
-   [x] Create `dashboard` folder
-   [x] Create `data` folder
-   [x] Create `docs` folder
-   [x] Create `images` folder
-   [x] Create `.gitattributes`
-   [x] Create `Readme.md`
-   [X] Create `progress_tracker.md`
-   [X] Create `issue_log.xlsx`
-   [ ] Create `data_dictionary.md` / `data_dictionary.xlsx`
-   [X] Create `assumptions.md`
-   [X] Define final naming convention for project files

### 5.2 Dataset Collection Checklist

-   [x] Identify primary dataset
-   [x] Record dataset filename: `credit_risk_dataset (2).xlsx`
-   [x] Identify source: Kaggle
-   [X] Record Kaggle dataset URL
-   [X] Save the original/raw dataset without modification
-   [X] Place raw dataset inside `data/raw/`
-   [X] Verify workbook opens correctly
-   [X] Check number of worksheets
-   [X] Check number of rows and columns (Row count- 386975,Coloumns count-12)
-   [X] Review column names
-   [ ] Identify target/default/risk variable, if available
-   [X] Record basic dataset description
-   [X] Document any known limitations of the source dataset (Static data)

### Phase 1 Deliverable

**Expected output:**

``` text
data/
└── raw/
    └── credit_risk_dataset (2).xlsx
```

**Phase completion criteria:**

-   Dataset is safely stored in the raw-data location.
-   Dataset source is documented.
-   Dataset structure is understood at a high level.
-   Project documentation files are created.
-   No modifications have been made to the original raw dataset.

------------------------------------------------------------------------

# 6. Phase 2 -- Data Understanding & Data Dictionary

**Status:** 🟡 In Progress

**Objective:** Understand every variable in the dataset before
performing cleaning or analysis.

### Tasks

-   [X] Inspect all worksheets
-   [X] Identify total rows and columns
-   [X] Review all column names
-   [X] Identify numerical variables
-   [ ] Identify categorical variables
-   [ ] Identify date variables, if any
-   [ ] Identify borrower-related variables
-   [ ] Identify loan-related variables
-   [ ] Identify repayment/default variables
-   [ ] Identify potential target variable
-   [ ] Understand units of measurement
-   [ ] Check unique values for categorical variables
-   [ ] Prepare data dictionary
-   [ ] Identify variables relevant to credit risk
-   [ ] Document initial observations

### Data Dictionary Template

  -------------------------------------------------------------------------
  Column Name Data Type   Description   Unit /      Example     Credit Risk
                                        Format                  Relevance
  ----------- ----------- ------------- ----------- ----------- -----------
  TBD         TBD         TBD           TBD         TBD         High /
                                                                Medium /
                                                                Low

  -------------------------------------------------------------------------

### Phase 2 Deliverables

-   `docs/data_dictionary.xlsx` or `docs/data_dictionary.md`
-   Dataset overview
-   Variable classification
-   Initial data-quality observations

------------------------------------------------------------------------

# 7. Phase 3 -- Data Cleaning & Preparation

**Status:** ⬜ Not Started

**Objective:** Prepare a reliable and analysis-ready dataset while
documenting every material transformation.

### Tasks

-   [ ] Create a copy of the raw dataset for cleaning
-   [ ] Check missing values
-   [ ] Measure missing-value percentage
-   [ ] Identify duplicate records
-   [ ] Check duplicate borrower/loan IDs, if applicable
-   [ ] Check incorrect data types
-   [ ] Check invalid values
-   [ ] Standardize categorical values
-   [ ] Check inconsistent labels
-   [ ] Identify outliers
-   [ ] Investigate extreme financial values
-   [ ] Decide treatment for missing values
-   [ ] Decide treatment for duplicates
-   [ ] Decide treatment for outliers
-   [ ] Create derived variables where required
-   [ ] Validate cleaned dataset
-   [ ] Document all material changes in the issue log
-   [ ] Save cleaned dataset separately from raw data

### Data Quality Checks

  Check                     Status   Result / Notes
  ------------------------- -------- ----------------
  Missing values            ⬜       
  Duplicate records         ⬜       
  Data types                ⬜       
  Invalid values            ⬜       
  Inconsistent categories   ⬜       
  Outliers                  ⬜       
  Required fields           ⬜       
  Final validation          ⬜       

### Phase 3 Deliverables

``` text
data/
├── raw/
│   └── credit_risk_dataset (2).xlsx
└── cleaned/
    └── [cleaned_dataset]
```

------------------------------------------------------------------------

# 8. Phase 4 -- Exploratory Data Analysis (EDA)

**Status:** ⬜ Not Started

**Objective:** Explore the dataset and identify patterns, distributions,
relationships, and potential risk drivers.

### Tasks

-   [ ] Analyze overall borrower population
-   [ ] Analyze loan distribution
-   [ ] Analyze income distribution
-   [ ] Analyze credit-related variables
-   [ ] Analyze employment characteristics
-   [ ] Analyze loan characteristics
-   [ ] Analyze default/non-default distribution
-   [ ] Calculate descriptive statistics
-   [ ] Analyze distributions of key numerical variables
-   [ ] Analyze categorical variables
-   [ ] Identify relationships between variables
-   [ ] Perform correlation analysis where appropriate
-   [ ] Identify potential risk patterns
-   [ ] Create supporting charts
-   [ ] Document observations

### Suggested EDA Questions

1.  What is the overall size of the credit portfolio represented by the
    dataset?
2.  What percentage of borrowers are in each outcome/default category?
3.  What are the major borrower characteristics?
4.  What are the major loan characteristics?
5.  Which variables appear to differ between default and non-default
    groups?
6.  Are there noticeable relationships between income, debt, loan
    amount, and credit risk?
7.  Are there unusual or extreme observations requiring further
    investigation?

### Phase 4 Deliverables

-   EDA analysis file/notebook
-   EDA charts
-   EDA observations
-   Documented risk-related patterns

------------------------------------------------------------------------

# 9. Phase 5 -- Financial & Credit Risk Analysis

**Status:** ⬜ Not Started

**Objective:** Apply financial-analysis techniques to assess borrower
repayment capacity and identify measurable credit-risk indicators.

### Tasks

-   [ ] Define credit-risk metrics
-   [ ] Identify relevant financial ratios
-   [ ] Calculate Debt-to-Income Ratio (DTI), if applicable
-   [ ] Calculate Loan-to-Income Ratio, if applicable
-   [ ] Analyze credit utilization, if applicable
-   [ ] Analyze loan burden
-   [ ] Analyze repayment/default behavior
-   [ ] Compare risk indicators across borrower groups
-   [ ] Compare default and non-default groups
-   [ ] Analyze risk by income segment
-   [ ] Analyze risk by loan amount
-   [ ] Analyze risk by employment characteristics
-   [ ] Analyze risk by credit history/score, if available
-   [ ] Identify major credit-risk drivers
-   [ ] Validate calculations
-   [ ] Document formulas and assumptions

### Ratio Documentation Template

  ------------------------------------------------------------------------------
  Metric           Formula        Purpose        Result         Interpretation
  ---------------- -------------- -------------- -------------- ----------------
  DTI              TBD            Measure debt   TBD            TBD
                                  burden                        
                                  relative to                   
                                  income                        

  Loan-to-Income   TBD            Assess loan    TBD            TBD
                                  size relative                 
                                  to income                     

  Credit           TBD            Assess usage   TBD            TBD
  Utilization                     of available                  
                                  credit                        
  ------------------------------------------------------------------------------

> **Important:** Only calculate a ratio when the required source
> variables exist in the actual dataset. Do not add a metric merely
> because it is common in credit-risk analysis.

### Phase 5 Deliverables

-   Financial analysis workbook/notebook
-   Credit-risk calculations
-   Ratio analysis
-   Risk-driver analysis
-   Supporting charts

------------------------------------------------------------------------

# 10. Phase 6 -- Risk Segmentation & Risk Indicators

**Status:** ⬜ Not Started

**Objective:** Translate the analysis into meaningful borrower-risk
segments.

### Tasks

-   [ ] Define risk segmentation methodology
-   [ ] Establish criteria for risk categories
-   [ ] Create borrower risk segments
-   [ ] Analyze characteristics of each segment
-   [ ] Calculate default rate by segment
-   [ ] Identify high-risk characteristics
-   [ ] Identify lower-risk characteristics
-   [ ] Validate segmentation logic
-   [ ] Document segmentation assumptions
-   [ ] Review whether segmentation is supported by the data

### Suggested Segments

-   Low Risk
-   Medium Risk
-   High Risk

> The final criteria should be determined from the dataset and analysis.
> Do not assign arbitrary thresholds without documenting and justifying
> them.

### Phase 6 Deliverables

-   Risk segmentation methodology
-   Risk-category analysis
-   Risk profile summary
-   Supporting visualizations

------------------------------------------------------------------------

# 11. Phase 7 -- Visualization & Dashboard

**Status:** ⬜ Not Started

**Objective:** Present the most important credit-risk findings in a
clear and decision-oriented format.

### Tasks

-   [ ] Define dashboard objectives
-   [ ] Select key KPIs
-   [ ] Select relevant charts
-   [ ] Create portfolio overview
-   [ ] Create default/risk overview
-   [ ] Create borrower segmentation view
-   [ ] Create risk-driver visualizations
-   [ ] Add appropriate filters
-   [ ] Validate dashboard numbers against analysis
-   [ ] Improve formatting and readability
-   [ ] Add titles and clear labels
-   [ ] Capture final dashboard screenshots
-   [ ] Save dashboard output in `dashboard/`
-   [ ] Save supporting images in `images/`

### Potential KPIs

-   Total Borrowers
-   Total Loans / Loan Amount
-   Average Loan Amount
-   Average Income
-   Default Rate
-   High-Risk Borrower Count
-   High-Risk Percentage
-   Average DTI, if applicable

> Final KPIs should be selected only after the dataset has been
> examined.

### Phase 7 Deliverables

``` text
dashboard/
└── [final_dashboard_file]

images/
├── [chart_1]
├── [chart_2]
└── [dashboard_screenshot]
```

------------------------------------------------------------------------

# 12. Phase 8 -- Key Findings & Business Recommendations

**Status:** ⬜ Not Started

**Objective:** Convert analytical results into concise financial and
business insights.

### Tasks

-   [ ] Summarize major findings
-   [ ] Identify key credit-risk drivers
-   [ ] Identify high-risk borrower characteristics
-   [ ] Identify lower-risk characteristics
-   [ ] Quantify important findings
-   [ ] Develop business implications
-   [ ] Develop credit-risk recommendations
-   [ ] Distinguish evidence-based findings from assumptions
-   [ ] Ensure recommendations are supported by analysis

### Insight Template

  Finding   Evidence / Metric   Business Impact   Recommendation
  --------- ------------------- ----------------- ----------------
  TBD       TBD                 TBD               TBD

### Recommendation Areas

-   Credit screening
-   Borrower monitoring
-   Risk-based lending
-   Portfolio monitoring
-   Credit policy
-   Early-warning indicators
-   Risk segmentation

------------------------------------------------------------------------

# 13. Phase 9 -- Validation & Quality Review

**Status:** ⬜ Not Started

**Objective:** Perform a final quality-control review before publishing
the project.

### Tasks

-   [ ] Reconcile key figures
-   [ ] Validate formulas
-   [ ] Check calculations
-   [ ] Check dashboard-to-analysis consistency
-   [ ] Review data-cleaning decisions
-   [ ] Review assumptions
-   [ ] Review issue log
-   [ ] Check charts and labels
-   [ ] Check spelling and formatting
-   [ ] Confirm all files open correctly
-   [ ] Check folder structure
-   [ ] Check that raw data has not been overwritten
-   [ ] Remove unnecessary temporary files
-   [ ] Perform final analytical review

### Quality-Control Checklist

  Area                  Status   Reviewer Notes
  --------------------- -------- ----------------
  Data integrity        ⬜       
  Calculations          ⬜       
  Financial ratios      ⬜       
  Risk classification   ⬜       
  Dashboard             ⬜       
  Documentation         ⬜       
  GitHub structure      ⬜       

------------------------------------------------------------------------

# 14. Phase 10 -- Documentation & GitHub Finalization

**Status:** ⬜ Not Started

**Objective:** Complete professional documentation and prepare the
repository for presentation.

### Tasks

-   [ ] Update `Readme.md`
-   [ ] Update `progress_tracker.md`
-   [ ] Complete `issue_log.xlsx`
-   [ ] Complete data dictionary
-   [ ] Complete assumptions document
-   [ ] Document methodology
-   [ ] Add project workflow
-   [ ] Add key findings
-   [ ] Add business recommendations
-   [ ] Add dashboard screenshots
-   [ ] Add tools and technologies
-   [ ] Add project limitations
-   [ ] Add future improvements
-   [ ] Review GitHub folder structure
-   [ ] Check filenames
-   [ ] Remove unnecessary files
-   [ ] Review final README presentation
-   [ ] Commit final project
-   [ ] Push final changes to GitHub

### Final Repository Checklist

``` text
Credit-Risk-Analysis/
│
├── analysis/
│   ├── ...
│
├── dashboard/
│   ├── ...
│
├── data/
│   ├── raw/
│   │   └── credit_risk_dataset (2).xlsx
│   └── cleaned/
│       └── ...
│
├── docs/
│   ├── progress_tracker.md
│   ├── issue_log.xlsx
│   ├── data_dictionary.xlsx
│   ├── assumptions.md
│   └── methodology.md
│
├── images/
│   ├── ...
│
├── .gitattributes
└── Readme.md
```

------------------------------------------------------------------------

# 15. Issue Log Reference

Maintain a separate issue log throughout the project.

**File:** `docs/issue_log.xlsx`

### Record an issue whenever you encounter:

-   Missing data
-   Duplicate records
-   Invalid values
-   Data-quality problems
-   Formula errors
-   Calculation inconsistencies
-   Unexpected analytical results
-   Dashboard errors
-   Documentation gaps
-   Validation/reconciliation differences

### Issue Log Status

  Issue ID   Issue   Phase     Priority   Status   Resolution
  ---------- ------- --------- ---------- -------- ------------
  CR-001     TBD     Phase 1   TBD        Open     TBD

------------------------------------------------------------------------

# 16. Assumptions Log Reference

Maintain assumptions separately from the issue log.

**File:** `docs/assumptions.md`

Record:

-   Business assumptions
-   Data-treatment assumptions
-   Ratio assumptions
-   Risk-segmentation assumptions
-   Thresholds used
-   Outlier-treatment decisions
-   Missing-value treatment
-   Any limitations that affect interpretation

------------------------------------------------------------------------

# 17. Change Log

Use this section to record major project changes.

  --------------------------------------------------------------------------------------------
  Date           Phase          Change                           Reason         Impact
  -------------- -------------- -------------------------------- -------------- --------------
  01-Sep-2026    Phase 1        Project repository and folder    Project        Established
                                structure created                initiation     project
                                                                                workspace

  01-Sep-2026    Phase 1        Kaggle dataset selected:         Dataset        Primary
                                `credit_risk_dataset (2).xlsx`   collection     dataset
                                                                                established
  --------------------------------------------------------------------------------------------

Add a new row whenever a material project decision or structural change
is made.

------------------------------------------------------------------------

# 18. Weekly Progress Log

Use this section as a simple journal of your work.

## Week 1

**Date:** 01-Sep-2026

**Phase:** Phase 1 -- Data Collection & Project Setup

### Completed

-   Project topic finalized.
-   Repository/project folder created.
-   `analysis`, `dashboard`, `data`, `docs`, and `images` folders
    created.
-   `.gitattributes` created.
-   `Readme.md` created.
-   Credit-risk dataset identified from Kaggle.
-   Dataset filename recorded as `credit_risk_dataset (2).xlsx`.

### In Progress

-   Creating project documentation.
-   Preparing the dataset for detailed inspection.

### Next Steps

1.  Record the exact Kaggle source/link.
2.  Place the raw dataset in `data/raw/`.
3.  Inspect workbook structure.
4.  Record rows, columns, and worksheets.
5.  Begin the data dictionary.
6.  Move to Phase 2 after Phase 1 completion.

### Issues / Blockers

-   None currently recorded.

------------------------------------------------------------------------

# 19. Current Next-Step Queue

Because the project is currently in **Phase 1**, complete these items
before moving to Phase 2:

-   [ ] Save `credit_risk_dataset (2).xlsx` in the raw-data location.
-   [ ] Record the exact Kaggle URL.
-   [ ] Record dataset author/source information.
-   [ ] Record download date.
-   [ ] Check workbook/sheet names.
-   [ ] Record row and column counts.
-   [ ] Review all column names.
-   [ ] Create `data_dictionary.xlsx`.
-   [ ] Create `issue_log.xlsx`.
-   [ ] Create `assumptions.md`.
-   [ ] Complete the Phase 1 completion criteria.
-   [ ] Mark Phase 1 as 🟢 Completed.
-   [ ] Start Phase 2 -- Data Understanding & Data Dictionary.

------------------------------------------------------------------------

# 20. Final Project Completion Criteria

The project can be considered complete only when:

-   [ ] Dataset source is documented.
-   [ ] Raw and cleaned datasets are clearly separated.
-   [ ] Data dictionary is complete.
-   [ ] Data-cleaning decisions are documented.
-   [ ] Issues and resolutions are documented.
-   [ ] Assumptions are documented.
-   [ ] EDA is completed.
-   [ ] Financial/credit-risk analysis is completed.
-   [ ] Risk segmentation is justified and documented.
-   [ ] Dashboard/visualizations are completed.
-   [ ] Findings are supported by quantitative evidence.
-   [ ] Business recommendations are linked to findings.
-   [ ] Calculations have been validated.
-   [ ] Documentation is complete.
-   [ ] GitHub repository is organized and presentation-ready.

------------------------------------------------------------------------

## 21. Project Notes

Use this section for important observations that do not belong in the
issue log.

-   
-   
-   

------------------------------------------------------------------------

## 22. Final Reflection

At the end of the project, document:

## \### What I Learned

-   
-   

## \### Financial Analysis Skills Developed

-   
-   

## \### Data Analytics Skills Developed

-   
-   

## \### Challenges Faced

-   
-   

## \### How I Solved Them

-   
-   

## \### Future Improvements

-   
-   

------------------------------------------------------------------------

**Last Updated:** 01-Sep-2026\
**Current Phase:** Phase 1 -- Data Collection & Project Setup\
**Overall Status:** 🟡 In Progress
