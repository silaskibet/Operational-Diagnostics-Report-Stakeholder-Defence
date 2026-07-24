# Operational Diagnostics Report & Stakeholder Defence

## Description
This repository contains the deliverables for the Week 5 Operational Diagnostics and Analysis project. The project involves investigating a "Mystery Ops Dataset" to identify operational bottlenecks, perform root cause analysis, and communicate these findings effectively to stakeholders through both a written report and a simulated video presentation. It also includes reflections on peer feedback and a recent hackathon.

## Repository Contents
Based on the project requirements and the repository structure, this repository contains the following files:

*   **`week5_diagnostics_analysis.ipynb`**: The primary Jupyter Notebook containing the Python code for the technical coding challenge. It includes:
    *   **Data Profiling**: Complete univariate and bivariate analysis, summary statistics, missing value checks, and distribution plots.
    *   **Anomaly Detection**: Identification and visualization (via Box/Scatter plots) of significant outliers.
    *   **Root Cause Analysis**: Drill-down analysis, Pareto Analysis to quantify impacts, and Correlation Analysis to evaluate drivers.
    *   **Visualizations**: Publication-quality charts built using Seaborn or Plotly.
    *   **Documentation**: Markdown cells detailing the investigation process and rationale.
*   **`Week5_Diagnostics_Report_SilasKibet.pdf`**: A 2-page executive summary directed at a busy Operations Director. It provides context for the operational problem, states the root cause supported by embedded charts, and offers 2-3 actionable recommendations without technical jargon.
*   **`Week5_Presentation_SilasKibet.mp4`**: A 5-7 minute stakeholder defence video presentation. It includes a simulated segment answering a sceptical question from a Director ("Are you sure?") backed by data.
*   **`pod_feedback.md`**: A brief summary of the feedback received during the Peer Pod Role-Play session (acting as "Sceptical Directors") and notes on how the argument was improved based on that feedback.
*   **`hackathon_reflection.md`**: A 200-word reflection addressing team performance during Hackathon #1. It covers the biggest technical hurdles faced, resolutions, and lessons learned for future teamwork.

## Project Structure & Methodology

### Part A: Technical Diagnostics
The analysis focuses heavily on exploratory data analysis (EDA) to find where operations are failing. Through grouping by time, location, and category, the notebook isolates the core problem and proves the top drivers using the Pareto principle and correlation checks. 

### Part B: Stakeholder Communication
Data science is only as good as its communication. The PDF report and video presentation synthesize the heavy technical analysis from Part A into actionable, business-friendly insights targeted at executive decision-makers.

### Part C & D: Collaboration & Reflection
Continuous improvement is documented through peer feedback (`pod_feedback.md`) and a retrospective on the recent technical hackathon (`hackathon_reflection.md`).

## Author
*   **Silas Kibet**
