# Rota Automation with Python

## Overview
This project automates the generation of staff rotas using Python and Excel data inputs. It is designed to handle complex scheduling constraints, such as alternating shifts, weekend coverage rules, and soft/hard preferences. The notebook applies optimisation logic to assign people to shifts fairly and efficiently.

## Objective
To develop a data-driven rota scheduling tool that reduces manual work, ensures fair distribution of shifts, and allows for easy adaptation to future rule changes.

## Tools Used
- **Python (Jupyter Notebook)**
- **Excel** for input data
- **Pandas** for data wrangling
- **NumPy** for calculations
- **Constraint Programming (Google OR-Tools / Custom Logic)**
- **Power BI** (Visuals folder) for presenting outputs

## Project Structure
Rota-Automation/
├── Complex Rota Solution.ipynb # Jupyter notebook with the automation logic
├── rota_data.xlsx # Input data including staff, shifts, rules
├── Visuals/ # Screenshots from Power BI showing final results
├── README.md # This file

## Features
- Reads rota inputs from Excel
- Applies logic for fair distribution of shifts
- Handles alternating patterns (e.g. Derek and Heather)
- Accounts for weekend-specific constraints
- Exports or displays rota-ready outputs
- Visual output generated in Power BI for reporting

## Example Visuals
Some of the visuals created for the rota output are located in the `Visuals/` folder:
- Heatmaps showing staff coverage
- Daily shift assignment breakdowns
- Coverage vs requirement visuals

## Outcome
- Significantly reduced manual rota-building time
- Introduced a repeatable, adaptable rota generation process
- Visualised and validated coverage vs staffing needs

## Next Steps
- Add logic for public holidays and absences
- Build a Power App UI for interactive rota generation
- Push results automatically to Power BI via automation

## Getting Started
To run this notebook locally:
1. Clone this repository
2. Open `Complex Rota Solution.ipynb` in Jupyter
3. Ensure `rota_data.xlsx` is in the same folder
4. Run the notebook to generate the output rota

---
