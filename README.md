
````markdown
# 🔐 **Secure Cloud App – Encrypted Login & Registration System**


A secure and beginner-friendly Flask web application for user **registration and login**, featuring **AES password encryption** and **SQL injection protection**. Designed with a beautiful UI and clean code structure – ideal for learning and showcasing secure web development.

---

 💡 Features

- 🔑 Register & Login with encrypted credentials
- 🔒 AES-256 Encryption using Python's `cryptography` module
- 🛡️ SQL Injection Protection via parameterized queries
- 🎨 Responsive UI (purple gradient design, mobile friendly)
- 💽 SQLite database storage
- ✨ Easy to understand for students and beginners

---

 🖥️ Screenshots


 
- Login Page  : ![image](https://github.com/user-attachments/assets/480a7e18-e64e-4f8b-9464-1bb68e98b964)

 

---

 🚀 How to Run Locally

1. Clone the repo
```bash
git clone https://github.com/amnatariq290/Secure-Cloud-App-Encrypted-Login-Registration-with-SQL-Injection-Protection.git
cd Secure-Cloud-App-Encrypted-Login-Registration-with-SQL-Injection-Protection
````

2. **Create virtual environment**

```bash
python -m venv venv
venv\Scripts\activate    # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Generate encryption key**

```bash
python generate_key.py
```

5. **Run the app**

```bash
python app.py
```

6. Visit:
   `http://localhost:5000`

---

## 📁 Project Structure

```
Secure-Cloud-App/
│
├── app.py
├── db.py
├── encryption.py
├── generate_key.py
├── secret.key
├── requirements.txt
├── users.db
│
├── static/
│   └── images/
│       └── bg.jpg
│
├── templates/
│   ├── index.html
│   ├── login.html
│   └── success.html
│
└── README.md
```



## 🛠 Built With

* Python 3.x
* Flask
* SQLite
* Cryptography (Fernet)
* HTML/CSS




## 👩‍💻 Author

**Amna Tariq**
Computer Engineering Student | Python & Front-End Developer




## ⭐ Star This Repo

If you found this useful, consider giving it a ⭐ to support my work!


