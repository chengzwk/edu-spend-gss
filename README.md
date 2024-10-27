# US Education Spending Opinion Analysis (1972-2012)

This project explores public opinion on education spending in the United States over the years 1972 to 2012, using data from the General Social Survey (GSS). Specifically, it focuses on how public opinion has evolved regarding whether the nation spends too little, too much or about right amount of money on improving the education system.

## Description

The purpose of this project is to analyze trends in public opinion on education spending in the U.S., identify how these opinions have changed over time, and explore potential relationships between respondents' education levels and their views on education spending.

The analysis addresses the following research questions:

* 1.1. What is the proportion of people in the US population who think they're spending too little money on improving the nation's education system in year 1972 - 2012, respectively?

* 1.2. Has the proportion of people who think they're spending too little money on education increased from year 1972 to year 2012?

* 1.3. Is there a relationship between education level and the opinion on education spending in the U.S.? 

This analysis is conducted in R, with visualizations using ggplot to support the findings.

## Getting Started

### Dependencies

- **R** (version 4.0 or higher recommended)
- **Rstudio**
- **R Libraries**:
  - `dplyr` for data processing
  - `ggplot2` for creating plots
  - `statsr` for conducting statistical inference
  - `tidyr` for data manipulation and visualization
  - `purrr` for functional programming
  - `gt` for creating styled tables
  
### Viewing the report

To view the report of the analysis, open the knitted report (the `edu-spend-gss.html` file) at [this address](https://html-preview.github.io/?url=https://github.com/chengzwk/edu-spend-gss/blob/main/stat_inf_project.html)

### Installing

1. Clone the repository:

```bash
git clone https://github.com/chengzwk/edu-spend-gss.git
```

2. Install the necessary R libraries if you haven’t already:

```R
install.packages(c("tidyverse", "dplyr", "ggplot2", "statsr", "gt"))
```

### Executing program

To run the analysis:

- Download the [source data file](https://d3c33hcgiwev3.cloudfront.net/_5db435f06000e694f6050a2d43fc7be3_gss.Rdata?Expires=1730160000&Signature=MPGaI-fvURqnHr6LHr6zFElCDHUs2800~MfIG76QzO~EgG92SdJ3zZM4RtqqfT1x7F2KUetH0e18KP7HbMrLhLiQSdhlVX1-Z5MItiYUBMpjJ-Q0-IDQ6~gQGV7SKx0GT4Kev~-ObTuG~58WqLYvRUoUpczpThMrvFNpnQCsKiI_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

- Open the project Rmd file `edu-spend-css.Rmd` in R studio, then click "Knit". Alternatively, open the Rmd file and click "Run" -> "Rull All" to run all code blocks.


## Help

Common troubleshooting tips:

- If you encounter issues with library dependencies, ensure all packages are installed and loaded before running the code.
- Data loading errors may indicate that the data files are missing or located in the wrong directory. Please make sure the source data file is placed in the same directory as the project Rmd file.

## Authors

Cheng Zhen

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

This project is the summary project for the Coursera course [Inferential Statistics](https://www.coursera.org/learn/inferential-statistics-intro/home/module/1) by Duke University.
