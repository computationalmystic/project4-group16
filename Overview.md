# Group Overview:
By: Dominic Mantro, Jinbo Liu, & Sweta Pragyan Praharaj

# Core Objects:
- Members: Student, TA, Instructor, System Admin
- Secondary 'Members': Course, Assignment, Submission
- Classes: courseInfo(), submissionInfo(), studentInfo(), instructorInfo(), adminInfo(), taInfo(), assignmentInfo().
- Methods: login(), logout(), validateUser(), addPriveleges(), downloadFile(), uploadFile(), removeCourse(), addCourse(), gradeAssignment(), addTA(), removeTA(), addInstructor(), removeInstructor().

# Next Steps:
First, we would need to implement/code all of the above classes and methods. Next, our group needs to design the UI interface for the system. The UI will need a login/logout page along with an interface for viewing & submitting the assignments and seeing student grades. The system admin, TA, and instructor will also need a control panel of some sorts so they can perform their specific extra abilities (that students cannot perform). Next, we would have to create a database to store all of the info including username/passwords, assignments, student/ta/instructor/admin information, and grade data. Then we would need to establish a server that can host all of this stuff. Obviously, throughout the process we will be testing all of these things.