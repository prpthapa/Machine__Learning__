## Day 54 - Date and Time Feature Engineering

Today I learned how to perform **Date and Time Feature Engineering** using Pandas by extracting meaningful information from datetime columns.

### Topics Covered

- Converting object columns to datetime
- Extracting date features
- Working with `.dt` accessor
- Creating new date-based features
- Calculating time differences

### Key Concepts Learned

- Converted string dates into datetime format using `pd.to_datetime()`.
- Extracted useful features from date columns:
  - Year
  - Month
  - Month Name
  - Day
  - Day Name
  - Day of Week
  - Week Number
  - Quarter
  - Semester
  - Weekend Indicator
- Used `np.where()` to identify weekends.
- Calculated the difference between the current date and previous dates using `timedelta`.
- Learned how date feature engineering helps machine learning models identify seasonal and time-based patterns.

### Functions Practiced

- `pd.to_datetime()`
- `.dt.year`
- `.dt.month`
- `.dt.month_name()`
- `.dt.day`
- `.dt.day_name()`
- `.dt.dayofweek`
- `.dt.isocalendar().week`
- `.dt.quarter`
- `np.where()`
- Date subtraction using `datetime`

### Key Takeaway

Date and time columns contain valuable hidden information. By extracting meaningful features such as year, month, weekday, quarter, and weekend indicators, we can improve the performance of machine learning models and gain deeper insights during data analysis.
