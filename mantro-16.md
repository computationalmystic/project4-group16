# Dom's To-Do List (Group Project) 

[Based off of my last groups work located at: https://www.github.com/Claire-Hough/Cnhfg6/blob/master/project-2/project_document.md/]

To Do List:
- Design UI
- Class List:
-- tAInfo()
-- studentInfo()
-- professorInfo()
-- adminInfo()
-- submissionInfo()
-- assignmentInfo()
-- uploadedFile()

Students:
- Students must login to their account to access the system.
-- Credentials must pass through login credential databse & server.
- Students can upload files (aka turn in assignments).
-- File Upload system has to check if the student's uploaded file is the right file format.
-- File Upload system is only available if the submissions are still open.
-- File Upload system has to make sure the student's file is under the file size limit.
- Students can resubmit their files (assignments).
-- File Upload system has to make sure resubmissions option is available and that the due date has not yet been reached.
- Students can view their grades on assignments.
- Students are enrolled in courses.
- Students have the following variables attached to them:
-- Email
-- Section_ID
-- Major
-- Course_ID
-- Pawprint
-- Student_ID
-- Credentials (Username/Password)
-- Name (First/Last)
-- Enrolled_In (leads to Course Info)
-- Views (leads to Assignment)
-- Submits (leads to Submission Info)

TA's:
- TA's must login to their account to access the system.
-- Credentials must pass through login credential databse & server.
- TA's assist courses.
-- They are assigned to a course.
- TA's grade submissions.
-- Grading System has to have the ability to view submissions.
-- Grading System has to have the ability to add comments.
-- Grading System has to have the ability to enter and attach a grade to a students submission.
-- Grading System must update the grade database once the TA publishes their grades.
- TA's have the following variables attached to them:
-- Email
-- Course_ID
-- Pawprint
-- Student_ID
-- Name (First/Last)
-- Credentials (Username/Password)
-- Assists (leads to Course Info)
-- Grades (leads to Submission info)
-- Views (leads to Assignment)

Professor/Instructor:
- A Professor must login to their account to access the system.
-- Credentials must pass through login credential databse & server.
- A Professor teaches a course.
-- They are linked to a course.
- A Professor can also grade submissions, along with TAs.
-- Can Overwrite TA Grade
-- (see TA's grade submission requirements for th rest)
- A Professor can post assignments.
-- Must upload file through the same file management system that students do.
-- Can't exceed a certain file size.
- A Professor can create/edit/remove courses/sections within their managed courses/sections.
-- Updates class/section database.
- Professor has the following variables attached to them:
-- Email
-- Course_ID
-- Instructor_ID
-- Name (First/Last)
-- Credentials (Username/Password)
-- Teaches (leads to Course Info)

System Admin:
- A System Admin must login to their account to access the system.
-- Credentials must pass through login credential databse & server.
- A System Admin can manage Instructors.
-- They can add/edit/remove Instructors from the database and courses.
-- Updates system database.
- System Admin has the following variables attached to them:
-- Email
-- Name (First/Last)
-- Credentials (Username/Password)
-- Permissions
-- Controls (leads to Instructor)

Interacting (Non-Roles):
- Courses:
-- A Course has the following variables attached to it:
--- Course_ID
--- Instructor_ID
--- Student_Pawprint
--- TA_Pawprint

- Assignment:
-- Assignments have the following variables attached to them:
--- Date_Posted
--- Assignment_ID
--- Description
--- Due_DATE

- Submission:
-- Submission has the following variables attached to them:
--- Submission_ID
--- File
--- Comment
--- Due_Date
--- Student_Pawprint
--- TA_Pawprint
--- Grade
--- Date_Submitted
--- Assignment_ID