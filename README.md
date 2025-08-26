📌 Overview

TalentScout is an AI-powered interactive hiring assistant designed to streamline the candidate screening process for recruitment agencies. Built using Python, Gradio, and NLP techniques, this chatbot engages candidates, collects key details, validates inputs, and evaluates their technical skills using semantic similarity scoring.

✨ Features

✔ Interactive Candidate Experience – Friendly chat-based interface
✔ Input Validation – Checks for proper name, email, and contact number format
✔ Dynamic Skill Questions – Tailored for Python or Java roles with optional library-specific queries
✔ AI-Powered Scoring – Uses Sentence Transformers for semantic similarity, scores on 0–10 scale
✔ Final Evaluation Summary – Provides total score and feedback for recruiters
✔ Custom UI – Includes a cat-with-glasses image above the chat

🛠 Technology Stack

Language: Python

Frontend: Gradio

NLP Model: Sentence Transformers
 (for semantic similarity)

Deployment: Google Colab / Local Python

🚀 How It Works

Start Chat – User enters details (name, email, phone, skill preference).

Validation – Ensures correct input format (re-asks if incorrect).

Skill Questions – Based on selected skill (Python / Java) with an optional follow-up on libraries.

Answer Evaluation – Uses AI to compare responses against expected keywords and score 0–10.

Final Summary – Displays total score and short feedback for recruiters.

📷 UI Preview

(Add your screenshot here)
Example:


⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/TalentScout.git
cd TalentScout


Install dependencies:

pip install gradio sentence-transformers


Run the chatbot:

python app.py


Or open in Google Colab for quick testing.

📊 Scoring System

Each question is evaluated using semantic similarity

Score scaled from 0 to 10

Empty or irrelevant answers get 0

Higher similarity = higher score

🔮 Future Enhancements

✅ Add multiple skill categories (Data Science, Web Development, etc.)

✅ Integrate resume upload & parsing

✅ Export candidate evaluation as PDF/CSV

✅ Deploy as a web app using Hugging Face Spaces or Streamlit


Feel free to fork this repo and submit PRs for improvements!

Do you want me to:
✅ Include a sample screenshot section with placeholder image,
✅ Add badges like “Made with Python” and “Open Source”,
✅ Provide an example conversation in the README?

Or should I keep it clean and simple for now?
