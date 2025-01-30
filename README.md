# Daily-Reminder-System

# Description

The Daily Reminder System is a simple GUI-based application that allows users to schedule daily reminders. Users can add tasks with a specific time, view scheduled reminders, and receive notifications when the task time arrives. The system is built using Python, Tkinter for GUI, and MySQL for data storage.

# Features

Add reminders with a task name and time.
View all scheduled reminders.
Automated notification when it's time for a task.
Background thread continuously checks for upcoming reminders.
Data stored in MySQL database.

# Requirements

Python 3.x
Tkinter (Included with Python)
pymysql (for MySQL connectivity)
MySQL Server

# Installation

__Clone the repository:__
git clone https://github.com/your-repo/daily-reminder.git
cd daily-reminder

 __Install dependencies:__
pip install pymysql

__Set up the MySQL database:__
Create a database named reminders_db.
Ensure your MySQL credentials are correctly set in the script.

# _Run the application:_
python daily_reminder.py

# _Usage_
Enter a task name and a reminder time in HH:MM format.
Click Add Reminder to save it.
The system will alert you when it's time for the task.

# _License_
This project is open-source and available under the MIT License.
