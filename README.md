**ABOUT THE DATA**
The data contains the monthly local tax collections from October 2022 to March 2026. This data also contains the different sources of the collections, the total collections, and the different authority names.

**##COLUMNS**
The columns include:
•	Authority code
•	Authority name (Name of Authority)
•	Allocation month
•	Allocation date
•	Total collections
•	Prior period collections (Collections from any original or amended returns whose due date was before the most recent return due date and collections of delinquent balances.)
•	Current period collections (Collections from the most recent return(s) due.)
•	Future period collections (Collections from returns not yet due.)
•	Audit collections (Collections from audited periods)
•	Unidentified (Occasional proportionate disbursements of local tax collected and remitted by businesses but not identified by specific location.)
•	Single local rate collections (Proportionate share of disbursement of local tax collected and remitted by remote sellers opting to report local tax using the single local tax rate.)
•	Service Fee (Two per cent of the total collections retained by the state.)
•	Current retained (Two per cent of the net total collections less the monthly service fee.)
•	Prior retained (Reimbursement of the amount retained in the previous month's allocation.)
•	Net payment (Payment amount.)

**DATA CLEANING**
First started with importing the pandas, numpy, matplotlib and matplotlib.pyplot libraries.
The pandas library helps access and read the data.
The cleaning process begins with checking the different data types from each column, checking for null values, checking for unique values and duplicated values.

**DATA ANALYSIS**
The following values have been calculated:
Total number of collections
Total annual collections
Total collections by authority name
Prior collection percentage
Ratio of prior collections to total collections
Total prior collections by authority name
Sum of all current period collections
Sum of current period collections by authority name
Ratio of current period collections to total collections
Sum of all future period collections
Sum of future period collections by authority name
Ratio of future period collections to total collections
Total audited collections
Total audited collections by authority name
Annual total audited collections
Total single local rate collections
Single local rate collections ratio
Total single local rate collections by authority name
Annual total single local rate collections
Total number of service fees
Verifying service fee percentage(2% of total collections)
Total service fees paid by authority name
Annual total service fees paid
Total current retained collections
Current retained collections ratio
Total current retained collections by authority name
Total annual current retained by allocation 
Total net payment
Total net payment by authority name
Ratio of net payment to total collections
Correlation analysis.

**VISUALIZATION**
Annual total collections by year
Future period collections by year
Annual current period collections
Annual audit collections
Annual unidentified collections
Annual single local rate collections
Annual net payment
Top 10 locations for total collections



