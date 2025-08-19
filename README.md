# mad1-proj-jan25

## Description

Quiz Master -  is a comprehensive quiz management system designed for both admins and users. Admins can easily create, manage, and schedule quizzes, while users can explore, attempt, and monitor their performance through interactive dashboards and detailed charts.

## Technologies Used

- Flask  
- Flask-SQLAlchemy  
- SQLite  
- Jinja2  
- HTML, CSS, Bootstrap  
- JavaScript, Chart.js  

## Architecture

- **Routes**: Located in `app.py`, all user and admin routes handle quiz management, search functionality, quiz attempts, and result storage.
- **Models**: Defined in `model.py` using SQLAlchemy ORM, managing database relationships for users, quizzes, subjects, chapters, questions, and scores.
- **Templates (Frontend UI)**: All HTML files are inside the `templates/` folder, categorized as:
  - **Admin Templates**: `templates/admin/` for quiz creation and user tracking.
  - **User Templates**: `templates/user/` for quiz attempts, search results, and performance tracking.
- **Static Files**: Images are stored in the `static/` directory.
- **Database**: Uses SQLite.

## Features

Features :-
 Admin Dashboard
•	Manage Subjects & Chapters: Easily create, edit, or delete subjects and chapters.
•	Quiz Management: Create quizzes with specific dates and durations.
•	Search Functionality: Quickly search for users, subjects, and quizzes.
•	Performance Overview: View summary charts of quiz results and user activity.
•	Quiz Control: Edit or delete quizzes and their questions.
•	MCQ-Based Quizzes: Conduct multiple-choice quizzes with set schedules and time limits.
  User Dashboard
•	Explore Quizzes: Browse and attempt quizzes from various subjects and categories.
•	Quiz Timer: Automatically submits quizzes when time is up.
•	Performance Tracking: View detailed records of scores and past attempts.
•	Summary Charts: Visualize your performance trends with interactive graphs.


## Video

Presentation Video Link:  
[Google Drive Link] https://drive.google.com/file/d/1E9wBgZq7hdbk9QzybljtNzZDrqeIiafg/view?usp=drivesdk
