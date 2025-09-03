# US Debt Tracker (Excel)

An Excel-based analysis and projection of United States public debt, including data cleaning, yearly percentage changes, monthly seasonality, and a 5-year projection summary.

---

## Research Questions & Answers

1. **What was the Yearly Debt Percentage Increase for each year compared to the previous year?**  
   - From 2016–2019, the Total Public Debt Outstanding grew at an average of ~5% per year.  
   - In 2020, debt spiked significantly, most likely due to U.S. pandemic response measures.  
   - 2021–2022 showed a return to more normalized growth rates.  

2. **Which months historically have seen the highest/lowest increases in Total Debt?**  
   - **Highest increases:** January, February, November, December.  
   - **Lowest increases:** April, May, June, July.  
   - **Hypothesis:** The high-debt months align with U.S. holidays (Thanksgiving, Christmas, New Year), when consumer spending is historically higher. Lower-debt months correspond to periods without major holidays.  

3. **What is the projected growth of the publicly held debt in the next few years?**  
   - 1997–2007: Debt increased by ~$1 Trillion.  
   - 2008–2019: Debt rose from ~$6 Trillion to ~$17 Trillion.  
   - 2020–2022: Debt climbed from ~$21.5 Trillion to ~$25 Trillion.  
   - **Projection (2023–2027):** Publicly held debt is expected to increase steadily, reaching **~$33 Trillion by 2027**.  

**Conclusion:** U.S. publicly held debt continues to follow a steady upward trajectory, with clear seasonal variations and long-term growth trends.  

---

## Project Structure

- **Scenario**: Problem brief, key questions, and data dictionary.  
- **Raw Data**: Source-extracted daily debt records.  
- **cleaned data**: Dates formatted, numeric fields standardized.  
- **Yearly Percentage Change**: Yearly YoY calculations with line chart.  
- **Monthly Historical**: Pivot table of monthly averages with seasonality chart.  
- **Projected**: Forward 5-year projection (2023–2027) with area chart.  
- **Final Output**: Written summary of conclusions.  

---

## How It Works

1. **Data Preparation**: Convert dates, clean nulls, and format numbers.  
2. **Yearly Change**: Calculate YoY % change for each debt series.  
3. **Monthly Seasonality**: Build pivot grouped by Month → Average of Total Debt Outstanding.  
4. **Projection**: Extend publicly held debt for 5 years with baseline assumptions.  

---

## Usage

- Start with **Final Output** to read conclusions.  
- Explore **Yearly Percentage Change** for annual dynamics.  
- Use **Monthly Historical** for seasonal insights.  
- Adjust assumptions in **Projected** for scenario testing.  

<img width="1817" height="632" alt="image" src="https://github.com/user-attachments/assets/e15c6a36-53db-43b2-b179-63aa7c9c4439" />
