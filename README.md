# Automation-of-Concrete-Mix-Design
#### Nebraska Department of Transportation
#### CIVE 202 – Civil Engineering Analysis II
#### Carter Janssen, Luke Moore, Adam Meismer
#### February 24, 2026
#
## Overview
This project automates the Nebraska Department of Transportation (NDOT) concrete mix design workflow by translating the logic contained in the NDOT Mix Design Excel worksheet into a modular Python-based application.
The original Excel tool performs volume-based mix design calculations for one cubic yard of concrete. While accurate, the spreadsheet relies on manual data entry and embedded formulas that are not easily scalable or transparent. The purpose of this project is to:
replicate all engineering calculations in Python,
implement sequential user input prompts,
generate a formatted 1-cubic-yard weight chart,
evaluate four realistic concrete mix scenarios, and
improve transparency, repeatability, and reliability of the workflow.
The automated model mirrors the Excel logic while improving structure, modularity, and documentation.

## Tasks
The translation from Excel to Python was done using a modular approach to program using calculations from the excel sheet. Sequential user input prompts were implemented using structured input() statements to mirror the layout of the Excel worksheet. Verification was performed by running identical input sets through both the original Excel worksheet and the Python script

## Results
SCN-3 provides the highest technical performance potential, SCN-2 offers the best balance of sustainability and durability, SCN-1 serves as a reliable baseline, and SCN-4 prioritizes workability over strength optimization. The water and aggregate weights are identical across all four scenarios with water being 4lb and all aggregates being 17lbs each. 


#
## User Guide
1. Open attached python code file in Jupyter Notebook
2. Run the notebook from top to bottom to initialize functions and scenario definitions.
3. Enter all requred inputs the program asks for
4. Recieve Outputs
