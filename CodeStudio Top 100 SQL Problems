-- Challenge: Combine Two Tables
-- Level: Easy

-- Write a SQL query for a report that provides
-- the following information for each person 
-- in the Person table, regardless if there is
-- an address for each of those people.

select
    Person.FirstName,
    Person.LastName,
    Address.City,
    Address.State
from Person
left join Address
on Person.PersonId = Address.PersonId;

-- Challenge: Second Highest Salary
-- Level: Medium

-- Write a SQL query to get the second highest salary
-- from the Employee table. 

select
    salary
from Employee
limit 1 offset 1;

-- Challenge: Big Countries
-- Level: Easy

-- A country is big if it has an area of bigger
-- than 3 million square km or a population 
-- of more than 25 million.
-- Write a SQL solution to output big countries'
-- name, population, and area.

select
    name, 
    population,
    area
from World
where area > 3000000
    or population > 25000000;
