# Largie-Ramazani-Analysis
Repo for analysis of Largie Ramazani and how his performance translates from La Liga to the Premier League

---

## Why I Built This

I wanted to analyse Ramazani's performances across the season after watching him live. I wanted to see how he compared to other attackers in La Liga and the Premier League.

---

## What It Does

Ramazani is compared to La Liga wingers and forwards by calculating his percentile rank across selected metrics.
The absolute metrics are then adjusted before calculating his percentile rank against wingers and forwards in the Premier League.

---

## Inputs

Wyscout event data for La Liga in CSV format
Adjusted Ramazani event data and unadjusted Premier League event data in a single CSV
Image in PNG format

---

## Output

PNG comparing Ramazani vs La Liga players
PNG comparing Ramazani's adjusted metrics vs Premier League players

---

## Libraries Used

- pandas, numpy, scipy — data manipulation and analysis
- matplotlib, mplsoccer, PIL — visualisation

---

## Notes

Ramazani data adjusted manually in Excel and stored as a separate CSV
Adjustment ratio calculated from Opta Power Rankings, also performed in Excel