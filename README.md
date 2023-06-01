# Library Management System

The Library Management System is a database management project developed using NetBeans and MySQL. It provides a comprehensive solution for managing the functioning of a library, including the management of library members, books, and the issuance and return of books.

## Features

The Library Management System offers the following features:

1. **Library Member Management:** The system allows the addition, deletion, and modification of library members, including both staff and students. It provides a user-friendly interface to manage member details such as name, contact information, and membership status.

2. **Book Management:** The system provides functionality for adding, deleting, and modifying library books. Each book entry contains information such as title, author, publication date, and availability status. The system ensures that the book inventory is up-to-date and allows easy management of the library's collection.

3. **Issuance and Return of Books:** The system facilitates the issuance and return of books to library members. When a member wants to borrow a book, the system checks the availability and updates the book status accordingly. It also records the issuance date and due date for tracking purposes. Upon return, the system updates the book status and calculates any fine applicable based on the return date.

4. **Fine Calculation:** If a member fails to return a book within the due date, the system calculates the fine based on the predefined rules. The fine amount is calculated automatically and added to the member's account. This feature helps in enforcing timely returns and ensuring accountability among library members.

## System Requirements

To run the Library Management System, ensure that you have the following software installed:

1. NetBeans IDE: Version X.X or above. (Download: https://netbeans.apache.org/download/index.html)
2. MySQL Server: Version X.X or above. (Download: https://www.mysql.com/downloads/)

## Installation and Configuration

1. Clone or download the project files from the repository.
2. Import the project into NetBeans IDE.
3. Create a new MySQL database for the Library Management System.
4. Import the database schema and data from the provided SQL file (`TABLES and DB.sql`).
5. Configure the MySQL database connection settings in the project files (`library_management`).
6. Build and run the project in NetBeans IDE.

## Usage

Upon successfully running the Library Management System, you will be presented with a user-friendly interface to interact with the system. You can use the provided functionality to perform tasks such as adding and managing library members, books, issuing and returning books, and calculating fines.

Please refer to the user manual or documentation for detailed instructions on how to use each feature of the Library Management System.

## Contributors

The Library Management System was developed by Sounak Mandal. 
I appreciate any feedback, bug reports, or suggestions for improvement. You can reach us at [sounak.mandal2020@vitstuddent.ac.in].

## License

You are free to modify and distribute the software as per the terms of the license. Please refer to the LICENSE file for more information.
