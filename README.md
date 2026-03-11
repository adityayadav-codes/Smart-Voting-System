
# 🗳️ Smart Voting System (Team Project

![HTML](https://img.shields.io/badge/HTML-Frontend-orange)
![CSS](https://img.shields.io/badge/CSS-Styling-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Logic-yellow)
![Python](https://img.shields.io/badge/Python-Backend-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-darkgreen)

A **Smart Voting System** is a web-based application that allows users
to securely vote online. The system ensures that each registered voter
can vote only once while administrators can manage candidates and view
election results.

This project demonstrates the integration of **frontend technologies
with a Python backend and MongoDB database**.

------------------------------------------------------------------------

## 📌 Features

✔ User Registration and Login\
✔ Candidate Listing\
✔ Online Voting System\
✔ One Person -- One Vote Mechanism\
✔ Real-time Vote Counting\
✔ Admin Panel for Managing Candidates\
✔ Result Display System

------------------------------------------------------------------------

## 🛠️ Technologies Used

  Technology   Purpose
  ------------ ---------------------------------------------------
  HTML         Structure of the web pages
  CSS          Styling and layout
  JavaScript   Client-side logic
  Python       Backend development
  MongoDB      Database for storing users, candidates, and votes

------------------------------------------------------------------------

## 🗄️ Database Design

### users Collection

  Field       Description
  ----------- --------------------------------
  \_id        Unique user ID
  name        Voter name
  email       User email
  password    User password
  has_voted   Boolean flag for voting status

### candidates Collection

  Field   Description
  ------- -----------------
  \_id    Candidate ID
  name    Candidate name
  party   Political party
  votes   Number of votes

### votes Collection

  Field          Description
  -------------- ---------------------
  \_id           Vote ID
  user_id        Reference to voter
  candidate_id   Candidate voted for
  timestamp      Voting time

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/adityayadav-codes/smart-voting-system.git
```

### 2️⃣ Install Required Python Libraries

``` bash
pip install flask pymongo
```

### 3️⃣ Start MongoDB

Make sure MongoDB is running locally.

### 4️⃣ Run the Application

``` bash
python app.py
```

Open your browser and visit:

    http://localhost:5000

------------------------------------------------------------------------

## 📂 Project Structure

    Smart-Voting-System
    │
    ├── static
    │   ├── css
    │   │   └── style.css
    │   ├── js
    │   │   └── script.js
    │
    ├── templates
    │   ├── index.html
    │   ├── login.html
    │   ├── register.html
    │   └── vote.html
    │
    ├── app.py
    ├── database.py
    └── README.md

------------------------------------------------------------------------

## 🎯 Learning Outcomes

-   Building **full-stack web applications**
-   Integrating **Python backend with MongoDB**
-   Implementing **secure login systems**
-   Managing **database operations**
-   Designing **interactive web interfaces**

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Add OTP-based voter authentication\
-   Implement blockchain-based voting security\
-   Add admin analytics dashboard\
-   Improve UI with React or Bootstrap\
-   Deploy the system on cloud servers

------------------------------------------------------------------------

## 👨‍💻 Author

**Aditya Yadav**

GitHub: https://github.com/adityayadav-codes



