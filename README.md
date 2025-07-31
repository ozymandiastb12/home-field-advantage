# Home Field Advantage Analysis

Analysis of home field advantages in college football (Power 4) and NFL (2014-2024).

## What it does
Calculates which teams perform significantly better at home vs away by measuring the difference in margin of victory.

**Formula:** Home Field Advantage = Average Home Margin - Average Away Margin

## Requirements
```r
library(cfbfastR)  # For college football
library(nflfastR)  # For NFL
library(dplyr) 
library(ggplot2)
```

## Usage
```r
# College Football (Power 4)
source("cfb_hfa_analysis.R")

# NFL (All 32 teams)
source("nfl_hfa_analysis.R")
```

## Output
- Top 15 teams ranked by home field advantage
- Visualization of top 10 with team colors
- Summary statistics

## Data
- 11 seasons (2014-2024)
- **CFB:** Power 4 conferences only (SEC, Big 12, Big Ten, ACC), min. 50 games
- **NFL:** All 32 teams, regular season only, min. 80 games
- Sources: cfbfastR, nflfastR
