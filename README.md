# CyberQuest
An educational game designed to teach my students the fundamentals of Computer Science.
Built using Python and Flask.

## 💡 Features

- 🧠 Multiple-choice quizzes covering core CS topics
- 📊 Score tracking and session management
- 🎨 HTML/CSS interface using Flask templating
- 💾 SQLite database to manage question scenarios

## 🛠️ Tech Stack

- Python
- Flask
- SQLite
- HTML/CSS
- Flask-Session

## 🎯 Purpose

CyberQuest was created as part of my role as a teaching assistant to introduce younger students to computing concepts in a fun, accessible way. It has been used in classroom sessions to teach logic, algorithms, and problem-solving.

## 🚀 How to Run

## Running CyberQuest Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PriyaBargota/CyberQuest.git
   cd CyberQuest
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install required packages:**
   ```bash
   pip install flask flask-session cs50 pytz requests
   ```

4. **Set the Flask app environment variable:**
   ```bash
   export FLASK_APP=app.py
   ```

5. **Run the app:**
   ```bash
   python -m flask run
   ```

6. **Open your browser and go to:**  
   [http://127.0.0.1:5000](http://127.0.0.1:5000)
