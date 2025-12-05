🧪 Online Examination System – SQL Project

A complete SQL-based system designed to manage online examinations efficiently.
This project handles students, subjects, exams, questions, answers, and results while providing automated evaluation, reporting, and analytical insights.

📌 Project Overview

The Online Examination System is built to track student performance, manage exam workflows, and generate analytical reports. The database ensures accurate linkages between students, exams, questions, responses, and results. 

Presentation1

🏗️ Database Design
1. Students Table

  Stores student details such as ID, name, email, and class year.
  Each student is uniquely identified and linked to their answers and results.


Presentation1

2. Subjects Table

  Maintains a list of academic subjects, each identified by a unique subject ID.
  Used to connect exams with subjects.


Presentation1

3. Exams Table

  Holds exam details such as exam ID, subject ID, date, and duration.
  Enables mapping between subjects and their scheduled exams.


Presentation1

4. Questions Table

  Stores all questions belonging to specific exams, including correct answer options.
  Supports multiple-choice exam structures.


Presentation1

5. Answers Table

  Captures each student's selected answer for every question.
  Used to evaluate performance by comparing with correct answers.


Presentation1

6. Results Table

  Stores final marks, grades, and overall performance metrics for each student–exam pair.
  Supports analytics and reporting.


Presentation1

🔍 SQL Features Implemented
✔ Subqueries

Examples include:

Students who never scored Grade 'A'

Exams with average marks > 7

Students who submitted incorrect answers


Presentation1

✔ Joins

Used to retrieve combined information across multiple tables, such as:

Student results with subject names

Student responses with question text

Subject-wise average marks


Presentation1

✔ Views

Views created for:

Top performers (Grade A students)

Student-level report cards


Presentation1

📊 Sample Outputs

Student performance reports

Subject-wise analytics

Exam-level evaluation summaries

🛠️ Technologies Used

SQL / MySQL

ER Diagrams & Relational Modeling

Joins, Subqueries, Views, Constraints
