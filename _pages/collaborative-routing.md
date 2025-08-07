---
layout: single
title: "Collaborative Routing for Multiple Paratransit Operators"
permalink: /projects/collaborative-routing/
author_profile: true
---


**Role:** Platform architect (in collaboration with IT Curves)

### Background

Paratransit services are often provided by multiple independent operators within the same region.  Because each operator manages its own fleet and bookings, some vehicles run empty while others are overloaded, resulting in wasted miles and higher costs.

### Our Solution

I designed a **demand‑exchange platform** that allows operators to share trip requests and optimize routes collaboratively.  The core engine is a mixed‑integer program that generates exchange bundles via column generation and valid inequalities.  The platform bundles compatible requests and reallocates them across fleets to maximize overall utilization.  We built the prototype in GAMS and Python and created a user interface for dispatchers to review suggested exchanges.

### Impact

Pilot experiments showed that participating operators could increase revenue by 8 % and reduce empty‑leg mileage by 12 %.  The collaborative routing concept demonstrates how optimization and coordination mechanisms can unlock value in fragmented mobility markets.

### Get the Paper & Code

Download the preprint [here]({{ site.baseurl }}/files/integrating-dial-a-ride.pdf).  A production‑ready version of the platform and open‑source code are under development.

<p><img src="{{ site.baseurl }}/assets/img/project-collaborative-routing.png" alt="Collaborative routing illustration" style="max-width:100%; height:auto;" /></p>
