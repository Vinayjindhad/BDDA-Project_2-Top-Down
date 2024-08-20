# BDDA-Project_2-Top-Down




The primary goal of this project is to design a comprehensive database system for managing Voter ID cards using a top-down approach. The project involves creating an ER diagram, translating it into database tables, defining roles and permissions, and inserting dummy data for testing.

Steps Involved:
Identify Entities:

The project begins by identifying the key entities required for the database. These entities are:
Voter: Represents individuals who are eligible to vote.
Address: Contains the address details of each voter.
VoterID: Stores the unique voter ID information associated with each voter.
Define Relationships:

After identifying the entities, the relationships between them are defined:
A Voter can have one Address (1
relationship).
A Voter is associated with one VoterID (1:1 relationship).
Create ER Diagram:

An ER (Entity-Relationship) diagram is created to visually represent the entities and their relationships. This diagram serves as the blueprint for the database design.
Translate ER Diagram to Tables:

The ER diagram is then translated into a set of SQL tables:
Voter Table: Stores voter information (e.g., VoterID, FirstName, LastName, DateOfBirth, Gender, AddressID).
Address Table: Contains address details (e.g., AddressID, Street, City, State, ZipCode).
VoterID Table: Holds voter ID data (e.g., VoterID, VoterNumber, IssueDate, ExpiryDate).
Assign Roles & Permissions:

Roles are defined within the organization, and permissions are assigned over the database tables:
Admin: Full access to all tables.
Data Entry Clerk: Can insert and update records.
Supervisor: Can view and update records but cannot delete.
Auditor: Has read-only access to all tables.
Insert Dummy Data:

Dummy data is inserted into the tables to test the database design. This ensures that the structure and relationships function as expected.
