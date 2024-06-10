# Intelligent-Tutoring-System
Intelligent Tutoring System for Personalized Learning with an implemented Chatbot for tutoring featuring a personalized study recommender.
Intelligent Tutoring System (ITS) by TanakaTrust
Overview
Welcome to the Intelligent Tutoring System (ITS) developed by Tanaka Trust. This system is designed to enhance the educational experience by providing personalized tutoring, interactive learning modules, and real-time feedback to students. The ITS aims to support both students and educators by offering a robust platform for learning and assessment.
Features
Personalized Learning Paths: Tailored educational content and assessments based on individual student performance and learning preferences.
Interactive Modules: Engaging and interactive learning activities, quizzes, and tutorials.
Real-Time Feedback: Immediate feedback on assessments to help students understand their progress and areas needing improvement.
Data Analytics: Detailed reports and analytics for educators to track student performance and identify trends.
Scalability: Capable of handling increasing numbers of students and data volume with ease.
Security: Strong security measures including authentication, access control, encryption, and data auditing.
Installation
Prerequisites
Operating System: Windows, macOS, or Linux
Database: MySQL
Web Server: Apache or Nginx
Programming Language: Python 3.8+
Framework: Django 3.0+
Steps
Clone the Repository
bash
Copy code
git clone https://github.com/TanakaTrust/ITS.git
cd ITS
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Configure Database
Update the DATABASES settings in ITS/settings.py with your MySQL database credentials.
Run Migrations
bash
Copy code
python manage.py migrate
Create a Superuser
bash
Copy code
python manage.py createsuperuser
Run the Development Server
bash
Copy code
python manage.py runserver
Access the ITS at http://127.0.0.1:8000.
Usage
Admin Portal
Access the admin portal at http://127.0.0.1:8000/admin.
Use the superuser credentials to log in.
Configure courses, modules, and user accounts.
Student Portal
Students can sign up and log in through the main page.
Access personalized learning paths and complete interactive modules.
Educator Portal
Educators can monitor student progress, create assessments, and review analytics.
Contribution
We welcome contributions to enhance the ITS. Please follow these steps:
Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes and push to your fork.
Submit a pull request with a detailed description of your changes.
Support
For any issues, questions, or support, please contact us at mangachenat@yahoo.com.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Thank you for using the Intelligent Tutoring System by Tanaka Trust. We hope it enhances your educational experience!
