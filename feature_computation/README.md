In this dataset, you have 3 columns: date, servicePoint, volume
where date is the current date
servicepoint the meter service point (3 differents service in the dataset)
and volume the volume of water consumed per day.

- Variable v1: Elapsed time without consumption.
compute for each servicepoint the variable v1 defined by Difference between day of analysis and last day with significant consumption (greater than 20 liters
for 2 consecutive days).
Definition: We denote To the last day of consumption according to the definition above and T the current
day. We then have v1 = T - To

- Variable v2: Non-zero consumption rate over 90 days before To
This variable describes the percentage of days with consumption on the 90 days before To. If certain
consumptions are missing, the rate is calculated on the available consumptions.
There may be no data before To.

*** The computation will be done using PySpark.***