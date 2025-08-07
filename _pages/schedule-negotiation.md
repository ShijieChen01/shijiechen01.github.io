---
layout: single
title: "Schedule Negotiation for Paratransit under Uncertainty"
permalink: /projects/schedule-negotiation/
author_profile: true
---

<p><img src="{{ site.baseurl }}/assets/img/schedule-negotiation.png" alt="Schedule negotiation illustration" style="max-width:100%; height:auto;" /></p>

**Role:** Principal investigator and lead algorithm designer (IT Curves)

### Background

Paratransit riders have different sensitivities to waiting time.  Some users are willing to adjust pickup times for a discount, while others place a high value on punctuality.  Traditional scheduling treats all riders the same, leaving operators with mismatched schedules and low vehicle utilization.

### Our Solution

I developed a **non‑convex mixed‑integer nonlinear model** that embeds riders’ value‑of‑time and flexibility parameters directly into the dispatch problem.  To solve the large model efficiently, I created a **fix‑and‑optimize heuristic** that alternates between fixing binary variables and re‑optimizing continuous variables.  The algorithm negotiates pickup times in real time through the rider mobile app, offering incentives for flexibility.  We implemented the solution in Python, GAMS and CPLEX and integrated it into the IT Curves platform.

### Impact

Field pilots showed a 3.5× return on investment: average solution times fell by 30 %, rider acceptance increased by 20 % and vehicle utilization improved【396237119823057†L69-L90】.  The module balances efficiency with rider preferences, demonstrating how sophisticated optimization and heuristics can enhance mobility services.

### Get the Paper & Code

You can download the full paper [here]({{ site.baseurl }}/files/schedule-negotiation.pdf).  The negotiation algorithm will be released as open‑source software in the future.