# School Management RBAC

**Name : Harshit Raj**

**Deployed Link  -https://realschoolmanagementsystem.netlify.app/Adminlogin**

## PROJECT
The School Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. 
It aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

- **Admin Dashboard:** Administrators can manage student records, teacher information, courses, exams, assignments, track student attendance, add teachers, and view school performance metrics.
- **Student Dashboard:** Students have access to their own dashboard where they can view their class schedules, assignments, submit assignments, and track their academic progress.
- **Teachers Dashboard:** Teachers can manage class schedules, assign and grade exams and assignments, and view student performance metrics.


## Technologies Used
- **Frontend:** React, styled-components
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Firebase, JWT
- **Deployment:** Backend - Render, Frontend - Netlify


## FEATURES
## Student Features
- Class: See class and teacher assigned
- Course: Ability to view course
- Notices: Access to view notices
- Password Update: Ability for students to update their passwords

## Faculty Features
- Student Details: Ability for faculty to view student details
- Password Update: Ability for faculty to update their own passwords
- Notices: Ability for faculty to add notices
- Materials Upload: Ability for faculty to upload course materials
- Timetable Management: Ability for faculty to manage timetables
- Exam Mark Recording: Ability for faculty to record exam marks

## Admin Features
- Account Creation: Ability for admins to add new students, faculty, and admin accounts
- Account Details Modification: Ability for admins to modify the details of each account
- Subject Management: Ability for admins to add/edit subjects
- Notices Management: Ability for admins to add/edit notices

## Setup Instructions
1. **Clone the repository:**
> git clone https://github.com/Harshit-Raj-14/School-Management-RBAC

2. **Set up environment variables:**
Create a file called .env in the backend folder. Inside it write this :
> MONGO_URL = mongodb://127.0.0.1/school
If you are using MongoDB Compass you can use this database link but if you are using MongoDB Atlas then instead of this link write your own database link.

3. **Install Dependencies**
> cd frontend

> npm install

> cd backend
> npm install

5. **Run the development servers:**
- Start the backend server:
> npm start

- Start the frontend server:
> npm start

