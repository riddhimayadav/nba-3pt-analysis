# Three-point shooting and NBA team success

A statistical study of the relationship between three-point shooting and team win percentage across **150 team-seasons**, from **2019–20 through 2023–24**.

**Author:** Riddhima Yadav  
**Course:** SDS 320E, Spring 2025

## Questions and method

Using team statistics collected from Basketball Reference, the project asks whether three-point attempt volume and shooting-efficiency category are associated with win percentage. A linear model fitted in R includes attempts per game and high/low efficiency categories.

## Results

The fitted model estimates that the low-efficiency group has a win percentage **0.129 lower**, or approximately **12.9 percentage points lower**, than the high-efficiency group, holding attempt volume constant. Attempt volume is not statistically significant in that model (`p = 0.479`).

These are observational associations. The model does not establish that changing three-point efficiency causes a particular increase in wins. The poster discusses omitted variables and repeated teams across seasons.

## Artifacts

- [Final poster](poster/Poster%20Report.pdf): model output, figures, and limitations.
- [Preliminary report](report/Prelim%20Report.pdf): exploratory analysis and R code excerpts.
- [Collected data](data/NBA%20Data%20Collection.csv): the analysis dataset.
- `NBA Data Collection.xlsx`: the data collection workbook.

The repository currently preserves the data and reports. It does not yet include a standalone R/RMarkdown script that reproduces the full final analysis; the code excerpts in the preliminary report are not a complete reproduction package.

## Sources

- [Basketball Reference](https://www.basketball-reference.com/) — team statistics.
- Grimes, P. J. (2024). [The NBA has a 3-pointer problem](https://ftw.usatoday.com/2024/10/nba-three-pointers-record-attempts-problem), USA Today — project motivation.
