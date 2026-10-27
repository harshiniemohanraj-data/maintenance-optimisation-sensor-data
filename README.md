# Maintenance Time Allocation Optimisation Using Sensor Data

## Project Overview

An Adelaide University group project exploring how predictive analytics and optimisation can support industrial equipment maintenance planning using the AI4I 2020 Predictive Maintenance Dataset.

## My Contribution

My contribution focused on optimisation modelling and sensitivity analysis.

- Worked on allocating limited maintenance hours to prioritised machines using Integer Linear Programming (ILP).
- Analysed what-if scenarios involving inspection duration, maintenance capacity and downtime-cost assumptions.
- Evaluated how changes in operational assumptions affected maintenance resource allocation.

## Key Finding

Under the project's assumptions, reducing inspection duration from 2 hours to 1.5 hours increased modelled machine coverage from 20 to 26 machines within a 40-hour maintenance budget — a potential 30% increase.

This is a model-based scenario result, not a verified real-world improvement.

## Tools and Techniques

Python, Pandas, Scikit-learn, PuLP, Integer Linear Programming, sensitivity analysis and data visualisation.

## Project Notebook

[View the Jupyter Notebook](notebooks/GROUP_4_PROJECT_1_PART_B.ipynb)

## Dataset

The project used the [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset), a synthetic industrial dataset.

## Limitations

The dataset does not represent actual mine-site operating data. Maintenance durations and downtime costs are assumptions, so the results require validation using real operational data before implementation.

## Project Context

Completed as a group assignment at Adelaide University. The contribution described above focuses on optimisation modelling and sensitivity analysis.
