# Mahyar Mirzazadeh, MD

Medical doctor and self-taught Python programmer. My clinical background is general
practice and sleep medicine; my MD thesis (Qazvin University of Medical Sciences,
2023) compared obstructive sleep apnea severity between REM and non-REM sleep.

The work here is about one problem: research papers are trusted far more than they
are verified. I rebuild clinical analyses from raw data and write tools that check
published numbers automatically.

## Repositories

### [osa-psg](https://github.com/Mahyarrk/osa-psg)
Reanalysis of my own thesis dataset in Python. All 99 published descriptive
statistics reproduce from the raw polysomnography records; two table errors in the
original SPSS output did not. On top of the audit I built a classifier comparison:
full sleep-lab signals vs. the signals a consumer smartwatch can actually measure,
for OSA severity screening. (Python, scikit-learn, AGPL-3.0)

### [project-veritas](https://github.com/Mahyarrk/project-veritas)
A statistics auditor for scientific papers. It extracts every reported number from
a manuscript, recomputes each one from the raw data with pandas, and shows the exact
calculation behind every match or mismatch. Validated against my thesis, whose two
known errors it caught. (Python, Streamlit, AGPL-3.0)

## Stack
Python, pandas, scikit-learn, scipy, Streamlit, Git, uv

## Contact
- LinkedIn: [linkedin.com/in/mahyar-mirzazadeh-550b3b166](https://www.linkedin.com/in/mahyar-mirzazadeh-550b3b166)
- Email: mahyarmirz@gmail.com
