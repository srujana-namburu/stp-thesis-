# 🧠 AI-Powered Smart Trip Planner

The **AI-Powered Smart Trip Planner** is a Django-based travel assistant that helps users plan their trips efficiently using AI technologies. It provides personalized travel recommendations, sentiment analysis of tourist reviews, safety tips, and emergency features to ensure a smooth and safe journey.

## 🚀 Features

- 🔐 **User Authentication**: Secure registration and login.
- 🧠 **AI Chatbot**: Interactive travel assistant powered by Generative AI (Ollama server).
- 💬 **Sentiment Analysis**: Analyzes tourist reviews using SVM to recommend whether to visit a place.
- 📍 **Emergency Hospital Locator**: Locates nearby hospitals using geolocation.
- 💸 **Budget-Based Hotel Recommender**: Suggests hotels based on user budget using ML.
- ⚠️ **Travel Safety Tips**: Generates location-based safety advice using TF-IDF.
- 📌 **Bucket List**: Users can save dream destinations.
- 🧭 **Tourist Guide**: Provides must-visit places, weather info, and attractions.
- ⭐ **Review & Rating Analyzer**: Uses Random Forest to estimate destination worth.
- 📊 **Dynamic Pie Charts**: Visualizes sentiment analysis results interactively.

---

## 🛠 Tech Stack

| Category               | Technologies Used                                         |
|------------------------|-----------------------------------------------------------|
| 🧑‍💻 Backend            | Django, Python                                             |
| 🌐 Frontend            | HTML, CSS, JavaScript                                     |
| 🧠 AI/ML               | SVM, Random Forest, TF-IDF, NLP, Generative AI (Ollama)  |
| 🗃️ Database            | SQLite (can be upgraded to PostgreSQL/MySQL)             |
| ☁️ Deployment          | AWS EC2 Instance (Linux), APIs integration               |
| 📦 Others              | REST APIs, Git, GitHub, Bootstrap, Matplotlib            |

---

## ⚙️ Setup Instructions

1. **Clone or Upload Project**
   ```bash
   git clone https://github.com/yourusername/smart-trip-planner.git
   cd smart-trip-planner
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

---
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
🧪 Testing
Verify login/signup functionalities.

Test chatbot responses.

Input real reviews to check sentiment results.

Use hospital locator and check API integration.

Generate safety tips for different locations.

📈 AI Model Performance

Model	Purpose	Accuracy / Metric
SVM	Sentiment Analysis	85% F1-score
Random Forest	Destination Worth Estimation	88% accuracy
TF-IDF + NLP	Travel Safety Tips	Contextually relevant



