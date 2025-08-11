---
layout: single
title: "Efficient Scheduling System for Paratransit"
permalink: /projects/efficient-scheduling/
author_profile: false
---



**Role:** Lead algorithm designer and developer (in collaboration with IT Curves)

### Background

ADA paratransit services provide door‑to‑door transportation for people with disabilities, but delivering those rides efficiently is challenging.  Legacy scheduling systems treat vehicles as homogeneous and operate on fixed timetables.  As a result, costs per trip are high and many seats go unused, while riders face long wait times.
<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_MRMS screen.png" alt="Nested decomposition algorithm illustration" style="max-width:100%; height:auto;" /></p>

### Our Solution

Working with IT Curves and transit agencies, I led the design of a **nested‑decomposition algorithm** that breaks the large scheduling problem into manageable subproblems.  A column‑generation engine creates candidate vehicle itineraries, and a temporal decomposition layer orchestrates conventional paratransit vans, accessible taxis and ride‑hailing vehicles.  We implemented the algorithm in Python and GAMS, packaged it as a microservice API and integrated it into the existing dispatch platform.
<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_Rolling Horizon Framework.png" alt="Nested decomposition algorithm illustration" style="max-width:50%; height:auto;" /><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_Re-optimization2.png" alt="Nested decomposition algorithm illustration" style="max-width:50%; height:auto;" /></p>

### Impact

The MetroAccess pilot in Washington, DC demonstrated dramatic improvements: **annual operating costs dropped by approximately 15 % (~\$4 million savings)**, on‑time performance improved and riders reported higher satisfaction.  The algorithm has since been commercialized and is being adopted by other transit agencies, showcasing how advanced optimization can deliver tangible value to industry.

<p  style="text-align: center;"><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_routes_before.png" alt="Nested decomposition algorithm illustration" style="max-width:50%; height:auto;" /><img src="{{ site.baseurl }}/assets/img/Efficient_Scheduling_routes_after.png" alt="Nested decomposition algorithm illustration" style="max-width:50%; height:auto;" /></p>
### Get the Paper & Code

You can download the full paper [here]({{ site.baseurl }}/files/empowering-metroaccess.pdf).  The source code for the nested‑decomposition engine will be open‑sourced soon.

