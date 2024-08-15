### Student Management System Project

#### Project Overview
The goal of this project is to apply the principles of Object-Oriented Programming (OOP) to build a simple Student Management System. This system will allow the management of students, courses, and enrollments, demonstrating the use of classes, objects, inheritance, polymorphism, and encapsulation.

#### Requirements

1. **Class Structure**:
   - **Person**: A base class with common attributes for `Student` and `Instructor`.
   - **Student**: Inherits from `Person` and includes attributes specific to students.
   - **Instructor**: Inherits from `Person` and includes attributes specific to instructors.
   - **Course**: Represents a course with attributes such as course name, course ID, and a list of enrolled students.
   - **Enrollment**: Represents the enrollment of a student in a course with attributes such as student, course, and grade.

2. **Functional Requirements**:
   - Ability to add, remove, and update students and instructors.
   - Ability to add, remove, and update courses.
   - Enroll students in courses.
   - Assign grades to students for specific courses.
   - Retrieve a list of students enrolled in a specific course.
   - Retrieve a list of courses a specific student is enrolled in.

#### Detailed Instructions

**1. Person Class:**
Define a `Person` class that has the following attributes:
- `name`: Name of the person
- `id_number`: ID number of the person

Include a `__str__` method to return a string representation of the person.

**2. Student Class:**
Define a `Student` class that inherits from `Person`. Add an attribute `major` for the student's major. Override the `__str__` method to include the student's major.

**3. Instructor Class:**
Define an `Instructor` class that inherits from `Person`. Add an attribute `department` for the instructor's department. Override the `__str__` method to include the instructor's department.

**4. Course Class:**
Define a `Course` class with the following attributes:
- `course_name`: Name of the course
- `course_id`: ID of the course
- `enrolled_students`: List to keep track of students enrolled in the course

Include methods to add and remove students from the course. Override the `__str__` method to return a string representation of the course.

**5. Enrollment Class:**
Define an `Enrollment` class with the following attributes:
- `student`: The student enrolled
- `course`: The course in which the student is enrolled
- `grade`: The grade assigned to the student (initially set to `None`)

Include a method to assign a grade to the student. Override the `__str__` method to return a string representation of the enrollment.

**6. Student Management System:**
Define a `StudentManagementSystem` class that will manage the students, instructors, courses, and enrollments. It should include methods to:
- Add, remove, and update students and instructors
- Add, remove, and update courses
- Enroll students in courses
- Assign grades to students for specific courses
- Retrieve a list of students enrolled in a specific course
- Retrieve a list of courses a specific student is enrolled in

#### Grading Criteria

1. **Functionality (40 points)**
   - Correct implementation of classes and their relationships (20 points)
   - Correct implementation of methods and functionalities (20 points)

2. **Code Quality (35 points)**
   - Proper use of OOP principles: encapsulation, inheritance, polymorphism (15 points)
   - Code readability: clear and consistent naming conventions, comments, and documentation (15 points)

3. **Completeness (25 points)**
   - All specified requirements are met (15 points)
   - Additional features or enhancements beyond the basic requirements (10 points)

