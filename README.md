# **Practical Assessment**
## **Lou Geh University**
The Lou Geh University stores details about university students, courses, the semester a student took a particular course (and his mark and grade if he completed it), and what degree program each student is enrolled in. 
Consider the following requirements list: 
-	The university offers one or more courses.
-	A course is made up of one or more subjects.
-	A student must enroll in a course.
-	A student takes the subjects that are part of her course.
-	A course has a name, a course identifier, the total credit points required to graduate, and the year it commenced.
-	A subject has a name, a subject identifier, a credit point value, and the year it commenced.
-	Students have one or more given names, a surname, a student identifier, a date of birth, and the year they first enrolled. We can treat all given names as a single object—for example, “John Paul.”
-	When a student takes a subject, the year and semester he attempted it are recorded. When he finishes the subject, a grade (such as A or B) and a mark (such as 60 percent) are recorded.
-	Each subject in a course is sequenced into a year (for example, year 1) and a semester (for example, semester 1).

## **Task**
1. Create a prototype based on the attached problem
2. Technologies and design to be used are the following:
    * Backend -  PHP
    * Database - MySQL
    * Frontend - Basic HTML, CSS and Javascript
3. As for your application documentations you need to provide the ff:
   1. ERD
   2. DFD
4. Provide a ```README.md``` containing the setup guide.
5. The application should be published in Github via forked repository and for final version of your prototype will create a ```Pull request``` in Github 
6. You will send the Github link to us thru our email devops@biotechfarms.com on or before **31-08-2024** 12:00 PM


    ### **Directory structure**
    ```
    my-app/
    ├── configs                      (Config scripts)
    |   └── db.php
    ├── controllers                      (PHP Controller scripts)
    |   └── UserController.php
    ├── js/
    |   └── app.js                       (Javascript scripts)
    ├── css/
    |   └── style.css                    (CSS scripts)
    ├── index.html                       (Entry point)
    ├── documentation/                   (Documentation files and assessts)
    |   └── UserController.php
    └── README.md                        (Project documentation)
    ```
    ### **Submission format**
    - Repository should show codebase directory directly **DO NOT PUT YOUR CODE BASE IN A ZIP FILE** use git commands instead to push your code-base and further updates.
    - Prototype's latest version should be the default branch of the repository.
    - Provide a READ.ME file on how to install and deploy your prototype, and its prerequisite, software, sdk(if needed), and driver.
