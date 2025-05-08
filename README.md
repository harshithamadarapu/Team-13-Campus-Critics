# 🎓 Campus Critics – Rate Your Professors

Campus Critics is a website where students can **rate professors**, **share course experiences**, and **interact via a student community**. The platform ensures review authenticity through **email based OTP Registartion**, helping students make better academic decisions.

---

##  Features

- 🔐 **OTP based Registration** using university email 
- 🔍 **Search professors** by name
- 🌟 Submit detailed **ratings** with feedback
- 📊 View professor pages with **weighted average scores**
- 🗣️ Post and comment in the **community forum** 

## 📁 Project Structure
end/
│
├── main.py # Flask app: routes, views, OTP logic
├── change.py # Additional routing or review changes
├── database.py # DB creation and seeding
├── database.db # SQLite database file
├── users.csv # Sample user data
├── modified.csv # Sample professor or rating data
├── .env # Environment variables (SMTP config)
├── templates/ # HTML templates (UI views)
│ ├── login.html
│ ├── dashboard.html
│ ├── professor.html
│ ├── community.html
│ └── ...
└── README.md # You're reading it!


---

## 🧰 Tech Stack

- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: SQLite  
- **Authentication**: Email OTP via SMTP  
- **Environment Management**: python-dotenv  

---

## ⚙️ Setup Instructions (Run Locally)

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/campus-critics.git
   cd campus-critics/end

