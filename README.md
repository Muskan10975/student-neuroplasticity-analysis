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

* **Muskan Irfan (Main Author):** Lead Researcher who conceptualized, designed, and led the entire research study lifecycle. Formulated the hypotheses, structured the research questions, spearheaded the questionnaire design, directed the data analysis workflow (descriptive statistics, scale construction, and reliability checks), and authored the final comprehensive report.
* **Muhammad Yasir Qurashi:** Data Analyst who collaborated closely with the lead author to execute the inferential statistics phase, constructing the bivariate correlation matrices and building the multiple linear regression models.
* **Mehak Irfan:** Co-researcher who assisted in the comprehensive literature review, contributed directly to the structural layout of the survey, and actively managed the participant data collection phase.
* **Muhammad Ahsan Islam:** Co-researcher who contributed to the collaborative survey questionnaire design and assisted in distributing the survey for targeted data collection.
* **Hamza Mumtaz:** Co-researcher who supported the initial framework design of the survey instrument and helped coordinate data collection efforts.
* **Tooba Noor:** Co-researcher who assisted in drafting the survey questionnaire items and participated in the data collection process.
* **Asma Abbas:** Co-researcher who contributed to the survey development phase and assisted the team in gathering participant responses.
* **Falak Sajjad (Supervisor):** Research Supervisor who provided vital academic guidance, methodological oversight, and structural direction to the student research team throughout the study's design and analysis stages.
