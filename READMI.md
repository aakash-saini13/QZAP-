# QZAP – Student Exam & Interview Prep App

QZAP is an interactive app designed to help students prepare for **exams and interviews** by providing structured guidance on **programming syntax**.  
Students can upload their questions in **JSON format**, and the app will automatically present those questions for practice and explanation.

---

## 🚀 Features
- Upload quiz questions in JSON format  
- Automatically parse and display questions with multiple options  
- Syntax-focused guidance for programming practice  
- Helpful for **exam revision** and **interview preparation**  
- Simple and student-friendly design  

---

## 📂 JSON File Syntax

Your JSON file should follow this structure:

```json
{
  "title": "My Quiz",
  "questions": [
    {
      "q": "2+2?",
      "options": ["1", "2", "4", "8"],
      "answer": 2
    }
  ]
}
