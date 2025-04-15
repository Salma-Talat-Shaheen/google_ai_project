# Google AI Project
### **`Shelly Bot — Your Academic Companion`**

🔗 Live Demo:Visit Shelly Bot [here](https://ai.google.dev/competition/projects/shelly-bot)

[](https://github.com/Salma-Talat-Shaheen/google_ai_project/blob/main/shelly.jpg)
📚 What It Does
Shelly Bot is an interactive web page designed to be a friendly companion and electronic guide for high school graduates preparing for university life.

It helps students by:

Answering academic inquiries in a fun and engaging way

Clarifying the differences between majors, titles, and universities

Assisting students in shaping their academic path

When a student submits a question or expresses a concern, the Gemini API takes over. We've crafted a structured prompt that defines:

How the response should be formatted

What tone to use

What types of questions are acceptable

The responses from the API are tailored to be as helpful and relevant as possible.

🎥 Unique Response Format
Instead of showing replies in plain text, Shelly Bot delivers answers in video format, making the experience more dynamic and engaging.

💡 Extra Features
Shelly also suggests relevant resources based on the student's inquiry—such as:

Recommended courses

Scholarships

University programs

📨 Stay Updated
Students can also subscribe to our newsletter to receive the latest academic opportunities and updates directly.



***
### Setup 

#### Requirements:

- Python
- Pip

### Environment
- ```GEMINI_API_KEY```: The API key for Google Gemeni. Defaults to "".
- ```CONTENT_PATH```: The content directory key for storing output. Defaults to `.\tmp\output`

### To run locally


  
```
pip install -r requirements.txt
python app/main.py
```

### To run locally with docker

```
docker compose up --build
```
### To deploy to AWS

#### 1. Install AWS

#### 2. Set AWS profile
```

```
#### 2. Run serverless deploy
```
npm install
serverless deploy --stage dev
```
