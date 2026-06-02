# Entrance Exam Preparation Platform
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
-	[Frontend Development: React framework with Tailwind](/frontend).
-	[Backend Development: Node js](/backend).
-	Database Storage: Mongo DB.
-	Code Development: VS-Code Editor.
-	Code Collaboration and Version Controls: Git and Github.
-	Deployment: [Vercel](https://vercel.com/).
-	Document Preparation Tools: Microsoft Word, UML, Drawio, Gantt-Chart
## Model-View-Controller (MVC) Pattern
Following the standards of modern software engineering, the system utilizes the MVC pattern to organize its internal structure:
-	View: The View represents the visual layer that allows users (Students, Teachers, and Admins) to interact with the system. In this platform, the View is composed of React components that display study materials, practice exams, and progress dashboards.
-	Controller: The Controllers are implemented as RESTful APIs within the Node js framework. They act as the intermediary between the View and the Model. When a user performs an action, the Controller receives the request, calls the appropriate services for processing, and returns the results to the View in JSON format.
-	Model: The Model layer consists of Javascript objects (Entities) and MongoDB collections that represent the system’s data and business logic. This includes data structures for User Profiles, Exam Questions, Subject Content, and Performance Analytics.
