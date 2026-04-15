# Progress Log

## Step 1 - Project setup
- Created project folder in VS Code
- Initialised Git repository
- Added folder structure (data, docs, screenshots)
- Created README.md
- Created .gitignore
- Defined project as a construction cost and performance dashboard

## Step 2 - Created base dataset
- Created Excel workbook for the construction cost dashboard
- Added BoQ sheet with work packages and category-level budgets
- Added monthly actual cost data by category
- Added planned vs actual progress data for 12 months
- Added project summary information
- Structured the workbook to support later EVM calculations and Power BI reporting

## Step 3 - Added EVM calculations
- Created EVM sheet for monthly project performance tracking
- Linked planned and actual progress from the progress sheet
- Calculated Planned Value (PV) and Earned Value (EV)
- Created monthly summary sheet for monthly and cumulative actual cost
- Linked cumulative actual cost (AC) into the EVM model
- Calculated Cost Variance (CV) and Schedule Variance (SV)
- Calculated Cost Performance Index (CPI) and Schedule Performance Index (SPI)

## Step 4 - Power BI cost analysis
- Loaded Excel model into Power BI
- Created category dimension table for proper data modeling
- Built Budget vs Actual cost chart by category
- Built monthly cost trend line chart
- Fixed data type and aggregation issues during visual creation

## Step 5 - Power BI dashboard completion
- Built KPI cards for budget, actual cost, CPI, and SPI
- Created cost analysis visuals by category
- Built monthly cost trend chart
- Developed S-curve for planned vs actual progress
- Added insights interpreting project performance

## Step 6 - Final documentation and portfolio polish
- Updated dashboard insights to match final CPI and SPI values
- Captured dashboard screenshots for GitHub presentation
- Added dashboard preview images to README
- Added key findings summary to README
- Finalised repository structure for portfolio use