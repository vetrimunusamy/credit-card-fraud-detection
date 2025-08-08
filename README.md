Dataset Link :- https://www.kaggle.com/mlg-ulb/creditcardfraud

1)  First  Create virtualenvironment with following COMMAND:-

        virtualenv venv

 NOTE:- venv is name of name of virtualenvironment. we can give any name which we want.

2) Then Activate venv:-

        venv\Scripts\activate

3) Then Install requirements.txt with following COMMAND:-

        pip install -r requirements.txt


4)  create superuser by following COMMAND in your root directory:-

        python manage.py createsuperuser

5)  Then start your server by typing following COMMAND:-

        python manage.py runserver



# Credit Card Fraud Detection 🕵️‍♂️💳

A full-stack web application for detecting fraudulent credit card transactions using machine learning (Logistic Regression). Built with Django, scikit-learn, Pandas, and integrated with secure user authentication, CSV upload, and dynamic data analysis.

## 🔍 Features

- Upload CSV datasets to detect fraudulent transactions
- Logistic Regression model for real-time prediction
- Fraud ratio calculation and class distribution insights
- Null value analysis and evaluation metrics
- Interactive data table with pagination (DataTables)
- User login, registration, and session handling
- File management for uploaded datasets
- Responsive UI with HTML, CSS, JavaScript

## 🛠️ Tech Stack

**Frontend:**
- HTML5, CSS3, Bootstrap
- JavaScript, DataTables

**Backend:**
- Python, Django
- Pandas, scikit-learn
- SQLite (local database)

**Tools:**
- Git, GitHub, VS Code

## 📁 Project Structure





    NOTE:- If you are adding some model in models.py or changing something don't forget to make migrations 

        python manage.py makemigrations

    and migrate it to database

        python manage.py migrate


