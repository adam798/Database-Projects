# University Course Assessment Database

# Problem Description

This project aims to design a database that serves as a repository for questions related to courses offered at the university. The primary objective is to assess whether the learning outcomes of these courses are being achieved. The project is guided by the following business rules:

# Component 1: Entity-Relationship Diagram (ERD)

Professors at the university teach a variety of courses.
Each course may have a different combination of assessment types, such as exams, projects, assignments, quizzes, and presentations.
Professors can use various combinations of assessments for the courses they teach.
Each assessment is assigned a weight by professors.
Some assessments consist of multiple questions, each with its own point value.
Sample solutions are stored for some assessments, particularly for written exams.
Every question in an assessment is associated with a learning objective.
Learning objectives are categorized into six levels: Knowledge, Comprehension, Application, Analysis, Synthesis, and Evaluation.
Each level of learning objectives is further divided into up to 10 subcategories known as Graduate Attribute Indicators (GAI).
Professors aim to assess students comprehensively, ensuring that all GAIs are covered by at least one question/assessment, and each learning outcome is tested by two questions during the term.

# Component 2: Implementing the ERD
This component involves the actual implementation of the Entity-Relationship Diagram.
The database will store information about courses, assessments, professors, questions, learning objectives, and more.
Queries will be designed to retrieve specific information and perform data analysis.
Component 3: Embedded SQL
In this section, we will work with SQL queries to access and manipulate the data stored in the database.
The queries will help answer various questions, such as the percentage of students passing a specific course, the alignment of assessments with learning outcomes, and the types of assessments offered by specific courses in a given year and term.
Project Objectives
The objectives of this project are as follows:

# Design an effective database to store course assessment data.
Implement the ERD in a relational database management system (RDBMS).
Develop SQL queries to extract meaningful insights from the data.
Provide a solution to evaluate course assessments and learning outcomes.
Note
While the maximum cardinality is important, we will exercise judgment regarding the minimum cardinality when it is not explicitly mentioned in the text.
The successful completion of this project will enable the university to make informed decisions and ensure the quality of education by assessing the alignment of assessments with learning objectives.

For further details on the project, please refer to the associated project components (Component 1, Component 2, and Component 3).
