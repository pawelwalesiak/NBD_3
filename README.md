# NBD3
Zadania mongodb
Run mongo shell with the following command:

mongo

specify database to use with the following command:

use nbd

Build the following queries:

1. Find one person from the database

2. Find one Chinese woman

3. Find all German men

4. Find all people in the database with weight in the <68, 71.5) range

5. First and last names and cities of people born in 21st century

6. Add yourself to the database (data on credit card, address and weight may be fictional)

7. Remove people with height >190cm from the database

8. Replace “Moscow” with “Moskwa” in city names for all people in the database

9. Add property “hobby” with value “table tennis” to all people with first name “Antonio”

10. Remove the “email” property from all people having “Editor” as their job

Send solutions in the following format: for each task send 2 files – file with the query and file with result. Name files using the following pattern: query_X.js, result_X.json where X is the task #.

In order to save query results to file wrap the query with printjson function and add .toArray() after find if necessary – e.g. printjson(db.products.find().toArray()).

Put such query into a file, run mongo shell the following way:

mongo dbname queryfile >> resultfile

e.g.

mongo nbd query_1.js >> result_1.json
