# CFB Home Field Advantage Analysis

Analysis of Power 4 college football home field advantages (2014-2024).

## What it does
Calculates which teams perform significantly better at home vs away by measuring the difference in margin of victory.

**Formula:** Home Field Advantage = Average Home Margin - Average Away Margin

## Requirements
```r
library(cfbfastR)
library(dplyr) 
library(ggplot2)
```

## Usage
```r
source("hfa_analysis.R")
```

## Output
- Top 15 Power 4 teams ranked by home field advantage
- Visualization of top 10 with team colors
- Summary statistics

## Data
- 11 seasons (2014-2024)
- Power 4 conferences only (SEC, Big 12, Big Ten, ACC)
- Minimum 50 games per team
- Source: cfbfastR
