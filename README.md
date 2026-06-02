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
**Signing in** <br>
![SignIn](/screenshots/photo_21_2026-06-02_20-38-16.jpg)
![SignIn](/screenshots/photo_22_2026-06-02_20-38-16.jpg) <br>
**Creating Account** <br>
![CreateAccount](/screenshots/photo_19_2026-06-02_20-38-16.jpg)
![CreateAccount](/screenshots/photo_20_2026-06-02_20-38-16.jpg) <br>
**Stream Selection** <br>
![StreamSelec](/screenshots/photo_18_2026-06-02_20-38-16.jpg) <br>
**Student Dashboard** <br>
![StudDash](/screenshots/photo_17_2026-06-02_20-38-16.jpg)
![StudDash](/screenshots/photo_16_2026-06-02_20-38-16.jpg) <br>
**AI tutor** <br>
![AItut](/screenshots/photo_13_2026-06-02_20-38-16.jpg)
![AItut](/screenshots/photo_1_2026-06-02_20-38-15.jpg) <br>
**Course Management** <br>
![CourseMan](/screenshots/photo_3_2026-06-02_20-38-16.jpg)
![CourseMan](/screenshots/photo_5_2026-06-02_20-38-16.jpg) <br>
**User Management** <br>
![UserMan](/screenshots/photo_7_2026-06-02_20-38-16.jpg) <br>
**Subject Management** <br>
![SubjectMan](/screenshots/photo_8_2026-06-02_20-38-16.jpg) <br>
**Profile Details** <br>
![ProfDet](/screenshots/photo_9_2026-06-02_20-38-16.jpg) <br>
**Q&A Management** <br>
![Q&AMan](/screenshots/photo_4_2026-06-02_20-38-16.jpg) <br>
**Topics** <br>
![Topics](/screenshots/photo_15_2026-06-02_20-38-16.jpg) <br>
**Concepts**
![Concepts](/screenshots/photo_14_2026-06-02_20-38-16.jpg) <br>
**Exercises** <br>
![Exercises](/screenshots/photo_10_2026-06-02_20-38-16.jpg) <br>
**Issues** <br>
![Issues](/screenshots/photo_6_2026-06-02_20-38-16.jpg) <br>
