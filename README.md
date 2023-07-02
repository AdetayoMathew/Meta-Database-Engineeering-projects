# Meta-Database-Engineeering-projects
# MetaDatabaseEngineering-Mysql-capastone-project
# Project Background
Based in Chicago, Illinois, Little Lemon is a family-owned Mediterranean restaurant, focused on traditional recipes served with a modern twist. The chefs draw inspiration from Italian, Greek, and Turkish culture and have a menu of 12–15 items that they rotate seasonally. The restaurant has a rustic and relaxed atmosphere with moderate prices, making it a popular place for a meal any time of the day.

Little Lemon is owned by two Italian brothers, Mario and Adrian, who moved to the United States to pursue their shared dream of owning a restaurant. To craft the menu, Mario relies on family recipes and his experience as a chef in Italy. Adrian does all the marketing for the restaurant and led the effort to expand the menu beyond classic Italian to incorporate additional cuisines from the Mediterranean region.
# Tasks
1. Create SQL statement to print all records from Bookings table for the following bookings dates using the BETWEEN operator: 2021-11-11, 2021-11-12 and 2021-11-13.
2. Create a JOIN SQL statement on the Customers and Bookings tables. The statement must print the customers full names and related bookings IDs from the date 2021-11-11.
3. Create a SQL statement to print the bookings dates from Bookings table. The statement must show the total number of bookings placed on each of the printed dates using the GROUP BY BookingDate.
4. Create a SQL REPLACE statement that updates the cost of the Kabsa course from $17.00 to $20.00.
5. Create a new table called "DeliveryAddress" in the Little Lemon database with the following columns and constraints:

ID: INT PRIMARY KEY

Address: VARCHAR(255) NOT NULL

Type: NOT NULL DEFAULT "Private"

CustomerID: INT NOT NULL FOREIGN KEY referencing CustomerID in the Customers table

6. Alter table structure

Create a SQL statement that adds a new column called 'Ingredients' to the Courses table.

Ingredients: VARCHAR(255).

7. Create the "BookingsView" virtual table to print all bookings IDs, bookings dates and the number of guests for bookings made in the restaurant before 2021-11-13 and where number of guests is larger than 3.

8. Create a SQL SELECT query using appropriate MySQL string function to list "Booking Details" including booking ID, booking date and number of guests. The data must be listed in the same format as the following example:

ID: 10, 

Date: 2021-11-10, 

Number of guests: 5

  ![Uploading Screenshot (552).png…]()



