# smt_dashboard
PowerBI dashboard for calculating different power plans against historical SmartMeterTexas consumption/generation
Can help optimize PowerWall purchasing, but will 'use' more powerwall then you may actually have when calculating potential savings. Built more as a tool to visualize if you're copnsidering too many or too few PowerWalls to cover peak usage (PowerWall Avg (kWh).

TBD on adding PowerWall count into savings calculations.

Requirements:
- PowerBI Desktop: https://powerbi.microsoft.com/en-us/desktop/
- Usage Data: https://www.smartmetertexas.com/
- Export your 15 minute interval data (IntervalData.csv) and copy it to C:\SMT\IntervalData.csv
- 'Refresh' - Should update with your data or error if file does not exist
  
 My Data is also viewable [here](https://app.powerbi.com/view?r=eyJrIjoiMzg0YzRlZmMtNTcwYS00ZjFhLWFjNjUtMTYzMmI3NzNhZjgyIiwidCI6ImMwOTAwM2RlLTg0YjYtNDEzZC04MDllLWJjOTNjODFmM2ZhNSJ9)
