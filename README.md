# MindTrail – Learning Tracker
(((( YET TO BE DEPLOYED ))))

MindTrail is a personal project I built to help track study goals and learning habits over time. It's a full-stack web app made using **Django (backend)** and **React.js (frontend)**, and was inspired by the need to stay more consistent with my daily learning .

I wanted to create something simple yet useful — a space where you can log what you study, set weekly targets, and get visual feedback on your progress.

---------------------------------------------------------------------------------------------------------------------------------------------

## Features

- Set learning goals for different subjects
- Log study sessions with notes and time spent
- View charts of your weekly progress
- Secure login system using JWT
- Simple, clean interface built with React and CSS

---------------------------------------------------------------------------------------------------------------------------------------------

## Tech Stack

- **Frontend:** React.js, CSS, Chart.js
- **Backend:** Django REST Framework
- **Auth:** JWT-based token authentication
- **Database:** SQLite (for now)

---------------------------------------------------------------------------------------------------------------------------------------------

## How This Is Structured

```
MindTrail/
├── backend.zip   ← Django backend code
├── frontend.zip  ← React frontend code
└── README.md     ← This file
```

You can unzip both parts and run them separately on your local machine.

---------------------------------------------------------------------------------------------------------------------------------------------

## How to Run It

### Backend:
```bash
unzip backend.zip
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
----------------------------------------------
### Frontend:
```bash
unzip frontend.zip
cd frontend
npm install
npm start
```

Just make sure the frontend is calling the correct backend API URL (e.g. `http://localhost:8000`).

---------------------------------------------------------------------------------------------------------------------------------------------

## Why I Haven’t Deployed It Yet

Right now, the project isn’t live because I’m still finalizing a few parts and want to improve the design and features before deploying. The backend and frontend work perfectly on localhost, and I’ve included all instructions for anyone who wants to try it out locally.

Once everything is polished, I’ll deploy it using platforms like Render and Vercel.


*********** if you have any ideas on improving the project or adding a new feature to it or a feedback 

--------> https://github.com/dhruv11bhandari 

*****************************************************************



