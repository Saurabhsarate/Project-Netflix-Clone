# Netflix Clone

A fully responsive Netflix-style streaming web app built with modern web technologies.  
This project replicates the core UI/UX and functionality of Netflix, including browsing movies/TV shows, watching trailers, and user authentication.

---

## 🚀 Live Demo

🔗 [View it live on Netlify](https://your-netlify-app-url.netlify.app)  
*(Replace with your actual deployment URL)*

---

## 🖥️ Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Screenshots](#screenshots)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Running Locally](#running-locally)  
- [Project Structure](#project-structure)  
- [Available Scripts](#available-scripts)  
- [Environment Variables](#environment-variables)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## ✨ Features

- 🔎 Browse movies and TV shows by genre  
- 🎥 View trailers in a modal overlay  
- 🔑 User authentication with Firebase Auth (Email/Password & Google)  
- 📑 “My List” – save your favorites  
- 🌙 Dark & Light mode toggle  
- 📱 Fully responsive across desktop, tablet & mobile  

---

## 🛠️ Tech Stack

- **Frontend:** React, Redux Toolkit, Tailwind CSS  
- **Backend:** Firebase (Authentication, Firestore)  
- **API:** [The Movie Database (TMDB) API](https://www.themoviedb.org/)  
- **Deployment:** Netlify / Vercel  

---

## 📸 Screenshots

| Home Page                     | Movie Detail Modal            |
|-------------------------------|-------------------------------|
| ![Home](screenshots/home.png) | ![Modal](screenshots/modal.png) |

---

## 🏁 Getting Started

### Prerequisites

- Node.js (v14+) & npm  
- A TMDB API Key (sign up at https://www.themoviedb.org/)  
- Firebase project (for Auth & Firestore)

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/abhipraydhoble/Project-Netflix-Clone.git
   cd Project-Netflix-Clone
   
## Install dependencies
'''bash
npm install


## Running Locally
## 1. Create a .env.local file in the project root, then add:


REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id

## 2.Start the dev server


npm start
Open http://localhost:3000 in your browser.

### 🗂️ Project Structure

Project-Netflix-Clone/
├── public/                 # Static assets & HTML
├── src/
│   ├── api/                # TMDB API calls
│   ├── assets/             # Images, icons, etc.
│   ├── components/         # Reusable React components
│   ├── features/           # Redux slices
│   ├── hooks/              # Custom React hooks
│   ├── pages/              # Route-based components
│   ├── styles/             # Tailwind overrides & globals
│   ├── App.js              # App entry & routing
│   └── index.js            # React DOM render
├── .env.local              # Environment variables (gitignored)
├── package.json            # NPM dependencies & scripts
└── tailwind.config.js      # Tailwind CSS config

### 📋 Available Scripts
In the project directory, you can run:

Command	                  Description
npm start	                 Runs the app in development mode
npm run                    build	Builds the app for production
npm test	                 Launches the test runner (Jest)
npm run                    lint	Lints code with ESLint

### 🌐 Environment Variables
Variable	                                  Purpose
REACT_APP_TMDB_API_KEY	                 TMDB REST API key
REACT_APP_FIREBASE_API_KEY	             Firebase project API key
REACT_APP_FIREBASE_AUTH_DOMAIN	         Firebase Auth domain
REACT_APP_FIREBASE_PROJECT_ID	           Firebase project identifier
REACT_APP_FIREBASE_STORAGE_BUCKET	       Firebase Storage bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID	 Firebase messaging sender ID
REACT_APP_FIREBASE_APP_ID	               Firebase app ID

### 🤝 Contributing
1.Fork the repo

2.Create your feature branch (git checkout -b feature/AwesomeFeature)

3.Commit your changes (git commit -m 'Add some feature')

4.Push to the branch (git push origin feature/AwesomeFeature)

5. Open a Pull Request

Please adhere to the Contributor Covenant code of conduct.

### 📄 License
Distributed under the MIT License. See LICENSE for more information.

### 📬 Contact
Saurabh Sarate -saurabhsarate257@gmail.com
Project Link: (https://github.com/Saurabhsarate/Project-Netflix-Clone)
