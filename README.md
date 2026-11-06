# Jonas Kalkreuth

Analytical chemist (MSc), transitioning into data analysis and data science.\
In the lab I learned to question every measurement. Now I apply that to data: clean it carefully, validate models honestly, and document each decision.

**Looking for:** part-time or temporary roles in data analysis or data science.\
**Contact:** [kalkreuthjonas@gmail.com](mailto:kalkreuthjonas@gmail.com)

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

## Tools

**Daily:** Python, pandas, NumPy, scikit-learn, pytest, Git, GitHub Actions\
**Also used:** SQLite, DuckDB, Streamlit, Plotly, Jupyter\
**Learning now:** SQL (window functions, CTEs)\
**Lab background:** FTIR / ATR-IR, TG-FTIR, chemometrics
