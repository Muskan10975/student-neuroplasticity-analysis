# Student Neuroplasticity, Cognition, and Academic Performance Analysis

This repository contains the statistical data analysis, regression workflows, and empirical findings evaluating how daily habits and potential neuroplasticity-enhancing practices impact cognitive traits and academic success among university students.

## 📌 Project Overview
While existing literature thoroughly establishes predictive links between cognitive variables and student outcomes, this project bridges the gap by providing direct survey data analysis mapping everyday routines directly to standardized behavioral scales. 

* **Sample Size ($N$):** 212 University Students
* **Software Used:** IBM SPSS Statistics

---

## 📊 Variables & Framework

The study structured variables into three distinct core roles to map out behavioral relationships:

### A. Independent Variables (Neuroplasticity-Related Practices)
* `sleep_hours`: Average uninterrupted sleep hours (Ordinal numeric scale)
* `exercise_improve_cognition`: Perceived cognitive benefits of physical exercise
* `nutritional_balanced_freq`: Frequency of consuming balanced meals
* `nature_improve`: Perceived cognitive benefits of exposure to nature
* `creative_activities_benefits`: Benefits from art, music, or writing
* `extracurricular_activities`: Direct participation in extracurricular/professional activities

### B. Mediating Scale Construct Variables
* `cognitive_engagement`: Multi-item scale tracking cognitive engagement in learning
* `emotional_regulation`: Multi-item scale assessing emotional self-regulation capacities

### C. Outcome Variable
* `academic_Performance`: Combined scale score measuring learning habits and self-reported performance reflects.

*Note: Scale internal consistency and reliability were thoroughly verified using Cronbach's Alpha prior to computing composite mean scores.*

---

## 📈 Analysis & Core Findings

### 1. Predicting Cognitive Engagement (Model $R^2 = 29.6\%$)
Multiple linear regression indicates that lifestyle practices significantly predict a student's cognitive engagement levels:
* **Significant Positive Predictors:** Physical exercise ($p < .001$), Extracurricular activities ($p = .001$), Nature exposure ($p = .002$), and Creative activities ($p = .013$).
* **Non-Significant Predictors:** Sleep hours and nutrition did not show direct predictive effects within this multi-variable model.

### 2. Predicting Emotional Regulation (Model $R^2 = 66.0\%$)
* Nature exposure emerged as a remarkably strong positive predictor ($t = 16.664, p < .001$).
* Physical exercise that improves cognition also acted as a significant positive predictor ($p < .001$).

### 3. Mediation & Academic Outcomes (Model $R^2 = 17.3\%$)
* **Cognitive engagement** acts as a significant positive predictor of ultimate academic performance ($t = 5.360, p < .001$).
* **Mediation Effect:** Cognitive engagement **partially mediates** the positive relationship between active neuroplasticity practices (exercise, nature, creative habits) and student academic success. 
* **Direct Impact:** Extracurricular activities remain the strongest single direct predictor of total academic performance outcomes ($t = 3.785, p < .001$).

---

## 👥 Authors & Contributions
* **Muskan Irfan (Main Author):** Conceived and designed the entire study framework, hypotheses, literature review, survey methodology, and authored the final comprehensive analysis report.
* **Muhammad Yasir Qurashi:** Executed the data analysis workflow, scale coding, reliability checks, and multiple linear regression models.
* **Muhammad Ahsan Islam:** Contributed to the literature review, research question design, survey formulation, and data collection.
* **Mehak Irfan:** Contributed to the conceptual framework, research question design, survey methodology, and data collection.
