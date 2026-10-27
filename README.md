# Maintenance Time Allocation Optimisation Using Sensor Data

## Project Overview
An Adelaide University group project exploring how analytics and optimisation can support industrial equipment maintenance planning using the AI4I 2020 Predictive Maintenance Dataset.

## My Contribution
I worked on the optimisation modelling and sensitivity analysis components.

- Applied Integer Linear Programming (ILP) to prioritise maintenance under limited maintenance-hour constraints.
- Analysed what-if scenarios involving maintenance capacity, inspection duration and downtime-cost assumptions.
- Evaluated how changes in inspection duration could improve maintenance coverage.

## Key Finding
Under the project's assumptions, reducing inspection duration from 2 hours to 1.5 hours increased modelled coverage from 20 to 26 machines within a 40-hour maintenance budget — a potential 30% increase.

## Tools and Techniques
Python, Pandas, Scikit-learn, PuLP, Integer Linear Programming, sensitivity analysis and data visualisation.

## Dataset and Limitations
The project used the synthetic AI4I 2020 Predictive Maintenance Dataset. The results are scenario-based estimates, not verified real-world savings. Actual deployment would require validation with operational sensor data, maintenance records and real cost information.

Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)

## Project Context
Completed as a group project at Adelaide University. The contribution described above focuses on optimisation modelling and sensitivity analysis.
