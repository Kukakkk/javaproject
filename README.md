The program allows you to keep records of the library, which books who (employee, client) bought and for what amount.
The employee's of library has a 15% discount for all goods in library.
The project consist of 4 classes.
The first one is the Main class, which consist connection to database on postgresql and also has 6 functions to work with data from database.
The Main class is the most valuable than others.
First function - it's adding books into database by using prepareStatemt("insert...")
Second function - adding a customer data who bought books into database.
Third function - adding a employee data who bought books into database.
Fourth function - refilling the number of books which was imported to database.
Fifth function - shows the data about customer's purchases.
Sixth function - shows the data about employee's purchases.

The class Person is abstract and has 2 inherited classes customer and employee. This classes has only 1 method - outputData, which is shows the person's purchases.
The employee has a 15% discount, so the employee outputs another sum of purchase.
