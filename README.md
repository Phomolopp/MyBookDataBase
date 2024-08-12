# MyBookDataBase
## Overview
  This project defines a simple database schema for managing a collection of books and their respective   authors. The database contains two main tables: Authors and Books, with a relationship between them     based on the AuthorID.
  
# Database Schema
## Table: Authors
  This table stores information about the authors.
  
  <img src="https://github.com/user-attachments/assets/6c55dc71-0253-4541-b80e-d0303a58afb3" />
    
## Table: Books
  This table stores information about the books and associates each book with an author.
  
  <img src = "https://github.com/user-attachments/assets/93cb45b4-6908-4413-a38c-77889dc07a24"/>

# Relationships
  The Books table includes a foreign key AuthorID that references the AuthorID in the Authors table,     establishing a one-to-many relationship. This means each author can be associated with multiple        books, but each book is associated with a single author.
  
# Usage
To set up this database schema, execute the SQL commands provided. This will create the Authors and Books tables with the structure described above.

        example
        INSERT INTO Authors (First_Name, Last_Name, Nationality)
        VALUES ('George', 'Orwell', 'British');

        INSERT INTO Books (Author, Description, AuthorID, Title, Price, PublicationDate)
        VALUES ('George Orwell', 'A dystopian novel', 1, '1984', 19.99, '1949-06-08');
        
# License
This project is open-source and available under the MIT License.

## Author Table
<img src = "https://github.com/user-attachments/assets/1f5ddc8c-30bf-4b25-8687-3e74967d0550"/>

## Book Table
<img src = "https://github.com/user-attachments/assets/8c1cca6d-1d1b-4272-b09a-03a1afa3a448"/>

