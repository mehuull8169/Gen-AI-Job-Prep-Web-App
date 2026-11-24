Gen-AI Job Prep Web App
A full-stack web application that helps users prepare for job interviews with AI-generated questions, practice sessions, and feedback.
Features
AI-powered mock interview practice
Dynamic interview question generation
Feedback and evaluation
User registration and login
Interview reports
Tech Stack
Frontend: React.js, Vite, SCSS
Backend: Node.js, Express.js
AI: Generative AI API integration
Database: Add the database actually configured in this project
Getting Started
1. Clone the repository
```bash
git clone https://github.com/mehuull8169/Gen-AI-Job-Prep-Web-App.git
cd Gen-AI-Job-Prep-Web-App
```
2. Install and run the backend
```bash
cd Backend
npm install
```
Create a `.env` file using the variable names required by the backend configuration. Do not commit API keys or other secrets.
Run the backend using the start script defined in `Backend/package.json` (for example, `npm run dev` if that script exists).
3. Install and run the frontend
Open another terminal:
```bash
cd Frontend
npm install
npm run dev
```
Open the local URL printed by Vite in your terminal.
Project Structure
```text
Gen-AI-Job-Prep-Web-App/
├── Backend/
├── Frontend/
└── README.md
```
Notes
Add screenshots or a demo link here when available.
Document the exact environment variable names in a safe `.env.example` file.
Update the database entry above to match the database used by the project.
Author
Mehul Jain
