# Title
Job-application-tracker

# Description
A full-stack MERN application (MongoDB, Express, React, Node.js) designed to help users organize, track, and manage their job applications effectively.


# Motivation
I am building this project to help college students track their job applications, ensuring they have a record of where they've applied. The application will also send reminders before interview times, helping users prepare and stay on schedule. By providing an organized platform, this project aims to assist users in managing their job search process and performance more effectively.


# Features

1.Log new job applications with company details and status.

2.Update application statuses (e.g., applied, interview scheduled, offer received).

3.Receive email reminders for upcoming interviews.

4.Centralized platform for tracking all job applications.

# Technologies Used
1. Frontend: React
2. Backend: Node.js, Express
3. Database: MongoDB
4. Styling : CSS / Talwind / Materia-UI
5. Email Integration: Nodemailer(for email reminders)

# Setup Instructions
1.Clone the Repository

   https://github.com/ankitdeveloper7/Job-Application-Tracker.git
   
2.Navigate to the Project Directory

    cd Job-Application-Tracker
3.Configure environment variables in .env(e.g., database URL, API keys).     
4.Install backend dependencies 

    cd server
    npm install
 5.Install frontend dependencies 

    cd ../client
    npm install   
 6.Start the backend server 

    cd ../server
    nodemon start   
 7.Start the frontend server 

    cd ../client
    npm run dev    
 8.Open your browser and go to http://localhost:5173 to view the application

   
This format makes each step clear and easy to follow, with all the necessary commands in place. Great job on the setup instructions!


# Usage Guide

* **Update User Profile**: Allows users to edit and update their personal details, such as name, contact information, and other relevant profile information.

* **Add a New Job Application**: Users can log new job applications by entering details such as the company name, job title, application date, and additional notes.

* **Update Application Status**: Track the progress of each application by updating its status (e.g., Applied, Interview Scheduled, Offer Received).

* **Delete an Application Entry**: Remove an application from the tracker once it's no longer relevant, helping keep the list organized.

* **Upload or Write Documents**: Users can upload documents like resumes and cover letters for each job application, or add custom notes for reference. This feature helps keep all necessary materials accessible in one place.

* **Save Contacts**: Store contact information for recruiters or company representatives. This feature can include fields for names, phone numbers, email addresses, and notes to streamline follow-ups and communications.

* **Set Interview Reminders**: Option to set reminders for upcoming interviews or follow-up dates, helping users stay on track without missing critical deadlines.

