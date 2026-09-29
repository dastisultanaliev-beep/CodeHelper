🤓 CodeHelper — Programmer Assistant

CodeHelper is a simple desktop application built with Python that provides quick access to useful programming resources.

The application uses CustomTkinter for its graphical interface, opens useful websites in the browser, and stores launch statistics using SQLite.

✨ Features

🤖 Quick access to ChatGPT

🎥 Quick access to YouTube

🧑‍💻 Quick access to Python Documentation

📊 Tracks how many times each resource has been launched

💾 Stores statistics in an SQLite database

🌙 Dark theme

🖥️ Simple and user-friendly graphical interface

🛠️ Technologies

Python 3

CustomTkinter — GUI framework

SQLite3 — database

Webbrowser — opens websites in the default browser

📁 Project Structure
CodeHelper/
│
├── main.py
├── pc_helper.db
└── README.md


pc_helper.db is created automatically when the application is launched for the first time.

🚀 Installation
1. Clone the repository
git clone https://github.com/USERNAME/CodeHelper.git
cd CodeHelper

2. Install dependencies

Install CustomTkinter:

pip install customtkinter

3. Run the application
python main.py


After running the program, the application window will open.

📊 How Statistics Work

When the application starts, it creates an SQLite database:

pc_helper.db


The database contains an apps table with the following fields:

Field	Description
id	Unique identifier
name	Application/resource name
launches	Number of launches

Every time the user clicks one of the buttons, the launch counter for that resource increases by 1.

For example:

Launch Statistics

ChatGpt: 5
Youtube: 3
Python Docs: 7

🌐 Available Resources

The current version provides quick access to:

ChatGPT

YouTube

Python Documentation

🎯 Project Purpose

This project was created for learning and practicing:

Python programming

GUI application development

Functions and event handling

SQLite databases

Button events

Opening web pages with Python

Storing and displaying statistics

🔮 Future Improvements

Possible improvements for future versions:

🔍 Search for resources

➕ Add custom websites

🗑️ Remove resources

📈 Add statistics charts

⚙️ Add application settings


🔗 Save custom links

⌨️ Add keyboard shortcuts

🎨 Add theme selection

📅 Track daily and monthly statistics

👨‍💻 Author

Your Name

This project was created with Python for educational purposes.

⭐ If you find this project useful, consider giving it a star!
