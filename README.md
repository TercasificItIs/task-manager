# task-manager

A simple Task Manager web app built with Python and Streamlit, supporting full CRUD (Create, Read, Update, Delete) functionality.
<img width="900" height="864" alt="image" src="https://github.com/user-attachments/assets/e3118876-75d7-4a46-b3cf-6fdd0d3ba41d" />

## Features

- **Add tasks** — enter a title and click "Add Task" or press "ENTER"
  <img width="941" height="748" alt="image" src="https://github.com/user-attachments/assets/112dd634-6625-490e-8ee7-9853476ea3a6" />

- **Mark complete** — click ✅ to toggle a task as done (shows as strikethrough)
  <img width="881" height="146" alt="image" src="https://github.com/user-attachments/assets/98cc8732-6c7c-48d2-8d63-47a2912d5f7b" />

- **Delete tasks** — click 🗑️ to remove a task
  <img width="866" height="149" alt="image" src="https://github.com/user-attachments/assets/104a5de4-404f-485f-8c97-7f663eb75f25" />

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
