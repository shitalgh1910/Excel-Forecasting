# Excel-Forecasting
This repository demonstrates three different forecasting methods in Microsoft Excel.
## Methods Overview

1. **FORECAST Function**
   - Syntax: `=FORECAST(x, known_y's, known_x's)`
   - Example:
     ```excel
     =FORECAST(A2, B2:B11, A2:A11)
     ```
   - Requires historical data with both x and y values

2. **Graph-Trendline Method**
   - Create line graph > Add Trendline
   - Options: Linear, Exponential, Polynomial, etc.
   - Display R² value (closer to 1 = better fit)
   - Shows equation (y = mx + b)

3. **Forecast Sheet (Windows Only)**
   - Data Tab > Forecast Sheet
   - Set timeline and value ranges
   - Adjust confidence intervals and periods

## Prerequisites
- Microsoft Excel (2016 or later for Forecast Sheet)
- Basic understanding of Excel functions
- Sample data with time-based observations
