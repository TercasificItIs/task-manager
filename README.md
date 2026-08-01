# task-manager

A simple Task Manager web app built with Python and Streamlit, supporting full CRUD (Create, Read, Update, Delete) functionality.

<img width="914" height="761" alt="image" src="https://github.com/user-attachments/assets/0a1f3873-7e66-4aa1-9156-a5ee6f2accf9" />

## Features

- **Add tasks** — enter a title and click "Add Task" or press "ENTER"
- **Mark complete** — click ✅ to toggle a task as done (shows as strikethrough)
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
