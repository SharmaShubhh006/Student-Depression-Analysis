# Student Depression Data Analysis

## Overview

This project provides a comprehensive analysis of student depression and its relationship with various academic, lifestyle, and psychological factors. Using a rich dataset of student survey responses, the analysis explores how sleep duration, academic pressure, financial stress, and study satisfaction correlate with reported depression rates. The findings aim to inform educators, mental health professionals, and policymakers about key risk factors and potential intervention points.

## Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Key Findings](#key-findings)
- [Detailed Analysis](#detailed-analysis)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Future Work](#future-work)
- [License](#license)
- [Contact](#contact)

## Dataset Description

The dataset consists of anonymized survey responses from students, with the following key variables:

| Variable                        | Description                                              |
|----------------------------------|----------------------------------------------------------|
| Gender                          | Student's gender                                         |
| Age                             | Student's age                                            |
| Academic_Pressure               | Self-reported academic pressure (1–5 scale)              |
| Study_Satisfaction              | Satisfaction with study experience (1–5 scale)           |
| Sleep_Duration                  | Average nightly sleep (categorized)                      |
| Dietary_Habits                  | Self-reported dietary habits                             |
| Suicidal_Thoughts               | History of suicidal thoughts (True/False)                |
| Study_Hours                     | Weekly study hours                                       |
| Financial_Stress                | Self-reported financial stress (1–5 scale)               |
| Family_History_of_Mental_Illness| Family history of mental illness (True/False)            |
| Depression                      | Self-reported depression (Yes/No)                        |
| Age_group                       | Age group category                                      |

## Key Findings

- **Depression Prevalence:** The dataset is nearly balanced, with 252 students reporting depression and 250 not reporting depression.
- **Sleep Duration:** Depression rates are similar (~52%) for students sleeping less than 5, 5–6, or 7–8 hours. Students sleeping more than 8 hours have a lower depression rate (45%).
- **Academic Pressure:** Depression rates increase sharply with academic pressure, from 17% (lowest pressure) to 85% (highest pressure).
- **Financial Stress:** Higher financial stress is associated with higher depression rates, rising from 31% (lowest stress) to 71% (highest stress).
- **Study Satisfaction:** Students with the lowest study satisfaction have the highest depression rates (73%), while those with the highest satisfaction have the lowest rates (31%).

## Detailed Analysis

### Depression by Sleep Duration

| Sleep Duration      | Depression Rate |
|---------------------|----------------|
| Less than 5 hours   | 52%            |
| 5–6 hours           | 52%            |
| 7–8 hours           | 52%            |
| More than 8 hours   | 45%            |

- Students sleeping more than 8 hours show a notably lower depression rate.

### Depression by Academic Pressure

| Academic Pressure (1–5) | Depression Rate |
|-------------------------|----------------|
| 1 (Lowest)              | 17%            |
| 2                       | 31%            |
| 3                       | 50%            |
| 4                       | 67%            |
| 5 (Highest)             | 85%            |

- Depression risk rises dramatically with increased academic pressure.

### Depression by Financial Stress

| Financial Stress (1–5) | Depression Rate |
|------------------------|----------------|
| 1 (Lowest)             | 31%            |
| 2                      | 38%            |
| 3                      | 52%            |
| 4                      | 63%            |
| 5 (Highest)            | 71%            |

- Financial stress is a strong predictor of depression risk.

### Depression by Study Satisfaction

| Study Satisfaction (1–5) | Depression Rate |
|--------------------------|----------------|
| 1 (Lowest)               | 73%            |
| 2                        | 62%            |
| 3                        | 50%            |
| 4                        | 40%            |
| 5 (Highest)              | 31%            |

- Higher study satisfaction is associated with lower depression rates.



*This analysis aims to support data-driven decisions in student mental health and academic support initiatives.*

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d9aeaf69-addc-407d-83fc-2c646d35d186" />
