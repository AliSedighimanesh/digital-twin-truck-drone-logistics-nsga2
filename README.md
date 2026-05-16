# Digital Twin-Enabled Multi-Objective Truck–Drone Logistics with NSGA-II

This repository contains the data, code, optimization outputs, and figures supporting the article:

**A Digital Twin-Enabled Multi-Objective Optimization Framework for Low-Carbon, Risk-Aware, and Resilient Truck–Drone Logistics in Sustainable Cities**

## Overview

This project develops a digital twin-enabled computational testbed for evaluating sustainable urban truck–drone logistics. The framework uses NSGA-II to generate Pareto-efficient delivery policies across five objectives:

- operational duration;
- CO₂ emissions;
- total road–aerial risk;
- operating cost;
- resilience penalty.

The study focuses on decision-support for sustainable cities by comparing truck-only delivery, greedy truck–drone delivery, and representative NSGA-II policies, including safety-first, balanced, low-carbon, and efficiency-oriented strategies.

## Repository contents

```text
notebooks/       Jupyter notebook used to reproduce the optimization experiment
data/            Synthetic truck–drone logistics instance and scenario data
outputs/tables/  Baseline, Pareto, representative policy, and robustness tables
outputs/pareto/  NSGA-II final population and Pareto-front outputs
outputs/figures/ Manuscript and supplementary figures
supplementary/   Additional supplementary figures
