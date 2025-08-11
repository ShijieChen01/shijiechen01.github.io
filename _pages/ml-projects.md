---
layout: single
title: "ML Projects"
permalink: /ml-projects/
author_profile: true
---

<div class="project-block">
  <h3><a href="/ml-projects/flight-baggage/">Flight‑Level Checked Baggage Prediction</a></h3>
  <img src="/assets/img/project-baggage-prediction.png" alt="Flight‑level baggage prediction figure" style="max-width:60%; height:auto;">
  <p><strong>Problem:</strong> Aircraft load planners need accurate forecasts of checked bags a few hours before departure to efficiently palletize and load aircraft. Existing models treat over‑ and under‑prediction errors symmetrically and rarely operate at the individual flight level.</p>
  <p><strong>Approach:</strong> Leveraging a dataset of nearly one million flights from a major U.S. airline and supplemental socioeconomic indicators, I engineered features and trained multiple linear regression, LightGBM and XGBoost models. To reflect airline practice, we devised a piecewise quadratic loss function that penalizes under‑prediction more than over‑prediction. Bayesian optimization tuned model hyperparameters.</p>
  <p><strong>Results:</strong> The gradient‑boosting methods substantially outperformed the baseline linear regression. XGBoost delivered the highest predictive accuracy, while LightGBM achieved comparable performance with significantly less training time. Our asymmetric loss function further improved prediction accuracy and provided guidance on selecting the appropriate algorithm for different flight categories.</p>
  <p><strong>Skills:</strong> Data cleaning, feature engineering, Python, multiple linear regression, LightGBM, XGBoost, custom loss function design and hyperparameter tuning.</p>
</div>


<div class="project-block">
  <h3><a href="/ml-projects/hurricane-evacuation/">Data‑Driven Hurricane Evacuation Decision Modeling</a></h3>
  <img src="/assets/img/project-hurricane-model.png" alt="Data‑driven hurricane evacuation model figure" style="max-width:60%; height:auto;">
  <p><strong>Problem:</strong> Hurricane evacuation planning has traditionally relied on theory‑driven discrete choice models. Few studies employ data‑driven methods to model how individuals comply with government evacuation orders.</p>
  <p><strong>Approach:</strong> In 2020 I co‑designed a mixed‑mode survey of coastal Florida residents during the Atlantic hurricane season, preprocessed the responses and applied supervised learning algorithms—multinomial logistic regression, random forest and support vector classification—to predict whether people would evacuate under various hurricane threats. We also formulated a conceptual optimization model to embed these predictive insights into government‑led evacuation planning.</p>
  <p><strong>Results:</strong> People’s perception of hurricane risk, rather than government orders, emerged as the primary driver of evacuation decisions. COVID‑19 risk played a minor role, influencing only destination choice. Among the models tested, random forest achieved the best classification performance.</p>
  <p><strong>Skills:</strong> Survey design, Python, data preprocessing, supervised learning (logistic regression, random forest, SVM) and optimization modeling.</p>
</div>


