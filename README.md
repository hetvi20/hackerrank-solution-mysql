# hackerrank-solution-mysql problem 1
Population Density Difference


--Problem STATEMENT (Query problem )
/*
Given a City table, whose fields are described as
+-------------+----------+
| Field       | Type     |
+-------------+----------+
| ID          | int(11)  |
| Name        | char(35) |
| CountryCode | char(3)  |
| District    | char(20) |
| Population  | int(11)  |
+-------------+----------+
print the difference between the maximum and minimum city populations.
*/

Solution 
select max(population)-min(population) as populationdestiny from CITY;
