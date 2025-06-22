# 📄 Smart ATS Resume Evaluator

A powerful and user-friendly Streamlit application that evaluates your CV or resume against any job description using Google Gemini AI. Designed to help job seekers quickly identify matched and missing keywords, optimise their resumes, and improve alignment with specific roles.
§
---

## 🚀 Features

- 📎 **Upload PDF Resume**: Just drag and drop your CV in PDF format.
- 🔍 **Paste Job Description**: Add the job description directly into the sidebar.
- 🤖 **AI-Powered Evaluation**: Uses Gemini 2.0 Flash to analyse and compare your resume with the job description.
- ✅ **Matched & ❌ Missing Keywords**: Highlights both in a side-by-side layout.
- 📈 **Match Score**: Displays a percentage score based on relevance.
- 🧾 **Profile Summary**: Summarises your key strengths and alignment with the role.
- 📥 **Download Summary**: Save the AI-generated summary as a text file.

---

## 🖥️ App Preview

## Front UI
<img width="1460" alt="Screenshot 2025-05-28 at 09 50 59" src="https://github.com/user-attachments/assets/8f5142ba-3a9f-4fab-af1a-d09a11251834" />

## Score Match View
<img width="1448" alt="Screenshot 2025-05-28 at 09 54 25" src="https://github.com/user-attachments/assets/ba6407b2-2e30-48a9-bd8d-e8421d6c5ac7" />

## Detailed View
<img width="1450" alt="Screenshot 2025-05-28 at 09 55 36" src="https://github.com/user-attachments/assets/226bc20b-5d5b-4b2f-9b96-d8777e90487b" />

---

## 📦 Installation & Usage

### 🧰 Requirements

- Python 3.8 or later
- Google API Key (for Gemini)

### 🔧 Setup

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/smart-ats-resume-evaluator.git
cd smart-ats-resume-evaluator
````

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Set Your API Key**

Create a `.env` file in the root directory and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

4. **Run the App**

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 📁 Project Structure

```
smart-ats-resume-evaluator/
│
├── app.py               # Main Streamlit app
├── requirements.txt     # Required Python packages
├── .env                 # API key (do not upload this!)
├── README.md            # You're reading it!
```

---

## 🤝 Contributions

Contributions, suggestions, and issues are welcome!
Feel free to fork the repo and submit a pull request.

---

## 🛡️ Disclaimer

This tool is designed to provide guidance and should not be seen as a final decision-making system. Always review AI-generated summaries manually before submission.

---

## 📧 Contact

Created by **Rohith Obillaneni**
📩 [rohithobillaneni92@gmail.com](mailto:rohithobillaneni92@gmail.com)
📍 Luton, UK
🔗 [LinkedIn](https://www.linkedin.com/in/rohithobillaneni)

---

## 📜 Licence

This project is licensed under the MIT Licence - see the [LICENSE](LICENSE) file for details.
