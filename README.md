# 🎓 Campus Critics – Rate Your Professors

Campus Critics is a website where students can **rate professors**, **share course experiences**, and **interact via a student community**. The platform ensures review authenticity through **email based OTP Registartion**, helping students make better academic decisions.

---

##  Features

- 🔐 **OTP based Registration** using university email 
- 🔍 **Search professors** by name
- 🌟 Submit detailed **ratings** with feedback
- 📊 View professor pages with **weighted average scores**
- 🗣️ Post and comment in the **community forum** 

## Tech Stack

- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS, Javascript 
- **Database**: SQLite3
- **Authentication**: Email OTP via SMTP  
- **Environment Management**: python-dotenv  


## Setup Instructions (Run Locally)

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/campus-critics.git
   cd campus-critics/end

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate        # macOS/Linux
   venv\Scripts\activate           # Windows

3. **Install dependencie**


   ```bash
   pip install -r requirements.txt
   
4. **Configure the `.env` file**

   Create a file named `.env` inside the `end/` directory and add your email credentials for OTP:
   EMAIL_USER=your_email@example.com
   EMAIL_PASS=your_email_app_password

   
5. **Initialize the database**

```bash
python database.py






   
