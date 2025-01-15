## Databox Configuration

### Connecting to Google Sheets

1. **Add Data Source**
   - Log into Databox
   - Navigate to Data Manager → + New Connection
   - Select "Google Sheets"
   - Authorize Databox to access your Google account

2. **Configure Connection**
   ```
   Connection Name: Marketing Metrics
   Sheet URL: [Your Google Sheet URL] (e.g., "https://docs.google.com/spreadsheets/d/your-sheet-id/")
   Refresh Rate: Every 1 hour (e.g., 1 day, 1 hour, 15 mins)
   ```

3. **Map Data Columns**
   - Select your named range
   - Map columns to Databox metrics
   - Set data types (number, percentage, currency)

### Creating Custom Metrics

1. **Basic Metrics**
   ```
   Metric Name: Daily Revenue
   Data Source: Column 'Revenue'
   Aggregation: Sum
   Time Dimension: Column 'Date'
   ```

2. **Calculated Metrics**
   ```
   Metric Name: Average Order Value
   Formula: ${Revenue} / ${Orders}
   Format: Currency (USD)
   ```
