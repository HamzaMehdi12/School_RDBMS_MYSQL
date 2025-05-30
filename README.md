# School_RDBMS_MYSQL
Architected and provisioned the Course, Teacher, Student, and Parent tables based on an enhanced EER diagram, enforcing 1–N and N–1 referential integrity with cascading foreign keys, then seeded them with dimensionally compliant sample records (14 course offerings, 6 faculty, 40 student entities, 15 guardian entries).

Orchestrated a bulk DML workflow: leveraged a unified UPDATE … CASE statement to perform windowed mapping of Teacher_ID, course_ID, and course_name across student ID ranges, followed by an UPDATE … JOIN to propagate normalized credits from the Course dimension, while procedural WHILE loops were prototyped but eschewed in PopSQL due to its delimiter constraints.

### EER Diagram
![EER Diagram School](https://github.com/user-attachments/assets/a43a2a66-8850-4b0a-ac5f-a8004c17022e)
