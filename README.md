# Life Expectancy at Birth
Males and Females datasets across different regions with the details of life expectancy across the decades. 

## Description

This report analyzes the Adult Income dataset to explore income inequalities tied to
demographic factors such as race, gender, age, and others. The dataset contains 48,842
entries, with no missing values after preprocessing. Key findings include an average age
of 38.64 years, a predominantly wage-dependent sample, and a significant
representation of White (85.5%) and male (66.9%) individuals. These demographics
suggest potential biases in income distribution.

We used logistic regression and random forest models to predict income. Logistic
regression struggles with class imbalance, while the random forest model achieves 85%
accuracy, with better precision and recall for high-income predictions (>50K). However,
its 61% recall for the >50K class indicates challenges in accurately identifying high
earners, particularly females, blacks, and other people from underrepresented groups.
The analysis highlights systemic income disparities tied to race and gender, reflecting
broader societal inequities.

## Usage

- Open the notebook updated-colab-notebook.ipynb in Google Colab.
- Follow the steps in the notebook to load the dataset and run the analyses.
- Modify the parameters in the code cells to explore different aspects of the data.

## Dataset 

The dataset used in this project is sourced from World Health Organization Website 
https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/ghe-life-expectancy-and-healthy-life-expectancy 
It includes demographic information, location, and other relevant features for analyzing life expectancy across
the region.

## Installation
To set up this project locally:
1. Clone the repository:
   ```bash
   git clone git@github.com:ahmeraza/WHO-Life-Expectancy.git
```