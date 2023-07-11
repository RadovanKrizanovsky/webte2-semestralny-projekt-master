<table align="center">
  <tr>
    <th>Entire assignment is repost from my other profile</th>
  </tr>
</table>

# WEBTE2 Final Assignment LS 2022/2023

## Links
- App: https://site173.webte.fei.stuba.sk/
- GitHub: https://github.com/fa5tkill3r/webte2-semestralny-projekt
- Video: https://youtu.be/TTSsWNQA32s

This is the final assignment for the WEBTE2 course for the academic year 2022/2023.

## General Instructions
- The project will be completed in teams of four, and the tasks should be evenly distributed among team members.
- The assignment must be submitted packed in the MS Teams environment no later than 18.5.2023 (23:55) by one team member. Late submissions will be penalized with a deduction of 1 point per day for each team member.
- The entire project should be hosted on the school server for the purpose of course completion.
- When submitting through MS Teams, include the URL of the page on the school server in the comment section.
- The webpage should be optimized for Chrome and Firefox browsers.
- It is recommended to work with the Internet, explore different websites, but be aware that plagiarism will result in severe consequences.
- If a team member cannot answer a question regarding the implementation of a specific part, it will be considered as incomplete.
- Well-designed projects or their parts may be published publicly.

## Assignment Description
The task is to develop an application that allows the random generation of mathematical problems for students and later checks their solutions.

Keep in mind the importance of graphical design, appropriate structuring, easy navigation, and overall usability. You should also focus on ensuring the security of the entire application. The use of a PHP framework is allowed for this project.

The developed application should meet the following requirements:

1. Use a version control system such as GitHub, GitLab, or Bitbucket for project development.
2. Design a bilingual website (Slovak and English). Note that when switching languages, the page should remain on the same page the user was on before the switch, not the homepage of the application.
3. Create a responsive website, including the graphics used.
4. The application should have two types of roles: student and teacher.
5. After logging in, a student should have access to two functionalities:
   - Generating mathematical problems for solving.
   - Overview of assigned tasks, including the ability to submit their solutions. The overview should clearly indicate which tasks have been submitted and which ones haven't.
   Each task can be generated and submitted individually.
6. The generation of tasks will be based on LaTeX files provided as part of the assignment.
   - The number of files is not predefined, so if a new LaTeX file is added, the application should handle and process it accordingly.
   - LaTeX files may reference images, which also need to be loaded and processed by the application. The method of loading and processing images depends on your preferences.
   - Each file represents a set of problems (the number of problems in a file is not predefined), and the student can be randomly assigned one problem to solve from each set.
7. The teacher should be able to:
   - Define which LaTeX files the student can generate problems from and within which time period.
   - Assign points for each set of problems (all problems defined in one file should have the same value). The assignment of points should also apply to problems generated for individual students.
   - View a clear table of all students (name, surname, student ID) with information about the number of problems generated, the number of problems submitted, and the points awarded for each student. The table should support sorting based on all the mentioned criteria (if numerical values are equal, the sorting criterion should be the surname).
   - View the details of each student, including the tasks generated, tasks submitted, submitted answers, correctness status, and points awarded for each task.
8. The students should write their answers mainly in the form of mathematical expressions (e.g., fractions, differential equations, etc.). Use available online tools like a mathematical editor at http://camdenre.github.io/src/app/html/EquationEditor to handle the answer inputs.
9. The correctness of answers should be checked based on the expected results provided in the LaTeX files. It should be noted that students' answers may not have the exact same format as the expected results in the files. For example, 3/4 is the same as 0.75, and 2s+16s+4 is the same as s+0.5s+0.251. In case of rounding for result comparison, round to 4 decimal places.
   It is possible to use freely available libraries or even Computer Aided Systems (CAS), such as Maxima or Octave, for answer evaluation. In such a case, the CAS needs to be installed on the server.
10. In addition to the functionalities defined in point 6, the teacher should have the following capabilities:
    - Define the maximum number of points a student can receive for each set of problems (all problems defined in one file will have the same maximum point value).
    - Export the student overview table to a CSV file.
    - View the details of each student, including the tasks generated, tasks submitted, submitted answers, correctness status, and points awarded for each task.
11. The application should include a user manual on how to use the application from both the student and teacher perspectives. The manual should be generatable in PDF format. Any changes made on the website should reflect in the dynamically generated PDF file.
12. The application should be submitted as a Docker package.
13. Create a video documenting the functionality of the developed application. If a functionality is not shown in the video, it will be considered as not implemented.

## Additional Requirements
When submitting the project, include the following in MS Teams:
- Technical documentation (same requirements as for other assignments), including:
  - Login and password for administrative access to the database and the application.
  - Division of tasks among team members.
  - Clearly indicate any tasks that were not completed.
- The application itself:
  - Docker package or
  - Packed files including the configuration file, which should define all the necessary settings, and an SQL file for database population.
- Created video.

Additionally, when submitting, provide:
- The location address to identify the project under your name.
- The URL of the project in the version control system.

## Evaluation Proposal
Tasks | Points
----- | ------
Bilingualism | 6
Application login (student, teacher) | 6
GUI and functionality for students (including mathematical editor) | 16
GUI and functionality for teachers | 16
Solution correctness verification | 16
Export to CSVand PDF | 10
Docker package | 16
Usage of version control system by all team members (minimum 3 commits per member) | 8
Finalization of the application | 18
Video | 8

Please note that the table provided at the end of the document is incomplete, and the missing content is marked with ellipsis. You will need to fill in the missing information in the table or provide the complete information based on the requirements of the assignment.


