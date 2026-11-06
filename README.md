# Jonas Kalkreuth | Data Analyst

Chemical engineer (MSc) specialised in analytical chemistry, moving into data analysis and data science.\
Industrial lab work taught me measurement uncertainty, method validation and careful documentation.\
Those habits carry over directly to working with data.

**Looking for:** part-time or contract roles in data analysis, Python analytics or scientific data analysis.\
**Contact:** [kalkreuthjonas@gmail.com](mailto:kalkreuthjonas@gmail.com)

## Core skills

- Python, pandas, NumPy, scikit-learn
- Statistical analysis, regression and machine learning
- Data cleaning, validation and preprocessing
- SQL, SQLite, DuckDB
- Data visualisation with Plotly and Streamlit
- API integration, automation, pytest and GitHub Actions
- Infrared spectroscopy (FTIR / ATR-IR) and chemometrics

## Projects

### Finished

**[ir-spectra-analyzer](https://github.com/jonaskalkreuth/ir-spectra-analyzer)**\
Classifies the material behind an FTIR spectrum into 8 classes, such as polymers for microplastic screening.\
Compares library matching, SVM, Random Forest and a rule baseline on 4,113 held-out spectra.\
Library matching wins (F1-macro 0.987). The README shows how near-duplicate spectra inflate every score.\
`scikit-learn` · `signal processing` · `OpenSpecy`

**[instagram-engagement-analysis](https://github.com/jonaskalkreuth/instagram-engagement-analysis)** — [live demo](https://instagram-engagement-analysis-busaeulgqrnwwzwp9zph5y.streamlit.app/)\
Finds which content features go with higher engagement on a musician's account, after removing account growth.\
Theme matters most. Captions, hashtags and timing show no clear effect.\
`Instagram Graph API` · `DuckDB` · `bootstrap CIs` · `Streamlit`

**[freelance-finance-pipeline](https://github.com/jonaskalkreuth/freelance-finance-pipeline)**\
Turns a year of bank and PayPal exports into a German EÜR tax figure.\
It removes double-counted transfers between own accounts first. Runs on synthetic demo data.\
`pandas` · `reconciliation` · `Excel` · `Plotly`

### In progress

**[carbonate-cement-PLS](https://github.com/jonaskalkreuth/carbonate-cement-PLS)**\
Reproduces my own peer-reviewed paper ([Kalkreuth et al. 2023, *J. Am. Ceram. Soc.*](https://doi.org/10.1111/jace.19546)) in open-source Python instead of commercial Bruker OPUS software.\
PLS regression predicts CaCO₃ content in cement paste from ATR-IR spectra.\
Calibration error lands within 0.3 wt% of the paper for two of three methods. The preprocessing recipe is still open.\
`scikit-learn` · `PLS` · `chemometrics` · `pytest`

**[job-scraping](https://github.com/jonaskalkreuth/job-scraping)**\
A weekly pipeline that collects European data-role job postings and counts the skills they ask for.\
It has collected 4,300 distinct jobs from four sources since June 2026.\
`APIs` · `SQLite` · `launchd` · `pytest`

**[europapark-crowd-forecast](https://github.com/jonaskalkreuth/europapark-crowd-forecast)**\
Predicts quiet days at Europa-Park before the season starts, using only calendar information.\
A ridge model beats two simple baselines on quiet-day precision in both test seasons.\
`time series` · `scikit-learn` · `uv` · `ADRs`
