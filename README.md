# Do Comics Mirror America?
### Women at work in Marvel and DC characters vs. the real U.S. workforce, 1940–2025

Team project for **BA780 – Introduction to Data Analytics**, Boston University Questrom (MS in Business Analytics).

## The question
Since the 1940s, American women moved into paid work and into jobs once closed to them. Did Marvel and DC characters reflect that change, and how far behind were they?

## Data
- **Marvel and DC Fandom wikis**: 49,922 characters after cleaning (gender, debut year, occupation)
- **IPUMS USA**: U.S. employment by occupation and sex, 1940–2023
- **FRED / BLS**: women's labor force participation, 1948–2026

About 15,000 free-text occupations were sorted into the same census job groups, so characters and real workers can be compared directly.

## Key findings
- The share of new female characters rose from **11.5% in 1960 to 40% in 2025**, but the full roster is still about **70% male**.
- Comics best match the workforce of about **7 years earlier** (r = 0.89).
- Female characters get jobs where real women were already common (**50% vs 43%** women in real life).
- Female characters reached 20% of historically male jobs only in the **2010s**; real women did in the **1980s**.
- **57%** of female characters have a job listed, against **67%** of male characters.

## Tools
Python, pandas, NumPy, Matplotlib, seaborn (Google Colab)

## Contributors
- Albert Dorofeev (Project Manager)
- Carly Barry
- Daniel Igbokwe
- Eliza Bashirian
- Emanuele Borroni
