# MLB Umpire Pitch-Call Analysis

An analysis of MLB ball/strike call accuracy using Statcast pitch-level data from 2015–2025.

## Project Overview

This project uses MLB Statcast data to evaluate called ball and strike accuracy and examine patterns in missed umpire calls.

The analysis includes:

- MLB-wide missed ball/strike call rates
- Average missed calls per game
- Team-level analysis of missed calls against each team
- Identification of teams most affected by incorrect ball/strike calls
- Year-to-year analysis from 2015–2025
- Visualizations of umpire call accuracy and team-level outcomes

## Methods

Pitch-level Statcast data were processed in R using the `baseballr` and `tidyverse` packages.

Called pitches were compared with a strike-zone classification based on pitch location (`plate_x`, `plate_z`) and the batter-specific vertical strike-zone boundaries (`sz_top`, `sz_bot`).

The project was developed as a reproducible R Markdown analysis.

## Files

- **MLB_Umpire_Pitch_Call_Analysis.Rmd** — complete R code and analysis
- **MLB_Umpire_Pitch_Call_Analysis.html** — rendered project report

## Tools

- R
- R Markdown
- baseballr
- tidyverse
- ggplot2
- MLB Statcast data

## Author

**Ty Curtis**  
B.S. Statistics, University of Wisconsin–Madison
