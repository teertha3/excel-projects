## Car Inventory Data Analysis using Excel

### Objective
To analyze a company car inventory dataset by cleaning raw text data, performing calculations, and generating insights using Excel formulas, pivot tables, and charts.

### Dataset Source
- Raw text dataset obtained from a public GitHub repository:
  - https://github.com/shadsluiter/ExcelExamples
- The dataset was originally provided as a text (.txt) file and imported into Excel for analysis.
- Dataset used strictly for learning and academic purposes.

### Files Included
- **Excel Workbook**: Contains the cleaned dataset, calculations, pivot table, and charts
- **Word Report**: Summarizes key findings with embedded charts exported from Excel

---

### Excel Features & Techniques Used

#### Data Import & Cleaning
- Imported a raw text (.txt) file into Excel using delimiter-based import
- Text-to-columns conversion for structured tabular data
- Corrected data entry errors (e.g., letter ‘O’ vs number ‘0’ in year fields)
- Applied number formatting for mileage values

#### Text & Lookup Functions
- LEFT, MID, RIGHT functions to extract values from Car ID
- CONCATENATE function to generate a new Car ID
- UPPER function to standardize ID formatting
- VLOOKUP with absolute references to map:
  - Manufacturer codes to full names
  - Model codes to full model names

#### Calculations & Logical Functions
- IF function to:
  - Calculate vehicle age correctly across pre-2000 and post-2000 years
  - Determine whether a car is covered under warranty
- Arithmetic formulas to calculate:
  - Vehicle age
  - Miles driven per year
- Adjusted formulas to handle edge cases (e.g., new vehicles)

#### Data Analysis & Visualization
- Pivot Table to summarize total miles driven by each driver
- Column chart created from pivot table results
- Scatter plot showing relationship between:
  - Age of the car (years)
  - Total miles driven
- Added trendline to identify driving patterns
- Conditional formatting to highlight high and low mileage vehicles
- Sorting data to identify most and least driven cars

---

### Key Insights
- Identified drivers with the highest total mileage
- Observed a strong relationship between vehicle age and miles driven
- Detected outlier vehicles with unusually high or low usage
- Determined warranty coverage status for each vehicle

---

### Report Generation
- Exported charts from Excel into a Microsoft Word report
- Created a structured report summarizing:
  - Top drivers by mileage
  - Scatter plot analysis of vehicle usage

---

### Key Learning Outcomes
- Working with raw text datasets in Excel
- Applying advanced Excel formulas for text manipulation and logic
- Using pivot tables for summarization
- Creating analytical charts for decision-making
- Integrating Excel analysis with Word reporting

---

### Tools Used
- Microsoft Excel
- Microsoft Word
