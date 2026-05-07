# 📝 Flask Note-Taking App

A simple, lightweight note-taking application built with Python and Flask. This project demonstrates a full-stack implementation using SQLite for database management and a clean CSS-based UI.

## ✨ Features
- **Create Notes**: Quickly add new notes with a title and content.
- **View Notes**: A responsive grid layout to view all saved notes.
- **Edit Notes**: Update existing notes easily.
- **Delete Notes**: Remove unwanted notes with a confirmation prompt.
- **Persistent Storage**: Uses SQLite to keep your notes safe.

## 🛠️ Tech Stack
- **Backend**: [Flask](https://flask.palletsprojects.com/) (Python)
- **Database**: SQLite
- **Frontend**: HTML5, CSS3, Jinja2 Templates

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/winos1045-wq/flask-notes-app.git
   cd flask-notes-app
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

4. **Access the app**:
   Open your browser and go to `http://localhost:3000`

## 📁 Project Structure
- `app.py`: The core application logic and routes.
- `requirements.txt`: List of Python dependencies.
- `static/css/style.css`: Styling for the application.
- `templates/`: HTML templates for the UI.
- `database.db`: The SQLite database file (automatically created).

## 📜 License
This project is open source and available under the [MIT License](LICENSE).
