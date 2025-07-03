
# 📘 Study Buddy – Your AI-Powered Study Partner

**Study Buddy** is an intelligent web app designed to make learning more interactive, personalized, and collaborative. Built during the **GenAI Creatathon**, it blends the themes of **Education, Learning, and Community Building** using cutting-edge AI and intuitive UI design.


## 🚀 Features

### 📚 Study Notes & Quizzes

* Upload a **PDF** or **enter any topic**.
* Get:

  * ✅ Simplified **explanations**
  * 📘 Concise **summaries**
  * 🧠 Auto-generated **MCQs** for practice
* Powered by **Gemini 2.0 Flash** for fast and smart content generation.

### 🤝 Find Project Partner

* Input your **personality traits** and **interests**.
* Get matched with fictional student profiles (for demo purposes).
* See:

  * 🔗 **Compatibility percentage**
  * 🧠 **Reasons for match**
  * 💡 A unique **project idea** with roles assigned for both teammates

---

## 🛠️ Tech Stack

| Technology               | Purpose                          |
| ------------------------ | -------------------------------- |
| **Python**               | Core backend logic               |
| **Streamlit**            | Fast & beautiful UI              |
| **Gemini 2.0 Flash API** | AI-powered text generation       |
| **PyPDF2**               | Extracts text from uploaded PDFs |

---

## 🧠 How It Works

### 🎓 Study Mode

1. **PDF Upload**

   * Reads and parses uploaded PDF content (up to 8000 characters).
   * Sends content to Gemini API with three prompts:

     * Explanation
     * Summary
     * Quiz (5 MCQs + answer key)
      
2. **Topic Input**

   * Generates the same three outputs based on a topic you type.



### 🧑‍🤝‍🧑 Project Partner Matching

1. Enter:

   * Your **name**
   * Selected **interests** (e.g., AI, Python)
   * Selected **personality traits** (e.g., Leader, Analytical)

2. The app:

   * Generates **5 fictional student profiles**
   * Selects **top 2 matches** using Gemini
   * Calculates a **compatibility score**
   * Suggests a **custom project idea** based on shared interests



## 📸 Screenshots

![image](https://github.com/user-attachments/assets/be2e433f-22c8-4005-9cb7-c5448d8de1d4)

![image](https://github.com/user-attachments/assets/2987be8f-c741-47bf-8283-b61fbdf5dafa)


---

## 🧪 Sample Prompts Sent to Gemini

* **Explain Prompt**
  `"Explain the following study material in simple terms:\n\n<text>"`

* **Quiz Prompt**
  `"Create 5 MCQs with 4 options each about the topic <topic>. Provide answers at the end."`

* **Matching Prompt**
  `"Generate 5 fictional student profiles for someone with interests X and traits Y..."`

---

## ⚙️ Setup Instructions

1. Clone the repository

   ```bash
   git clone https://github.com/iffatadnann/studybuddy.git
   cd studybuddy
   ```

2. Install dependencies

   ```bash
   pip install streamlit google-generativeai PyPDF2
   ```

3. Add your **Gemini API key**
   Replace the empty string in `genai.configure(api_key="")` with your key.

4. Run the app

   ```bash
   streamlit run app.py
   ```

---

## 🧩 Future Enhancements

* 🔐 Add user authentication
* 📊 Score tracking and quiz history
* 📥 Download generated notes
* 🤖 Real-time chat with Gemini AI tutor

---

## 🙌 Acknowledgments

* Built during the **GenAI Creatathon**
* Inspired by the need for smart educational tools
* Gemini Flash API by **Google AI**

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE).


