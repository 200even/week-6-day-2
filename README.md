# week-6-day-2
Linq redux - querying database


Today 
----
1. Discuss Resharper tools
2. Discuss Bootstrap fluid layouts
3. Discuss Linq queries (take, skip, group by, order by, count)


Homework
----
Submit an issue and a gist contain the linq queries for the following requests. Use generatordata.com to get a csv of random people that have the columns  firstname, lastname, dob, city, state. Import this in a database in sql server and create an web application that has a "code first from database" DB Context that talks to that database.

Queries:

1. Return an alphabetized list of people, but only return a string object that represents their fullname formated like "LastName, FirstName"
2. Return a list of people that have a lastname that starts with 'C' and a state that starts with 'A'
3. Return a list of states and the number of people in each state.
4. Return a list of the number of people in each birth month (i.e. January: 5, February 3)
5. Return the 30th through 40th (10 people) of people alphabetized by firstname
6. Return a list of distinct firstnames
7. Figure out the difference in ages between the oldest person and youngest person (hint: use SqlFunctions.DateDiff())

Resources
------
[LINQ Samples](http://linqsamples.com/)
