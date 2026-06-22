Here’s a sample **README** file for your project:

---

# EduAssist - AI-Powered Educational Platform

**EduAssist** is an innovative, AI-powered educational platform that provides a set of powerful tools designed to enhance the learning experience. Whether you're preparing for a coding interview or just looking to optimize your resume for job applications, **EduAssist** has got you covered with real-time MCQ generation, PDF querying contest tracking, and ATS resume optimization. Powered by advanced AI models like Google Gemini Pro and LangChain, the platform tailors resources to individual needs.

## Features

### 1. **Real-Time MCQ Generator**
Converts any uploaded PDF or text file into multiple-choice quizzes automatically. Powered by Google Gemini Pro, it lets you customize your study sessions by choosing your preferred topic, difficulty level, and number of questions.

- Upload a PDF or text file.
- Specify the number of MCQs, subject, and complexity level.
- Instantly get a custom quiz to test your knowledge and review key concepts.

### 2. **Ask to PDF**
Chat with multiple PDFs and get instant answers directly from your documents. This feature lets you upload your files and ask anything you need, pulling accurate responses straight from the text.

- Upload multiple PDFs.
- Ask questions related to the uploaded files.
- Get relevant answers by analyzing the content of the PDFs.

### 3. **Contest Calendar**
Keep track of upcoming contests across major coding platforms like Codeforces, LeetCode, and CodeChef all in one place. The platform automatically fetches live schedules so you never miss a competition.

- View and track upcoming coding contests.
- Easily set reminders for the matches you want to compete in.

### 4. **ATS Resume Analyzer**
Optimize your resume to get past automated Applicant Tracking Systems (ATS). This feature compares your resume directly against a job description, gives you a match score, and highlights the exact keywords you need to add to get noticed by recruiters.

- Upload your resume alongside the job description you are targeting.
- Get an instant, detailed ATS compatibility score.
- Discover missing keywords and get a tailored profile summary to improve your application.

## Tech Stack

- **Backend**: Python, LangChain, Google Gemini Pro
- **Frontend**: Streamlit
- **APIs & Tools**:
  - PyPDF2 (for PDF handling)
  - Pandas (for data handling)
  - dotenv (for environment configuration)
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/study-buddy.git
   cd study-buddy
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add environment variables for APIs (e.g., Google Gemini Pro, LangChain) in a `.env` file.

4. Run the application:
   ```bash
   streamlit run app.py
   ```




