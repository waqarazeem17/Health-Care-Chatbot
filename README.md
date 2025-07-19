# 🩺 Healthcare Chatbot

This is a **Healthcare Chatbot** developed using **Python** and basic **Natural Language Processing (NLP)** techniques. It simulates a simple conversation with a virtual healthcare assistant to predict diseases based on user symptoms and provide basic health advice.

## 📌 Features

- Interactive chatbot interface  
- Symptom-based disease prediction  
- Machine Learning models (Decision Tree, SVM)  
- Basic Natural Language Processing (NLP)  
- Text input through terminal or web interface  
- Responds until the user types “bye”  

## 💻 Technologies Used

- Python  
- Flask (for web interface)  
- NLTK (Natural Language Toolkit)  
- Scikit-learn  
- Pandas and NumPy  
- HTML/CSS (for frontend)  

## 📂 Project Structure

```text
healthcare-chatbot/
│
├── app.py               # Flask application (main file)
├── chatbot.py           # Core chatbot logic
├── model_training.py    # ML training (Decision Tree, SVM)
├── dataset.csv          # Dataset with symptoms and diseases
├── templates/
│   └── index.html       # Webpage template
├── static/
│   └── style.css        # Custom CSS
└── README.md            # Project documentation
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/healthcare-chatbot.git
cd healthcare-chatbot
```

### 2. Install required libraries

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install flask nltk scikit-learn pandas numpy
```

### 3. Run the Flask app

```bash
python app.py
```

### 4. Open in your browser

```
http://localhost:5000
```

Now you can interact with your Healthcare Chatbot through a web interface.

## 🧠 How It Works

- User enters symptoms in plain English.  
- The input is preprocessed using NLP techniques.  
- A trained ML model (Decision Tree or SVM) predicts the most likely disease.  
- The chatbot replies with a diagnosis and basic advice.  
- The conversation continues until the user says "bye".  

## 📊 Dataset

- The dataset contains rows of symptoms and corresponding diseases.  
- Used for training the ML model.  
- Format: `Symptom1, Symptom2, ..., Disease`  

## 💬 Example Conversation

```
User: I have cough and sore throat.
Bot: You may be suffering from Flu. Please stay hydrated and consult a doctor if symptoms worsen.
```

## ✅ Future Improvements

- Add voice interaction  
- Integrate medicine suggestions  
- Expand dataset for better accuracy  
- Deploy live on cloud platform  
- Add session memory  

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share for educational purposes.

## 🙋‍♂️ Author

**Waqar Azeem**  
Student at Bahria University  
For queries, email: your.email@example.com
