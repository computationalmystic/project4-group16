REFERENCE FROM MY DESIGN DOCUMENT :[https://www.github.com/Claire-Hough/Cnhfg6/blob/master/project-2/project_document.md/](https://www.github.com/Claire-Hough/Cnhfg6/blob/master/project-2/project_document.md/)]

TO DO LIST: 
Create an User Interface 
Create Classes as below:

## ***1.LOGIN***(Root Class)

**Variables**: 
username, email, password, newPassword,

**Methods**: createSession, authentication, authorization, forgotPassword, changePassword
1.**createSession**: sets time duration and checks if username and password is not empty.
1.**authentication**: check if the username exists.If no then display a message. If yes, check if the password matches the username.If no display a message.If yes process authorization and then navigate to home page.

2.**authorization**: check in which category the username is present (admin/student/TA/Instructor).

3.**forgotPassword**: Prompt the user to enter the email. Send an email to the

4.**changePassword**: Prompt the user to enter the username and currentPassword. Process authentication. Prompt the user to enter newPassword twice and check if that matches. Change the password to newPassword.
## 2.***ADMIN***:

**Variables:**
 adminName, pawprint(Login),
**Methods**: validateUser, validateCourses, assignUserType, addPrivileges, addCoursetoInstructor.

## 3.***ASSIGNMENT***

**Variables**: AssignmentFile, SubmissionTime, userName

**1.CreateAssignment**: 1.check userType(only accessible to Instructor/TA). 2.uploadAssignment 3.checkFileType 4.Enter Deadline 5.Enter Comments 6.showAssignmentCreationTime 7.sessionAvailableTillDeadline

**2.SubmitAssignment**: 1.check userType(only accessible to Students). 2.uploadAssignment 4.Enter Comments 5.SubmitAssignment 6..showAssignmentSubmissionTime .7.requestResubmission

**3.DeleteAssignment**: Instructor/TA can delete an assignment

**4.UpdateAssignment**: Instructor/TA has update Assignment for eg. change deadline, change question etc.

**5.GradeAssignment**: chooseGradingMethod(Instructor can choose different methods to grade). 

## 4.***COURSE***:

**Variables**:courseName, courseID(from Admin),
InstructorName, InstructorDetails, syllabus(from Instructor),
TAName,TADetails(TA),assignments, students

4.**STUDENT**:

**Variables**:
studentName, pawprint(from Login),
courseList(from Courses),
assignmentList, grades(from/to Assignments)

**Methods**:
submitAssignment, enterComments (to Assignment)

## ***5.TA:***

**Variables**:
studentName, pawprint(Login),
courseList(Courses),
assignmentList, grades(Assignments)

**Methods**:
createAssignment, updateAssignment, deleteAssignment, enterComments (to Assignment).

## ***6.INSTRUCTOR***:

**Variables**:
instructorName, pawprint(from Login),
courseList, studentList, TAList,(from/to Courses),
assignmentList,grades(from/to Assignments)

**Methods**:
createAssignment, updateAssignment, deleteAssignment, enterComments (to Assignment).
addStudent, updateStudent( to Students and Courses)
addTA,updateTA, addPrivilegesTA, updatePrivilegesTA( to TA)
addSyllabus(to Courses)

## 7.***LOGOUT***

**Methods**: endSession
