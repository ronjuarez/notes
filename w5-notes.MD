# These are my notes from LHL Week 5

##A quick note on algorithms

**An algorithm is a recipe!**
* They are like a set of steps that are instructions.
* In comp sci an algorithm is a set of steps.

*Algorithms are everywhere!...*
* Some algorithms are fast and some are slow.

> Why does the runtime of an algorithm depend on the number of operations and how do I determine what it is?
* Runtime is determined by the number of elementary operations an algorithm runs.
* Elementary operations are any operations that result in some sort of manipulation of data 
* If an algorithm performs `n` number of operations, We say running time is in `n`.
* Algorithms that don't deal with loops take constant time.
* Involves using `n` based on the size of the data.
* Every instance of a variable is `n` every operation counts as a number.
* Runtime is represented as `3n + 2` in this example 3 is the number of instances of our variable and 2 is the number of operations completed.

> What is binary search?
* Binary search is a type of search that finds en element in a list by spliting the list in half until it finds the required element.
* This is a logarithmic type of search.

**This is a list of questions I would like to review and take notes on that I haven't been able to do yet**
* How can we study the search report of an array of ordered elements?
* How do linear and binary search relate to eachother?
* How do we determine a runtime's worst case scenario?
* Why does the number of steps that an algorithm needs to perform only go up by one when the data is doubled in size?
* What's the difference between quadratic and linear time?
* Why does Big O notation descirbe inputs?
* What is basic Big O notation?
* Why do we drop constants and lower order terms when we talk about big O notation?



## A Longer Note on Databases

> SQL stands for Structured Query Language
**Here is a list of SQL keywords and how they work**
* We create tables in SQL using the CREATE keyword.
* We add elements by using the INSERT INTO keyword.
* We assign each element it's value using the VALUES keyword.
* We create a row by following the VALUES keyword followed by () and the values for our row entry.
* When creating our DATABASE schema we indicate what data type each row will receive as an INPUT VALUE.
* The SELECT keyword let's us query the data.
* The WHERE keyword let's us specify a condition.
* The FROM keyword fetches the query from the database.
* The ORDER BY keyword let's us SORT our query results.
* The CREATE TABLE keywords create a table within the database.
* Aggregate functions are useful for getting information about multiple entries in a table.
* Aggregate functions include max & min values, avg or average, sum and differece amogst many others.
* We can type an SQL query on multiple liones as long as we end the whole thing witha semi colon
* We retrieve multiple tables at once using JOIN.
* INNER JOIN's only display's rows when there is a matcing row in two tables.
* OUTER JOIN's will allow us to include data from multiple tables where there aren'yt any matches.
* There are three types of OUTER JOIN's, LEFT, RIGHT and FULL.
* JOIN RIGHT or LEFT includes all the data accross tables being joined and add's it to the specified direction relative to the table even non-conditional data
* JOIN OUTER FULL join's all data from both tables.
* The GROUP BY keyword let's us order the results by the property specified.
* The HAVING keyword is like the WHERE keyword except it works on aggregate data.
* We can use the result of a query as the value of our SELECT statement.
* We can SELECT a data set and use the IN keyword to search another selected data set.
* SELECT DISTINCT keyword will select one specific instance of a data.+
* DELETE used with WHERE will DELETE a specified entry.
* UPDATE is used with WHERE and SET can change it's value.
* Always use WHERE with UPDATE and DELETE.


* Reducing redundancies makes data highly sapce efficient on disk.
* Database design is the organization of data according to a database model
* ONTOLOGY is the theory behind database design that deals with classifying interrelated data.
* Designers descrive what data will be stored by gathering domanin knowledge during the requirements process.
* ERD or Entity Relationship diagrams help us design database efficiently.

> What is the PURPOSE of DATABASE?
* FIND and ORGANIZE data required, DIVIDE information into TABLES, TURN item information in COLUMNS and SPECIFY primary keys.

* We APPLY normalization to refine DATABASE design and REDUCE redundancies.
* This process involves creating tables to hide duplicate data where it can still be referenced. 
* Database designers must determine the way that data depends and relates to eachother.
* Once the data is organized it can be stored into TABLES or OBJECTS.
* If data is duplicated there's likely another Tab;e that can be accessed with a foriegn key.
* Each table should have rows, each row should have a uique primary key.
* No tables should contain multiple columns that can access the same information
* Two considerations to always have in mind: Does the DB have internal redundancies? Are the depancies between data logically organized?
* THe foreign key is ALWAYS on the MANY side.
* if information can relate to more than one key represent it on a table.


> DDL and DML
* Data Definition Language are the keywords we use to define a DB Schema.
* The most common DDL statements are CREATE -> to ADD, ALTER -> to EDIT, and DROP -> to DELETE.
* Any blank value in a table is considered a NULL value, anything defined in the schema as NOT NULL needs a value.
* Data Manipulation language lets us mutate data entries
* THe most common DML statements are SELECT -> to GET DATA, INSERT -> to ADD ROWS, UPDATE -> to DELETE rows.



