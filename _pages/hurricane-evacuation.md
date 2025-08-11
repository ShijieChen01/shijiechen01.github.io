---
layout: single
title: "Data‑Driven Hurricane Evacuation Decision Modeling"
permalink: /ml-projects/hurricane-evacuation/
author_profile: true
---

**Role:** lead data scientist

### Background

Hurricane evacuation planning has historically relied on theory‑driven discrete choice models and expert judgement. However, these approaches often fail to capture how individual residents actually respond to evacuation orders under evolving storm threats and pandemics.


<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/hurricane-Problem.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/hurricane-TwoMetroRegionsFL-1.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>


### Our Approach

In 2020 we launched a mixed‑mode survey of residents along Florida’s coast during the Atlantic hurricane season. The survey collected demographic attributes, hurricane risk perceptions, COVID‑19 concerns and past evacuation behaviours. After cleaning and encoding responses, we trained supervised learning models—including multinomial logistic regression, random forest and support vector classification—to predict whether a household would evacuate under various storm categories. We also formulated a conceptual optimization framework for government agencies to embed these predictive insights into dynamic evacuation planning.


### Findings

The data revealed that residents’ perception of hurricane risk—not government orders—was the primary driver of evacuation decisions. Random‑forest classifiers achieved the best prediction accuracy, especially when rare response categories were consolidated. COVID‑19 concerns affected where evacuees chose to go rather than whether they left home. These findings suggest that emergency managers should tailor evacuation messaging to local risk perceptions and incorporate data‑driven models into decision support systems.

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/hurricane-dist_pre_destination-1.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/hurricane-dist_evacuation_tendency-1.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/hurricane-compare_destination-1.png" alt="Nested decomposition algorithm illustration" style="max-width:80%; height:auto;" /></p>

### Skills Used

Survey design, data preprocessing, Python, logistic regression, random forest, support vector machines and optimization modeling.

### Download the Paper

Read the full research paper [here]({{ site.baseurl }}/files/hurricane-evacuation-paper.pdf).
