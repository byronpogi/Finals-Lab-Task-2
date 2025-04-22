Final Task 2

This portfolio showcases my understanding of MySQL database creation through a simplified system for managing student assignment submissions. It outlines the step-by-step process of creating tables for students, assignments, and their submissions. The relational schema is designed using appropriate data types, relationships, and constraints such as primary keys, foreign keys, and composite keys to ensure data integrity and consistency.

1. Student Table Creation:

The username field is defined as a VARCHAR(50).

username serves as the primary key to uniquely identify each student.

2. Assignment Table Creation:

The shortname field is set as a VARCHAR(50) and acts as the primary key.

The due_date field is a DATE and cannot be null.

The url field is a VARCHAR(255) and can be left null.

3. Submission Table Creation:

The fields username and shortname are both defined as VARCHAR(50).

version is defined as an INT.

submit_date is a DATE and must not be null.

data is stored in a TEXT field.

A composite primary key is set on (username, shortname, version) to uniquely identify each submission attempt.

Foreign key constraints are added to link username to the student table and shortname to the assignment table.

Table Relationships Overview:

Student Table

Primary Key: username

Relationship: One student can make multiple submissions (One-to-Many with the submission table).

Assignment Table

Primary Key: shortname

Relationship: Each assignment can receive multiple submissions (One-to-Many with the submission table).

Submission Table

Composite Primary Key: (username, shortname, version)

Relationships:

Each submission is linked to a single student (Many-to-One with student).

Each submission is for a single assignment (Many-to-One with assignment).

This design effectively captures a Many-to-Many relationship between students and assignments, with the version field allowing multiple submission attempts per student-assignment pair.

## Screenshots

![Image](https://github.com/user-attachments/assets/3230a3a2-5300-4ea8-a798-dc7e887bcd68)
![Image](https://github.com/user-attachments/assets/49df2d61-b4cc-4b53-9855-b2cde686accc)
![Image](https://github.com/user-attachments/assets/111aeca8-428b-4fed-a6df-c3b70df27444)
![Image](https://github.com/user-attachments/assets/50cc0bfa-026f-45b1-bc1a-4b2ceb90db73)
![Image](https://github.com/user-attachments/assets/3599fdcb-5df7-4f4c-8c2e-63a8c3d9b8f8)
![Image](https://github.com/user-attachments/assets/c71c658b-7c6f-4068-8436-ee0bad8010f9)
![Image](https://github.com/user-attachments/assets/f039ba1a-18dd-4196-92ea-f83b7a8d464b)
![Image](https://github.com/user-attachments/assets/1cddcc96-3080-427c-9376-7455ba11df62)
