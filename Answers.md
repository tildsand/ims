- get_data.php
1. create_table.sql creates a table called animals. 4 columns are created: ID (INT), name (str), domain (str), propulsion (str). Size of data: 255 characters. The first column holds the primary key (ID) because it is an int. AUTO_INCREMENT increases the ID by 1.

2. Open: <?php, close: ?>

3. Create variables: $variablename = value;

4. servername = 80, username = github, password = password, dbname = database name, holds the default variables

5. Connects to database. Line 10-12 because the user should know if the connection fails.

6. Echo prints the statement, print in other programming languages. 

7. Outputs HTML code.

8. The link variable points to the sql query (SELECT * FROM animals). Used to access an object method. 

9. num_rows is a property access (number of rows).

10. The number of rows must be greater than 0, then each table row is printed.

- index.php
1. Prints a welcome message, if user is on the homepage. First file to homepage. 

- insert_data.html
1. A form is something a user can fill in (values submitted by the user to the server)

- insertdata.php
1. Holds all the data that the user has submitted(send and retrieve data: POST and GET)

2. Left blank because they are meant to be submitted by the users, '?' are placehoders. It is a safety feature, a way of defining the datatypes beforehand. 

3. We have already autocreated an ID.

4. Close the connection after data has been inserted, risky to hold it open. As a double-security. 