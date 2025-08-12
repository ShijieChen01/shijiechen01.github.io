---
layout: single
title: "Flight‑Level Checked Baggage Prediction"
permalink: /ml-projects/flight-baggage/
author_profile: true
---

**Role:** Lead data scientist (in collaboration with a major airline company in the U.S.)

### Background

Aircraft load planners need accurate forecasts of the number of checked bags a few hours before departure to efficiently palletize and load aircraft. Existing models treat over‑ and under‑prediction errors symmetrically and rarely operate at the individual flight level, leading to operational inefficiencies.

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/project-baggage-prediction.png" alt="Nested decomposition algorithm illustration" style="max-width:60%; height:auto;" /></p>

### Our Approach

Using a proprietary dataset of nearly one million flights from a major U.S. airline and supplemental socio‑economic indicators, I engineered features capturing flight characteristics, booking patterns and regional demographics. I trained multiple models—including multiple linear regression, LightGBM and XGBoost—to predict checked‑baggage counts. Recognizing that under‑prediction is more costly than over‑prediction, we devised a **piecewise quadratic loss function** that penalizes under‑prediction more heavily. Bayesian optimization tuned model hyperparameters for the gradient‑boosting methods.



### Results

The gradient‑boosting models substantially outperformed the baseline linear regression. XGBoost delivered the highest predictive accuracy, while LightGBM achieved comparable performance with significantly lower training times. Incorporating our asymmetric loss function further improved the accuracy of baggage forecasts and provided actionable guidance for planners on selecting the most appropriate model for different flight categories.

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/Baggage_prediction_residual_differCu_MLR.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/Baggage_prediction_residual_MLR_LGBM.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

### Skills Used

Data cleaning, feature engineering, Python, multiple linear regression, LightGBM, XGBoost, custom loss function design and hyperparameter tuning.

### Download the Paper

Read the full research paper [here]({{ site.baseurl }}/files/flight-baggage-paper.pdf).
