# Student Lifestyle & Academic Performance Analysis

## Project Overview

A comprehensive statistical analysis examining the relationship between lifestyle factors and academic success among 2,000 university students. This project applies advanced statistical methods, including correlation analysis, Central Limit Theorem demonstration, and multiple sampling techniques, to identify key predictors of student performance.

---

## Key Findings

- **Study Hours Drive Success**: Strong positive correlation (r = 0.734) between daily study hours and grades
- **Stress-Performance Trade-Off**: High-stress students achieve the highest grades (8.39/10) but sacrifice sleep (7.05 hrs/night)
- **Gender-Neutral Patterns**: No significant differences in lifestyle patterns between male and female students
- **Time Allocation**: Students sacrifice exercise time for study time (r = -0.488)

---

## Dataset Information

- **Source**: [Kaggle Student Lifestyle Dataset](https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset)
- **Size**: 2,000 students
- **Variables**: Study hours, sleep patterns, physical activity, social time, stress levels, grades
- **Data Quality**: Clean dataset with 0% missing values

**Note**: This repository includes the Dataset under Apache 2.0 license.

---

## Technologies & Methods

### Programming & Tools
- **R** - Statistical analysis and data processing
- **R Markdown** - Reproducible research documentation
- **plotly** - Interactive data visualizations
- **ggplot2** - Statistical graphics

### Statistical Methods
- Correlation analysis (Pearson)
- Central Limit Theorem demonstration
- Stratified & simple random sampling
- ANOVA and regression modeling
- Distribution analysis

### R Libraries Used
```r
library(plotly)      # Interactive visualizations
library(dplyr)       # Data manipulation
library(tidyverse)   # Data science toolkit
library(reshape2)    # Data reshaping
library(knitr)       # Report generation
```

---

## Analysis Components

### 1. Single Variable Analysis
- Stress level distribution (51.4% high stress)
- Grade distribution (normal, mean = 7.79)
- Gender demographics

### 2. Multi-Variable Analysis
- Study hours vs grades correlation
- Stress level impact on performance
- Lifestyle pattern comparisons

### 3. Statistical Validation
- Central Limit Theorem verification
- Sampling methods comparison
- Performance category segmentation

### 4. Correlation Analysis
- Complete correlation matrix
- Interactive heatmap visualization
- Factor relationship identification

---

## Key Insights & Recommendations

### For Students
- Aim for 7-9 study hours daily while maintaining 7-8 hours of sleep
- Balance academic effort with wellness activities
- Monitor stress levels and sleep quality

### For Educators
- Monitor high-achieving students for signs of sleep deprivation
- Implement time management workshops
- Create stress reduction programs

### For Institutions
- Develop sustainable academic success programs
- Balance academic rigor with student well-being
- Gender-neutral support strategies are effective

---

## Repository Structure
```
student-lifestyle-performance-analysis/
├── README.md                          # Project overview
├── CS544Final_Morshedi.Rmd           # R Markdown analysis code
├── CS544Final_Morshedi.html          # Rendered HTML report
├── student_lifestyle_dataset.csv      # Source dataset
└── LICENSE                            # MIT License
```

---

## How to Run This Analysis

### Prerequisites
- R (version 4.0 or higher)
- RStudio (recommended)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/morshediem-mm/student-lifestyle-performance-analysis.git
```

2. Install required R packages:
```r
install. packages(c("plotly", "dplyr", "tidyverse", "reshape2", "knitr"))
```

3. Open `CS544Final_Morshedi.Rmd` in RStudio

4. Click "Knit" to generate the HTML report

---

## Statistical Highlights

- **Normal Distribution**: Grade distribution validates parametric methods
- **Central Limit Theorem Verified**: Sample means SD (0.132) approximately equals theoretical SD (0.136)
- **Sampling Reliability**: All methods produce estimates within 0.073 points of population parameters
- **Strong Predictors**: Study hours (r = 0.734), Physical activity (r = -0.341)

---

## About This Project

This analysis was completed as part of my MS in Health Informatics program at Boston University (CS544). It demonstrates proficiency in statistical analysis, data visualization, reproducible research practices, and R programming.

---

## Author

**Elham Morshedi Meibodi**  
MS Health Informatics | Healthcare Data Analyst  
DDS with 10+ years of clinical experience

[LinkedIn](https://linkedin.com/in/elham-morshedi-meibodi-dmd) | [Email](mailto:morshediem@gmail.com) | [Google Scholar](https://scholar.google.com/citations?user=NAKEQVMAAAAJ)

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgments

Dataset Citation:
```
Sumit Kumar. (2024). student lifestyle dataset. Kaggle. 
https://doi.org/10.34740/KAGGLE/DSV/9876359
```

- Course: CS544 - Foundations of Analytics & Data Visualization
- Institution: Boston University Metropolitan College
- Dataset License: Apache 2.0

---

*Last Updated: October 2025*
```

---
