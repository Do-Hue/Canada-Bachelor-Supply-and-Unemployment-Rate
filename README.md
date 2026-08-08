# The Relative Supply of Bachelor's Degree Holders and the Unemployment Gap in Canada

This repository contains the replication code and analysis for a paper research examining whether the relative supply of bachelor's degree holders affects the unemployment gap between degree and non-degree holders in Canada.

## Research Question
Does the increasing supply of bachelor's degree holders in Canada reduce the unemployment advantage that degree holders traditionally enjoy over non-degree holders?

## Key Findings
- **Individual-level analysis**: A 1 percentage point increase in bachelor density is associated with a small reduction in the unemployment gap (coefficient = 0.071, SE = 0.021, p < 0.05)
- **Province-year panel analysis**: The gap widens in favor of bachelor's degree holders at the aggregate level (coefficient = -0.421, SE = 0.116, p < 0.05)
- The unemployment gap remains negative throughout 2006-2025, confirming bachelor's degree holders consistently face lower unemployment

## Data
- Statistics Canada Labour Force Survey (LFS), 2006-2025
- Sample: Active labour force participants aged 22+, across 10 Canadian provinces
- Excludes post-graduate degree holders
- Raw datasets are accessible at this website:  https://www150.statcan.gc.ca/n1/pub/71m0001x/71m0001x2021001-eng.htm
 
## Methodology
1. Linear Probability Model (LPM) with interaction terms
2. Probit model for unemployment probability
3. Province-year panel regression for the unemployment gap
