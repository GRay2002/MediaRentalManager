# MediaRentalManager
A robust and user-friendly database system made exclusively for CD and DVD rental shops is called RentHub

# CD DVD Rental Store Database

The CD DVD Rental Store Database is a comprehensive database system designed to manage the operations of a CD DVD rental store. It allows for efficient tracking of inventory, customer information, employee shifts, and rental transactions. This README file provides an overview of the database structure, query examples, and usage instructions.

## Table of Contents

- [Database Structure](#database-structure)
- [Queries](#queries)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Database Structure

The CD DVD Rental Store Database consists of several tables that store different types of information. Here is an overview of the main tables:

- `Employees`: Stores employee information, including their first name, last name, and job details.
- `Shifts`: Manages employee shift schedules, including the store ID, employee ID, and time table day.
- `Jobs`: Contains job descriptions for employees, such as manager or day shift.
- `Movies`: Stores details about movies available for rent, including the movie ID, name, release date, awards, and description.
- `Music_Albums`: Contains information about music albums, including the album ID, name, release date, and description.
- `Video_Games`: Stores details about video games, including the game ID, name, release date, and description.
- `Vinyl_Records`: Contains information about vinyl records, including the record ID, name, release date, and description.
- `Rent`: Manages rental transactions, storing information such as the CD ID, customer CNP, rented on date, and return on date.
- `Stores`: Stores store information, including the store ID and address.
- Other supporting tables may exist for expenses, subscriptions, and more, depending on the specific requirements of your rental store.

## Queries

The CD DVD Rental Store Database supports various queries to retrieve and manage data. Here are some example queries:

1. Join between 3 tables (Employees, Shifts, Jobs) to generate a time table with employee shifts.
2. Show all employees from a store that have a certain job.
3. Look up employees working a certain shift at a specific store.
4. Look up which CD was rented by a customer given their CNP.
5. Given a CNP, show all data regarding a client's renting history.
6. Search for the most rented CD (most popular CD).
7. Look up where a CD is stocked.
8. List all products sold by the store, including the dealer, producer, and contact information.
9. Compute monthly expenses for each store.
10. List all expired subscriptions and customer details.

## Usage

To use the CD DVD Rental Store Database, you need to have a supported relational database management system (RDBMS) installed, such as MySQL, PostgreSQL, or Oracle Database. Follow these steps to set up the database:

1. Create a new database in your RDBMS.
2. Import the provided SQL script or execute the necessary SQL statements to create the required tables and populate them with sample data.
3. Connect your application or SQL client to the database.
4. Use the available queries to retrieve or manipulate the data according to your needs.

Ensure that you have the necessary permissions to perform database operations and handle sensitive customer or financial information securely.

## Contributing

Contributions to the CD DVD Rental Store Database are welcome! If you have any improvements, bug fixes, or new features to propose, please follow these steps:

1. Fork the repository and create a new branch for your contribution
