# Missing Persons Portal

A sophisticated Django-based web application designed to help find missing persons using AI-powered facial recognition and sentiment analysis.

## 🌟 Key Features

### 👤 User Portal
- **Case Registration**: Easily register a missing person case with photos and descriptions.
- **My Profile**: Manage user details and view submitted cases.
- **Case Status**: Real-time tracking of investigation progress.
- **Feedback System**: Users can provide feedback, which is analyzed for sentiment to improve services.

### 👮 Admin & Police Portal
- **Dashboard**: Overview of active cases, found persons, and statistics.
- **Manage Cases**: Add, edit, and update statuses of missing person reports.
- **AI Face Matching**: Automatically find matches for missing persons using advanced facial recognition algorithms.
- **Case Analysis**: Visualize case trends through dynamic graphs.
- **Sentiment Analysis**: View sentiment trends from user feedback to assess public response.

## 🛠️ Technical Stack

- **Backend**: Django (Python)
- **Database**: SQLite (default), supports MySQL.
- **AI/ML**:
  - `OpenCV` & `Pillow` for image processing.
  - `DeepFace` & `TensorFlow` for facial recognition.
  - `NLTK` & `TextBlob` for sentiment analysis.
- **Frontend**: HTML5, CSS3, JavaScript (Responsive Design).
- **Other**: `requests`, `numpy`.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- pip

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd missing_persons
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On Linux/macOS:
   source venv/bin/activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Run the Server**:
   ```bash
   python manage.py runserver
   ```
   Visit `http://127.0.0.1:8000/` in your browser.

## 📁 Project Structure

- `mainapp/`: Handles core website pages (Home, About, Contact).
- `userapp/`: Manages user authentication, registration, and case management.
- `adminapp/`: Contains police dashboard, case matching logic, and analysis tools.
- `assets/`: Static files (CSS, JS, Images) and templates.
- `media/`: Storage for uploaded person photographs.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
