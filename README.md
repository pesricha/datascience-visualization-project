# Delhi Education Data Analysis 2023-24

## Overview
This project analyzes district-wise education statistics for Delhi during the 2023-24 academic year, focusing on school enrollment, pass percentages, and quality indices for Class X and XII examinations.

## Data Source
**Dataset**: District wise Number of Schools, Student Enrollment and Pass Percentage for Class X and XII in Delhi during 2023-2024

**Source**: Government of India Open Data Platform  
**URL**: https://www.data.gov.in/resource/district-wise-number-schoolsstudent-enrollment-and-pass-percentage-class-x-and-xii-delhi  
**Data Format**: CSV  
**License**: Government Open Data License - India (GODL)

## Project Structure
```
datascience-visualization-project/
├── Delhi_Government_School_Details.ipynb  # Main analysis notebook
├── EducationDataset_2023-24.csv          t
├── README.md                             
└── plots/                                
    ├── scatter_plot.png               
    ├── box_plot.png                   
    └── bar_line_plot.png               
```

## Analysis Components

### 1. Scatter Plot Analysis
**Purpose**: Examine the relationship between student enrollment numbers and pass percentages  
**Key Findings**:
- Negative correlation between enrollment size and pass percentage
- Class X correlation: -0.437 (moderate negative)
- Class XII correlation: -0.227 (weak negative)
- Indicates potential resource strain in high-enrollment districts

### 2. Box Plot Analysis
**Purpose**: Analyze distribution patterns and identify outliers in educational performance  
**Key Findings**:
- Class XII consistently outperforms Class X (97.22% vs 94.92% average)
- Quality indices show significant variation across districts
- One outlier district in Class XII quality index identified

### 3. Bar/Line Plot Analysis
**Purpose**: Compare infrastructure and demographic distribution across Delhi districts  
**Key Findings**:
- East District has highest enrollment (189,406 students, 121 schools)
- Student-to-school ratios vary from 432 to 2,644 across districts
- Gender distribution remains relatively balanced across all districts

## Key Insights and Observations

### Educational Performance
- **High Overall Performance**: Pass percentages exceed 89% for Class X and 94% for Class XII
- **Consistency**: Relatively stable performance across different districts
- **Class Progression**: Students show improvement from Class X to Class XII

### Resource Distribution
- **Infrastructure Gaps**: Significant variation in student-to-school ratios
- **Capacity Constraints**: High-enrollment districts face potential overcrowding
- **Resource Allocation**: Need for targeted infrastructure development

### Policy Implications
1. **Infrastructure Development**: Focus on districts with high student-to-school ratios
2. **Quality Assurance**: Investigate factors contributing to performance variations
3. **Resource Optimization**: Learn from high-performing districts for best practices


## Citations and References

### Data Citation
Government of India. (2024). *District wise Number of Schools, Student Enrollment and Pass Percentage for Class X and XII in Delhi during 2023-2024*. Open Government Data (OGD) Platform India. Retrieved from https://www.data.gov.in/resource/district-wise-number-schoolsstudent-enrollment-and-pass-percentage-class-x-and-xii-delhi


### Government Data License
This analysis uses data published under the Government Open Data License - India (GODL), which permits use, distribution, and reproduction of the data for research and analysis purposes.


---
*This analysis was conducted as part of a __DS200 Research Methods__ assignment focusing on exploratory data analysis of government education datasets.*