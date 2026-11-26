# Elo Expected Scores and Tournament Performance

**R · Data joins · Validation · Statistical analysis**

## Overview
Compare actual chess tournament scores with rating-based expectations.

## Analytical workflow
Parse tournament records, reshape rounds, join opponent ratings, validate matching using Gary Hua's approximately 1605 average opponent rating, calculate Elo expected scores and compare with actual scores.

## Project files
- [Data 607 Week 5B Code Base.Rmd](Data%20607%20Week%205B%20Code%20Base.Rmd) — analysis source.
- See the repository for accompanying rendered reports and any included source data.

## Reproduce
Open the R Markdown source, install the packages listed in its setup and knit with the tournament source available.

## Limitations
Unrated rounds do not receive expected scores; official actual totals may include special entries.

*Academic project — DATA 607, CUNY School of Professional Studies.*
