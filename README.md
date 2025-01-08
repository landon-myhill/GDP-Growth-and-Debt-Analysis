# GDP Growth vs. Debt Ratio Analysis

## Overview

This project analyzes the relationship between GDP growth and debt-to-GDP ratios across various countries over several decades. The dataset includes information from the 1940s to 2010, containing GDP growth and debt ratio data for 20 countries. The analysis involves visualizing the data, fitting regression models, and calculating next year's growth rate and the change in GDP growth between consecutive years.

## Dataset

The dataset used for this analysis is `debt.csv`, which includes the following columns:

- **Year**: The year the data is from.
- **Country**: The country the data corresponds to.
- **Growth**: The GDP growth rate for that year.
- **Ratio**: The debt-to-GDP ratio for that year.

## Dependencies

This analysis requires the following R packages:

- `dplyr`: For data manipulation.
- `ggplot2`: For plotting and visualizations.

You can install these packages by running the following commands in R:

```r
install.packages("dplyr")
install.packages("ggplot2")
