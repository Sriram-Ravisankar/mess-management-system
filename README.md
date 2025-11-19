## 🍽️ MessNet: web Based Mess Management System for Hostel Administration

MessNet is a web-based, all-in-one mess automation platform built using Django.
It modernizes hostel mess workflows by allowing students to manage their menu, leave requests, bills, feedback, and lost & found through an elegant, user-friendly interface.

The system also empowers administrators with full control over menu updates, leave approvals, billing, notifications, and more—all from a centralized backend.

## 🎨 Modern UI Experience

MessNet ships with a clean, responsive UI featuring:

Sleek layout built with Tailwind CSS

Sidebar navigation with animated Lucide icons

Dashboard with live updates using real-time polling

Seamless module switching (Menu, Leave, Bills, Feedback, Lost & Found)

Mobile-first responsive design

Toast-like feedback messages

Feedback with 1–5 rating


## ✨ Core Features
👨‍🎓 Student Features

● Dashboard Overview
   
   ○ Profile info (Name, Hostel ID, Department, Mobile)
      
   ○ Latest mess bill & payment status
      
   ○ Leave request status
      
   ○ Today’s food menu
      
   ○ Latest admin notifications

● Weekly Food Menu

● Mess Leave Request

   ○ Apply for leave
      
   ○ Auto bill adjustment based on approved days

● Mess Bill Tracking

   ○ Monthly bill list with paid/due status

● Feedback & Rating System

   ○ 1–5  rating + comment

● Lost & Found Portal

   ○ Submit item reports

   ○ View admin-approved posts

● Real-Time Notification System

🛠️ Admin Features

● Add/update weekly Food Menu

● Approve/Reject Leave Requests

● Auto-generate bill adjustments

● Activate/Deactivate Admin Notifications

● Approve Lost & Found entries

● View feedback (read-only)

● Manage student profiles


## 🧰 Technology Stack 
● Backend

   * [Python](https://www.python.org/)

   * [Django](https://www.djangoproject.com/) (Web Framework)

   * [SQLite](https://www.sqlite.org/index.html) (Development Database)
     
● Frontend

   * [Tailwind CSS](https://tailwindcss.com/) (Styling)

   * [Lucide Icons](https://lucide.dev/)

   * [JavaScript (ES6)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

   * [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)  
   
   * [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)


## 🖼️ Screenshots

Place screenshots inside a /screenshots folder.

📌 Dashboard

![Dashboard](screenshots/dashboard.png)

📌 Food Menu

![Menu](screenshots/menu.png)

📌 Leave Request

![Leave](screenshots/leave.png)

📌 Bills

![Bills](screenshots/bills.png)

📌 Feedback

![Feedback](screenshots/feedback.png)

📌 Lost & Found

![LostFound](screenshots/lostfound.png)


## 🚀 Getting Started
Prerequisites

* [Python 3.10+](https://www.python.org/downloads/)
* [Git](https://git-scm.com/downloads/)

🔧 Installation (Django Backend)
1. Clone the Repository
    ○ git clone https://github.com/your-username/mess-management-system.git
      cd mess-management-system

2. Create & Activate Virtual Environment

For Windows

python -m venv venv
.\venv\Scripts\activate


For macOS/Linux

python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Apply Migrations
python manage.py makemigrations
python manage.py migrate

5. Create Admin User
python manage.py createsuperuser

6. Run Server
python manage.py runserver

Backend is now live at:
👉 http://127.0.0.1:8000/

👉 Admin Panel: http://127.0.0.1:8000/admin

🧑‍🏫 How to Use
1. Create an Account

Ask the admin to register a student account or use Django admin to create users.

2. Login to Student Dashboard

See:

Profile details

Today's menu

Bill summary

Leave status

3. Submit Leave Request

Fill the leave request form.
Admin approves or rejects from the backend.

4. Check Monthly Bills

Bills update with:

Leave deductions

Payment status

5. Give Feedback

Use the star-based rating system to submit mess feedback.

6. Lost & Found

Report missing items or browse admin-approved entries.

7. Admin Workflow

Visit: /admin
Manage:

Menu

Leaves

Bills

Notifications

Lost & Found

Users

📄 About

MessNet is designed to simplify hostel mess operations through automation, transparency, and a delightful user experience.
