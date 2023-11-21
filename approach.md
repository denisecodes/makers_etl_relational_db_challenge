### Task

Identify the top 5 members in terms of booking frequency.

### Approach

1. Check what the bookings table look like
2. Choose the columns I need to regarding the top 5 members
3. Use an aggregate function i.e. COUNT to count the number of bookings per member and save as a new column
4. Use GROUP BY on member's id to COUNT base on member's id
5. Use ORDER BY total_bookings DESC to show highest to lowest bookings
6. Use LIMIT 5 to only collect the top 5 rows
7. Save the final result to a pandas dataframe
8. Create a table on psql locally to load the data
9. Load the dataframe to the table
10. Check to see if the table in psql shell looks like the dataframe