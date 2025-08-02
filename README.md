📚 **StudyMate — Your AI Study Companion **
StudyMate is a multi-functional Streamlit app that helps students and job seekers with: 
🧠 PDF Q&A – Ask questions directly from your study notes or textbooks. 
🧭 Career Roadmap Generator – Get a personalized learning plan to reach your dream job.
🤖 ATS Resume Checker – Improve your resume with AI-powered analysis. 
Built using Streamlit, Hugging Face Transformers, and custom prompts to integrate powerful language models.


📂 **File Structure** 
StudyMate/ 
├── app.py            # Main Streamlit application \n
├── ats.py            # Resume analysis with Hugging Face API \n
├── qna.py            # Question answering with BERT model \n
├── roadmap.py        # Roadmap generation using Mistral-7B model \n
├── requirements.txt  # Python dependencies \n
└── README.md         # This file


⚙️ **Installation**
1. Clone the repository
git clone https://github.com/your-username/studymate.git
cd studymate

2. Install dependencies
Create a virtual environment (optional):
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Then install the required packages:
pip install -r requirements.txt

3. Set your Hugging Face API token
Create a .env file (or export as an environment variable):
HF_TOKEN=your_huggingface_api_token
               Or 
export HF_TOKEN=your_huggingface_api_token


🔧**Features**
📄 PDF Q&A Upload any textbook or notes in PDF format Ask questions based on the document Powered by deepset/bert-large-uncased-whole-word-masking-squad2
🧭 Career Roadmap Generator Input your name, skills, and goal Receive a detailed multi-phase learning roadmap Includes suggested courses, tools, timelines, and projects Uses Hugging Face’s mistralai/Mistral-7B-Instruct-v0.1
📝 ATS Resume Checker Upload your resume in PDF format Optionally paste a job description Receive feedback on resume strengths, weaknesses, and suggestions Based on HuggingFaceH4/zephyr-7b-beta
