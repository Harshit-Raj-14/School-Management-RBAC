# School Management RBAC

## Name : Harshit Raj

## PROJECT
The School Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. 
It aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

- **Admin Dashboard:** Administrators can manage student records, teacher information, courses, exams, assignments, track student attendance, add teachers, and view school performance metrics.
- **Student Dashboard:** Students have access to their own dashboard where they can view their class schedules, assignments, submit assignments, and track their academic progress.
- **Teachers Dashboard:** Teachers can manage class schedules, assign and grade exams and assignments, and view student performance metrics.


## Technologies Used
- **Frontend:** React, Vite, styled-components
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Deployment:** Not deployed yet


## FEATURES
## Student Features

- Internal Marks: Access to view internal marks for courses
- External Marks: Access to view external marks for courses
- Course Materials: Ability to download course materials
- Notices: Access to view notices
- Timetables: Access to view their own timetables
- Password Update: Ability for students to update their passwords

## Faculty Features

- Student Details: Ability for faculty to view student details
- Password Update: Ability for faculty to update their own passwords
- Notices: Ability for faculty to add notices
- Materials Upload: Ability for faculty to upload course materials
- Timetable Management: Ability for faculty to manage timetables
- Exam Mark Recording: Ability for faculty to record internal and external exam marks

## Admin Features

- Account Creation: Ability for admins to add new students, faculty, and admin accounts
- Account Details Modification: Ability for admins to modify the details of each account
- Subject Management: Ability for admins to add/edit subjects
- Notices Management: Ability for admins to add/edit notices



## Setup Instructions

1. **Clone the repository:**

git clone https://github.com/yatunyi15075/mern-school-management-system.git


2. **Install dependencies:**

cd mern-school-management-system
npm install


3. **Set up environment variables:**

- Create a `.env` file in the root directory.
- Define the following environment variables:

  ```
  PORT=4000
  MONGODB_URI=your_mongodb_connection_string
  SECRET_KEY=your_secret_key_for_jwt
  ```

4. **Run the development servers:**

- Start the frontend server:

  ```
  npm run dev
  ```

- Start the backend server:

  ```
  npm start
  ```
