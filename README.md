# Train Service Punctuality

## Overview

This project examines the punctuality of train services in Great Britain from 2014 to 2023, focusing on whether there is a significant difference in punctuality between national and operator-specific train services. The analysis emphasizes the percentage of trains arriving within 15 minutes of their scheduled time.

## Research Question

- **Is there a significant difference in train punctuality between national and operator-specific services?**

Delays in train services are commonly attributed to three main factors:
1. Operator-related causes,
2. Network infrastructure issues,
3. External factors (e.g., weather or disruptions).

This study aims to explore how these factors contribute to differences in punctuality between the two service groups.

## Hypotheses

- **Null Hypothesis (H₀):**  
  There is no significant difference in train punctuality between national and operator-specific services.

- **Alternative Hypothesis (H₁):**  
  There is a significant difference in train punctuality between national and operator-specific services.

## Dataset

The dataset is sourced from **Network Rail** and spans train punctuality records from 2014 to 2023. Key columns include:
- **National or Operator**: Classification of service type.
- **Trains arriving within 15 minutes (percentage)**: Measure of punctuality.
- Additional attributes relevant to service operations.

## Analysis Workflow

1. **Data Cleaning**:
   - Identifying duplicates and null values.
   - Splitting the dataset into "National Services" and "Operator Services" groups.

2. **Visualization**:
   - Using Seaborn and Matplotlib to visualize the distribution of punctuality for each group.

3. **Hypothesis Testing**:
   - Conducting Welch’s t-test to compare the means of the two groups.

## Results

- Welch’s t-test revealed a statistically significant difference between the two groups, with a p-value of **6.26e-25** (p < 0.05).
- The analysis indicates that operator-specific services have a noticeable impact on train punctuality.

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/deji-dylan/train-service-punctuality.git


## Key Findings

Train punctuality varies significantly between national and operator-specific services.

Suspended services during the COVID-19 pandemic likely influenced punctuality trends.

These insights align with earlier research that highlights the role of operators in service reliability.

## Future Work

Explore the impact of external factors (e.g., weather or regional disruptions) on train punctuality.

Integrate more recent datasets to analyze post-pandemic trends.

Develop predictive models for punctuality using machine learning.

## References

Khattak, A., Wang, X., Son, S., & Agnello, P. (2011). Travel by University Students in Virginia. Transportation Research Record, 2255(1), 137–145.

Preston, J., Wall, G., Batley, R., Ibáñez, J. N., & Shires, J. (2009). Impact of Delays on Passenger Train Services. Transportation Research Record, 2117(1), 14–23.

## Acknowledgements

Special thanks to Network Rail for the dataset and inspiration drawn from previous research in the transportation sector.
