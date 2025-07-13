# Multilingual Chatbot – English | Tanglish | Telunglish 🗣️🤖

This is a **Multilingual Chatbot project** developed as part of my **internship at GB Tech Corp**.
The goal of this project is to **break language barriers** and help English-speaking users communicate seamlessly in **Tanglish (Tamil + English)** and **Telunglish (Telugu + English)**.

---

## 🌍 **Project Overview**

The chatbot is designed to:

* Understand user queries in **English, Tanglish, and Telunglish**
* Provide **relevant responses in multiple languages**
* Help businesses and support teams serve a **wider user base** across different linguistic backgrounds

---

## 🧠 **Key Features**

* **Multilingual Intent Recognition**
* **Text Preprocessing for Mixed Languages (Code-Mixed Data)**
* **SVM (Support Vector Machine) Model for Text Classification**
* **\~90% Accuracy Achieved on Test Dataset**
* **Web Interface for Real-time Chat Interaction**

---

## 🔧 **Tech Stack**

| Task                  | Tools & Technologies                        |
| --------------------- | ------------------------------------------- |
| **Data Preparation**  | Python, Pandas, NLTK                        |
| **Model Training**    | SVM (Support Vector Machine)                |
| **Language Handling** | Custom Tokenization for Tanglish/Telunglish |
| **Web Deployment**    | Flask, HTML, CSS, JS                        |
| **Development Env**   | Jupyter Notebook                            |

---

## 📂 **Workflow**

### 1️⃣ **Dataset Preparation**

* Created a **custom dataset of intents and responses** in **English, Tanglish, and Telunglish**.
* Cleaned and preprocessed mixed language text data to handle unique word patterns.

### 2️⃣ **Model Building**

* Trained an **SVM classifier** for text classification tasks.
* Achieved **\~90% accuracy** in intent detection.

### 3️⃣ **Web Integration**

* Built a **Flask-based web interface** for real-time chat interaction.
* Users can enter queries in their preferred language and get instant responses.

### 4️⃣ **Deployment**

* Deployed the chatbot for internal testing and demo presentation.
* Demonstrated the working prototype to the team.

---

## 💻 **How to Run the Project Locally**

```bash
# Clone the repository
git clone https://github.com/yourusername/Multilingual-Chatbot.git

# Navigate to the project folder
cd Multilingual-Chatbot

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

# Open the web browser and go to
http://127.0.0.1:5000/
```

---

## 🎥 **Demo Link**

[👉 Click Here for Live Demo or Video](#) *(Insert your deployed link or video demo here)*

---

## 🗣️ **Supported Languages**

* **English**
* **Tanglish (Tamil-English Mix)**
* **Telunglish (Telugu-English Mix)**

---

## 📈 **Results**

* **\~90% accuracy** on test dataset
* Successfully handled **code-mixed queries**
* Integrated with a **user-friendly web interface**

---

## 📬 **Contact**

For more details, collaboration, or feedback:

**Lavanya R**
[LinkedIn](https://www.linkedin.com/in/lavanya-r-479537274/) 

---

## ⭐ **Acknowledgment**

Thank you to **GB Tech Corp** for assigning this project as part of the internship group task and helping me gain experience in **Multilingual AI Chatbot development**.

---

### **Folder Structure Suggestion**

```
Multilingual-Chatbot/
│
├── app.py                 # Flask App for Chatbot
├── model/                  # Trained SVM model files
├── static/                 # CSS/JS files
├── templates/              # HTML Frontend files
├── dataset/                # Custom Multilingual Dataset
├── chatbot_training.ipynb  # Jupyter Notebook for training
└── README.md               # Project Documentation
```

---
