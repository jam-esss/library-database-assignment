# 📦 Library Database Project

## ℹ️ Overview

This project is apart of my university work, 'Introduction to Database Modelling'.

Unit 4 required me to model how a scenario would look (ERD), and Unit 9 required me to use SQL to model the ERD.

## ‼️ Unit 4 Objectives

### Unit 4

Scenario

A university library system wants to improve how books, members, and borrowing activities are managed. Currently, book borrowing is recorded manually, leading to inefficiencies and errors. The library system requires a database to store and manage information on books, library members, staff, and book loans effectively.
Business Rules and Requirements:

    The library has multiple books, each with a unique ISBN, title, author(s), edition, and publication year.
    A book may have multiple copies, each identified by a unique copy ID.
    Members register with the library and are assigned a unique member ID. The system stores their name, address, phone number, and email.
    Library staff oversee the lending process. Each staff member has a unique staff ID, name, role, and contact details.
    A member can borrow multiple books, but a book copy can only be on loan to one member at a time.
    Loan transactions store information about the borrow date, due date, and return date.
    Overdue books are tracked, and fines are imposed if a book is returned late.

Task 1: Entity-Relationship Model
Task Requirements

    Analyse the scenario to identify the key entities and their attributes.
    Define relationships between entities, including cardinality (one-to-one, one-to-many, many-to-many).
    Develop an Entity-Relationship Diagram (ERD) to visually represent the database structure.
    Justify your design choices, explaining how they align with the scenario’s requirements.

Guidance for Task 1

    Identify primary entities (e.g., Book, Member, Staff, Loan, Copy) and their attributes.
    Define primary keys for each entity.
    Establish relationship types (e.g., A book has many copies, a member borrows many books, and so on).
    Consider normalisation principles to avoid data redundancy.
    Use an ERD tool such as Microsoft Visio or Diagrams.net (draw.io).

Deliverable

    An ERD diagram illustrating all entities, attributes, relationships, and cardinalities.
    A written explanation of your model, highlighting key design choices and business rule implementations.

Task 2: Normalisation to Third Normal Form (3NF)
Task Requirements

    Convert the ERD into a set of relations (tables), ensuring they conform to Third Normal Form (3NF).
    Demonstrate the normalisation process from UNF (Unnormalised Form) to 3NF.
    Clearly define primary keys (PKs) and foreign keys (FKs) for each table.
    Provide justification for how your design ensures data integrity and eliminates redundancy.

Guidance for Task 2

    First Normal Form (1NF): Ensure atomicity (no repeating groups or multi-valued attributes).
    Second Normal Form (2NF): Ensure all attributes are fully functionally dependent on the primary key.
    Third Normal Form (3NF): Remove transitive dependencies.
    Consider how foreign key constraints maintain referential integrity.
    Provide an explanation of how normalisation improves database efficiency.

Deliverable

    A relational schema (set of tables) illustrating how the database conforms to 3NF.
    Step-by-step normalisation process (from UNF to 3NF) with explanations.
    A discussion on how normalisation prevents anomalies and improves efficiency.

### Unit 9

Scenario

Please refer to the scenario and your data model designed in your Mid-Module assessment and continue to develop your database to complete the required tasks.
Task 1: Query Your Database

There is a 1,500 word count limit for Task 1.
Task Requirements:

Using SQL, write a set of realistic queries based on the scenario. Your queries must demonstrate proficiency in:

    Joins – Using two, three, or more tables to retrieve meaningful information.
    Set operations – Using UNION, INTERSECT, and MINUS to combine or compare query results.
    Ordering – Sorting query results based on specified criteria.
    Grouping – Categorising data using GROUP BY.
    Aggregate functions – Using MIN, MAX, AVG, COUNT, and SUM for data analysis.

Guidance for Task 1

    Create (approx. 8) queries to extract information.
    Ensure queries are well-structured and include appropriate WHERE conditions for filtering data.
    Use aliases, functions, and joins effectively to enhance readability and efficiency.

Deliverables for Task 1

    SQL scripts for each query with a brief explanation of their purpose.
    Sample results demonstrating expected outputs.

Task 2: Implement Your Final Database Design Using MySQL
Task Requirements

    Create the database schema based on the given scenario.
    Define tables with appropriate primary keys (PKs) and foreign keys (FKs) to maintain referential integrity.
    Implement constraints such as NOT NULL, UNIQUE, CHECK, and DEFAULT values where necessary.
    Insert sample data into the database for testing.
    Ensure the database supports the required queries defined in Task 1.

Guidance for Task 2

    Use MySQL to design the relational database schema.
    Provide SQL scripts for table creation and sample data insertion.
    Implement indexes where necessary to optimise query performance.
    Consider constraints to enforce business rules and data integrity.

Deliverables for Task 2

    SQL scripts for table creation and sample data insertion.
    Screenshots or outputs from MySQL showing successful table creation and data population.

Task 3: Report on Implementation Challenges and Issues

There is a 1,500 word count limit for Task 3.
Task Requirements

Write a report discussing the challenges faced while implementing the database. Your report should include:

    Database Design Challenges – Issues encountered when designing the schema.
    SQL Query Challenges – Difficulties in writing and optimising queries.
    Data Integrity and Constraints – Problems ensuring referential integrity and constraints.
    Performance Considerations – Indexing and query optimisation techniques used.
    Reflections on Improvements – How the implementation could be improved for scalability and efficiency.

Guidance for Task 3

    Structure your report with headings and subheadings for clarity.
    Provide examples of problems encountered and how they were resolved.
    Discuss any refinements made to improve database efficiency.
    Use Harvard referencing to cite any academic sources. Using Cite Them Right.

Deliverable for Task 3

    A well-structured report (approximately 1500 words equivalent) discussing challenges, solutions, and improvements.

## 📊 Grade / Feedback

TBD

## ✍️ Authors

https://github.com/jam-esss

## ✅ License

Copyright © 2025 James Pink-Gyett. All rights reserved.
