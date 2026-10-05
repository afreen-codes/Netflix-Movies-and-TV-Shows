# Netflix-Movies-and-TV-Shows
# Descriptive Analytics of Netflix Movies and TV Shows Using Python

**Student:** Afreen Ansari | **Roll No:** 06 | **Section:** 27
**Course:** BCA (Data Science and Artificial Intelligence), Babu Banarasi Das University

## Objective
Build a descriptive analytics layer over the Netflix title catalog to answer five content-operations questions:
- What does the catalog's content mix look like (Movies vs. TV Shows, genres, ratings)?
- How has content addition activity trended over time?
- How is content rated by maturity level?
- Where is content sourced from, and how concentrated is that supply?
- Which parts of the catalog are at risk from incomplete metadata or thin content depth?

## Data
Kaggle "Netflix Movies and TV Shows" dataset (`netflix_titles.csv`), a mid-2021 snapshot with 8,807 titles and 12 fields. Missing values were never filled, no rows were deleted, and all simulated content is clearly labelled. Tools used: Python (pandas, Matplotlib), with Claude AI assisting analysis, chart generation and report drafting.

> Figures 7-10 use **simulated, illustrative data only**, because the dataset has no viewing-behavior fields. Figures 1-6 come from the actual dataset.

## Key Metrics
| Metric | Value |
|---|---|
| Total titles | 8,807 |
| Movies / TV Shows | 6,131 (70%) / 2,676 (30%) |
| Countries represented | 85 |
| Peak addition year | 2019 (2,016 titles) |
| Most common rating | TV-MA (36.4%) |
| Top category | Dramas (1,600 titles) |
| Top country | United States (3,211 titles) |
| Average TV seasons per show | 1.8 |
| Titles with complete metadata | 60.7% |

## Figures

### Figure 1 - Content Additions Trend by Year (2015-2021))
<img width="745" height="397" alt="Screenshot 2026-10-05 094730" src="https://github.com/user-attachments/assets/28b3f886-09cc-40ce-99f2-8bcf4a6b032a" />



### Figure 2 - Top 10 Content Categories by Title Count


<img width="765" height="412" alt="Screenshot 2026-10-05 094749" src="https://github.com/user-attachments/assets/0288c35e-f0b6-413b-8b0d-5337fea7a3c3" />




### Figure 3 - Maturity Rating Distribution


<img width="805" height="397" alt="Screenshot 2026-10-05 094805" src="https://github.com/user-attachments/assets/95df5d03-ecf2-4d6a-a0f7-9cd224b8beef" />




### Figure 4 - Top 10 Countries by Content Volume


<img width="727" height="401" alt="Screenshot 2026-10-05 094820" src="https://github.com/user-attachments/assets/a104e0df-5f52-4875-af86-61c1bdcb95fa" />




### Figure 5 - Catalog Metadata Completeness Tiers


<img width="795" height="426" alt="Screenshot 2026-10-05 094838" src="https://github.com/user-attachments/assets/a83458bc-aced-4476-9b66-7334865806da" />



### Figure 6 - TV Catalog Depth by Season-Count Tier


<img width="757" height="452" alt="Screenshot 2026-10-05 094851" src="https://github.com/user-attachments/assets/f5c86b98-e3cf-44b8-9212-32dd7f8d361f" />




### Figure 7 (Simulated) - Top 10 Titles by Views


<img width="740" height="401" alt="Screenshot 2026-10-05 094904" src="https://github.com/user-attachments/assets/0c0460b5-6028-4e7f-be18-84d5de192bad" />



### Figure 8 (Simulated) - Viewing Activity by Hour of Day


<img width="827" height="437" alt="Screenshot 2026-10-05 094921" src="https://github.com/user-attachments/assets/644529f7-aaa4-4681-a786-dbe3bece3de1" />




### Figure 9 (Simulated) - Viewing Duration and Completion by Content Type


<img width="786" height="351" alt="Screenshot 2026-10-05 094954" src="https://github.com/user-attachments/assets/d9c9228c-59da-44c5-8ce0-d4695aaafdeb" />



### Figure 10 (Simulated) - Relative Viewing Volume by Day of Week


<img width="732" height="415" alt="Screenshot 2026-10-05 095004" src="https://github.com/user-attachments/assets/fd93d7c1-46f8-43c3-8ba4-3fadefa1c1b3" />


## Business Insights
- Dramas and Comedies anchor over a third of the catalog, so under-represented genres offer more room to differentiate.
- TV Shows' share of yearly additions is rising, which suggests a shift toward series.
- 36% of titles come from the United States alone, a single-market dependency for a global platform.
- 67% of TV Shows have only one season, which makes a renewal-risk model a good next step.
- 8.2% of titles are missing two or more of Director, Cast and Country, a fixable discoverability gap.

## Limitations
- This is a single snapshot (through 2021-09-25), not a live feed. 2021 is a partial year.
- Truncated text fields may undercount multi-value entries.
- "Best-performing" means title count only, not engagement or revenue.
- All viewing-behavior figures (Section 9) are simulated.

## Source
Kaggle - "Netflix Movies and TV Shows" dataset (`netflix_titles.csv`).
