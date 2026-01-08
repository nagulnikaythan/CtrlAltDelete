🎓 EduBridge – AI-Powered School Management System

EduBridge is a Flask-based School Management System enhanced with an AI Voice Assistant  for teachers and students.  
It enables secure student–teacher interaction, marks management, doubt resolution, and AI-assisted queries using real backend data.

---

 🚀 Features

👨‍🎓 Student
- Secure login & signup
- Class & section based identity
- View marks (subject + exam wise)
- Doubt Desk – chat with teachers
- AI Assistant (text & voice)
- Profile management (email protected from editing)

👩‍🏫 Teacher
- Department-based access
- Class & section filtered student list
- Enter & update marks (no duplicate exams)
- Respond to student doubts
- Voice AI Assistant to query:
  - Student details
  - Marks & averages
  - Backend data (CSV + binary files)

🧠 AI & Voice Assistant

- Uses OpenAI GPT models
- Speech-to-Text via browser
- Text-to-Speech responses
- Automatically fetches data from:
  - `users.dat`
  - `marks.csv`
- Falls back to AI only when predefined commands don’t match

🔑 OpenAI API Key Setup (IMPORTANT)

EduBridge **does NOT ship with an API key** for security reasons.

### ✅ Steps to configure OpenAI API

1. Create an OpenAI account  
   👉 https://platform.openai.com/signup

2. Generate an API key  
   👉 https://platform.openai.com/account/api-keys

3. Open the file YOURAPI.txt: 
Paste only the API inside the file and save it

4. Paste **ONLY your API key** inside the file:


RUNNING INSTRUCTIONS 
🛠 Installation & Run Instructions

1 Install Dependencies
Run the following command in your terminal or PowerShell:

pip install flask 
pip install openai

2 Run the server
Start the EduBridge Flask application:

python app.py

3 Open in browser
After the server starts, open the following URL in your browser:

http://127.0.0.1:8000

