# Yulu - Hypothesis Testing 🚲📈

Welcome to the **Yulu Hypothesis Testing Project**.

**Yulu** is India’s leading micro-mobility service provider, focused on reducing traffic congestion through shared electric cycles for daily commuting.

## About Yulu 🌟

Yulu operates across metro stations, bus stops, office spaces, residential areas, and corporate offices, offering affordable and sustainable transport options.

Recently, Yulu has been facing revenue challenges and partnered with a consulting firm to identify factors influencing the demand for shared electric cycles in the Indian market. This project aims to provide actionable insights.

---

## Project Goals 🤝

- Identify key variables that influence the demand for shared electric cycles.
- Measure how effectively these factors explain rental demand.

---

## Dataset Overview 📊

### Columns:
- `datetime`: Date and time
- `season`: 1 = Spring, 2 = Summer, 3 = Fall, 4 = Winter
- `holiday`: Indicates if the day is a holiday
- `workingday`: 1 = Working day, 0 = Non-working day
- `weather`: Weather conditions
- `temp`: Temperature in Celsius
- `atemp`: Feels-like temperature in Celsius
- `humidity`: Humidity percentage
- `windspeed`: Wind speed
- `casual`: Count of casual users
- `registered`: Count of registered users
- `count`: Total number of cycle rentals (casual + registered)

---

## Statistical Methods Used 📚

- Bi-variate analysis
- 2-sample t-test
- ANOVA
- Chi-square test

---

## Analysis Workflow 🚦

1. Import the dataset and perform exploratory data analysis (EDA).
2. Analyze relationships between the `count` variable and features like `workingday`, `weather`, and `season`.
3. Select suitable statistical tests to determine:
   - Effect of working days on rentals.
   - Seasonal differences in rentals.
   - Impact of weather on rentals.
   - Relationship between weather and seasons.
4. Define hypotheses:
   - Null hypothesis (H₀)
   - Alternative hypothesis (H₁)
5. Check test assumptions (normality, equal variance) using plots or tests like Shapiro-Wilk and Levene’s test.
6. Perform statistical testing and calculate significance levels (alpha).
7. Draw conclusions based on test results.

---

## Objective 🎯

Help Yulu make data-driven decisions to improve micro-mobility services through clear and actionable insights.




