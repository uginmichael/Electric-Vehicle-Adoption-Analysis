# Electric Vehicle Adoption Analysis

## 1. Problem Statement

To analyze electric vehicle (EV) adoption trends in India by studying registrations, sales share, state-wise adoption, vehicle categories, and battery prices using data analysis and visualization.

## 2. Dataset Source and Description

**Official Reference Source:** [Government of India – VAHAN Dashboard](https://vahan.parivahan.gov.in/vahan4dashboard/)

The project uses an Excel dataset named `EV_Adoption_Messy_and_Cleaned_Dataset.xlsx`, containing a `Cleaned Dataset` sheet with information about EV registrations, sales share, market penetration, and battery prices.

*Note: The VAHAN dashboard is provided as a reference source; the uploaded Excel dataset is not automatically downloaded from it.*

## 3. Steps Followed

- **Data Cleaning:** Removed duplicates, standardized text columns, converted numeric values, and checked missing values.
- **Data Analysis:** Examined national EV trends, state-wise registrations, vehicle types, and battery prices.
- **Data Visualization:** Created line charts, bar charts, pie charts, and a correlation heatmap.
- **Summary:** Calculated registration growth and identified leading states from the available data.

## 4. Key Findings

- EV registration trends across the available years.
- Differences in EV adoption among states.
- Comparison of sales share and market penetration by vehicle type.
- Relationship between battery prices and EV registrations.

*Actual findings depend on the values in the uploaded dataset.*

## 5. How to Run the Project

1. Open Google Colab.
2. Upload the Python notebook or paste the project code.
3. Install the required libraries if needed:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

4. Run the code and upload the Excel dataset when prompted.
5. Ensure the workbook contains a sheet named `Cleaned Dataset`.
6. View the charts and download the generated Excel analysis report.

## 6. Screenshots of Charts

The project generates the following visualizations:

- Year-wise EV Registration Growth
- India EV Sales Share Trend
- State-wise EV Registrations
- EV Sales Share by Vehicle Type
- EV Market Penetration by Vehicle Type
- EV Battery Pack Price Trend
- Correlation Heatmap
- EV Registrations vs Battery Prices

Save chart screenshots in a `screenshots` folder and add their image paths here.

## 7. Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab
- Excel
