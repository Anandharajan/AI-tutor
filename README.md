Here's the updated README without the license section:  

---

# 🌟 AI Tutor Application  
![AI Tutor Banner](assets/The%20Crest%20Logo.png)  

An interactive learning platform powered by Google's Gemini AI. Your personal tutor at your fingertips! 📚🤖  

---

## 🗂️ Table of Contents  
- [✨ Features](#-features)  
- [📋 Requirements](#-requirements)  
- [⚙️ Setup](#-setup)  
- [🚀 Usage](#-usage)  
- [🛠️ Development](#-development)  
- [🤝 Contributing](#-contributing)  

---

## 📸 Screenshots  
![AI Tutor Interface](assets/screenshot.png)  

---

## ✨ Features  

### 🧑‍🎓 **Student Information Collection**  
- Collects student name and grade/year before starting.  
- Information persists across sessions.  
- Used in reports and analytics.  

### 🧠 **Interactive Learning**  
- Ask questions on any topic.  
- Get clear, detailed explanations with examples.  
- Powered by Google's Gemini AI.  

### 📝 **Quiz System**  
- Generate quizzes on any topic! 🎯  
- Includes **5 multiple-choice questions per quiz**.  
- Get **instant feedback** on your answers.  
- **Track your performance** over time.  

### 📊 **Progress Dashboard**  
- View all your quiz attempts.  
- Analyze **performance trends** with visual charts. 📈  
- Expandable quiz details for deeper insights.  

### 🗂️ **Reporting Features**  
- Download **PDF reports** of your quiz history.  
- Generate **shareable links** for progress reports. 🔗  
- Reports include:  
  - Student information.  
  - Quiz topics and scores.  
  - Detailed question analysis.  

---

## 📋 Requirements  

Ensure you have the following installed:  
- 🐍 Python 3.8+  
- 🌐 Streamlit  
- 🤖 Google Generative AI package  
- 📄 FPDF for PDF generation  

---

## ⚙️ Setup  

1. 📦 **Install dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  

2. 🔑 **Get a Google API key** from [AI Studio](https://aistudio.google.com/).  

3. 🚀 **Run the app**:  
   ```bash  
   streamlit run ai_tutor_app.py  
   ```  

4. 🌍 Open your browser at the provided local URL, typically:  
   [http://localhost:8501](http://localhost:8501)  

---

## 🚀 Usage  

1. Enter your **name and grade/year**.  
2. Use the **Interactive Learning** section to ask questions. 💡  
3. Generate **custom quizzes** on topics of your choice. 📝  
4. View your **progress dashboard** to track trends. 📊  
5. Download and share your **progress reports**.  

---

## 🛠️ Development  

- All changes are tracked in the `memlog` folder.  
- Student data is stored temporarily when generating shareable links.  
- PDF reports are **generated on-demand** and not stored permanently.  
- Uses:  
  - [Semantic Versioning](https://semver.org/) 📚  
  - [Conventional Commits](https://www.conventionalcommits.org/) 🛠️  

### 🌟 Want to contribute? Follow these steps:  
1. **Fork** this repository. 🍴  
2. Create a new branch:  
   ```bash  
   git checkout -b feature/YourFeatureName  
   ```  
3. **Commit** your changes:  
   ```bash  
   git commit -m "Add: YourFeatureName"  
   ```  
4. **Push** to your branch:  
   ```bash  
   git push origin feature/YourFeatureName  
   ```  
5. Open a **pull request**! 🤝  

---

🚀 Happy Learning!  
