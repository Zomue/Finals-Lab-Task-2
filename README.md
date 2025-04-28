## Finals Lab Task 2. Transforming ER Model to Relational Tables

Given the ER diagram representing student assignment submissions, convert it into MySQL tables. Capture all entities and their attributes, and define the relationships between students, submissions, and assignments. Identify the primary and foreign keys and ensure proper representation of any dependent or weak entities.

In converting the ER diagram, the following are the data types of the attributes:

## student table:
username: String (VARCHAR), up to 50 characters.

## assignment table:
shortname: String (VARCHAR), up to 50 characters.
due date: Date, cannot be null.
url: String (VARCHAR), up to 255 characters, can be null.

## submission table:
username: String (VARCHAR), up to 50 characters.
shortname: String (VARCHAR), up to 50 characters.
version: Integer, represents the version of the submission.
submit date: Date, cannot be null.
data: Text.

# Here's The Query Statements

## 1.Student Table.
![image](https://github.com/user-attachments/assets/9c7868c2-03a2-42c7-9672-93ccc46a0a56)


## 2.Assignment Table.
![image](https://github.com/user-attachments/assets/636d4ae7-6112-4cc6-a80e-bcc530383d2b)


## 3.Submission Table.
![image](https://github.com/user-attachments/assets/56b3f135-d436-4a46-b803-25b07ea1972a)



# Here's The Table Structures

## 1.Student Table.
![image](https://github.com/user-attachments/assets/7c00f7a4-05c9-4a99-b967-f1eff0415606)

## 2.Assignment Table.
![image](https://github.com/user-attachments/assets/c30ff0e2-5b0f-4883-a0d1-ed9ee4fe4769)

![image](https://github.com/user-attachments/assets/900672ee-c065-4e96-85d4-9db54b46d097)


# Entity-Relationship Diagram (EER):
![image](https://github.com/user-attachments/assets/ea321f43-5f2b-466a-a5b4-aaff219ee3f1)


# The Basis for the Creation of the Ralational Tables:
![image](https://github.com/user-attachments/assets/ced1e06c-824a-4c58-a867-d8d15efeece6)


[BACK TO PORTFOLIO](https://zomue.github.io/)
