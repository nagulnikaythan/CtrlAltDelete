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

**NOTE : PLEASE FOLLOW THE INSTRUCTIONS GIVEN BELOW AND IGNORE THE README FILE ATTACHED IN THE ZIP FILE **
How to run
clone the github repository into your local directory
Ensure Docker Desktop is installed and running on your machine get the Dockerfile and a docker-compose.yml file from the gdrive link and save it to the local directory.
open terminal in the directory and run command :

```
docker-compose build
```

To launch the system run the command:

```
docker-compose up
```


Once the terminal shows * Serving Flask app 'app', the system is live.
open you web browser(Edge) and go to: http://127.0.0.1:8000



