# CODERECET

## Project Repository
*Commit and save your changes here*

### Team Name :Without Chaaya
### Team Members : Dhiya Theres Joshy , Fenza Maria , Aiiswarya S , Helina Alex
### Project Description
In a college ecosystem rich with talent but limited by financial resources, we identified the need for a collaborative, non-monetary skill exchange platform — and thus, SkillSwap was born. SkillSwap is a smart, gamified Skill Barter System designed specifically for college students to teach, learn, and grow by exchanging skills like design, coding, music, public speaking, and more.
Our idea evolved from the simple notion of peer learning into an engaging, student-centric platform powered by AI-based matchmaking, gamification, and skill-chain bartering, where students can participate in multi-way exchanges when direct matches aren’t available.
Built with a React Native front-end and a FLask+Firebase backend, SkillSwap includes features like smart scheduling, student leaderboards, review systems, skill portfolios, and real-time group learning circles — making it not only useful and necessary for campus communities but also a powerful tool for students to build portfolios, grow confidence, and form meaningful academic networks.
 In short, it's LinkedIn meets Duolingo, purpose-built for college life — all without the money barrier.
.
.

## Technical Details : Teckstack- Hosting/Testing - VS code , Thunder client , Postman
                                  Frontend- React
                                  Backend - Flask using python
                                  Database - Firebase
### Technologies/Components Used :  Python- For backend
                                    Postman- For testing API endpoints
                                    Thunderclient- For testing API endpoints
                                    Live server- Testing and hosting
## For Software:

[Languages used] : Javascript , Python , HTML, CSS
[Frameworks used] : React, Flask,Node.js
[Libraries used] : Firebase SDK, Axios, Tailwind CSS
[Tools used] : Visual Studio Code(code editor),  Firebase console(for database setup),Git and GitHub( version control) , Postman ( API testing), vite( react build tool)

## For Hardware:

[List main components]
[List specifications]
[List tools required]

## Implementation : User signup and Profiles- stored in Firebase Firestore
smart match making - Backend bult in Flask( Python)-Matching based on mutual interest
Swipe- Stored in Firestore, Matched when both swipe each other
Mutual Matches - To view all people you have matched with
Chatrooms - Real time social layer
Gamification - Future add on based on skill points , streaks and leaderboards


## For Software:

### Installation
BACKEND
# 1. Clone the backend repo (or navigate to it)
git clone https://github.com/<your-username>/skilllink-backend.git
cd skilllink-backend/backend
# 2. Create a virtual environment
python -m venv venv
# Activate the virtual environment:
# For Windows:
venv\Scripts\activate
# 3. Install dependencies
pip install -r requirements.txt
# 4. Place your Firebase Admin SDK JSON file in the backend directory
# 5. Run the Flask server
python app.py
FRONTEND
# 1. Clone the frontend repo (or navigate to it)
git clone https://github.com/<your-username>/skilllink-frontend.git
cd skilllink-frontend
# 2. Install dependencies
npm install

### Run
Frontend- npm run dev
Backend- python app.py

### Project Documentation
Absolutely! Below is a comprehensive, professional Project Documentation for your SkilLink – Skill Barter System, structured to include Overview, Problem Statement, Features, Tech Stack, Architecture, Setup Instructions, API Overview, and Future Scope.

SkilLink – Skill Barter System for College Students

Overview

SkilLink is a gamified, trust-based platform where college students teach and learn from each other by bartering skills — without using money.

Students can create skill profiles, find mutual matches, swipe on profiles like a social app, and chat with peers to coordinate skill exchanges. The system tracks matches, builds user credibility, and supports flexible multi-step learning loops.
Objectives
	•	Create a system where students can teach and learn.
	•	Replace money with value-for-value barter.
	•	Encourage community learning via matching, swiping, and skill circles.
	•	Build trust, portfolios, and recognition via ratings and testimonials.

Key Features:
Feature	Description
•Skill Profile	Users list what they can teach & want to learn
•Matchmaking Engine	Matches users based on mutual teaching/learning skills
•Swipe Interface	Tinder-like swiping to explore and show interest
•In-app Chatrooms	Start chatting after mutual interest is shown

•Safety Tools	Only matched users can chat, plus report/block feature
•Gamification	Leaderboards, skill points, skill CVs, and portfolio building
•Skill Circles	Group-based interest rooms (e.g., UI Designers United)

Folder Structure

SkilLink/
│
├── backend/
│   ├── app.py                  # Flask main app
│   ├── firebase-adminsdk.json # Firebase credentials
│   ├── firebase_config.py     # Firebase init
│   ├── requirements.txt       # Python dependencies
│
├── frontend/
│   ├── App.js                 # React Native entry point
│   ├── components/            # Swipe Cards, Chat, etc.
│   ├── screens/               # Signup, Match, Chat UI
│   └── package.json           # JS dependencies
Firebase Structure

Collections
	•	users – user profiles
	•	swipes – track who liked whom
	•	matches – optional match records
	•	chats/{chatroomId}/messages – subcollection for chat messages

Backend Setup (Flask + Firebase)

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install Python dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

Frontend Setup (React Native + Expo)

# Navigate to frontend
cd frontend

# Install dependencies
npm install
# Start the Expo dev server
npx expo start
API Overview
Endpoint	Method	Description
/api/signup	POST	Create new user
/api/users	GET	Fetch all users
/api/match/<user_id>	GET	Return mutual skill matches
/api/swipe	POST	Like/pass another user
/api/matches/<user_id>	GET	Get all mutual matches
/api/chat/start	POST	Create/start chatroom
/api/chat/send	POST	Send a message
/api/chat/<chatroom_id>	GET	Fetch messages in a chatroom
Sample Use Case
	1.	Aisha teaches Resume Writing to Rahul
	2.	Rahul teaches HTML to Meera
	3.	Meera designs a poster for Aisha’s club
Everyone earns points, testimonials, and grows their skill portfolio.
Testing Suggestions
	•	Use Thunder Client or Postman to test APIs.
	•	Use Expo Go app to test frontend by scanning QR code.
Future Scope
	•	AI-based skill matching suggestions
	•	Calendar sync & reminder integration
	•	Streaks, XP badges, and rewards shop
	•	Alumni mentor pairing system
	•	University-level leaderboard competitions

### Screenshots (Add at least 3)

### Diagrams
Workflow(Add your workflow/architecture diagram here) Add caption explaining your workflow

## For Hardware:

### Schematic & Circuit
Circuit(Add your circuit diagram here) Add caption explaining connections
Schematic(Add your schematic diagram here) Add caption explaining the schematic

### Build Photos
Components(Add photo of your components here) List out all components shown
Build(Add photos of build process here) Explain the build steps
Final(Add photo of final product here) Explain the final build

### Project Demo

### Video
[Add your demo video link here] Explain what the video demonstrates

## Additional Demos
[Add any extra demo materials/links]

## Team Contributions
Dhiya There Joshy: Frontend stack, UI/UX
Fenza Maria K A: Backend stack
Aiswarya S: Database management
Helina Alex : Hosting and Testing backend stack
