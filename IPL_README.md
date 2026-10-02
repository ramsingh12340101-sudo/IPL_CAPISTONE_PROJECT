# IPL 2022 Match Analysis

Exploratory data analysis of all 74 matches from IPL 2022, using Python, pandas, and seaborn.

## Dataset

74 matches, 20 columns (teams, venue, toss, innings scores, match result, top performers). No missing values.

## Key findings

- **The toss barely mattered.** The toss winner went on to win the match in only 36 of 74 games (48.65%) — close to a coin flip, despite the common assumption that winning the toss is a meaningful advantage.
- **The season was geographically concentrated.** All but 2 of the 74 matches were played across just 4 venues, all in Mumbai and Pune — a result of 2022's pandemic-era centralized scheduling rather than a normal IPL season's usual spread of host cities.
- **Gujarat Titans topped the table** with 12 wins in their debut season.
- **Standout single-match performances:** Yuzvendra Chahal and Jos Buttler most frequently posted the match's best bowling figure and top score respectively. (Note: these counts reflect best-in-match performances summed across the season, not official season-long wicket/run totals.)

## Methods

- Data cleaning and validation (`pandas`)
- Aggregation and group-wise analysis (`groupby`, `value_counts`)
- Visualization (`seaborn`, `matplotlib`): bar charts, count plots, horizontal bar charts

## Files

- `ipl22.ipynb` — full analysis notebook, with charts rendered inline
- `ipl.csv` — source dataset (add your own copy; not included here)

## Tools

Python, pandas, NumPy, matplotlib, seaborn
