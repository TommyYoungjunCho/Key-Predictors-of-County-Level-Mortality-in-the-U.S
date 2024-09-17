# Key-Predictors-of-County-Level-Mortality-in-the-U.S

**Project Overview**

This research investigates the variables that lead to deviations in health outcomes at the county level in the United States, with a focus on the role of social determinants of health and environmental factors. The study aims to identify the key predictors of age-adjusted mortality rates and understand the impact of various factors on health outcomes. By utilizing statistical analysis and geographic visualization, the study seeks to provide insights for developing effective public health policies and interventions.

**Technologies Used**

- **Programming Languages**: R
- **Libraries**: dplyr, ggplot2, glmnet, caret, sf
- **Tools**: RStudio, GitHub

**Project Achievements**

- **Comprehensive Analysis**:
    - Successfully integrated and analyzed multiple datasets to identify key predictors of health outcomes at the county level.
    - Employed robust statistical methods to provide clear insights and actionable recommendations.
- **Insightful Visualizations**:
    - Developed geographic visualizations to highlight regions with poor health outcomes, facilitating better-targeted public health interventions.
- **Evidence-Based Recommendations**:
    - Provided practical recommendations for public health policies based on detailed analysis of health behaviors and socioeconomic factors.

**Period**

- 2024.3 ~ 2024.6

**GitHub Repository**

- https://github.com/TommyYoungjunCho/Key-Predictors-of-County-Level-Mortality-in-the-U.S

# Project Details

---

1. **Research Plan:**
    - **Aim**: To identify and explain the predictors of health outcomes at the county level in the U.S. by analyzing factors affecting age-adjusted mortality rates.
    - **Hypothesis**: Social determinants of health have a more substantial impact on health outcomes than environmental factors.
    - **Importance**: Understanding these factors is crucial for developing public health policies and strategies to reduce mortality and improve community health.
    
2. **Literature Review**:
    - **Social Determinants of Health**:
        - **Health Behaviors**: Smoking, physical inactivity, excessive drinking, and poor diet significantly impact health outcomes (Mokdad et al., 2004).
        - **Clinical Care**: Access to quality healthcare services is critical (Shi & Starfield, 2001).
        - **Social and Economic Environment**: Income, education, employment, and social support networks play a significant role in health outcomes (Adler & Ostrove, 1999).
    - **Environmental Conditions**:
        - **Physical Environment**: Factors like air and water quality, housing conditions, and access to green spaces affect health (Brunekreef & Holgate, 2002).
    
3. **Data and Methodology**:
    - **Datasets**:
        - **Primary Dataset**: 2018 County Health Rankings Data.
        - **Additional Data**: Average Household Size and Population Density data, and geographic data from US shapefiles.
    - **Variables**:
        - **Dependent Variable**: Premature age-adjusted mortality rate.
        - **Independent Variables**: Health Behaviors, Clinical Care, Social and Economic Environment, Physical Environment.
    - **Data Preprocessing**: Cleaned and transformed the data, removed rows with missing values, and converted variables to numeric types.
    - **Models**:
        - **Linear Regression**: Used to quantify the impact of independent variables on the dependent variable.
        - **Lasso Regression**: Applied for feature selection by shrinking coefficients of less important variables to zero.
    
4. **Results and Analysis**:
    - **Initial Analysis**:
        - Linear regression indicated the importance of independent variables on age-adjusted mortality in the following order: Health Behaviors, Social/Economic Factors, Clinical Care, Physical Environment.
    - **Hypothesis Testing**:
        - Confirmed that social determinants of health have a greater impact on mortality rates than environmental factors.
    - **Detailed Analysis**:
        - Lasso regression identified the top factors affecting mortality rates, with health behaviors being the most significant.
        - **Key Factors**: Food Environment Index, Smoking Rate, Physical Inactivity Rate, Excessive Drinking Rate.
    - **Geographic Visualization**:
        - Mapped the distribution of health behaviors and mortality rates across U.S. counties, highlighting regions with poor health outcomes, particularly in the southern and southeastern United States.
    
5. **Recommendations**:
    - **Health Behavior Improvement Programs**: Smoking cessation, promotion of physical activity, and alcohol moderation education.
    - **Improvement of Socioeconomic Environment**: Economic support, job creation programs, and expansion of educational opportunities.
    - **Integrated Public Health Policies**: Develop policies that consider both health behaviors and socioeconomic environments.
    - **Region-Specific Approaches**: Tailor policies to the characteristics of each region to address specific causes of mortality.
