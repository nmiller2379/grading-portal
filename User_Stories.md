# User Stories
1. As a user, I want to see a login page so that I can enter my credentials and login to the system.
2. As a user, I want to see a registration page so that I can create a new account, if I do not already have credentials.
3. As a user, I want to be able to login as an admin so that I can access the admin dashboard or as a user so that I can access the user dashboard.
4. As a user (student), I want to see a main dashboard so that I can see my current grade, due dates for upcoming assignments or assessments and any announcements.
5. As a user, I want to be able to navigate to a page where I can see all of my grades for all of my assignments and assessments to this point in the class.
6. On the grades page, I want to see a breakdown of my grades for each assignment or assessment so that I can see how I did on each part of the assignment or assessment.
7. On the grades page, I wan to see my overall grade for the class so that I can see how I am doing in the class.
8. On the grades page, I want to see my most recent grade for an assignment or assessment, along with any notes or feedback from the grader so that I can see how I did on the most recent assignment or assessment.
9. As a user, I want to be able to navigate to a page where I can submit my GitLab repository for an assignment or assessment for grading.
10. On the submission page, I want to see a form where I can enter the my GitLab repository project ID so that I can submit my assignment or assessment for grading. 
11. When the submit button is clicked, the program should make a request to the GitLab API to assign the project to the grader so that the grader can access the repository in GitLab and grade the assignment or assessment. The project should be assigned to the grader with the lowest number of assigned projects. If all graders have an equal number of assigned projects, the project should be randomly assigned to one of the graders.
12. On the submission page, I want to receive a message that tells me the submission was successful so that I know my assignment or assessment was submitted successfully. Or tells me there was an error if the submission was not successful.
13. As an admin (instructor or TA), I want to see a main dashboard so that I can see a list of all students in the class, their current grade, and any announcements.
14. As an admin, I want to be able to navigate to a page where I can see a form to create a new grade for a student so that I can enter a grade for a student.
15. The form should include fields for the student's name (a dropdown of available students), the assignment or assessment name, the grade, and any notes or feedback for the student.
16. On the form to create a new grade, I want to receive a message that tells me the grade was successfully created so that I know the grade was created successfully. Or tells me there was an error if the grade was not created successfully.
17. As an admin, I want to be able to navigate to a page where I can see a form to edit an existing grade for a student so that I can edit a grade for a student.
18. The form should include fields for the grade and any notes or feedback for the student. The name of the assignment or assessment should not be editable and should be the same as when the grade was created. The name of the student should not be editable and should be the same as when the grade was created.
19. On the form to edit an existing grade, I want to receive a message that tells me the grade was successfully updated so that I know the grade was edited successfully. Or tells me there was an error if the grade was not edited successfully.
20. Once a grade has been created or edited, the student should see the grade the next time they load their dashboard or their grades page.
20. As an admin, I want to be able to navigate to a page where I can see a form to create a new announcement for the class so that I can create an announcement for the class.
21. The form should include fields for the announcement title, the announcement message, and the date and a button to post the announcement to the user and admin dashboards.
22. On the form to create a new announcement, I want to receive a message that tells me the announcement was successfully created so that I know the announcement was created successfully. Or tells me there was an error if the announcement was not created successfully.
23. As an admin, I want to be able to navigate to a page where I can see a list of all announcements for the class so that I can see all announcements for the class. I should also be able to delete an announcement on this page or navigate to the page to edit the announcement.
24. As an admin, I want to be able to navigate to a page where I can see a form to edit an existing announcement for the class so that I can edit an announcement for the class.
25. The form should include a field for the the announcement message. The placeholder text should be the original message that is being edited. The form should also include a field for the date, of the announcement and a button to post the announcement to the user and admin dashboards. The title of the announcement should not be editable and should be the same as when the announcement was created.
26. On the form to edit an existing announcement, I want to receive a message that tells me the announcement was successfully edited so that I know the announcement was edited successfully. Or tells me there was an error if the announcement was not edited successfully.
27. As an admin, I want to be able to navigate to a page where I can see a list of all grades for all students in the class so that I can see all grades for all students in the class.
28. As an admin, I want to be able to navigate to a page where I can see a list of all grades for a specific student in the class so that I can see all grades for a specific student in the class.
29. I should be able to delete a grade on this page or navigate to the page to edit the grade.
30. As an admin, I want to be able to navigate to a page where I can see a form to post an assessment or project due date so that I can post an assessment or project due date for the class.
31. The form should include fields for the assessment or project name, the due date, and a button to post the due date to the user and admin dashboards.
32. On the form to post an assessment or project due date, I want to receive a message that tells me the due date was successfully posted so that I know the due date was posted successfully. Or tells me there was an error if the due date was not posted successfully.
33. As an admin, I want to be able to navigate to a page where I can see a list of all assessments and projects for the class so that I can see all assessments and projects for the class.
34. I should be able to delete an assessment or project on this page or navigate to the page to edit the assessment or project.
35. As an admin, I want to be able to navigate to a page where I can see a form to edit an existing assessment or project due date for the class so that I can edit an assessment or project for the class.

