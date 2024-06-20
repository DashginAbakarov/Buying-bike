# Buying-bike
-- I have preprocess the data and examined bike purchase for different aspects of people. I have also created a dashboard:

--1. First, I checked the data.

--2. Second, I removed duplicates.

--3. Martial status and Gender status were hard to identify. 

--4. Therefore, I replaced "M" with "Married" and "S" with "Single" in martial status, and "M" with "Male" and "F" with "Female" in gender status.

--5. I changed the Income column format from general to currency and removed the additional two digits "0" from the end.

--6. I looked at the Age column, which had many different values making it messy for plotting. Therefore, I created an empty column named "Age Bracket." Using an IF statement, I divided ages into three intervals: less than 31 means "Adolescent," higher than 31 and less than 55 means "Middle," and higher than 54 means "Old."

--7. I created a pivot table, inserted a table, and copied our worksheet. There was an error in the pivot table name field, which commonly occurs when one of the column headers is empty. I realized that the age column header was empty. To find empty cells, I can go to HOME > FIND/SELECT > GO TO SPECIAL > click BLANK.

--8. I added the Income column for VALUES, Gender column for ROWS, and Purchase Bike column for COLUMNS of the PIVOT TABLE. This helped me understand the average salary for purchasing a bike and to see the difference between the average salary of males and females.

--9. Then, I changed the Income values to averages.

--10. I selected the whole table and inserted recommended charts, adding axis names, etc.
Now, I want to know if "commute distance" is an important factor for bike purchase. To analyze this, I added the Gender column to VALUES, Purchase Bike to COLUMNS, and Commute Miles to ROWS. There was a small issue in our worksheet where "10 + Miles" did not sort correctly at the end. Therefore, I changed the name of that value to "More than 10 Miles."

--11. I examined "bike purchase" for different age ranges.

--12. As the next step, I created a dashboard.
