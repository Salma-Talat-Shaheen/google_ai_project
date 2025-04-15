# Google AI Project  
### **Shelly Bot  — Your Academic Companion**

**🔗Live Demo:** [Click here to visit Shelly Bot](https://ai.google.dev/competition/projects/shelly-bot)

<p align="center">
  <img src="https://github.com/Salma-Talat-Shaheen/google_ai_project/blob/main/shelly.jpg" alt="Shelly Bot Preview" width="600"/>
</p>

---

### ✦ What It Does

**Shelly Bot** is an AI-powered web assistant designed to support high school graduates in their transition to university. It offers academic guidance through a friendly and interactive experience.

---

### ✦ Key Functions

- Provides answers to academic questions in an engaging format  
- Explains the differences between majors, degrees, and universities  
- Helps students explore and shape their academic path  

---

### ✦ How It Works

When a student submits a question or expresses a concern, the **Gemini API** is triggered using a structured prompt that defines:
- Response formatting  
- Tone and clarity  
- Allowed scope of topics  

This approach ensures responses are clear, appropriate, and helpful.

---

### ✦ Response Format

Unlike traditional bots, Shelly Bot returns answers in **video format**, making the interaction more immersive and enjoyable.

---

### ✦ Additional Features

- Personalized suggestions for courses, scholarships, and university programs  
- A newsletter subscription option for ongoing academic updates and opportunities  

---

## ✦ Setup

### Requirements
- Python  
- Pip  

### Environment Variables
- `GEMINI_API_KEY`: Your Google Gemini API key (default: `""`)  
- `CONTENT_PATH`: Directory to store generated content (default: `./tmp/output`)  

---

## ✦ Run the App

### Locally
```bash
pip install -r requirements.txt
python app/main.py
```

### With Docker
```bash
docker compose up --build
```

### Deploy to AWS

1. Install AWS CLI  
2. Set AWS credentials:
```bash
aws configure
```
3. Deploy with Serverless:
```bash
npm install
serverless deploy --stage dev
```

---
