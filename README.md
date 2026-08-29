# AI-Based Sentiment Analyzer

##  Project Overview

The AI-Based Sentiment Analyzer is a Flask web application that analyzes the sentiment of user-provided text using a pretrained Transformer model. The application classifies text as positive, negative, or neutral and displays a confidence score.

##  Features

- Text-based sentiment analysis
- Positive, negative and neutral sentiment display
- Confidence score
- Recent analysis history
- SQLite database for storing results
- Web interface using HTML and CSS
- Input validation

##  Technologies Used

- Python
- Flask
- Hugging Face Transformers
- DistilBERT
- SQLite
- HTML
- CSS

##  Model Used

`distilbert-base-uncased-finetuned-sst-2-english`

The pretrained model is used to classify the sentiment of the entered text.

##  Project Structure

```text
sentiment-analyzer/
│
├── app.py
├── requirements.txt
├── README.md
├── sentiment.db
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
## How to Run
1. Clone the repository
git clone <your-repository-url>
cd sentiment-analyzer
2. Install dependencies
pip install -r requirements.txt
3. Run the application
python app.py
4. Open in browser
http://127.0.0.1:5000
📊 Working
User enters text.
Flask receives the input.
The text is processed by the Transformer sentiment model.
The sentiment and confidence score are generated.
The result is displayed to the user.
The analysis is stored in SQLite.
# Author

Arnav Raj Pandey
B.Tech Computer Science & Engineering
IILM University, Greater Noida
#Internship

Python Developer Internship
Codec Technologies Pvt. Ltd.
27 June 2026 – 27 July 2026


### For the Authentication System

Use a similar README:

```markdown
# Secure Authentication System

##  Project Overview

The Secure Authentication System is a Flask-based web application that provides user registration, login, logout and protected dashboard functionality.

The project uses bcrypt for secure password hashing and JWT for token-based authentication.

##  Features

- User registration
- Login and logout
- Password hashing using bcrypt
- Login verification
- JWT token generation
- Protected dashboard
- SQLite database
- Session-based access control
- Email uniqueness validation

##  Technologies Used

- Python
- Flask
- SQLite
- bcrypt
- PyJWT
- HTML
- CSS

##  Authentication Flow

```text
Registration
     ↓
Password Hashing
     ↓
SQLite Database
     ↓
Login
     ↓
Password Verification
     ↓
JWT Token Generation
     ↓
Protected Dashboard
     ↓
Logout
# How to Run
Install dependencies
pip install -r requirements.txt
Run the application
python app.py

Then open:

http://127.0.0.1:5000
#Project Structure
secure-authentication/
│
├── app.py
├── requirements.txt
├── README.md
├── users.db
│
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
│
└── static/
    └── style.css
# Author

Arnav Raj Pandey
B.Tech Computer Science & Engineering
IILM University, Greater Noida

# Internship

Python Developer Internship
Codec Technologies Pvt. Ltd.
27 June 2026 – 27 July 2026
