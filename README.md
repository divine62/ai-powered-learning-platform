# AI-Powered Learning Platform 🎓🤖

An intelligent web-based learning system that enhances education through personalized recommendations, AI-generated notes, and interactive tutoring.

---

## 📌 Overview

The **AI-Powered Learning Platform** is a full-stack web application designed to improve the learning experience using Machine Learning (ML) and Natural Language Processing (NLP).

The system curates YouTube educational videos, generates summarized notes from video transcripts, recommends personalized learning resources, and provides an AI chatbot tutor for interactive doubt-solving.

This project demonstrates full-stack development, AI integration, and scalable system design.

---

## 🎯 Objectives

- Curate educational YouTube videos using rating-based filtering and ML personalization.
- Convert video transcripts into AI-generated summarized notes.
- Recommend personalized notes and quizzes using TF-IDF ranking.
- Provide an NLP-powered chatbot for student queries.
- Build a scalable, modular web application using modern technologies.

---

## 🏗️ System Architecture

The platform consists of five major components:

1. **Frontend Layer** – React.js + Tailwind CSS
2. **Authentication Layer** – Firebase Authentication
3. **Backend API Layer** – Flask (Python)
4. **Machine Learning Engine** – TF-IDF (Scikit-learn)
5. **NLP Engine** – Hugging Face Transformers (BART, DistilGPT2)

```
AI-Powered-Learning-Platform/
│
├── frontend/              # React application
│
├── backend/
│   ├── routes/            # API endpoints
│   ├── services/          # Business logic
│   ├── models/            # MongoDB models
│   ├── ml/                # ML components
│   └── utils/             # Helper functions
│
├── docs/                  # Architecture & API documentation
├── requirements.txt
└── dockerfile
```

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- Tailwind CSS
- Firebase Authentication
- React YouTube

### 🔹 Backend
- Flask (Python)
- MongoDB (PyMongo)

### 🔹 Machine Learning
- Scikit-learn (TF-IDF Vectorization)
- Recommendation Ranking System

### 🔹 NLP
- Hugging Face Transformers (BART for summarization)
- DistilGPT2 (Chatbot)
- NLTK

### 🔹 External APIs
- YouTube Data API v3
- youtube-transcript-api

### 🔹 Deployment
- Docker
- Heroku / AWS

---

## 🚀 Key Features

### 👤 1. User Authentication
- Firebase email/password authentication
- Secure user profile storage
- Learning history tracking

---

### 🎥 2. Smart Video Recommendations
- Fetches videos using YouTube API
- Ranks videos using:
  - Likes
  - Views
  - TF-IDF similarity to user interest
- Personalized recommendation engine

---

### 📝 3. AI-Generated Notes
- Extracts YouTube transcripts
- Summarizes using BART model
- Generates downloadable PDF notes

---

### 🤖 4. AI Chatbot Tutor
- Answers conceptual queries
- Suggests relevant videos
- Assists with learning topics

---

### 🧠 5. Dynamic Quiz System
- Topic-based quizzes
- Stored in MongoDB
- Personalized suggestions

---

## 📊 Machine Learning Approach

The recommendation engine uses:

- TF-IDF vectorization of:
  - Video titles
  - Descriptions
  - User learning history
- Cosine similarity scoring
- Cold-start handling using trending videos

This ensures content personalization even for new users.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/divine62/AI-Powered-Learning-Platform.git
cd AI-Powered-Learning-Platform
```

---

### 2️⃣ Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Run Flask:

```bash
flask run
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file in backend:

```
MONGO_URI=
YOUTUBE_API_KEY=
FIREBASE_CONFIG=
HUGGINGFACE_TOKEN=
```

⚠️ Never commit secret keys to GitHub.

---

## 🧪 Testing

- Backend APIs tested via Postman
- Firebase Auth tested using Firebase Emulator
- Unit testing planned for ML components

---

## 📈 Future Improvements

- Mobile App Integration
- Advanced Collaborative Filtering
- Real-time recommendation updates
- User analytics dashboard
- Multi-language support

---

## 👩‍💻 Contributors

- Divya Upadhyay  
- Ebnee Shaid  
- Kirpal Singh  

Under the guidance of  
Assistant Professor (CSE Department)

---

## 🎓 Academic Relevance

This project demonstrates:

- Full-stack web development
- REST API design
- Machine Learning integration
- Natural Language Processing
- Cloud deployment
- Scalable system architecture

---

## 📄 License

This project is developed for academic and educational purposes.

---

