# HR-Analystics-with-PowerBI
This is an analysis that gives HR an insight into their employees attendance.

# Problem Statement/Insight
This dashboard helps HR understand their workers better. They get to see the present days % vs. the absent days %.
It was seen in this analysis that employees are present over 83% of the year and 16% absent.

Very few of these employees get to work from home, and Friday also happens to be the day with the highest record of absenteeism. As a matter of fact, absenteeism increases as we move towards the end of the week, which is Friday.

## Steps Followed
 Markup : - Step 1: Gathered data requirement from https://codebasics.io/resources/resume-project-data-analytics
 Markup : - Step 2: Studied the data and noted a few problems to solved by understanding the requirements
- Step 3: Data had 3 files in a folder which represented 3months attendance, April, May, and June
-- Step 4: Load the excel files through Get Data
-- Step 5: Data transformation was done in Power Query and the next bullets describe what was done
-- Step 6: Filtered rows to have just one month report
-- Step 7: Removed other columns and was left with just the data column since the transformation will be done on that month
-- Step 8: Expanded that table and promoted Headers by removing the top rows since they werent relevant
-- Step 9: Headers were renamed to have meaningful text
-- Step 10: Selected the good columns and unpivot the rest so the a 30 days columns become a date column and values on one column
-- Step 11: Automated the columns and changed data types
-- Step 12: A custom parameter was created and applied on a worksheet
-- Step 13: Invoked the custom function on the cleaned data and removed irrelevant columns
-- Step 14: Renamed field headers and changed data type appropriately
-- Step 15: Load combined data into Power BI by closing and apply
-- Step 16: A calendar table was created by using dax formular, CALENDARAUTO
-- Step 17: Data modeling was done on the date on both tables
-- Step 18: A few measures were created which can be found on my dashboard.
-- Step 19: Dashboard published

Thanks for reading!!

