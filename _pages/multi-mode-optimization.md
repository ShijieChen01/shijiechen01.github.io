---
layout: single
title: "Multi‑Mode Paratransit Optimization"
permalink: /projects/multi-mode-optimization/
author_profile: true
---


**Role:** Lead developer (in collaboration with IT Curves)

### Background

ADA paratransit services traditionally rely on a fleet of dedicated vehicles.  However, these fleets can be costly to maintain and cannot flexibly meet surging demand.  Meanwhile, ride‑hailing and taxi services have spare capacity that remains untapped.

### Our Solution

I collaborated with colleagues to extend mixed‑integer optimization models to integrate ride‑hailing and taxi modes into the paratransit dispatch problem.  We gathered and cleansed real trip data along with transportation‑network‑company supply information.  Heuristics were developed to warm‑start GAMS solves, dramatically speeding up convergence.

### Impact

In production use, the multi‑mode optimization delivered 13 % cost savings and reduced solve times by 25 % while expanding service coverage during peak periods.  By harnessing third‑party services, transit agencies can provide more responsive and cost‑effective transportation to riders.

### Get the Paper & Code

This project builds upon the research *Integrating Dial‑a‑Ride with Transportation Network Companies for Cost Efficiency*.  Download the paper [here]({{ site.baseurl }}/files/integrating-dial-a-ride.pdf).  The optimization code will be published as open source in a forthcoming release.

<p><img src="{{ site.baseurl }}/assets/img/project-multi-mode.png" alt="Multi‑mode optimization illustration" style="max-width:100%; height:auto;" /></p>
