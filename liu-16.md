this is the diagrams from last team assignment https://github.com/catscrossfitcomputers/mmhvyc/blob/master/project-two/Project%202.pdf

To do List

        Classes : course_info(), file_info(),assignment_info(),contact_info(),submission_info(), user(),

        methods : login(),check_assignment_open(), course_open(), file_type(),forgot password(),open/close_assignment(),download_file(), grading(),comments()

student:

        (login):to do any activity associated with courses, student must login to the system with their account number and password. Only the matched account number and password would be accessed. If both of them matched, now they can jump into course selection page. If account number wrong, prompt user to try another account, if password wrong, provide user to try another password.
        (forgot password):click this link and transfer the user to the page to make changes to their password. To do that, they need to verify their email address and receive a verify link, enter the link they are able to change password.

        (couse_info)/(register_info): before student are able to submit file for their assignment, they must select a course first, when student signle click the course penal, system will check if they were registed in this course, if not, system will prompt the user to select another coruse, if registered, show students the whole functions in course penal(assignments, grade, module, contact and submission)

        (check_assignment_open):within the course info class, implementing the method of check_assignment_open to check if the assignment was opened to submit file yet. If not opened, page will has not option to do that.

        (file_type):after student tried to submit a file, system will check if the file student submitted matches with the type professor preferred. if not matches, prompt user the type of file allowed in this assignment, and try to submit another one.

        (submit_count): student may be allowed to submit file several times, but if the times of submission exceed the limits, system prompts user they can not submit file for this assignment anymore.


TA:

        (login):to do any activity associated with courses, student must login to the system with their account number and password. Only the matched account number and password would be accessed. If both of them matched, now they can jump into course selection page. If account number wrong, prompt user to try another account, if password wrong, provide user to try another password.

         (forgot password):click this link and transfer the user to the page to make changes to their password. To do that, they need to verify their email address and receive a verify link, enter the link they are able to change password.

        (couse_info)/(register_info): before TA are able to post announcement or assignment, they must select a course first, when TA signle click the course penal, system will check if they were registed in this course, if not, system will prompt the user to select another coruse, if registered, show TA the whole functions in course penal(assignments, grade, module, contact and submission)

        (open/close_assignment):allow the TA to set the period of time of a assignment to be able to access and allow student submit files. After the time was setted, TA could still be able to make a change on the timer, extending the due date or close the entry before due date.
        
         (set_file_type):allow TA set the types of file which students are suppose to submit, also the requirement of size of file could be adjusted by TA. Once these setting done, student could only submit the files within the limitation of the specific type and size.

        (download_file): allows TA to download file submitted by students

        (grading): allows TA put grade or modify the grade of an assignment which were graded before.
                                                                                                                                                             (comment); allow TA put comments or modify the comment to an assignment

Professor:

                                                                                                                                                   (login):to do any activity associated with courses, student must login to the system with their account number and password. Only the matched account number and password would be accessed. If both of them matched, now they can jump into course selection page. If account number wrong, prompt user to try another account, if password wrong, provide user to try another password.                                                              
         (forgot password):click this link and transfer the user to the page to make changes to their password. To do that, they need to verify their email address and receive a verify link, enter the link they are able to change password.                                                                                                                                                                                     (open/close_assignment):allow the professor to set the period of time of a assignment to be able to access and allow student submit files. After the time was setted, TA could still be able to make a change on the timer, extending the due date or close the entry before due date.    
         
         (set_file_type):allow professor set the types of file which students are suppose to submit, also the requirement of size of file could be adjusted by TA. Once these setting done, student could only submit the files within the limitation of the specific type and size.
                                                                                                                                                 (download_file): allows professor to download file submitted by students

        (grading): allows professor put grade or modify the grade of an assignment which were graded before.                                         
        (comment); allow professor put comments or modify the comment to an assignment
