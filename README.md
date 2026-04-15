# AIML Adventure Hub

AIML Adventure Hub is a smart and interactive learning platform designed to help students understand Artificial Intelligence and Machine Learning in a fun, practical, and collaborative way. Instead of only reading theory, users can learn through modules, quizzes, code practice, games, simulations, and classroom participation.

The platform is built to make AIML easier for beginners while still being useful for intermediate and advanced learners.

---

## Project Idea

The main goal of this project is to create a modern learning environment where users can:

- Learn AI/ML concepts in a structured way
- Practice with coding examples
- Test knowledge using quizzes
- Understand concepts through mini-games
- Explore real-world AIML simulations
- Track performance and achievements
- Ask questions inside the platform
- Create or join classrooms for collaborative learning

This makes the project more than just a learning website. It becomes an engaging AI/ML learning ecosystem.

---

## Main Features

### User Authentication
The platform supports user account creation and login functionality. Users can sign up, log in, and continue their progress. Their activity, module completion, quiz attempts, and scores are connected to their learning dashboard.

### Structured Learning Modules
Learning content is divided into levels such as Beginner, Intermediate, and Advanced. Each module contains:
- Short explanations
- Topic summaries
- Examples
- Compact visual aids
- Easy navigation through the learning path

This helps users understand difficult AI/ML concepts step by step.

### Interactive Coding Playground
The platform includes a code playground where learners can work with AIML-related snippets. It supports Python-focused learning and also includes JavaScript examples. Users can:
- Edit starter code
- Run snippets
- View guided feedback
- Practice logic related to AI/ML concepts

### Quiz and Assessment System
After learning, users can test their understanding through quizzes. The quiz system includes:
- Multiple-choice questions
- Conceptual coding-style questions
- Instant results
- Feedback after submission
- Progress reflected in the dashboard

### Mini-Games for Learning
To make learning more engaging, the project includes concept-based mini-games such as:
- Decision Split Sprint
- Classification Sorter
- Neural Network Tuner

These games are designed to teach important ML concepts interactively rather than only through text.

### Real-World AIML Simulations
The project also includes small practical simulations such as:
- Spam Detection Studio
- Image Classification Demo

These sections show how AI/ML is applied in real-world problems and help connect theory with actual use cases.

### Dashboard and Gamification
Every user gets a personal dashboard showing:
- Points
- Level
- Module progress
- Quiz performance
- Game performance
- Activity history
- Streaks
- Badges
- Leaderboard ranking

This adds motivation and makes the learning process more engaging.

### Ask Questions Feature
Users can ask questions directly inside the platform. The system stores questions and provides tutor-style responses, making the app feel more interactive and supportive for learners.

### Classroom Creation and Joining
The platform also supports collaborative learning through classrooms. Users can:
- Create classrooms
- Get classroom codes
- Join classrooms using a code
- See classroom members
- Learn together in a more organized way

This feature makes the project useful for team learning and hackathon/demo environments.

---

## Technology Used

### Frontend
- HTML
- CSS
- JavaScript
- Font Awesome

### Backend
- Node.js
- Express.js
- body-parser
- cors

### Data Storage
- JSON files used as a lightweight local database

---

## Folder Structure

```bash
vibethon/
│
├── backend/
│   ├── data/
│   │   ├── users.json
│   │   ├── courses.json
│   │   ├── quizzes.json
│   │   ├── games.json
│   │   ├── simulations.json
│   │   ├── classrooms.json
│   │   └── questions.json
│   ├── server.js
│   ├── package.json
│   └── API_DOCS.js
│
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── js/
│   │       ├── main.js
│   │       ├── games.js
│   │       ├── quiz.js
│   │       └── fun-learning.js
│   └── index.html
│
└── README.md
