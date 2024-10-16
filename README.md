# TASK2-STUDENTS-DATABASE-MANGAMENT

STEP:-1 Create the new connection Oracle database with the name of the (STUDENTDB[STUDENTDATABASE]).
STEP:-2 After creating the new connection of the STUDENTDB 
  1. Create the table with the table of the students.
    1. student_id: Unique identifier for each student (auto-incremented).
    2. first_name: Student's first name.
    3. Last name: Student's last name.
    4. date_of_birth: Student's date of birth.
    5. email: Student's email address.
    6. phone: Student's phone number.
  2. After creating the table insert the value and execution it.

![Screenshot 2024-10-01 132915](https://github.com/user-attachments/assets/eba20ee6-220d-4f5f-85ca-933dc5cbaad0)
 STEP:-3 Create the table with the table of the Courses
  1.Purpose: Store details of each course offered.

Columns:
 1.course_id: Unique identifier for each course (auto-incremented).
 2.course_name: Name of the course.
 3.course_description: Description of the course.
 4.course_credits: Number of credits the course is worth.

![Screenshot 2024-10-10 083514](https://github.com/user-attachments/assets/7310e972-02f4-4563-b174-b3b4179e2bed)

STEP:-4 Create the table with the table of the enrollments
  1.Purpose: Manage the enrollment of students in courses and store their grades.

Columns:
 1.enrollment_id: Unique identifier for each enrollment (auto-incremented).
 2.student_id: References Students.student_id.
 3.course_id: References Courses.course_id.
 4.enrollment_date: Date of enrollment.
 5.grade: Grade achieved in the course.


![Screenshot 2024-10-16 174414](https://github.com/user-attachments/assets/807e9fad-782e-4f83-ba68-e05a8b8f7fc7)

STEP:-4 using the joins in table
   After using the joins the output  of the table are
   

 



 

