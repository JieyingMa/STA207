# ReadMe

In this repository, you'll find an HTML file and an Rmd (R Markdown) file. The HTML document presents the finalized analysis, viewable in any web browser for convenience. You can preview the report [here](https://rawcdn.githack.com/JieyingMa/STA207/5f16c54ebd3cc55de30e0469622793d38eb9d305/STA207-final%20report.html). The Rmd file contains the source code, including all statistical analyses and markdown notes. To use these files, open the Rmd in RStudio to modify or further analyze the data. For viewing the analysis, simply open the HTML file in a web browser. These resources are designed for those interested in the detailed statistical analysis and findings of our study. You can have a quick look of what we have done from the following summary.



## Investigation on Grade 1 Math Scores of Different Class Types

### Overview
How class size can affect the quality of teaching and the performance of students is always a hot topic in education. Schools can rationalize class sizes to achieve the best teaching and learning outcomes. Many researches based on the STAR experiment show that small classes have both the short-term impacts (e.g., test score improvement, grade retention reduction) and long-term impacts (e.g., higher graduation rate from high school, lager participation in college entrance exam) on students. In this study, we focus on whether class types effect students math scores in grade 1. And if there is an effect, which class types is related to the highest grade 1 math scores.

### Background
The STAR study investigated the impact of class size on student achievement in Tennessee, using a randomized design to place students in various class sizes from kindergarten through third grade. This section outlines the study's planning, design, and implementation, detailing the random assignment of students and teachers to classes of different sizes to assess the effects on academic performance and development. It highlights the structured approach to eliminate systematic bias, ensuring the reliability of findings on the importance of class size in educational outcomes.

### Descriptive Analysis
A comprehensive analysis of the STAR dataset shows significant findings on class size effects, student demographics, and academic performance, with an emphasis on grade 1 math scores.

#### Uni-variate Descriptive Statistics
The section presents a detailed statistical breakdown of the students' grade 1 performance, highlighting class size, demographic distributions, and score normalization due to missing data.

#### Data Aggregation
Focusing on class-level data aggregation, this part examines the distribution and impact of various factors, including class size and teacher characteristics, on class average math scores.

#### Caveats in Data
Acknowledges limitations in the study's implementation, including deviations from the experimental design and the handling of missing class data and mislabeling of class sizes.

#### Multivariate Description
This section explores the complex relationships between class average math scores, class types, school IDs, and urbanicity, revealing significant disparities and associations.

### Inferential Analysis
Utilizing Two-Way ANOVA and Tukey’s range test, this part provides an in-depth analysis of the factors influencing student math scores, supporting the positive impact of smaller class sizes.

### Sensitivity Analysis
The "Sensitivity analysis" section evaluates the robustness of the statistical model used to analyze class sizes and student math scores. It confirms the model's assumptions through residual analysis, suggesting no significant bias, and performs a Box-Cox transformation for normalization. Additional tests for variable heterogeneity reveal that including more variables does not significantly improve the model, leading to the decision to exclude them from further analysis. This decision is based on the observation that class size is intrinsic to class type and variables such as free lunch and student race are consistent within schools.

### Discussion
Summarizes key insights from the analysis, emphasizing the benefits of smaller class sizes on student performance and the influence of school and teacher characteristics on educational outcomes.

## Repository Structure
- 'STA207-final report.html': The final report of our analysis.
- 'STA207-final report.rmd': The .rmd file of our code.

