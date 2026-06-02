# Entrance Exam Preparation Platform
This project was submitted on **June 2/2026**, <br> 
given on **4th year, second semester**, <br>
it's the implementation of the documentation produced in the **4th year first semester course, Final year Project I**. <br>
## 👥 Group Contributors

| 🧑‍💻 Name | 🆔 Student ID |
| :--- | :--- |
| **Aman Atalay** | `UGR/4364/15` |
| **Asnake Mengesha** | `UGR/9465/15` |
| **Daniel Shitaye** | `NSR/9066/14` |
| **Fraol Dereje** | `UGR/6955/15` |

This Project is a mobile responsive web-based system that supports students taking the Ethiopian higher education university entrance examination.
The system provides:
- structured study resources,
- concept explanation with a set of working examples,
- curated list of interactive and solved problem sets,
- organized past year entrance examination problems,
- peer collaboration,
- admin and subject teacher management features.
## System Requirements
## Functional Requirements
-	[FR-01](https://github.com/Keradion/final-project-ii-ethiopian-university-entrance-exam/tree/main/frontend/src/pages/Register.jsx): The system shall allow students, teachers, and administrators to create or have a user account.
-	[FR-02](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/blob/main/frontend/src/pages/Profile.jsx): The system shall allow students, teachers, and administrators to view and update their account details.
-	[FR-03](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/blob/main/frontend/src/pages/Login.jsx): The system shall provide a login option for students, teachers, and administrators with a registered account
-	FR-04: The system shall provide a logout option for students, teachers, and administrators who are logged in.
-	[FR-05](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/blob/main/frontend/src/pages/ResetPassword.jsx): The system shall allow students, teachers, and administrators to reset their passwords.
-	FR-06: The system shall allow students to view and access all content uploaded under each subject.
-	[FR-07](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/blob/main/frontend/src/pages/ExamQuestionBank.jsx): The system shall allow students and teachers to access, search and filter previous-year exam problems by subject, chapter, by topic and exam year.
-	FR-08: The system shall provide students with a numerical progress indicator for subject completion and notify them when they reach 25%, 50%, 75%, and 100% milestones.
-	[FR-09](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/blob/main/frontend/src/pages/StudentDashboard.jsx): The system shall display students’ progress and results on the student's dashboard.
-	FR-10: The system shall allow students to join peer community groups via Telegram.
-	FR-11: The system shall notify students via in-app notifications and email about subject updates.
-	FR-12: The system shall allow students to navigate subjects and search for topics by title.
-	FR-13: The system shall provide interactive validations when students attempt exercises, quizzes, or previous-year questions under each topic.
-	FR-14: The system shall allow students to submit issues such as wrong answers, missing course materials, and related platform bugs.
-	FR-15: The system shall allow students to bookmark content for easy access.
-	FR-16: The system shall allow students to ask questions under each topic, and teachers can provide answers.
-	FR-17: The system shall allow a teacher to structure a subject by adding chapters and topics
-	FR-18: The system shall allow a teacher to add and manage content under each topic, including videos, concept pages, exercises, and previous-year exam questions.
-	FR-19: The system shall allow teachers to create and manage quizzes under each topic.
-	FR-20: The system shall allow the administrator to create a subject.
-	FR-21: The system shall allow the administrator to update subject information.
-	FR-22: The system shall allow the administrator to assign a teacher to a subject.
-	FR-23: The system shall allow the administrator to manage roles and activate or deactivate students’ and teachers’ accounts.
-	FR-24: The system shall display student reported issues such as wrong answers and missing subject content on the administrator and teacher dashboards and notify students of the outcomes.

## System development tools
-	[Frontend Development](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/tree/main/frontend): React framework with Tailwind.
-	[Backend Development](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/tree/main/backend): Node js.
-	Database Storage: Mongo DB.
-	Code Development: VS-Code Editor.
-	Code Collaboration and Version Controls: Git and Github.
-	Deployment: [Vercel](https://vercel.com/).
-	Document Preparation Tools: Microsoft Word, UML, Drawio, Gantt-Chart
## Model-View-Controller (MVC) Pattern
Following the standards of modern software engineering, the system utilizes the MVC pattern to organize its internal structure:
-	[View](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/tree/main/frontend/src/pages): The View represents the visual layer that allows users (Students, Teachers, and Admins) to interact with the system. In this platform, the View is composed of React components that display study materials, practice exams, and progress dashboards.
-	[Controller](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/tree/main/backend/src/controllers): The Controllers are implemented as RESTful APIs within the Node js framework. They act as the intermediary between the View and the Model. When a user performs an action, the Controller receives the request, calls the appropriate services for processing, and returns the results to the View in JSON format.
-	[Model](https://github.com/Keradion/Final_year_project_2-Entrance-Exam-Preparation-Platform/tree/main/backend/src/models): The Model layer consists of Javascript objects (Entities) and MongoDB collections that represent the system’s data and business logic. This includes data structures for User Profiles, Exam Questions, Subject Content, and Performance Analytics.
## Screenshots
________________________________________________
**Signing in**
![SignIn](/screenshots/photo_21_2026-06-02_20-38-16.jpg)
![SignIn](/screenshots/photo_22_2026-06-02_20-38-16.jpg)
________________________________________________
**Creating Account**
![CreateAccount](/screenshots/photo_19_2026-06-02_20-38-16.jpg)
![CreateAccount](/screenshots/photo_20_2026-06-02_20-38-16.jpg)
________________________________________________
**Stream Selection**
![StreamSelec](/screenshots/photo_18_2026-06-02_20-38-16.jpg)
________________________________________________
**Student Dashboard**
![StudDash](/screenshots/photo_17_2026-06-02_20-38-16.jpg)
![StudDash](/screenshots/photo_16_2026-06-02_20-38-16.jpg)
________________________________________________
**AI tutor**
![AItut](/screenshots/photo_13_2026-06-02_20-38-16.jpg)
![AItut](/screenshots/photo_1_2026-06-02_20-38-15.jpg)
________________________________________________
**Course Management**
![CourseMan](/screenshots/photo_3_2026-06-02_20-38-16.jpg)
![CourseMan](/screenshots/photo_5_2026-06-02_20-38-16.jpg)
________________________________________________
**User Management**
![UserMan](/screenshots/photo_7_2026-06-02_20-38-16.jpg)
________________________________________________
**Subject Management**
![SubjectMan](/screenshots/photo_8_2026-06-02_20-38-16.jpg)
________________________________________________
**Profile Details**
![ProfDet](/screenshots/photo_9_2026-06-02_20-38-16.jpg)
________________________________________________
**Q&A Management**
![Q&AMan](/screenshots/photo_4_2026-06-02_20-38-16.jpg)
________________________________________________
**Topics**
![Topics](/screenshots/photo_15_2026-06-02_20-38-16.jpg)
________________________________________________
**Concepts**
![Concepts](/screenshots/photo_14_2026-06-02_20-38-16.jpg)
________________________________________________
**Exercises**
![Exercises](/screenshots/photo_10_2026-06-02_20-38-16.jpg)
________________________________________________
**Issues**
![Issues](/screenshots/photo_6_2026-06-02_20-38-16.jpg)
________________________________________________
