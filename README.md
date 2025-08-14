# 🧠 AI-Powered Career Recommendation System

A web-based intelligent system that recommends suitable careers based on a user's skills, subject preferences, and interests using Machine Learning techniques (Clustering + Classification). Built with Python and PHP, and designed for students, job seekers, and career counselors.

---

## ✅ Key Features

- 🎯 Personalized career suggestions  
- 🌐 User-friendly web interface  
- 🧮 Skill and interest assessment  
- 🤖 ML model integration (Clustering + Classification)  
- 🛠️ Admin dashboard for managing users and recommendations  

---

## 🔧 Tech Stack

**Frontend:**  
- HTML  
- CSS  
- JavaScript *(optional: Bootstrap)*

**Backend:**  
- Django (Python)

**Machine Learning:**  
- scikit-learn  
- Pandas

**Database:**  
- SQLite *(Development)*  
- PostgreSQL *(Production-ready)*

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Level-R/carrer_match_AI.git
cd carrer_match_AI
```
### 2. Set Up Virtual Environment

```bash
python -m venv env
env\Scripts\activate   # Windows
# OR
source env/bin/activate  # Mac/Linux
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Development Server

```bash

python manage.py runserver
```
Now visit http://127.0.0.1:8000/ in your browser to use the system.

# 📁 Project Structure

```bash
career_match/
├── manage.py
├── career_match/            # Main project settings
│   ├── settings.py
│   ├── urls.py
├── recommendation_app/      # Your core app
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   ├── static/
├── ml_model/                # ML scripts (Clustering & Classification)
│   ├── clustering_model.py
│   ├── classification_model.py
├── templates/
└── static/
```

# 🙋‍♂️ Contact
For any queries or collaborations:
📧 abdurrahmanroky.bd@gmail.com
🌐 https://www.linkedin.com/in/abdur-rahman-roky

