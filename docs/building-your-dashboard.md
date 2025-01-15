## Building Your Dashboard

### Dashboard Layout

1. **Create New Dashboard**
   - Click "+ New Dashboard"
   - Select blank template
   - Set dimensions (16:9 recommended)

2. **Add Metric Blocks**
   ```
   Block Type: Number
   Metric: Daily Revenue
   Comparison: Previous Period
   Visualization: Up/Down Arrow
   ```

### Visualization Types

1. **Line Charts**
   ```
   Metrics: Revenue, Users
   Time Range: Last 30 Days
   Y-Axis: Auto-scale
   ```

2. **KPI Comparisons**
   ```
   Primary Metric: Current Month Revenue
   Compare To: Previous Month
   Display: Percentage Change
   ```

3. **Tables**
   ```
   Columns: Date, Revenue, Users, Conversion_Rate
   Sorting: Date (Descending)
   Pagination: 10 rows per page
   ```

### Dynamic Date Ranges

1. **Configure Time Periods**
    - Configure time periods selecting from Month-to-date, Quarter-to-date, Year-to-date

        ```
        Default: Last 30 Days
        Compare To: Previous Period
        Custom Ranges: MTD, QTD, YTD
        ```

2. **Date Range Selector**
   ```
   Type: Dropdown
   Options: Today, Yesterday, Last 7 Days, Last 30 Days, Custom
   Position: Top Right
   ```
