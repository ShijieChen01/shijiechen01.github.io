---
layout: single
title: "Collaborative Routing for Multiple Paratransit Operators"
permalink: /projects/collaborative-routing/
author_profile: true
---


**Role:** Lead algorithm designer and developer (in collaboration with IT Curves)

### Background

Paratransit services are often provided by multiple independent operators within the same region.  Because each operator manages its own fleet and bookings, some vehicles run empty while others are overloaded, resulting in wasted miles and higher costs.
<p><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_Map_service.png" alt="Nested decomposition algorithm illustration" style="max-width:60%; height:auto;" /></p>

### Our Solution

I designed a **demand‑exchange platform** that allows operators to share trip requests and optimize routes collaboratively.  The core engine is a mixed‑integer program that generates exchange bundles via column generation and valid inequalities.  The platform bundles compatible requests and reallocates them across fleets to maximize overall utilization.  We built the prototype in GAMS and Python and created a user interface for dispatchers to review suggested exchanges.

### Impact

Pilot experiments showed that participating operators could increase revenue by 8 % and reduce empty‑leg mileage by 12 %.  The collaborative routing concept demonstrates how optimization and coordination mechanisms can unlock value in fragmented mobility markets.

### Get the Paper & Code

A production‑ready version of the platform and open‑source code are under development.

