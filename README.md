📝 To-Do List Application
📌 Project Overview

The To-Do List Application is a web-based project that helps users manage their daily tasks efficiently. Users can add, update, and delete tasks, making it easier to organize and track their work.

This project is built using Python, Flask, SQLite, HTML, and CSS.

🚀 Features
Add new tasks
Update/Edit existing tasks
Delete tasks
View all tasks
Simple and user-friendly interface
🛠️ Technologies Used
Python
Flask (Web Framework)
SQLite Database
HTML5
CSS3
📂 Project Structure
TODO/
│
├── app.py                # Main Flask application
├── db_setup.py           # Database setup script
├── todo.db               # SQLite database
│
├── static/
│   └── style.css         # Styling for the application
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add_task.html
│   ├── update_task.html
│   └── navbar.html
│
└── venv/                 # Virtual environment (not required to upload)
⚙️ Installation and Setup
1. Clone the repository
git clone https://github.com/your-username/todo-app.git
2. Navigate to the project directory
cd todo-app
3. Create a virtual environment
python -m venv venv
4. Activate the virtual environment

Windows

venv\Scripts\activate
5. Install required dependencies
pip install flask
6. Setup the database
python db_setup.py
7. Run the application
python app.py
8. Open in browser
http://127.0.0.1:5000
📊 Functional Modules
Task Management
Add new tasks
Edit/update tasks
Delete tasks
Data Handling

Stores and retrieves task data using SQLite database.

User Interface

Provides a simple and clean interface for managing tasks efficiently.

🔒 Future Improvements
Add user authentication (login/signup)
Add task deadlines and reminders
Mark tasks as completed
Improve UI with Bootstrap or React
Add search and filter functionality
👩‍💻 Author

Akhila Mulukutla

📜 License

This project is for educational purposes.
