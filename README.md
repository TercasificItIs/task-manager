# task-manager

A simple Task Manager web app built with Python and Streamlit, supporting full CRUD (Create, Read, Update, Delete) functionality.

## Features

- **Add tasks** — enter a title and click "Add Task" or press "ENTER"
- <img width="941" height="748" alt="image" src="https://github.com/user-attachments/assets/112dd634-6625-490e-8ee7-9853476ea3a6" />


- **Mark complete** — click ✅ to toggle a task as done (shows as strikethrough)
- <img width="973" height="112" alt="image" src="https://github.com/user-attachments/assets/0807fa6e-fe46-4918-b841-d94475e3f464" />



- **Delete tasks** — click 🗑️ to remove a task
- Tasks are saved locally to a JSON file, so they persist between runs

## Tech Stack

- Python
- [Streamlit](https://streamlit.io/) for the web UI

## Installation & Usage

1. Clone or download this repository.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the app:
   ```
   streamlit run app.py
   ```
4. It will open automatically in your browser at `http://localhost:8501`.
