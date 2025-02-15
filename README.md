# Employee Mental Health Clustering Analysis

## Description
This project analyzes employee mental health in the tech industry using clustering techniques. The dataset contains information on employee demographics, mental health perceptions, and work-related factors. Using K-Means clustering, the dataset is segmented into two clusters, uncovering distinct patterns and recommendations for improving mental health support in the workplace.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Data Preprocessing](#data-preprocessing)
- [Clustering Analysis](#clustering-analysis)
  - [K-Means Clustering](#k-means-clustering)
  - [Silhouette Score](#silhouette-score)
- [Results and Insights](#results-and-insights)
  - [Cluster Characteristics](#cluster-characteristics)
  - [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [License](#license)
- [Contributors](#contributors)

## Introduction
The goal of this project is to gain insights into the mental health of employees within the tech industry. The dataset used in this analysis consists of 1259 entries, with 27 attributes, including demographic information, work-related factors, and mental health perceptions. By clustering the dataset using K-Means, the analysis identifies two distinct clusters with differing characteristics, which could help tailor mental health initiatives in the workplace.

## Dataset Overview
The dataset contains the following 19 key attributes:
1. `age`: Employee's age
2. `gender`: Gender of the employee
3. `country`: Country of the employee
4. `self_employed`: Whether the employee is self-employed
5. `family_history`: Whether there is a family history of mental health issues
6. `treatment`: Whether the employee has received treatment for mental health
7. `no_employees`: Number of employees in the company
8. `remote_work`: Whether the employee works remotely
9. `tech_company`: Whether the company is a tech company
10. `benefits`: Whether the employee receives mental health benefits
11. `care_options`: Awareness of mental health care options
12. `wellness_program`: Participation in wellness programs
13. `seek_help`: Whether the employee seeks help for mental health issues
14. `anonymity`: Awareness of anonymity in seeking mental health treatment
15. `leave`: Whether medical leave is available for mental health issues
16. `mental_health_consequence`: Potential consequences for discussing mental health at work
17. `phys_health_consequence`: Potential consequences for discussing physical health at work
18. `coworkers`: Awareness of coworkers' mental health issues
19. `supervisor`: Whether the employee has supportive supervisors

## Data Preprocessing
Before performing the clustering analysis, several preprocessing steps were conducted on the dataset:
1. **Handling Missing Values**: Any missing data points were handled through imputation or removal.
2. **Dropping Columns**: Irrelevant or redundant columns were dropped.
3. **Outlier Detection**: Outliers were detected and handled to ensure the quality of the data.
4. **Encoding**: Categorical variables were encoded to numerical representations suitable for clustering.

## Clustering Analysis

### K-Means Clustering
K-Means was used to partition the dataset into two clusters based on the characteristics of the employees. The optimal number of clusters, `K = 2`, was determined using domain knowledge and exploratory data analysis.

### Silhouette Score
To assess the quality of the clustering, a silhouette score of **0.45024** was achieved, indicating that the clusters are somewhat well-separated and meaningful.

## Results and Insights

### Cluster Characteristics
The clustering results revealed two distinct groups:
- **Cluster 0**: Predominantly older employees with better awareness of mental health benefits and care options. However, they are uncertain about wellness programs and treatment consequences.
- **Cluster 1**: Younger employees who are less informed about mental health benefits and care options. They also share uncertainties regarding wellness programs and potential consequences of discussing mental health at work.

### Recommendations
Based on the characteristics of the two clusters, the following recommendations can be made for improving mental health support in the workplace:

- **For Cluster 0 (Older Employees)**:
  1. **Enhanced Awareness Programs**: Implement targeted awareness programs on wellness initiatives and mental health resources.
  2. **Clear Communication on Benefits**: Ensure that employees are well-informed about available mental health benefits and care options.
  3. **Address Uncertainties**: Provide clear guidelines on anonymity and medical leave for mental health treatment.

- **For Cluster 1 (Younger Employees)**:
  1. **Focused Awareness Initiatives**: Tailor campaigns for younger employees to raise awareness of available mental health resources.
  2. **Information Dissemination**: Improve communication on mental health benefits and care options.
  3. **Clarity in Policies**: Clearly define company policies on mental health-related issues like anonymity and medical leave.

### General Recommendations for Both Clusters:
- Foster an open and supportive work environment where employees feel comfortable discussing mental health issues without fear of stigma or negative consequences.

## Conclusion
The clustering analysis has highlighted significant patterns in mental health awareness and perceptions among employees in the tech industry. Tailored mental health initiatives for different age groups and workplace environments can help improve access to mental health resources and create a supportive workplace culture.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors
- **Steve Marcello Liem**
- **Davin Edbert Santoso Halim**
