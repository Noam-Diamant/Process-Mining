# Process Mining Project: Sepsis Cases Event Log

## Overview
This project applies process mining techniques to a real-world healthcare dataset: the Sepsis Cases Event Log. The goal is to analyze, visualize, and extract insights from patient treatment processes using event logs, leveraging both data science and process mining methodologies.

## Repository Contents
- **sepsis_project.ipynb**: Main Jupyter notebook containing all data analysis, process mining, and visualization code.
- **Sepsis Cases - Event Log.csv**: The primary event log dataset in CSV format.
- **Sepsis Cases - Event Log.xes**: The event log in XES format, suitable for process mining tools.
- **report.docx / report.pdf**: Project report summarizing methodology, findings, and conclusions.
- **Sepsis Cases – Event Log.pptx**: Presentation slides summarizing the project and results.

## Dataset Description
The Sepsis Cases Event Log contains anonymized records of patient treatment events in a hospital. Each row represents an event (e.g., admission, lab test, discharge) with attributes such as:
- **Case ID**: Unique identifier for each patient case
- **Activity**: The event or action performed
- **Timestamp**: When the event occurred
- **Resource**: Who performed the event (if available)
- **Other attributes**: Additional context (e.g., diagnosis, outcome)

## Project Workflow
1. **Data Loading & Exploration**
   - Load the event log (CSV/XES) and inspect its structure
   - Explore case statistics, event types, and data quality
2. **Preprocessing**
   - Handle missing values, filter incomplete cases, and format timestamps
   - Convert data for use with process mining libraries (e.g., PM4Py)
3. **Process Discovery**
   - Apply algorithms (e.g., Alpha Miner, Heuristic Miner, Inductive Miner) to discover process models
   - Visualize the discovered process maps and control-flow graphs
4. **Conformance Checking**
   - Compare real event logs to reference models to identify deviations
   - Analyze bottlenecks, rework, and compliance issues
5. **Performance Analysis**
   - Calculate throughput times, waiting times, and resource utilization
   - Visualize key performance indicators (KPIs) and process variants
6. **Reporting & Presentation**
   - Summarize findings in the report and presentation
   - Provide actionable insights for process improvement

## How to Run
1. Install dependencies (see below)
2. Open `sepsis_project.ipynb` in Jupyter Notebook or JupyterLab
3. Run the notebook cells in order to reproduce the analysis and visualizations

## Dependencies
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- PM4Py (for process mining)
- Jupyter Notebook

## References
- [PM4Py Documentation](https://pm4py.fit.fraunhofer.de/)
- [Sepsis Cases Event Log Dataset](https://data.4tu.nl/articles/dataset/Sepsis_Cases_-_Event_Log/12707639)

## Authors
- Noam Diamant

---
This project demonstrates the application of process mining to healthcare data, providing insights into patient treatment pathways and opportunities for process optimization.
