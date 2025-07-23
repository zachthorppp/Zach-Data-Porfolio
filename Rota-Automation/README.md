*Rota Automation with Python, Power BI, and Power Platform**


**Overview**

This project automates the creation of staff rotas based on a set of business constraints such as rest days, fair shift distribution, and weekend coverage. Originally a time-consuming manual task, the new system I developed saves 0.7 FTE in manager time and improves clarity and access through visual dashboards.

The rota is generated using a Python script, exported to Excel via a PowerAutomate flow, and visualised through an interactive Power BI dashboard, which is embedded in PowerApps to allow users to easily view shift patterns and summaries.


**Tools \& Technologies**

\- Python – rota generation logic and excel output

\- Pandas – data handling

\- Excel – data input/output for Power BI

\- Power BI – visualisation of shift patterns and summaries

\- Power Automate – trigger the flow and produce JSON output


**Workflow**

1\. Triggered in PowerAutomate/Apps by Holiday uploads or manual trigger

2\. POST to Azure Functions with Holiday information as the body

3\. Creates the rota pattern and produces back a JSON

4\. JSON converted to excel in PowerAutomate

5\. PowerBI uses data to build report

6\. PowerBI refreshes and teams use the PowerBI report 


**File Structure for portfolio to share example**

rota-automation/

├── complex_rota_solution.py   # Main script for rota logic         

├── rota_data.xlsx             # Example of a generated rota data table

├── visuals/

│   ├── dashboard\_screenshot.png

│   └── rota.xlsx

└── README.md                   # Project overview (this file)


**Dashboard Highlights**

The Power BI dashboard includes:

\- Daily shift coverage overview

\- Shift summary per person (total shifts, weekends, rest days)


**Key Features**

\- Automated rota creation with constraint handling

\- Dynamic visual summaries for shift fairness and coverage

\- Eliminates manual scheduling work

\- Enables clear communication through integrated tools


**Business Impact**

\- Saved approx. 0.7 FTE in manager capacity

\- Improved accuracy, fairness, and transparency

\- Enabled repeatable, auditable process

\- Supported cultural shift toward data-led planning






