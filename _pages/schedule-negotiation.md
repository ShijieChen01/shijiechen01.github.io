---
layout: single
title: "Schedule Negotiation for Paratransit under Uncertainty"
permalink: /projects/schedule-negotiation/
author_profile: true
---

**Role:** Lead algorithm designer and developer (in collaboration with IT Curves)

### Background

Paratransit riders have diverse sensitivities to waiting time. Some users are willing to adjust pickup times for a discount, while others place a high value on punctuality. Traditional scheduling treats all riders the same, leading to mismatched schedules and low vehicle utilization.

### Our Solution

I developed a **non‑convex mixed‑integer nonlinear model** that embeds riders’ value‑of‑time and flexibility parameters directly into the dispatch problem. To solve the large model efficiently, I created a **fix‑and‑optimize heuristic** that alternates between fixing binary variables and re‑optimizing continuous variables. The algorithm negotiates pickup times in real time through the rider mobile app, offering incentives for flexibility. We implemented the solution in Python, GAMS and CPLEX and integrated it into the IT Curves platform.

![Schedule negotiation model illustration](/assets/img/project-schedule-negotiation.png)

### Impact

Field pilots showed a 3.5× return on investment: average solution times fell by 30 %, rider acceptance increased by 20 % and vehicle utilization improved. The module balances efficiency with rider preferences, demonstrating how sophisticated optimization and heuristics can enhance mobility services.

### Skills Used

Python, GAMS, CPLEX, heuristic algorithms.