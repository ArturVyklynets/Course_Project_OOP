# Course_Project_OOP
+------------------+       +------------------+       +------------------+       +------------------+
|      Users       |       |     Listings     |       | RentalRequests   |       |     Reviews      |
+------------------+       +------------------+       +------------------+       +------------------+
| id (PK)          |       | id (PK)          |       | id (PK)          |       | id (PK)          |
| username         |       | user_id (FK)     |       | user_id (FK)     |       | listing_id (FK)  |
| password         |       | title            |       | listing_id (FK)  |       | user_id (FK)     |
| email            |       | description      |       | request_date     |       | rating           |
| role             |       | location         |       | status           |       | comment          |
+------------------+       | price            |       | message          |       | date             |
                           | type             |       +------------------+       +------------------+
                           | available_from   |       
                           | available_to     |       
                           +------------------+       
